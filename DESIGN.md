---
name: Ziyarat quotes
description: Per za'ir quotes for Karbala, Najaf, Cairo and Umrah groups.
colors:
  white: "#FFFFFF"
  wash: "#F6F4F8"
  wash-deep: "#ECE9F0"
  line: "#E4E0E9"
  edge: "#8F889A"
  ink: "#221C26"
  ink-soft: "#5A5362"
  ink-faint: "#6F6878"
  gold-thread: "#B98A2C"
  gold-deep: "#84600F"
  gold-tint: "#FBF3DC"
  gold-line: "#E4CD95"
  rose: "#BE2459"
  rose-deep: "#8C1440"
  rose-tint: "#FCE5ED"
  saffron: "#F2B90F"
  saffron-deep: "#6E5100"
  saffron-tint: "#FFF2C6"
  mint: "#14795A"
  mint-deep: "#0D5E46"
  mint-tint: "#DAF3EA"
  lilac: "#6A4FC4"
  lilac-deep: "#4C3699"
  lilac-tint: "#ECE7FA"
  warn: "#9A4307"
  warn-tint: "#FFEFE2"
  red: "#B3261E"
  red-tint: "#FCEBEA"
  ok: "#1E7A4F"
typography:
  title:
    fontFamily: "Figtree, system-ui, -apple-system, Segoe UI, Roboto, sans-serif"
    fontSize: "26px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: "-0.015em"
  section:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 700
    lineHeight: 1.3
  body:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  small:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "13.5px"
    fontWeight: 400
    lineHeight: 1.45
  label:
    fontFamily: "Figtree, system-ui, sans-serif"
    fontSize: "12.5px"
    fontWeight: 500
    lineHeight: 1.3
rounded:
  tile: "6px"
  control: "8px"
  block: "10px"
  group: "12px"
  sheet: "14px"
  dialog: "16px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "12px"
  lg: "20px"
  xl: "28px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.white}"
    rounded: "{rounded.control}"
    height: "38px"
    padding: "0 16px"
  button-primary-hover:
    backgroundColor: "#3A3041"
  button-secondary:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    height: "38px"
    padding: "0 16px"
  button-secondary-hover:
    backgroundColor: "{colors.wash}"
  input:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    rounded: "{rounded.control}"
    height: "38px"
    padding: "0 10px"
  sheet:
    backgroundColor: "{colors.white}"
    rounded: "{rounded.sheet}"
  tick-chip:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink-soft}"
    rounded: "{rounded.control}"
    height: "36px"
    padding: "0 12px 0 10px"
  tick-chip-checked:
    backgroundColor: "{colors.gold-tint}"
    textColor: "{colors.ink}"
  journey-tile-iraq:
    backgroundColor: "{colors.rose}"
    textColor: "{colors.white}"
    rounded: "{rounded.tile}"
    height: "38px"
  journey-tile-cairo:
    backgroundColor: "{colors.saffron}"
    textColor: "{colors.ink}"
  journey-tile-saudi:
    backgroundColor: "{colors.mint}"
    textColor: "{colors.white}"
  journey-tile-flying:
    backgroundColor: "{colors.lilac-tint}"
    textColor: "{colors.lilac-deep}"
---

# Design System: Ziyarat quotes

## Overview

**Creative North Star: "White and gold thread"**

The look comes from white libas and the gold-thread topi: a bright white working surface, plum-black ink, and one fine gold crochet band as the only ornament. Colour is saved for meaning. Rose is Iraq, saffron is Cairo, mint is Saudi Arabia and lilac is time in the air, on the journey band, on each place's facts and on the lands-next-day toggle. The same system is shared by Ziyarat quotes, its marketing copy and Kun Safar History, so the three read as one FHMUM toolset.

This is a working tool for office staff at a desk. Controls are the standard ones (boxed inputs, tick chips, buttons, tabs, tables, dialogs); the world contributes type, palette, density and one signature move, the journey band. It replaced a teal-and-eight-point-star look; that look is not to be brought back.

**Key Characteristics:**
- White sheets on a faint violet-grey wash; never cream.
- One gold band, once per screen, as the hem of the top bar.
- Colour means something every time it appears.
- One typeface, Figtree, with tabular figures wherever numbers line up.
- Ink-filled primary buttons; selection is drawn in ink, never in a colour.

## Colors

A white ground, a plum-black ink, a gold thread, and rida colours that each carry one meaning.

