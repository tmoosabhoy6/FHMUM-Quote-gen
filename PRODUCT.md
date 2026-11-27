# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Office staff of Faiz-e-Husaini Mumbai (FHMUM), working at a desk on a desktop or laptop, many times a day (confirmed by the owner, November 2026). They quote ziyarat groups for Karbala, Najaf, Cairo and Umrah, usually with an enquiry open beside the app, and they know the vocabulary: za'ir, takhfeef, Faiz Nizam, Hotel Nizam, lawazim, Hubb. Phones must work, but the desk layout leads.

## Product Purpose

Turn a group size and a list of flights into a price per za'ir. The app works out nights, transport, visas, the Cairo Lawazim package and the Umrah days from the flights, then prices every stay and takhfeef option per adult, child and infant, and downloads the quote as an Excel sheet in the office's usual layout with live formulas. Success is a correct quote sent quickly, with nothing worked out by hand.

## Positioning

The itinerary is derived, not entered: staff type flights, and every priced fact (nights in Iraq, Cairo package, Egypt visa rule, Umrah route) follows from them and can be overridden one at a time.

## Operating Context

- One file, `index.html`, served by GitHub Pages from `main`. No build step.
- Quotes, rates and saved flights save in the browser first, then to the repository's `data` branch when a computer is connected with a GitHub token.
- Rates come from the Faiz-e-Haakimi Qahera Lawazim and the Faiz e Husaini Iraq transport circular, and are edited under Settings.
- The Excel export (ExcelJS, loaded from a CDN) is the document that leaves the office.

## Capabilities and Constraints

- Calculation rules, saved-data formats, storage keys and the Excel layout are fixed product behaviour. Visual work must not change them.
- Terms stay as the office uses them (za'ir, takhfeef, Faiz Nizam, Hotel Nizam, lawazim, Rida, +80).
- Amounts are shown in rupees with Indian digit grouping; dollars and riyals appear where the rate cards use them.

## Brand Commitments

- One shared visual identity across Ziyarat quotes, its marketing copy and Kun Safar History (confirmed by the owner, November 2026).
- The identity is the "White and gold thread" direction chosen by the owner; it is recorded in DESIGN.md.

## Product Principles

1. The price is the point: it stays in view while the quote is being built.
2. Show the working: every derived fact says where it came from and can be changed.
3. Familiar controls, the office's own words.
4. Colour carries meaning (which country, which state), never decoration.

## Accessibility & Inclusion

WCAG 2.1 AA is the working target: text contrast, visible keyboard focus, labelled inputs, and tap targets that work on a phone.
