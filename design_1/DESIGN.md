---
name: Dental Flower Studio
description: An owner-led aesthetic dental studio whose real before/after results are the proof.
colors:
  bg: "#faf9f8"
  surface: "#ffffff"
  ink: "#262224"
  ink-2: "#5f5a5c"
  line: "#e6e0e2"
  rose: "#a3405f"
  rose-deep: "#86304c"
  rose-soft: "#f5ebee"
  night: "#2a2125"
  night-2: "#3a2f34"
  night-ink: "#f4edef"
  night-mute: "#c4b5bb"
  viber: "#665cac"
  viber-deep: "#554b98"
  wa: "#0f7a6e"
  wa-deep: "#0b665c"
typography:
  display:
    fontFamily: "Forum, Times New Roman, serif"
    fontSize: "clamp(3rem, 1.6rem + 4.6vw, 5.75rem)"
    fontWeight: 400
    lineHeight: 0.98
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Forum, Times New Roman, serif"
    fontSize: "clamp(2.2rem, 1.5rem + 2.6vw, 3.6rem)"
    fontWeight: 400
    lineHeight: 1.05
    letterSpacing: "-0.01em"
  quote:
    fontFamily: "Forum, Times New Roman, serif"
    fontSize: "clamp(1.4rem, 1.1rem + 1vw, 1.9rem)"
    fontWeight: 400
    lineHeight: 1.3
  title:
    fontFamily: "Forum, Times New Roman, serif"
    fontSize: "1.6rem"
    fontWeight: 400
    lineHeight: 1.15
  title-sm:
    fontFamily: "Forum, Times New Roman, serif"
    fontSize: "1.4rem"
    fontWeight: 400
    lineHeight: 1.2
  lead:
    fontFamily: "Golos Text, system-ui, sans-serif"
    fontSize: "clamp(1.05rem, 1rem + .3vw, 1.2rem)"
    fontWeight: 400
    lineHeight: 1.65
  body:
    fontFamily: "Golos Text, system-ui, sans-serif"
    fontSize: "1.0625rem"
    fontWeight: 400
    lineHeight: 1.65
  button:
    fontFamily: "Golos Text, system-ui, sans-serif"
    fontSize: "0.97rem"
    fontWeight: 500
    lineHeight: 1
  label:
    fontFamily: "Tenor Sans, Gill Sans, sans-serif"
    fontSize: "0.7rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.18em"
  price:
    fontFamily: "Tenor Sans, Gill Sans, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.04em"
    fontFeature: "tnum, lnum"
rounded:
  photo: "4px"
  md: "6px"
  inset: "8px"
  card: "10px"
  pill: "999px"
spacing:
  gutter: "clamp(1rem, .4rem + 2.6vw, 3rem)"
  section: "clamp(4.5rem, 3rem + 6vw, 8.5rem)"
  wrap: "77.5rem"
  pair-gap: "6px"
  cta-gap: "0.75rem"
components:
  button-viber:
    backgroundColor: "{colors.viber}"
    textColor: "{colors.surface}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 1.5rem"
    height: "3.25rem"
  button-viber-hover:
    backgroundColor: "{colors.viber-deep}"
  button-wa:
    backgroundColor: "{colors.wa}"
    textColor: "{colors.surface}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 1.5rem"
    height: "3.25rem"
  button-wa-hover:
    backgroundColor: "{colors.wa-deep}"
  button-rose:
    backgroundColor: "{colors.rose}"
    textColor: "{colors.surface}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 1.5rem"
    height: "3.25rem"
  button-rose-hover:
    backgroundColor: "{colors.rose-deep}"
  button-sm:
    padding: "0 1.15rem"
    height: "2.6rem"
  button-lg:
    padding: "0 2.1rem"
    height: "3.75rem"
  tag-before:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: ".45rem .7rem .4rem"
  tag-after:
    backgroundColor: "{colors.rose}"
    textColor: "{colors.surface}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: ".45rem .7rem .4rem"
  contact-card:
    backgroundColor: "{colors.surface}"
    rounded: "{rounded.card}"
    padding: "clamp(2.5rem, 6vw, 4.5rem) clamp(1.25rem, 5vw, 4rem)"
---

# Design System: Dental Flower Studio

## Overview

**Creative North Star: "Her Work Is the Proof"**

A gallery-white aesthetic dental studio. The page reads first as a dental practice and second as a person: real patient transformations, photographed in her studio, carry the argument; the type and colour only frame them. The ground is the warm white of a treatment-room wall, the ink is the warm grey of her logo, and one rose accent marks what to do and what changed. Results sit on a dark night-rose field so the photographs read like prints on a lightbox wall.