### Primary
- **Ink** (#221C26): text, primary buttons, checked tick boxes, focused input borders.
- **Gold thread** (#B98A2C): the hem band, the mark, progress and saving indicators. Never used for text.
- **Gold deep** (#84600F): focus rings, the caret, gold text on white or gold tint.
- **Gold tint** (#FBF3DC) with **gold line** (#E4CD95): the grand-total row only. Selection is never gold: ticked, current and found states use an ink border on white, because a cream fill reads as Cairo's saffron.

### Secondary
- **Rose** (#BE2459, deep #8C1440, tint #FCE5ED): Iraq. Journey tiles, the Iraq facts header.
- **Saffron** (#F2B90F, deep #6E5100, tint #FFF2C6): Cairo. Journey tiles (ink text), the Cairo facts header.
- **Mint** (#14795A, deep #0D5E46, tint #DAF3EA): Saudi Arabia. Journey tiles, the Umrah facts header.
- **Lilac** (#6A4FC4, deep #4C3699, tint #ECE7FA): in the air. Flying tiles and the "+1 day" lands toggle.

### Neutral
- **White** (#FFFFFF): sheets, inputs, the top bar.
- **Wash** (#F6F4F8): the page behind the sheets, table headers, inset groups.
- **Wash deep** (#ECE9F0): hover fills, empty tiles, the tab track.
- **Line** (#E4E0E9): hairlines between rows and sections.
- **Edge** (#8F889A): input, chip and secondary-button borders (3.5:1 on white).
- **Ink soft** (#5A5362) and **ink faint** (#6F6878): secondary text and placeholders; both pass 4.5:1 on white and on wash.
- **Red** (#B3261E) on **red tint** (#FCEBEA): errors and "not found" only.
- **Warn** (#9A4307) on **warn tint** (#FFEFE2): notes that something is missing or worth checking, always with the triangle icon.

### Named Rules
**The Meaning Rule.** A rida colour appears only where its meaning is true. Rose is Iraq, saffron is Cairo, mint is Saudi Arabia, lilac is flying. Stay options (Faiz Nizam, Hotel Nizam) are alternatives, not places, and stay uncoloured.
**The One Band Rule.** The gold crochet band (a chain of linked loops with a picot between each) is drawn once per screen, under the top bar. Elsewhere gold is a 1px line, a hairline between price groups, or the grand-total tint.
**The Ink Selection Rule.** What is ticked, current or found gets an ink border on white (2px effective), never a colour fill.
**The No Grey-on-Colour Rule.** Text on a tinted field uses that hue's deep shade, not grey.

## Typography

**Display Font:** Figtree (with system-ui, -apple-system, Segoe UI, Roboto)
**Body Font:** Figtree
**Label/Mono Font:** none; figures use Figtree's tabular numerals.

**Character:** One round, even, open sans for everything, chosen because it carries the rupee sign and true tabular figures. Hierarchy comes from weight (400, 500, 600, 700) and a tight fixed scale, not from a second face.

### Hierarchy
- **Title** (700, 26px, 1.2, -0.02em): the quote's name, typed in place.
- **Headline** (700, 20px, 1.2, -0.015em): the price sheet and dialog titles; the docked price.
- **Section** (700, 17px, 1.3): section headings inside a sheet.
- **Body** (400, 15px, 1.5): field values and running text; helper text is capped near 62 to 70 characters.
- **Small** (400 to 600, 13 to 13.5px): helper lines, fact details, table cells.
- **Label** (500 to 600, 12.5px): field labels and column headings, in sentence case. Nothing smaller than 11.5px, and that only on tiles.

### Named Rules
**The Tabular Rule.** Any column of money, dates or counts sets `font-variant-numeric: tabular-nums`.
**The Sentence Case Rule.** Labels are sentence case, never tracked capitals.

## Layout

Two sheets on the wash: the form sheet (flexible) and the price sheet (420px, sticky under the top bar, scrolls inside itself when it is taller than the window). The page is capped at 1260px. From 1140 to 1239px the price sheet narrows to 380px. Below 1140px the price sheet drops under the form and the lead price docks to the bottom of the screen until the sheet scrolls into view. Below 760px the top-bar buttons become icons; below 640px controls grow to 44px.

Flight rows respond to the width of the card they sit in, not the window, through container queries: one row at 676px and up, a compact row down to 632px, then two rows (flight, route, lands, remove; date, times, look-up) sized to what each field holds, and three rows under 332px. The full breakdown is a full-width sheet under both columns.

Spacing steps are 4, 8, 12, 20 and 28px. Sections inside a sheet are separated by a hairline and 26 to 28px of padding; a heading sits closer to its own content (16px) than to the section above.

## Elevation & Depth

Flat, with one soft lift. Sheets carry `0 1px 2px rgba(34,28,38,.05), 0 12px 28px -16px rgba(34,28,38,.18)` over the wash. Dialogs and the toast carry `0 2px 6px rgba(34,28,38,.08), 0 28px 70px -20px rgba(34,28,38,.38)`. The hem band casts a short shadow down the page so the sticky bar reads as above the content. Nothing else has a shadow; groups inside a sheet are separated by hairlines, tints or the wash.

## Shapes

Tiles 5 to 6px, controls 8px, inset blocks 10px, bordered groups 12px, sheets 14px, dialogs 16px. Borders are 1px. Icons are authored SVG at one stroke weight (1.9 on a 24 grid) with round caps; no glyphs stand in for icons. The mark is four interlocking loops in gold thread, the repeat of a crochet rosette; the hem repeats the same loop as a chain.

## Components

- **Top bar:** white, 56px, sticky, hemmed by the gold band. Left: the mark and the app name. Right: where quotes are saved (a dot and a line of text), Saved quotes, Settings, and New quote as the primary button. At 760px and below the buttons become 44px icons and the save status moves under the app name, still with its words.
- **Buttons:** primary is ink with white text; secondary is white with an edge border; both 38px tall, 8px radius, 600 weight. Hover darkens or washes; active nudges 1px; disabled is 50 to 55% opacity. Dashed-border buttons add something (a flight, a family, a line item).
- **Inputs:** white, 1px edge border, 38px tall (44px on phones, 16px text). Hover darkens the border; focus is an ink border with a 3px gold glow; an invalid value turns red on red tint.
- **Focus:** a 2px gold-deep outline, 2px off the control.
- **Tick chips:** a bordered 36px chip with a square tick box. Ticked is white with a 2px ink border and an ink box. Some chips hold a small amount field.
- **Airport codes:** a code in Iraq, Cairo or Saudi Arabia takes that country's tint and deep text, so the flights table already shows the route's colours.
- **Place swatch:** a 9px rounded square in the place colour before a place in a sentence (the price sheet's summary) and before each place row of the full breakdown.
- **Journey band:** one 38px tile per day, coloured by where the group is at the end of that day, with the date inside, the weekday above (the month at the start of a row and on the 1st), a plane mark on days with a flight, and the place named on a coloured rule beneath. Tiles are 26 to 66px wide; a trip that will not fit one row breaks into even rows, never a sideways scroll. When a place's name is wider than its tiles it is dropped from the rule and a key under the band names every place. It shows the calendar; the priced nights are in the facts.
- **Place groups:** a bordered group per stay, in travel order, with a tinted header in the place's colour and its dates. Facts inside are a bold line, a detail line and, where it can be overridden, a Change button that opens an inset row.
- **Notes:** warn-tint boxes with a triangle icon, above the place groups.
- **Price sheet:** stay name in bold, prices at 18px bold tabular, takhfeef rows indented and lighter, a gold hairline between stays, the whole-group total on wash. Long stay names take a line of their own above their prices. When the list is taller than the window it scrolls inside the sheet under a fade, and Download Excel (primary) and the breakdown toggle stay pinned to the sheet's bottom edge above a hairline.
- **First run:** the price sheet shows a three-step checklist that ticks itself, and an example-group button.
- **Settings:** a wide dialog with a sticky row of section buttons that marks the section in view; rate tables use 104px inputs and scroll sideways on phones.
- **Quote name:** a borderless field at title size that wraps onto a second line rather than cutting a long name.
- **Dialogs:** native `<dialog>`, white, 16px radius, sticky header with the title and one closing button.
- **Motion:** 150 to 250ms state transitions on an exponential ease-out. The one authored moment is the band of tiles stitching in. Reduced motion removes the animations and keeps every state.

## Do's and Don'ts

- Do keep the price or the count readable at a glance; it is why the screen exists.
- Do reuse the tile band for anything that is a run of days or years.
- Do keep every new control at 38px (44px on phones) with a visible label.
- Don't add a second ornament, a second typeface, or a gradient.
- Don't use a rida colour as decoration or for a primary button.
- Don't use cream, teal, or the eight-point star; those belonged to the look this replaced.
- Don't put grey text on a tinted field, or text smaller than 12.5px outside tiles.
