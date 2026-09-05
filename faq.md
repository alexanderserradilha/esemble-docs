# FAQ

## Does the theme work without apps?

Yes. The one exception is collection filtering, which uses **Search &
Discovery**, Shopify's own free app.

## Why do variant colours show up as text?

Because the colour swatches have not been set up in the admin yet: **Settings →
Custom data → Option value swatches**. It is a Shopify feature, not a theme one —
configured once, it works in any theme.

## Can I show a Pix price and instalments?

Yes, and the theme works both out. The **Payment breakdown** block on the product
page takes a **Method name**, a **Discount** percentage and a **Maximum
instalments** count, and shows the discounted price and the instalment amount —
recalculated when the customer switches variant.

You write the method name, so it serves Pix as well as anything else.
**Enter the numbers your checkout actually applies**: the page promises, the
checkout delivers, and the gap between the two becomes a support ticket.

For free text with no arithmetic — "ships within 24h", say — use the **Payment
note** block.

## Does the theme have a cart drawer?

Yes, it is the default. Adding a product opens the panel without leaving the
page.

## How many photos per product?

The theme sets no limit. For performance, four to eight per product is usually
the balance.

## Is the theme translated?

It ships in English and Brazilian Portuguese. Under **Online Store → Themes →
Actions → Edit default theme content** you can change any string, and you can add
other languages.

## Is the theme accessible?

It is built on the browser's own elements — menus, drawers and dialogs use
`details` and `dialog` — so keyboard and screen reader work by default. Every
combination in the palette passes the contrast minimums (4.5:1 for text).
