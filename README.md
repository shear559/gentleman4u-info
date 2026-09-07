# 4MEN

**A Hebrew RTL men's accessories storefront with product discovery, an order-request flow and a management console.**

[Visit the storefront preview](https://gentleman4u.vercel.app)

<p align="center">
  <img src="assets/preview.webp" alt="4MEN storefront preview" width="100%">
</p>

Browse accessories by category, filter the catalogue, choose product variants and keep a cart or wishlist. The repository retains its original `gentleman4u` name; the storefront brand is 4MEN.

## Commerce and management

The implementation includes customer accounts, synchronized profile and shopping records, order intake, and an authenticated console for catalogue, inventory, fulfilment, returns and publication. Vercel Functions authorize these operations and store their records in Supabase/Postgres. Browser storage remains a device cache and holds preview drafts.

Catalogue publication is tied to product verification and store readiness. The management console brings incomplete product information, inventory exceptions and outstanding orders into one operational view.

## Current stage

The live site is a preview. Supabase, Vercel environment variables and Turnstile must be configured before customer accounts and persistent commerce are available. Merchant contact details and products also require verification before launch.

Preview checkout keeps a draft on the device. When the store is configured for WhatsApp orders, the customer reviews and sends the prepared request in WhatsApp. No card payment is processed or reported as complete.

## Screenshots

| Catalogue interface | Product interface |
|---|---|
| ![4MEN catalogue preview](assets/shop-catalog.webp) | ![4MEN product preview](assets/product-page.webp) |

<p align="center">
  <img src="assets/mobile-home.webp" alt="4MEN homepage on mobile" width="300">
</p>

## Stack

`HTML` · `CSS` · `JavaScript` · `Vercel Functions` · `Supabase Auth` · `Postgres` · `Turnstile`

Source is private. Built by [@shear559](https://github.com/shear559).
