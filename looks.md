# Looks

A look is one photo plus the pieces that appear in it. The theme shows a look
four ways: **Shop the look** (a photo with clickable hotspots), **Look grid**,
**Video feed**, and the **Appears in these looks** block on the product page.

## Shop the look

Pick the **Image**, choose which **Image side** it sits on, and add one **Piece**
block per product. Each piece has a **Linked product** and two percentage
controls, **Hotspot horizontal position** and **Hotspot vertical position**.

The position is relative to the photo, so the hotspot survives any crop and any
screen size.

The **Add the look to cart** button sends every ticked piece at once, each in the
variant chosen right there in the list. The list is always visible, so nothing
depends on finding a dot on a photograph.

## Look grid

One **Look** block per tile. Each takes an **Image**, a **Heading** and up to
three products — **Piece 1**, **Piece 2**, **Piece 3**. The tile opens a dialog
with the photo and the pieces.

## Video feed

One **Video** block per tile, each with a **Video** and a **Linked product**.
Vertical video (9:16) works best. Video plays muted and only while it is on
screen; the customer controls it with the button. Sound needs a tap from the
customer — that is a browser rule, not a theme one.

## Appears in these looks

This block on the product page is the only one that needs setting up. It lists
the looks a product belongs to, so a customer who arrived at one piece can see
the whole outfit.

It reads a metaobject, which you create once:

**Settings → Custom data → Metaobjects → Add definition**

| Field | Type | Key |
|---|---|---|
| Name | — | `Look` (type `look`) |
| Title | Single line text | `title` |
| Image | File (image) | `image` |
| Pieces | List of product references | `products` |
| Video | File (video) — optional | `video` |

Tick **Storefront access** on the definition. Each entry is then one look, and
any product listed in its **Pieces** shows that look on its own page.

Without the definition the block simply shows nothing. The three sections above
do not depend on it.
