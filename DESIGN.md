---
name: McBride Services LLC
description: Travis McBride, sewer and drain in Shamong and West Creek, NJ. Calm paper and water-navy bands, one green thing to do.
colors:
  mcbride-green: "#4cb648"
  mcbride-green-hover: "#64c560"
  green-lit: "#74cc6c"
  green-ink: "#1f6929"
  water-navy: "#143a5e"
  deep-navy: "#0b2038"
  ink: "#0b2038"
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  body-text: "#26384b"
  soft-text: "#4a5a6b"
  on-dark: "#f4f7fb"
  on-dark-soft: "#c6d5e6"
  water-blue-focus: "#1d64b0"
  error-red: "#b3261e"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(40px, 11.4vw, 80px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  display-desktop:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(64px, 6vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  headline-phone:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  title-list:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(20px, 5.6vw, 24px)"
    fontWeight: 400
    lineHeight: 1.2
  title-step:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "21px"
    fontWeight: 400
    lineHeight: 1.2
  label-display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
  numeral:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "20px"
    fontWeight: 400
    lineHeight: 1
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
rounded:
  field: "10px"
  card: "24px"
  pill: "999px"
spacing:
  chip-gap: "10px"
  stack: "16px"
  field-gap: "20px"
  gutter: "20px"
  gutter-desktop: "40px"
  card-padding: "clamp(20px, 5vw, 32px)"
  section: "64px"
  section-desktop: "96px"
components:
  button-primary:
    backgroundColor: "{colors.mcbride-green}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.mcbride-green-hover}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  eyebrow:
    backgroundColor: "rgba(11,32,56,.06)"
    textColor: "{colors.ink}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "9px 14px"
  eyebrow-on-dark:
    backgroundColor: "rgba(255,255,255,.12)"
    textColor: "{colors.on-dark}"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-padding}"
  input-field:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  arrow-circle:
    backgroundColor: "rgba(255,255,255,.1)"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.pill}"
    size: "44px"
  arrow-circle-hover:
    backgroundColor: "{colors.mcbride-green}"
    textColor: "{colors.ink}"
  step-numeral:
    backgroundColor: "{colors.mcbride-green}"
    textColor: "{colors.ink}"
    typography: "{typography.numeral}"
    rounded: "{rounded.pill}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.mcbride-green}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    size: "60px"
---

# Design System: McBride Services LLC

## Overview

**Creative North Star: "Clear Water, One Green Valve"**

A local trade page that earns trust through calm order. Full-bleed bands alternate between off-white paper and two water navies, so every section boundary is obvious from a phone thumb-scroll. Against all that blue, the McBride logo's green is the only saturated colour, and it appears only where there is something to do: the estimate button, the text circle, the service-row arrow on hover, and the step numerals. Everything is soft and borderless: pill buttons, 24px cards, tinted fields.

Density is low and the reading is plain. One display face (Cal Sans) carries headings, phone numbers, buttons and labels; the system stack carries running text at 16/1.7. There are no photos; the bands, the faint diagonal line texture on the navies and the real logo on a white header carry the atmosphere. Motion is three moments and no more: the hero H1 bounces in letter by letter, content below the first screen rises 12px once, and the text circle slides in after the hero.

This is Ellie's house "calm band" world (learned from lpmr.co.uk, first built for DPG Home Improvement), tuned to McBride's logo: green replaces the house gold, and the navies lean toward water.

**Key Characteristics:**
- Paper / water navy / paper / deep navy band rhythm, never a black ground.
- One accent fill (McBride green) with navy text on it; green as text only in its darker or lighter tuned shades.
- Cal Sans at weight 400 for every display role; system sans for body.
- Pills, 24px cards, 10px tinted fields; no borders at rest, no card shadows.
- Hover and focus show as a water-blue outline or a green arrow fill, never as a page-wide change.

## Colors

Two water navies on cool paper, with the logo's green as the single place to act.

### Primary
- **McBride Green** (mcbride-green): the one accent, used only as a fill: primary buttons, the floating text circle, step numerals, the arrow circle on hover, the eyebrow dot and text selection. Text on it is always Ink (6.3:1).
- **McBride Green, Lifted** (mcbride-green-hover): the primary button's hover fill only.
- **Green Lit** (green-lit): green as text or icon on navy: the accent phrase in dark-band headings, the closing phone icon, footer link hover, and the focus ring on dark bands (5.9:1 on water navy).
- **Logo Green Ink** (green-ink): the logo's own green, used when green has to be a mark on a light ground: trust-list icons, the header phone icon and its hover (6.2:1 on paper).

