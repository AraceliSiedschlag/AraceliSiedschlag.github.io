---
name: Araceli Siedschlag — Personal Site
description: A flat, mostly-monospace engineering ledger for a CS/DS student's professional record, with two scoped sans-serif exceptions.
colors:
  ink: "#0a0a0a"
  signal-blue: "#0066cc"
  body-text: "#2e2e2e"
  muted: "#6b6b6b"
  off-white: "#f4f4f4"
  paper: "#ffffff"
  blue-tint: "#e0f0fa"
typography:
  display:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "56px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "34px"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.01em"
  headline-sub:
    fontFamily: "'IBM Plex Sans', 'Helvetica Neue', Arial, sans-serif"
    fontSize: "22px"
    fontWeight: 700
    lineHeight: 1.1
  wordmark:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "22px"
    fontWeight: 600
  subline:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "18px"
    fontWeight: 700
  title:
    fontFamily: "'Roboto', 'Helvetica Neue', Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 600
    lineHeight: 1.1
  employer:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "13px"
    fontWeight: 500
  body:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.6
  body-dense:
    fontFamily: "'Roboto', 'Helvetica Neue', Arial, sans-serif"
    fontSize: "13px"
    fontWeight: 400
    lineHeight: 1.5
  body-dense-lg:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "13.5px"
    fontWeight: 400
    lineHeight: 1.5
  label:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "11px"
    fontWeight: 400
    letterSpacing: "0.12em"
  label-num:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "14px"
    fontWeight: 400
    letterSpacing: "0.08em"
  cta-line:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "30px"
    fontWeight: 700
    letterSpacing: "-0.01em"
  cta-line-mobile:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "25px"
    fontWeight: 700
  headline-mobile:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "26px"
    fontWeight: 700
  cta-pill:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "12px"
    letterSpacing: "0.08em"
  display-mobile:
    fontFamily: "'JetBrains Mono', 'SFMono-Regular', Menlo, monospace"
    fontSize: "38px"
    fontWeight: 700
    lineHeight: 1.1
rounded:
  none: "0px"
spacing:
  xs: "8px"
  sm: "16px"
  md: "24px"
  lg: "40px"
  xl: "80px"
components:
  button-primary:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "10px 18px"
  button-primary-hover:
    backgroundColor: "{colors.signal-blue}"
  button-secondary:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "14px 26px"
  pill:
    backgroundColor: "{colors.paper}"
    textColor: "{colors.ink}"
    rounded: "{rounded.none}"
    padding: "6px 12px"
  button-accent-solid:
    backgroundColor: "{colors.signal-blue}"
    textColor: "{colors.paper}"
    rounded: "{rounded.none}"
    padding: "14px 26px"
---

# Design System: Araceli Siedschlag — Personal Site

## Overview

**Creative North Star: "The Systems Ledger"**

This is a personal record built like an engineering ledger, not a marketing page: numbered entries, ruled lines, tabular facts. The system is deliberately flat: zero border-radius anywhere, thin 1px rules instead of shadows or cards-with-elevation, and a strict ink/off-white/paper neutral base that lets a single accent, Signal Blue, mark exactly what deserves attention (an active nav item, a role title, a dark highlight card, the closing CTA).

Typography is JetBrains Mono by default — the hero headline, section headers, most section-intro prose, labels, tags, dates, the wordmark, the closing CTA line. IBM Plex Sans is one contained exception: the two degree-banner names, nowhere else. Roboto is the other, and it's grown by individual request rather than a rule the system decided on its own: the Professional/Projects row titles and descriptions (the page's longest continuous reading content), and the Personal section's intro paragraph. Everything structural around those Roboto spots (dates, employer names, the dot-and-rule pattern) stays mono.

The visual language leans on structure rather than embellishment: a three-line ribbon motif top and bottom, `01`–`04` section numbering in Signal Blue, hairline dividers between every list row, and uppercase letter-spaced mono labels for every piece of metadata (dates, tags, kickers). Nothing in the system uses gradients, drop shadows, rounded corners, or a decorative/script typeface — those would all read as decoration in a system whose entire identity is "this is a ledger, not a brochure."

