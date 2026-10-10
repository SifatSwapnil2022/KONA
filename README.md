<div align="center">

# KONA

**Accessories for every you.**

Rings, chains, bracelets and earrings in anti-tarnish steel for men and women.
Designed in Dhaka, delivered across Bangladesh.

[![Live site](https://img.shields.io/badge/Live-konabd.shop-1F3D2B)](https://konabd.shop/)
[![Languages](https://img.shields.io/badge/Languages-English%20%7C%20Bangla-B8A88A)](https://konabd.shop/bn)

[Website](https://konabd.shop/) · [Shop](https://konabd.shop/shop) · [About](https://konabd.shop/about) · [Journal](https://konabd.shop/journal)

</div>

---

This repository holds the source code for the KONA online store at [konabd.shop](https://konabd.shop/).

KONA takes its name from the Bangla word কণা, a speck: the smallest amount of something. The idea behind the brand is that a small piece changes how a whole outfit reads. Every piece starts from a plain circle with one deliberate change made to it, and most of the collection is unisex.

## What the store does

**Browsing**

- Home page with the current collection, selected pieces, the Jora couple collection and journal highlights
- Shop page with filters for category, men or women, price, colour, size and stock, plus sorting by featured, newest or price
- Collections: New arrivals, Best sellers, Couple, Minimal, Statement
- Search with suggested terms

**Product pages**

- Photo gallery and an interactive 3D view (drag to rotate, pinch or scroll to zoom)
- Size selection with a size guide
- Material and care notes
- "Complete the look" and "You may also like" suggestions

**Ordering**

- Shopping bag, with "Add to bag" and "Buy now"
- Order by Messenger or WhatsApp, with the order message pre-filled
- Order tracking by order number and mobile number
- Customer account and wishlist

**Content**

- Journal with style articles
- About page and help pages: shipping, returns and exchange, size guide, FAQ, contact, privacy, terms
- Newsletter sign-up by email or mobile number
- English and Bangla interface

## Site map

| Path | Page |
|---|---|
| `/` | Home |
| `/shop` | All pieces, with filters and sorting |
| `/collections/men`, `/collections/women` | Shop by fit. Add `?category=rings` (or `earrings`, `necklaces`, `bracelets`, `pendants`, `chains`) to narrow it |
| `/collections/new`, `/collections/best-sellers`, `/collections/couple`, `/collections/minimal`, `/collections/statement` | Curated collections |
| `/products/{slug}` | Product page, for example `/products/chaya-signet-ring` |
| `/journal` | Articles |
| `/about` | Brand story and materials |
| `/account`, `/wishlist`, `/track` | Account, saved pieces, order tracking |
| `/info/{page}` | `shipping`, `returns`, `size-guide`, `faq`, `contact`, `privacy`, `terms` |
| `/bn/...` | The same pages with the Bangla interface |

## Catalogue

| | |
|---|---|
| Launch range | 18 pieces |
| Categories | Rings, pendants, chains, bracelets, earrings, necklaces |
| Material | 316L stainless steel |
| Finishes | Steel, Champagne, Onyx. Champagne and Onyx are PVD-coated |
| Naming | Bangla words for shapes: Britto (circle), Rekha (line), Bindu (dot), Dheu (wave) |
| Currency | Bangladeshi taka (৳) |

Product images are served from `/media/products/` and follow one naming pattern. Each product has a main image named `{slug}-{finish}.webp` and a second angle named `{slug}-alt.webp`:

```
media/products/chaya-signet-ring-steel.webp
media/products/chaya-signet-ring-alt.webp
```

Editorial images for the home page, About page and social previews are served from `/media/editorial/`.

## Delivery, payment and exchange

| | |
|---|---|
| Delivery area | Every district in Bangladesh |
| Delivery time | 1 to 2 days in Dhaka, 3 to 5 days elsewhere |
| Payment | Cash on delivery, bKash, Nagad, Visa, Mastercard |
| Exchange | Within 7 days |

## Hosting

The site runs on an Oracle Cloud server and is served at [konabd.shop](https://konabd.shop/).

## Roadmap

- Bangla translation for collection text and journal articles, which are still in English on `/bn`
- New pieces in testing: anklets and a wider cuff
- Engraving
- Delivery outside Bangladesh

## Team

KONA is run by a team of five: the founder, a brand executive and ambassador, a social media and admin dashboard handler, a designer, and research and development.

Founder: Md Sifatullah Sheikh · [KONA on LinkedIn](https://www.linkedin.com/company/kona-accessories)

## License

© 2026 KONA. All rights reserved. This is a private repository. The code, product photography, brand name and logo may not be copied or reused without written permission.