### Neutral
- **Water Navy** (water-navy): hero, services and closing bands.
- **Deep Navy** (deep-navy): the "how it works" band and the footer, always with the diagonal line texture.
- **Ink** (ink): headings and labels on light grounds, text on green, and the selected chip fill. Same value as Deep Navy, used in a text role.
- **Paper** (paper): the page ground and light bands.
- **Card White** (card): the header (so the logo's own white ground disappears) and the form card.
- **Field Tint** (field): fill of inputs and chips on the white form card.
- **Body Text** (body-text) and **Soft Text** (soft-text): running and secondary copy on light grounds (11.1:1 and 6.6:1 on paper).
- **On Dark** (on-dark) and **On Dark Soft** (on-dark-soft): headings and running copy on the navies (on-dark-soft is 7.8:1 on water navy).
- **Water Blue** (water-blue-focus): the form's hover and focus outline, caret colour and link hover inside the form. Deliberately not green, so a focused control never looks like a filled action.
- **Error Red** (error-red): field error border and the plain-sentence error message.
- **Hairline** (`rgba(11,32,56,.12)` on light, `rgba(255,255,255,.12)` on navy): the only lines in the system, dividing list rows.

### Named Rules
**The One Green Valve Rule.** Green fills mean "do this". Nothing decorative, no large green areas, no green section backgrounds. If an element isn't an action or a marker of one, it isn't green.

**The Tuned Green Rule.** Mid green never appears as text. On light grounds use Logo Green Ink; on navy use Green Lit. On a green fill, text is Ink, never white.

**The Accent Phrase Rule.** Only headings on dark bands (the hero and navy bands) set their last phrase in Green Lit. Headings on paper stay all Ink.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system sans (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** A friendly, rounded geometric display face doing every "say it out loud" job (headings, phone numbers, buttons, field labels), over an invisible system body that reads like a text message.

### Hierarchy
- **Display** (400, fluid 40 to 80px on phones, 64 to 84px from 1024px, 1.02): the hero H1 only. Max 13ch on phones, 17ch on tablets; on desktop the accent phrase drops to its own line.
- **Headline** (400, fluid 30 to 48px, 1.08, balanced wrap): every section H2.
- **Headline Phone** (400, fluid 30 to 52px, 1): the big tap-to-call number in the closing band.
- **Title List** (400, fluid 20 to 24px, 1.2): service rows and trust claims (claims sit at 1.15).
- **Title Step** (400, 21px, 22px on desktop, 1.2): step titles.
- **Label Display** (400, 17px, 1.2): form labels and legends; the header phone number uses the same face at 17px, 20px on desktop.
- **Button** (400, 18px, 1): all pill buttons.
- **Lede** (system, fluid 17 to 19px, 1.7, max 38ch): one sentence under a section heading. The hero promise is the same role at 17 to 20px, 1.5, max 32ch.
- **Body** (system, 16px, 1.7): running text and every input (16px so iOS doesn't zoom).
- **Label** (system 500, 14px, 0.02em): eyebrow pills, field hints, licence lines and the form footnote.

### Named Rules
**The One Display Face Rule.** Cal Sans at 400 is the only display face and the only display weight. Emphasis comes from size and colour, never from bold display type.

**The Sixteen Floor Rule.** Nothing a person types or reads as running copy goes below 16px; 14px is reserved for labels and fine print.

## Layout

A single centred column, max 1160px, with a 20px phone gutter that opens to 40px from 760px. Each section is a full-bleed band with 64px vertical padding (96px from 760px); the hero sits at 56/64px on phones and 96/112px on desktop. A section head is a left-aligned stack (16px gap, max 640px wide): optional eyebrow, H2, optional lede.

Responsive steps are 760px and 1024px. At 760px the hero buttons go side by side (min 240px each) and the seven service rows split into two columns (3 and 4, 56px apart). At 1024px the trust section and the estimate section become two-column splits with a 64px gap (the estimate heading sticks at 40px from the top), the steps go three across with 40px between, and the closing band puts the name left and the big number right. Below 380px chips tighten their side padding to 14px.

Content is laid out as lists divided by hairlines, not as grids of boxes. Every tap target is 44px or taller.

## Elevation & Depth

Flat. Depth comes from band contrast (paper against navy) and the faint 135deg line texture on the hero and deep-navy bands (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`), kept at about 4% white so it never reads as lines through text. Cards and fields have no shadow and no border at rest.

### Shadow Vocabulary
- **Floating lift** (`box-shadow: 0 10px 28px rgba(8,24,46,.3)`): the floating text circle only, because it is the one element that sits above the page.

### Named Rules
**The Flat Page Rule.** Only the floating text circle casts a shadow. Anything in the page flow is separated by band colour or a hairline, never by elevation.

## Shapes

Three corner values and nothing between them: full pills (999px) for buttons, chips, eyebrows and every circle (arrows, numerals, the text circle); 24px for the form card; 10px for text fields. Borders exist only as state: a 2px transparent border on buttons, fields and chips that takes colour on hover, focus or error, plus the hairline row dividers.

## Components

### Buttons
Big, soft and unmissable on a phone.
- **Shape:** full pill, 56px tall, 26px side padding, 18px Cal Sans, 10px gap to an optional 20px icon.
- **Primary:** McBride Green fill with Ink text. Full width inside the form.
- **Ghost:** transparent with a 2px border of on-dark at 70%, on-dark text; used only on dark bands as the secondary action.
- **Hover / Focus:** primary lifts to the hover green; ghost firms its border to white over a 10% white wash. Inside the form the primary also gains a 2px water-blue outline at 2px offset. Press scales to 0.98. Hover styles apply only on devices that really hover.
- **Limit:** at most two buttons together: one primary, one ghost.

### Eyebrow
A quiet label above the hero headline and a few section heads, never every one (here: hero, services, estimate).
- **Style:** 14px system 500 in a pill (9px by 14px) on a 6% ink tint, or 12% white on dark bands, led by a 7px McBride Green dot.
- **Rules:** a `<p>`, never a heading; no arrow, no hover, no shadow, never a full-strength green fill, so it can't be mistaken for a button. Ellie's chosen exception to the Impeccable floor against eyebrows; see the conflict note in HANDOFF.md.

### Chips
- **Style:** 48px pill on Field Tint, 18px side padding, 16px Ink text, 10px gap, wrapping.
- **State:** selected fills with Ink and white text. Hover shows a water-blue border; selected-and-hovered and keyboard focus show a water-blue outline offset 2px (not a border, which would vanish on the Ink fill).

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card White on a paper band.
- **Shadow Strategy:** none (see Elevation).
- **Border:** none.
- **Internal Padding:** fluid 20 to 32px, 20px between fields.

### Inputs / Fields
- **Style:** Field Tint fill, 10px corners, a 2px transparent border, 13px by 14px padding, 52px minimum height (textarea 110px), 16px Ink text, a slate placeholder, a water-blue caret. Each field has a Cal Sans label above it and an optional "(optional)" hint at 14px.
- **Focus / Hover:** the border turns water blue; no glow.
- **Error:** the border turns Error Red and stays red while focused; the message is a plain 16px sentence below the field.

### Navigation
- **Header:** white, 72px (84px from 760px), the real logo left at 54px (64px) high, the tap-to-call number right in Cal Sans with a Logo Green Ink phone icon. No menu.
- **Footer:** deep navy with the line texture; name in 20px Cal Sans, then area, phone and email as 44px-tall on-dark links that turn Green Lit on hover, then the licence line at 14px.

### Service Rows
The signature list on water navy. Each whole row is the link: 72px minimum, Title List type in on-dark, a hairline between rows, and a 44px arrow circle on the right (10% white wash). Only the arrow changes: on hover or focus it fills McBride Green with an Ink arrow, and keyboard focus rings the arrow, not the row. Tapping a row pre-selects the matching chip in the form.

### Step List
Numbered steps on deep navy: a 48px McBride Green circle with the number in 20px Cal Sans Ink, the step title in Title Step on-dark, and one line of on-dark-soft text.

### Trust List
Claims on paper as a divided list: a 40px stroked line icon in Logo Green Ink, the claim in Title List Ink, an optional 14px soft-text proof line (the licence number) beneath.

### Floating Text Circle
A 60px McBride Green circle bottom right (16px plus safe area) holding a 26px chat icon, opening an `sms:` link with a pre-written message. It slides up from 120px below once the hero has scrolled away (0.35s, `cubic-bezier(.2,.8,.2,1)`) and hides while the estimate form is on screen; when hidden it leaves the tab order and the accessibility tree.

### Motion
- **Hero H1 bounce-in:** JS splits the hero H1 into letters (words kept whole); each slides from 50px right and fades in over 1s on `cubic-bezier(.34,1.56,.64,1)`, 20ms apart, after Cal Sans loads (600ms cap). When the last letter lands the plain heading is restored. Hero H1 only.
- **Fade-up:** items below the first screen rise 12px and fade in over 0.4s ease-out, once.
- **State transitions:** 0.2s for buttons and arrows, 0.15s for fields and chips.
- All of it is off under reduced motion, and everything is visible without JS.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed bands (paper, water navy, deep navy) so every new section is obvious, and put the 135deg line texture only on the hero and deep-navy bands at 3.5% white.
- **Do** keep McBride Green to fills that mean "act", with Ink text on them.
- **Do** use Logo Green Ink for green marks on light grounds and Green Lit for green on navy.
- **Do** set every heading, number, button and form label in Cal Sans 400, and every input at 16px or larger.
- **Do** make focus visible everywhere: 3px water-blue outline at 3px offset on light, Green Lit on dark bands.
- **Do** keep tap targets at 44px or larger, including footer links and inline text links.
- **Do** keep everything visible at rest; motion only reveals what JS has hidden below the first screen.

### Don't:
- **Don't** use a black ground; the darkest surface is Deep Navy.
- **Don't** put white text on green or mid green as text on paper (both fail contrast).
- **Don't** add shadows to cards, fields or bands; only the floating circle lifts.
- **Don't** give headings on paper a green accent phrase; that treatment belongs to dark bands.
- **Don't** let the letter bounce-in touch any heading but the hero H1, and don't add parallax, counters or carousels.
- **Don't** add a bottom contact bar; the single floating circle is the only fixed element.
- **Don't** add a second display face or bold display weights.