Confirmed rejection: no soft/rounded UI, no card elevation/shadows, no third typeface, no color beyond the single Signal Blue accent.

**Key Characteristics:**
- Flat, ruled, ledger-like structure; hairline rules do the work shadows would do elsewhere.
- One accent (Signal Blue) used sparingly against a strict ink/off-white/paper neutral base.
- Mono-first typography: JetBrains Mono runs most of the page — headlines, section-intro prose, labels, wordmark, CTA — with two scoped exceptions: IBM Plex Sans on the degree-banner names, and Roboto on the job/project titles and descriptions where sustained reading matters most.
- Numbered, uppercase, letter-spaced labels for all metadata and section markers.
- Zero border-radius; every shape is a rectangle.
- Interaction is tactile and in-voice: rows highlight their own rule + dot on hover, tags invert to a "stamped" ink fill — never a generic lift/glow/scale.
- Degrees run as one ruled banner filled solid Signal Blue (white/tinted text, thin white divider), not two boxed cards — the one deliberate large-surface use of the accent.

## Colors

A near-monochrome ledger palette (ink, off-white, paper) with exactly one accent color carrying all emphasis.

### Primary
- **Signal Blue** (#0066cc): The system's only accent. Marks emphasis and action — role titles in timelines/projects, the active nav underline, the section-number glyphs, hero emphasis text, solid CTA buttons/pills, and (its one large-surface use) the full degree-banner background. Everywhere else it stays sparing by design; the banner is a deliberate, named exception — the one place blue is a surface rather than a highlight. Tuned one step darker than a pure #007fff during polish so blue text on white (and white text on blue) both clear 4.5:1 contrast — same hue, same role, verified accessible.

### Neutral
- **Ink** (#0a0a0a): Primary text color for headings, body emphasis, and structural elements (rules, borders, dot markers, primary buttons' background).
- **Body** (#2e2e2e): Running body copy color, one step softer than pure ink.
- **Muted** (#6b6b6b): Secondary/metadata text — employer names, timestamps, footer copy, inactive nav labels.
- **Off-White** (#f4f4f4): Section-level background fill (the Education section) and the fallback surface behind photo slots (the Personal grid, the hero headshot) — shows through only when a slot's image is missing or still loading.
- **Paper** (#ffffff): The page background and the mobile nav panel surface.
- **Blue-Tint** (#e0f0fa): Secondary text specifically on the Signal Blue degree-banner surface — a hue-tinted light blue rather than plain gray, so muted text stays legible and on-hue against a colored background (4.78:1 contrast, verified). Not used anywhere off that surface.

### Named Rules
**The One-Signal Rule.** Signal Blue is the only color that can carry meaning or emphasis. Every other color in the system is neutral (ink, body, muted, off-white, paper); if something needs to stand out, it turns blue — it never gets a new color.

## Typography

**Primary Font:** JetBrains Mono (with SFMono-Regular, Menlo, monospace fallback) — every role except one: hero headline, section headers, body prose, row titles, labels, tags, dates, the wordmark, the closing CTA line.
**Accent Font:** IBM Plex Sans, weight 700 (with Helvetica Neue, Arial, sans-serif fallback) — used in exactly one place: the two degree names on the banner.

**Character:** The ledger's mono voice carries almost the entire page, including its headlines — this is the identity the site keeps returning to after trying (and pulling back from) broader sans/mono splits. IBM Plex Sans is a single, contained sprinkle: distinct enough to make the degree banner feel like its own moment, small enough that it never competes with the mono system as a second voice.

### Hierarchy
- **Display** (JetBrains Mono, 700, 56px, line-height 1.1, letter-spacing -0.02em): Hero headline only.
- **Headline** (JetBrains Mono, 700, 34px, line-height 1.1, letter-spacing -0.01em): Section titles ("Professional", "Projects", etc.).
- **Headline-sub** (IBM Plex Sans, 700, 22px): Degree banner names — the system's one sans-serif use.
- **Wordmark** (JetBrains Mono, 600, 22px): The masthead site name.
- **Subline** (JetBrains Mono, 700, 18px): The hero subline ("Two degrees at Colorado School of Mines...").
- **Title** (Roboto, 600, 17px, line-height 1.1): Row-level titles — timeline role names, project titles — always rendered in Signal Blue. One of two roles that break from mono (see Named Rules); line-height is set explicitly regardless of tag (`<h3>` or `<p>`) so the role reads identically everywhere it's used.
- **Employer/Sub-label** (JetBrains Mono, 500, 13px): The line directly beneath a Title (currently just the timeline's employer name) — one weight step below Title, one above Body-dense, so it reads as its own tier rather than blurring into the description below it.
- **Body** (JetBrains Mono, 400, 16px, line-height 1.6): Running prose in section intros and descriptions; caps at ~58–64ch for readability. One exception: the Personal section's intro paragraph is set in Roboto instead (see Named Rules) — everything else using this role stays mono.
- **CTA-line-mobile** (JetBrains Mono, 700, 25px): The closing CTA headline's mobile (≤860px) size step.
- **Headline-mobile** (JetBrains Mono, 700, 26px): Section headers' mobile (≤860px) size step.
- **Body-dense** (Roboto, 400, 13px): Timeline and project row descriptions specifically — pairs with the Title role above it in the same rows. **Body-dense-lg** (JetBrains Mono, 400, 13.5px): The similar-looking but distinct role for course rows and the note card, which stay mono.
- **Label** (JetBrains Mono, 400, 11px, letter-spacing 0.12em, uppercase): Metadata that reads as a short tag or button — nav items, tags, kickers, footer text, CTAs. The floor is 11px everywhere; nothing on the page goes smaller for interactive or content-bearing text.
- **Label-num** (JetBrains Mono, 400, 14px, letter-spacing 0.08em): The single largest label role, used only for the `01`–`04` section-number glyphs.
- **CTA-line** (JetBrains Mono, 700, 30px, letter-spacing -0.01em): The closing CTA's headline ("Looking for summer 2027 data science work.").
- **CTA-pill** (JetBrains Mono, 400, 12px, letter-spacing 0.08em): Text inside the two closing CTA pills.
- **Display-mobile** (JetBrains Mono, 700, 38px, line-height 1.1): The hero headline's mobile (≤860px) size step.

### Named Rules
**The Two-Exceptions Rule.** JetBrains Mono is the page's typeface by default — headlines, labels, wordmark, CTA, and most intro prose. Exactly two exceptions break from it, each scoped and expanding only by explicit request: IBM Plex Sans on the degree-banner names (a display accent), and Roboto on reading-heavy content — currently the Professional/Projects row titles-and-descriptions and the Personal section's intro paragraph. Each new Roboto addition has been a deliberate, individually-requested carve-out, not a rule the system applies on its own judgment; don't add another one without being asked.

## Layout

A single centered column system for most sections (`max-width: 1040px`, `margin: 0 auto`, 24px horizontal padding on desktop / 20px on mobile), with two deliberate exceptions: the hero and the closing CTA narrow to 760px/720px for a tighter reading measure, and the hero itself is two-column, not stacked — a 340px photo on the left, the headline, subline, and a contact pill filling the remaining width on the right, vertically centered. Section rhythm is generous and consistent — 80px vertical padding per section (56px on mobile at the ≤860px breakpoint), each section opening with a full-width top rule. Below 860px, the top nav collapses into a toggled full-width panel, the hero switches from a row to a stacked column (photo on top, capped at 220px wide, text below), the degree banner stacks to a single column with its divider rotating to horizontal, and the five-photo Personal grid drops from 5 columns to 2. Density is even and generous — this is a resting, non-cramped ledger, not a compressed data table.

Coursework is a two-part structure, not a single grid: the two course lists ("Completed", "In progress") sit in a 2-column grid because they're the same kind of content at different lengths, while "What I use it for" (a short reflective note, not a list) runs as its own full-width row beneath, separated by a hairline rule, with a fixed-width label column beside the note card. Grouping equal-height list columns together and giving the qualitative aside its own horizontal band avoids the empty-space problem of forcing three unequal content types into one equal-height grid row.

### Named Rules
**The Equivalent-Columns Rule.** Only put content in side-by-side equal-width columns when it's genuinely the same kind of content. A list and a short qualitative note are not columns of the same row — the note gets its own full-width band instead.

## Elevation & Depth

Flat by design: no box-shadows anywhere in the system. Depth and separation are conveyed entirely through rules (1px solid borders) and tonal contrast (off-white section backgrounds against a white page, a solid Signal Blue divider between banner entries) rather than shadow or blur.

### Named Rules
**The Flat-By-Default Rule.** No surface ever lifts on shadow. Separation between elements comes from a hairline rule or a flat background-color shift — never from elevation.

## Shapes

Purely rectangular: `border-radius: 0` is set explicitly even on elements (pills, photo slots, timeline dots) that would default to round in most design systems. Borders are always 1px solid, either full-strength ink (`--rule`) for structural dividers (masthead, section tops, the degree banner) or a faint gray `#d9d9d9` (`--rule-faint`) for internal list rows. The recurring geometric signature is the three-line "ribbon" motif (ink / blue / ink, 2–3px tall) that opens and closes the page — echoed at smaller scale by the degree banner's own Signal Blue divider.

## Components

Every interactive and static component shares the same terse, utilitarian character: no rounding, no shadow, thin rules, and uppercase mono labels wherever there's metadata to show.

### Buttons
- **Shape:** Square corners throughout (0px radius).
- **Primary (resume button):** Ink background (#0a0a0a), white text, 10px/18px padding, uppercase 11px label type with 0.12em letter-spacing.
- **Secondary/Outline (CTA "Download resume"):** Transparent/paper background, 1px ink border, ink text, 14px/26px padding.
- **Solid accent (CTA email pill):** Signal Blue background, white text — the one button variant that uses the accent as a fill rather than a border.
- **Hero contact pill:** Reuses the CTA's outline pill classes directly (`cta__pill cta__pill--outline`) rather than a new component — same `mailto:` action, same visual language, just surfaced where a visitor lands first instead of only at the very bottom of the page.

### Chips / Pills
- **Style:** Paper background, 1px ink border, ink text, uppercase 11px label type, 0.1–0.12em letter-spacing, 6–7px/12–14px padding.
- **Use:** Skill tags and "what I use it for" pills — always neutral, never accent-colored, since color is reserved for content emphasis, not tags.
- **Hover:** Inverts to a solid ink fill with white text — reads as a "stamped" record, not a lift or glow. Non-clickable, but responsive to the cursor as a tactile detail.

### Banner (degrees)
- **Shape:** One continuous horizontal band, filled solid Signal Blue, framed by top and bottom ink rules (`border-top`/`border-bottom: 1px solid var(--ink)`) — no card container around either entry.
- **Text on the banner:** Name in white (Headline-sub role); detail line in Blue-Tint (#e0f0fa), not plain muted gray — colored surfaces get hue-tinted secondary text, never gray-on-color; date in white, uppercase Label role.
- **Divider:** A 1px translucent white rule between the two degree entries (horizontal on mobile) — thin and structural, not a Signal Blue accent line, since the surface itself is already blue.
- **Internal Padding:** 28px/32px per entry (22px/20px on mobile).
- **Why a banner, not cards:** two boxed cards read as two separate objects; a single ruled, colored band reads as one record with two rows — closer to the ledger's own "one continuous sheet" logic than a pair of isolated containers.

### Navigation
- **Style:** Uppercase 11px mono labels, 0.12em letter-spacing, Muted-gray by default. The active section's label goes ink with a thickened (3px) Signal Blue underline; inactive items keep a thin 2px muted-gray underline. Hover goes ink with an ink underline. (Distinction is color-only, not opacity — opacity-dimmed gray text failed contrast and was fixed during polish.)
- **Items:** Professional, Coursework, Projects, Personal (each scroll-spied against its section), a Contact dropdown, and the separately-styled Resume button.
- **Contact dropdown:** A bare `mailto:` nav link was tried first and removed — it's easy to mistake for broken since nothing visibly happens without a configured mail client. The current version is a button (`nav__contact-toggle`, styled and underlined like a normal nav item) that toggles a bordered dropdown panel (`nav__contact-dropdown`) showing the email as a real, selectable/clickable text link. It always gives visible feedback on click regardless of mail-client setup, and it lives in the sticky masthead, so it's reachable from anywhere on the page without scrolling — no separate floating action button needed. Closes on outside click, Escape (returning focus to the toggle), or navigating to another section.
- **Mobile header contact icon:** Text "Contact" plus "Menu" plus the wordmark doesn't fit in the mobile header row (~406px needed at typical sizes vs. 375px on the smallest common phone) — a text label was tried and rejected for width. Instead, a small drawn envelope icon (`mobile-contact-toggle`, plain stroke SVG, no icon-font/emoji) sits directly beside "Menu" in a `mobile-controls` wrapper, always visible without opening the hamburger menu, toggling the same dropdown pattern. Both buttons share an explicit 38px height (rather than each deriving its own height from padding/line-height, which happened to land at slightly different values) so the two boxes read as one matched pair, not two different-sized controls next to each other. Both mobile-controls buttons are `flex-shrink: 0`; the wordmark is the one element allowed to truncate (`text-overflow: ellipsis`) if a viewport is narrower than all three items combined — the icon and Menu button never lose space to the name.
- **Overflow:** The desktop nav wraps (`flex-wrap: wrap`, right-aligned) rather than overflowing if a future item ever pushes total width past what the masthead can hold before the mobile breakpoint kicks in.
- **Mobile:** Below 860px, the nav collapses behind a bordered "Menu" toggle button and opens as a full-width paper panel with left-aligned, horizontally-laid-out items; the Contact dropdown becomes a borderless, transparent inline reveal in that same panel rather than a floating bordered card.

### List Rows (timeline / project rows)
A signature recurring pattern: a small square ink dot, a title in Signal Blue, a muted secondary line, and a regular-weight description in Body color, separated from the next row by a faint hairline rule. Used identically for the Professional timeline and the Projects list — the system's primary way of presenting "one record, then the next." The title and description are set in Roboto (the Title and Body-dense roles); the dot, date, and employer/kicker line around them stay mono — this is the one place in the system where the reading content itself, not just a headline, breaks from the mono default. Project rows may close with an optional `project-row__link` line (11px, uppercase, muted, e.g. "Code available on request") when no public repo/demo exists yet — same Label treatment as everywhere else, not a distinct "coming soon" style.
- **Hover:** The row's top hairline rule darkens from faint gray to ink, and its dot fills solid Signal Blue — the row reads as "highlighted," the way a finger traces a line in a paper ledger. No shadow, no lift, no background fill.

### Group Labels (coursework / skills)
When a list or pill row would otherwise exceed ~4 items, split it into labeled sub-groups rather than leaving one long undifferentiated list. Each group gets a small muted uppercase label (`course-group__label` / `skill-group__label`, 11px, 0.1em tracking) above it, with 20px separating one group from the next. This is a chunking device, not a new visual role — it borrows the same Label treatment used everywhere else.

### Photos (hero headshot, Personal grid)
Real photos now fill both the hero (a 4:5 portrait crop, `object-fit: cover`, 1px ink border, no radius) and the Personal section's grid (five photos, 3:4 crop each, same border treatment, `overflow: hidden` on the slot). No placeholder is currently showing anywhere on the page. If a slot goes empty again in the future (a new grid position added before a photo exists for it, say), reuse the retired Image Placeholder pattern rather than inventing a new one: an off-white, 1px-ink-bordered, zero-radius box holding a centered uppercase Label ("05 — Pending"). No stock imagery, no icon standing in for a person — an honest gap reads better than a fake fill.

### Resume Embed (CTA section)
An inline `<iframe>` showing the résumé PDF directly on the page, borderless — the PDF's own page edge reads as its boundary, no framing device needed. Sits below the CTA pills, so the download/mailto actions stay the primary path while the PDF itself is immediately viewable without a click. Deliberately breaks out of the CTA section's 720px text measure (up to 960px wide, full-viewport-width on narrow screens) since a résumé needs to actually be readable, not constrained to match paragraph width; height is driven by `aspect-ratio: 8.5 / 11` rather than a fixed pixel value, so the full page stays visible at any viewport width without internal scrolling. Where inline PDF rendering is less reliable (some mobile browsers), the "Download resume" pill above it remains the fallback.

## Do's and Don'ts

### Do:
- **Do** keep JetBrains Mono as the page's default typeface, and confine the two exceptions to their scoped roles: IBM Plex Sans on degree-banner names, Roboto on the Professional/Projects row titles-and-descriptions and the Personal intro — see the Two-Exceptions Rule. Never expand either without an explicit decision.
- **Do** reserve Signal Blue for emphasis and action only — role/project titles, active nav, the one highlight card, solid CTAs.
- **Do** use hairline rules (`--rule` or `--rule-faint`) as the only separation device between stacked records; don't reach for shadow or elevation instead.
- **Do** keep every corner square (`border-radius: 0`) on every component, including pills and image placeholders.
- **Do** set metadata (dates, tags, kickers, nav labels) in uppercase mono with 0.08–0.12em letter-spacing, 11px minimum — nothing content-bearing goes below 11px.
- **Do** give every link, button, and pill a hover state (Signal Blue or ink, matching its default treatment) — a control that only reacts on click reads as unfinished.
- **Do** ground interactive moments in the ledger's own vocabulary — a row's hairline rule and dot responding on hover, a pill inverting to a "stamped" ink fill — never a generic card-lift, glow, or scale transform.
- **Do** distinguish active/inactive/hover nav and text states by color and weight, never by opacity alone — opacity dimming compounds with an already-midtone gray and fails contrast.
- **Do** respect `prefers-reduced-motion` on the scroll-reveal transition.

### Don't:
- **Don't** add a second accent color; if something new needs emphasis, it uses Signal Blue or it stays neutral.
- **Don't** add drop shadows, gradients, or rounded corners anywhere — they contradict the flat ledger metaphor.
- **Don't** introduce a fourth typeface, use IBM Plex Sans anywhere except the degree-banner names, or add Roboto to a new role without being explicitly asked — the mono-default-with-two-exceptions split is the system's current core identity, and Roboto's footprint has grown by individual request each time, not by a standing rule.
- **Don't** box the degree entries back into separate bordered cards; the banner (one ruled band, one internal divider) is the current form.
- **Don't** fill an empty photo slot or headshot placeholder with stock imagery or invented content — leave it as an honest off-white placeholder, labeled in-voice ("05 — Pending", in the Label role), until a real photo exists for it.
- **Don't** put a kicker/eyebrow label above a heading; fold the qualifying detail into the heading text itself instead (e.g. "B.S. in Computer Science", not "Bachelor of Science" over "Computer Science").
- **Don't** bold supporting/description copy as heavily as the title it supports; descriptions stay at regular weight in Body color so the Signal Blue title still leads.
- **Don't** reach for a generic "AI portfolio" interaction (card hover-lift, glow, gradient shimmer, bounce) — every interactive moment must trace back to something already in the ledger's own visual vocabulary.
