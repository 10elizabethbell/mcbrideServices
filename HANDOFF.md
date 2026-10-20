# McBride Services LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/mcbrideServices/ · **Repo:** https://github.com/10elizabethbell/mcbrideServices · **Built:** 2026-10-20 from Muse brief of 2026-10-20 (flyer cross-posted to two NJ Facebook groups)

## Confirm first
- **Does 609.206.1300 take texts?** The hero's "Text Travis", the estimate form and the floating circle all open a text. If it's a landline, switch them to call / copy-message.
- **HIC #13VH13310600** against the NJ license lookup (see gaps).

## What's built
- One page, calm band style: white header (real McBride logo cropped from the flyer, tap-to-call 609.206.1300 top right) → water-navy hero → paper trust band → navy services → deep-navy "How it works" → paper estimate form → navy close → deep footer.
- Palette mapped from the logo and flyer: paper #f4f6fb; water navy #143a5e and deep navy #0b2038 (the flyer's black bottom band, made navy); McBride logo green #4cb648 as the one accent fill with navy text on it; the logo's own #1f6929 when green has to be text on light; water blue #1d64b0 for form hover/focus outlines.
- Hero: plain textured navy band (no usable photo, see gaps). Eyebrow "Sewer & drain · Licensed & insured", H1 "Drains flowing again in Shamong & West Creek." with the letter bounce-in, one promise line naming Travis, two buttons: "Get a free estimate" (filled, scrolls to the form) and "Text Travis" (outlined, `sms:`).
- Trust: "I'll show you what's down there." (the video inspection differentiator, per Muse's note) plus three flyer claims: Licensed & insured (NJ HIC #13VH13310600), Fast response, Honest & reliable ("Free estimates" was cut from the list as the sixth repeat of the phrase).
- Services: the flyer's seven services as rows; each row jumps to the form and pre-selects the matching chip.
- Estimate form: job chips, name (required), town, what's happening → composes a text to Travis; if the page is still in view 1.2s after submit (no Messages app opened), a fallback shows the number and a "copy your message" button.
- Floating text circle on (hidden on the hero and over the form). Fade-up on below-the-fold content. All content shows at once with reduced motion or no JS.
- Favicon / home-screen icon: a white "M" on logo green (the logo itself is unreadable at 16px). og.png (1200×630) for the Facebook link preview.

## Assumptions I made
- **Email is mcbrideservicesllc@gmail.com** — read off the flyer image. The brief says "mecbride…"; that's Muse's typo. Footer only.
- **Voice is first person "I" as Travis.** The flyer names only Travis; his wife posts the ads. If it's a crew, switch to "we".
- **Texting works on 609.206.1300.** The brief says unknown; the flyer only says "call". The header number, close and the form fallback all still offer the call.
- **"I can run a camera down your line to find exactly where the problem is, so you see it for yourself before anything gets dug up."** — inferred from the flyer's "Video sewer inspections — Locate problems. See the difference." Confirm with Travis that he shows customers the footage.
- **Service area** is the flyer's "Shamong/West Creek, New Jersey", read as two towns. The page invites "Not sure I cover your town? Call and ask." rather than listing towns.
- **Customers aren't treated as a 40+ audience** (brief doesn't say), so the default calm motion is in.
- How-it-works step copy ("I look first, then tell you plainly what it needs", "Dependable service, clean results." is the flyer's own line) paraphrases flyer lines "Dependable service. Clean results." / "Honest & reliable".

## Placeholders and gaps
- **HIC #13VH13310600** matches the flyer image, but I haven't checked it against the NJ Division of Consumer Affairs license lookup. Check before handing over (or drop the number and keep "Licensed & insured").
- **No Facebook link anywhere.** There's no business page; the ads come from Lisa McBride's personal profile, which shouldn't be the public "see my work" link. When Travis has a page, add the "Click to see more of my work." row under a proof section and in the footer.
- **No photos of real jobs.** The flyer's pictures (drain, camera, jetter, pipes) look like stock/illustrations, so none are used. No proof section exists yet.
- Logo is a 536px crop of a 600px flyer JPEG on white: it's fine in the white header but soft. Ask for the original file.
- No hours, no reviews, no prices, no years in business.

## Questions for the owner
- Do you take texts on 609.206.1300?
- Could you send the original logo file and 4–6 photos of real jobs (camera screen shots, a dug-up line, a jetter in action, before/after)?
- Which towns do you cover between Shamong and West Creek? (Tabernacle, Medford, Southampton, Little Egg Harbor, Tuckerton…?)
- Emergency / after-hours calls? Hours?
- Do you show customers the camera footage (or send them the video)?
- Is it just you, or a crew ("I" vs "we")?
- Any Google reviews or happy customers willing to be quoted?

## Ideas not built (yours to pick)
- **Signature world, runner-up:** a camera crawling down a sewer pipe in the hero, its light sweeping the pipe walls, stopping at a root intrusion; drag to steer the camera. Other worlds considered: hydro-jet spray blasting a clog clear (drag to jet), water flowing through the logo's silver pipe, roots growing into a line, ripples from the flyer's water drop.
- A proof section with a "camera view" frame (rounded monitor look) for Travis's real inspection stills, once supplied.
- "Before you call" mini FAQ (Is the estimate really free? Do I need to be home? Can you find my sewer line?) — only with Travis's answers.
- Desktop hero right side is empty (calm style, like DPG). Could hold a large real job photo once one exists.
- Finish reviewer wanted the footer cut to just email + licence, since the close band's big number and the footer's number can share one phone screen. Not applied: your rules allow the number again in the close and footer, and the calm footer carries name, area, phone and email. Your call.
- Impeccable findings kept on purpose (Ellie's calm-style choices): eyebrow pills, the repeating-gradient band texture, the H1 bounce-in, the floating circle, Cal Sans.

## Not verified
- Real-device touch and the `sms:` handoff on iOS/Android (body decoding checked in headless Chrome only).
- Inside Facebook's in-app browser.
- Input fill #e6ecf5 on the white form card is 1.19:1 (WCAG 1.4.11 asks 3:1). It is the house value from the calm style; labels sit above every field. Darken to ~#cfd9e8 if you want it to pass.
- Frame rate of the bounce-in on old phones.
