# Sections

Everything below is added through **Add section** in the customizer. None of it
needs an app.

## Storefront and catalogue

| Section | What it is for |
|---|---|
| **Featured collection** | One collection, as a carousel or a grid. This is your "Best sellers", "New in", "Sale" |
| **Collection grid** | Category cards with a photo |
| **Featured product** | One product, large photo, buying decision beside it. With variants the button opens the product page — choosing a size for the customer would sell the wrong one |
| **Related products** | Shopify's own recommendations, related or complementary |
| **Quick order list** | A table of every variant with a quantity field, and one button. For wholesale and repeat buying |

## Editorial

| Section | What it is for |
|---|---|
| **Slideshow** | A campaign, one slide or several. Height is a setting, not the shape of the first photo |
| **Hero** | A single full-width image with a heading over it |
| **Image with text** · **Image banners** | Paired image and text |
| **Alternating rows** | A run of image-and-text rows that swap sides on their own |
| **Collage** | One tall block beside a stack. Each piece is an image, a product or a collection |
| **Image gallery** | A grid of photos, with separate column counts for desktop and mobile |
| **Rich text** | A centred heading and paragraph |
| **Blog posts** | The latest posts from a blog |

## Proof and trust

| Section | What it is for |
|---|---|
| **Benefits strip** | Delivery, instalments, security, returns. Four icons |
| **Scrolling strip** | Short phrases moving across the width of the screen. For anyone who asked for less motion, they hold still |
| **Testimonials** | Quotes with an author |
| **FAQ** | An accordion |
| **Size guide** | A table with the columns you define, for your measurements page |

## Video and looks

| Section | What it is for |
|---|---|
| **Video row** · **Video feed** | Video with a product attached. See [Looks](looks.md) |
| **Shop the look** · **Look grid** | See [Looks](looks.md) |
| **Floating video** | A circle pinned in a corner that opens the full video when tapped |

## Capture and navigation

| Section | What it is for |
|---|---|
| **Email signup banner** | Newsletter over a photo. The address lands in your Shopify marketing list |
| **Menu** | One of your navigation menus shown in the body of the page, as pills or columns |
| **Category strip** | Categories as circles or squares, in the footer of every page |
| **Custom section** · **Custom Liquid** | Your own blocks, or your own code, wherever you want it |

---

## Payment breakdown

A block on the product page, and the reason this theme exists for a Brazilian
store.

The figures live in **Theme settings → Payment**, not on the block: a shop has
one Pix discount and one instalment plan, not one per section. The cash price is
set in the display family at display size, in the **Money** colour from
**Theme settings → Functional colour**. You give it a
**Method name**, a **Discount** percentage and an **Instalments** count, and the
theme works out both figures and shows them:

> **R$ 151,05** with Pix
> or up to 4x R$ 39,75 interest free

You write the method name, so it covers Pix, bank transfer, or whatever your
store takes. The figures are recalculated when the customer switches variant,
because a stale discounted price sitting beside a price that just changed
contradicts the page it is on.

**Enter the numbers your checkout actually applies.** The theme does not read
your payment rules: it shows what you type.

## Badges and payment icons

Payment icons appear in the footer on their own, from whatever is active in your
checkout — nothing to configure. For badges of your own (secure site,
memberships), use the footer's **Badges** block, which takes up to six images.
