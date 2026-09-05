# Common problems

## Colour swatches do not appear

Set the swatches up in **Settings → Custom data → Option value swatches**.
Without that, the theme shows text pills.

## The photo does not change when a colour is picked

The image has to be attached to the variant in the admin: open the product, click
the variant, and select its image.

If you want the gallery to show only that colour's photos, set **Group photos by
option** on the product section to the option that holds colour.

## Filters do not appear on the collection

Install the **Search & Discovery** app and create the filters in it. The theme
only displays what is configured there. Check that **Enable filtering and
sorting** is on in the collection section too.

## The sale badge does not appear

The product needs a **compare-at price** higher than its current price.

## "Appears in these looks" is empty on the product page

The block depends on the `look` metaobject. Check the definition exists, that it
has **Storefront access**, and that the product is in the **Pieces** list of some
look. See [Looks](looks.md).

## The floating contact button does not appear

That is deliberate: with no link filled in, it is not rendered.

## Video does not play with sound

Browsers only allow sound after the customer taps. The theme cannot work around
it.

## Sections do not appear on scroll

If you turned **Reveal sections on scroll** on and nothing happens, the
customer's system probably has "reduce motion" enabled. In that case everything
appears at once — deliberate.

## The logo is too big on mobile

There are two width controls, one for desktop and one for mobile, on the
**Header** section: **Logo width** and **Logo width on mobile**.

## The announcement bar still says "Free shipping over a set amount"

That is the shipped default. Click the announcement bar in **Customize** and
change the **Text** on the message block.