The voice is calm and feminine without being decorative. Forum's flared Roman capitals and Tenor Sans' wide caps both come from her own lockup; Golos Text carries everything a nervous patient actually has to read. The only ornament is her tooth-petal flower mark. There is no conceptual metaphor and no stock imagery: the stationery/invitation world was built and rejected as too far from a dental studio, and nothing from it carries forward.

The build is pure HTML and CSS with no JavaScript. Booking happens only through Viber and WhatsApp deep links; there is no email form anywhere.

**Key Characteristics:**
- Real before/after photography as the hero and the main section, always in matched pairs.
- Warm near-white ground, warm grey ink, a single rose accent, one dark night-rose field.
- Flared serif display, wide-tracked caps for labels, a plain humanist sans for reading.
- Pill-shaped buttons in the messaging channels' own colours; rose pills for in-page booking jumps.
- Hairline rules instead of boxes; soft, long, low-opacity shadows only on raised photo and card surfaces.
- Restrained motion: one wipe-in on the hero result, a slow zoom on case hover, nothing else.

## Colors

A warm-neutral, nearly achromatic palette (every neutral leans faintly to rose, hue around 350) with one saturated rose accent and two third-party channel colours that belong to Viber and WhatsApp, not to the brand.

### Primary
- **Studio Rose** (#a3405f): the "after" state and the call to act. Fills the "След" tag, the rose booking buttons, the focus ring and the caret. As ink it appears only at a few small anchoring points: the second line of the hero headline (the "after" promise, "Същата вие."), the approach step numerals, the opening and closing quote marks on her quotation, and the flower mark on the contact card.
- **Deep Rose** (#86304c): hover state of rose buttons; text colour of selections.
- **Blush** (#f5ebee): the services field background and text-selection fill. A surface, never a fill for controls.

### Neutral
- **Treatment-Room White** (#faf9f8): the page ground and the translucent base of the sticky header and mobile dock.
- **Pure Surface** (#ffffff): the contact card, the "Преди" tag ground, the white border around the hero's inset photo.
- **Logo Grey Ink** (#262224): headings and body text.
- **Soft Grey Ink** (#5f5a5c): leads, secondary copy, nav links, captions, the header lockup mark.
- **Hairline** (#e6e0e2): every rule, the header and dock borders, the default underline of text links.
- **Night Rose** (#2a2125): the Results field and the footer. The only dark surface.
- **Night Well** (#3a2f34): the loading ground behind case photos on the night field.
- **Night Ink** (#f4edef): text on the night field; focus ring colour on the night field.
- **Night Mute** (#c4b5bb): secondary text and captions on the night field, the footer flower mark.

### Channel colours (third-party, not brand)
- **Viber Violet** (#665cac, hover #554b98) and **WhatsApp Teal** (#0f7a6e, hover #0b665c): used only on their own booking buttons, always as a pair, always with the channel's icon.

### Named Rules
**The Rose Means Action-or-After Rule.** Rose as a solid fill is reserved for things you press (rose booking buttons) and for the "after" state (the "След" tag). As ink it stays at small anchoring points (a numeral, a quote mark, the "after" line of the hero headline). Never use rose for decoration, section backgrounds, borders or icons beyond those points; its tint, Blush, is the only rose surface.

**The One Dark Field Rule.** Night Rose is the field for results and the footer only. Photographs of results sit on it; nothing else goes dark.

**The Channel Colours Belong to the Channel Rule.** Viber violet and WhatsApp teal appear only on their own buttons, never as accents elsewhere.

## Typography

**Display Font:** Forum (with Times New Roman, serif)
**Label Font:** Tenor Sans (with Gill Sans, sans-serif)
**Body Font:** Golos Text (with system-ui, sans-serif)

**Character:** Forum's flared, slightly engraved Roman forms carry the elegance of her lockup at a large size; Tenor Sans, always in wide-tracked uppercase, carries the studio's quieter second voice; Golos Text is a plain, highly legible Cyrillic-first sans for everything that must be read. All three are self-hosted with Cyrillic and Latin subsets; Forum's Cyrillic file is preloaded.

### Hierarchy
- **Display** (Forum 400, clamp(3rem → 5.75rem), line-height 0.98, -0.02em): the hero headline only. Its second line breaks onto its own line in rose.
- **Headline** (Forum 400, clamp(2.2rem → 3.6rem), 1.05, -0.01em, balanced wrap): every section heading.
- **Quote** (Forum 400, clamp(1.4rem → 1.9rem), 1.3, max 30ch): her quotation in the doctor section, framed by rose Bulgarian quote marks („ “).
- **Title** (Forum 400, 1.6rem, 1.15) and **Title small** (Forum 400, 1.4rem, 1.2): process step names and service names respectively.
- **Lead** (Golos 400, clamp(1.05rem → 1.2rem), max 44ch): the hero introduction; section intros use body at 1.1rem.
- **Body** (Golos 400, 1.0625rem, 1.65): all reading text; paragraph measure held at 38–46ch.
- **Button** (Golos 500, 0.97rem, line-height 1): every button label; 0.9rem small, 1.05rem large.
- **Label** (Tenor Sans 400, 0.62–0.74rem, tracking 0.18–0.22em, uppercase): the "Преди / След" tags, fact labels (Телефон, Адрес, Работно време), the doctor's role line, the "Dental Flower Studio" line of the lockup.
- **Price** (Tenor Sans 400, 1.05rem, 0.04em, tabular lining numerals): service prices, right-aligned on the baseline of the service name.

### Named Rules
**The Lockup Voices Rule.** Forum and Tenor Sans exist because her lockup uses flared Roman caps over a wide humanist sans. Forum takes display, headings and the name; Tenor Sans takes only short uppercase labels and prices. Never set running text in either.

**The Single-Weight Serif Rule.** Forum is used at weight 400 only; hierarchy comes from size, not weight. Golos uses 400 for text and 500 only for button labels.

## Layout

A single centred wrap of 77.5rem, with a fluid side gutter (clamp(1rem → 3rem)) and fluid vertical section padding (clamp(4.5rem → 8.5rem)). Sections alternate ground to mark the story: white hero, night-rose Results, white Approach, blush Services, white Doctor and Studio, a raised white contact card, night-rose footer.

Section headings sit in a two-column head: the heading on the left, a short grey intro paragraph on the right, bottom-aligned. Content below uses two-column grids (hero 1 : 1.08, approach 1 : 1, doctor 0.85 : 1, price list in two columns, cases in two columns with the first case spanning both).

The header is sticky, translucent white with a 10px blur and a hairline bottom border; anchor scrolling offsets by 5.5rem to clear it.

Responsive behaviour:
- Below 1060px the header nav disappears; the rose "Запиши час" button remains.
- Below 860px every two-column grid collapses to one column; the hero photo composition caps at 34rem wide.
- Below 760px a fixed bottom dock with the Viber and WhatsApp pair replaces the header button and the hero buttons, so booking is always one tap away; the body gains 5rem of bottom padding to clear it.
- Below 420px price rows stack name over price.

### Named Rules
**The One Step to Book Rule.** At every width, a Viber/WhatsApp pair or a rose booking button is visible or one tap away: header button on desktop, fixed dock on mobile, the contact card at the end.

## Elevation & Depth

Mostly flat, separated by hairlines and changes of field colour. Shadows are reserved for raised physical things (buttons, photographs, the contact card) and are always soft, long, negatively spread and tinted with the warm ink (rgb 38 34 36), never black and never offset hard.

### Shadow Vocabulary
- **Button rest** (`0 1px 2px rgb(38 34 36 / .12), 0 8px 18px -10px rgb(38 34 36 / .45)`): every button.
- **Button lift** (`0 2px 4px rgb(38 34 36 / .12), 0 14px 26px -12px rgb(38 34 36 / .5)`): button hover, together with a 2px rise.
- **Print** (`0 30px 60px -30px rgb(38 34 36 / .45)`): the large hero "after" photograph.
- **Inset print** (`0 2px 6px rgb(38 34 36 / .12), 0 24px 44px -18px rgb(38 34 36 / .5)`): the overlapping "before" photograph, which also carries a 6px white border like a mounted print.
- **Card** (`0 1px 2px rgb(38 34 36 / .06), 0 30px 70px -40px rgb(38 34 36 / .45)`): the contact card.

### Named Rules
**The Hairline-Not-Box Rule.** Lists (process steps, prices, facts) are separated by 1px hairlines, not enclosed in cards. On Blush the hairline is rose at 18% opacity. The contact card is the only enclosed container.

## Shapes

Gentle, small radii on rectangles and full pills on anything you press or any state label. Photographs keep their native portrait proportion (3:4; the full-width case uses 4:5 to keep its height in check) with barely softened corners (4–8px). Buttons and tags are full pills (999px). The contact card is the softest container (10px). The focus ring is a 2px outline offset 3px with a 4px radius.

The only recurring silhouette is her five-petal tooth flower, which appears in the header lockup (grey), on the contact card (rose) and in the footer (night mute). In this build that mark is a hand-drawn stand-in of her logo awaiting the real file; it is not a designed mark and must be replaced, never refined or reused as a pattern.

## Components

### Buttons
Smooth, confident pills that lift slightly under the finger.
- **Shape:** full pill (999px), minimum height 3.25rem, 0 1.5rem padding, icon 1.3rem with 0.6rem gap.
- **Channel buttons (primary booking):** Viber violet and WhatsApp teal with white label and the channel's own icon, always shown as a pair, Viber first. These are the only booking mechanism.
- **Rose button:** Studio Rose with white label, no icon; used for in-page jumps to the contact section ("Запиши час", "Запишете консултация").
- **Hover / Focus:** hover darkens to the deep variant, rises 2px and lengthens the shadow (0.3s, cubic-bezier(.16, 1, .3, 1)); active returns to rest; focus shows the rose 2px outline.
- **Sizes:** small (2.6rem, header), default (3.25rem; 3rem in the dock), large (3.75rem, contact card).
- **Text link:** grey underlined link with a hairline-coloured underline that turns rose with the text on hover.

### Before/After Pair (signature)
The core proof unit, used in the hero and every result.
- **Order:** "Преди" (before) on the left, "След" (after) on the right. Never reversed.
- **Crop:** both photographs at the same face-scale, 3:4 portrait, focal point around 35% from the top so the mouth sits in the same place in both frames.
- **Tags:** a pill label in the top-left corner of each photo, Tenor Sans caps. "Преди" is ink on 92% white; "След" is white on Studio Rose.
- **Gallery form:** two photos side by side with a 6px gap on the night field, 4px corners; each photo links to the full image and zooms 1.55x toward the mouth on hover (0.9s ease). Caption below in Night Mute names the treatment.
- **Hero form:** a large "after" print (76% width, right-aligned) wiping in once from left on load, with a smaller "before" print (38% width) overlapping its lower-left corner in a 6px white mount. The caption states that the photos are published with written consent.

### Studio Strip
Four phone photographs of the real premises in walk-through order (entrance, waiting area, certificates wall, treatment room), on the white ground directly after the doctor section. 3:4 crops, 6px corners, a Tenor Sans caps label under each. Four equal columns with every second photo dropped 2.5rem; below 860px it becomes a horizontal scroll-snap strip that bleeds to the screen edge. No hover effect, no links.

### Doctor Portrait
Her supplied phone portrait (`assets/studio/dr-neycheva.jpg`), cropped 4:5 with the focal point high so the face stays in frame, 6px corners.

### Process Steps
A numbered list with large rose Forum numerals (2.6rem) in a 3.5rem column, Forum step title, grey description, hairlines between steps.

### Price List
Two-column list on Blush. Each row: Forum service name and a grey one-line description on the left, a Tenor Sans tabular price on the right on the shared baseline, rose hairline between rows.

### Contact Card
The single raised container: white, 10px radius, card shadow, centred content. Flower mark in rose, headline, short lead, a large Viber/WhatsApp pair, then a three-column facts row (phone, address, hours) with Tenor Sans labels above body-size values, separated from the buttons by a hairline.

### Navigation
- **Header:** sticky translucent bar; lockup on the left (flower mark, name in Forum caps with 0.1em tracking over "Dental Flower Studio" in Tenor Sans caps), grey nav links at 0.92rem that turn ink with a rose underline on hover, a small rose booking button on the right.
- **Footer:** centred on Night Rose: flower mark, name, studio line, wrapped Night Mute links that turn white with an underline on hover, copyright.
- **Mobile dock:** fixed bottom bar below 760px, translucent white with blur and a hairline top border, holding the Viber/WhatsApp pair at equal width.

### Placeholder for client input
Every unknown client fact (phone, address, hours, prices, treatment names) is a `.tbd` em dash with a "Предстои" tooltip, never an invented value. These are temporary and are removed as the client supplies facts.

## Do's and Don'ts

### Do:
- **Do** lead with real before/after results; the photographs are the argument.
- **Do** show every result as a pair: "Преди" left, "След" right, matched face-scale 3:4 crops, a white "Преди" tag and a rose "След" tag.
- **Do** keep booking to Viber and WhatsApp deep links, shown as a pair with their icons, Viber first.
- **Do** keep rose to action, the "after" state and a few small ink anchors (numerals, quote marks, the "after" headline line).
- **Do** separate lists with 1px hairlines (#e6e0e2, or rose at 18% on Blush) rather than cards.
- **Do** tint shadows with the warm ink and keep them soft, long and negatively spread.
- **Do** use Bulgarian quote marks („ “) and keep body measure at 38–46ch.
- **Do** mark every unknown client fact with the `.tbd` placeholder instead of a guessed value.
- **Do** honour prefers-reduced-motion: all animation and transitions off.

### Don't:
- **Don't** add JavaScript; the site is static HTML and CSS.
- **Don't** add an email or contact form; booking is Viber and WhatsApp only.
- **Don't** use stock photography or stock smiles; only her own patients' photographs, with consent.
- **Don't** use rose for decoration, section fills, borders or generic icons.
- **Don't** set running text in Forum or Tenor Sans, or use Forum at any weight other than 400.
- **Don't** treat the current flower SVG as a finished mark: it is a stand-in for her logo, to be replaced with the supplied file and never redrawn.
- **Don't** reintroduce the rejected stationery/invitation world or any conceptual metaphor.
- **Don't** add motion beyond the hero wipe-in, the case hover zoom and the button lift.
