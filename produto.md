# Product page

The buying column is built from **blocks**: you choose which ones exist and in
what order.

| Block | What it is for |
|---|---|
| Vendor · Title · Price · SKU | The basics. Price can show a tax note |
| Variant picker | Colour as a swatch, everything else as a pill |
| Quantity selector | With plus and minus buttons |
| Buy buttons | Add to cart, and dynamic checkout buttons |
| Description | The product copy |
| Fit note | E.g. "The model is 1.75 m and wears a size S" |
| Size guide | Opens one of your pages in a dialog |
| Payment breakdown | Shows the cash price and the instalment. The figures live in **Theme settings → Payment**. See [Sections](secoes.md) |
| Payment note | Free text with an icon, no arithmetic |
| Store pickup | Availability at locations with pickup enabled |
| Badges | Up to four images of your own |
| Collapsible row | An accordion with text, or one of your pages |
| Appears in these looks | See [Looks](looks.md) |
| Text · Divider · Share · Custom Liquid | Extras |

## Gallery

Photos scroll sideways with snapping, and the thumbnails sit below. Choosing a
thumbnail works with JavaScript turned off, because they are links.

**Gallery layout** switches between the carousel and a stacked column.

When a customer picks a colour, the gallery moves to that variant's photo — as
long as you attached the image to the variant in the admin.

**Group photos by option** goes one step further: pick the option that holds
colour, and the gallery shows only the photos of the selected colour instead of
every photo on the product.

**Column pinned while scrolling**: choose which of the two columns stays put.
Pin the shorter one so the longer one moves past it. Pinning both pins neither
in any useful way.

## Size guide

Create a page under **Content → Pages** with your table and select it in the
block. Tables in page content are formatted automatically.

## Variant availability

A combination that is out of stock stays clickable and shows struck through. That
is deliberate: the customer needs to see the size exists, even if not in that
colour.
