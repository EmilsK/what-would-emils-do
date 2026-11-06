---
name: what-would-emils-do
description: Emīls Kraucis's product-design taste as when → do → because rules an agent can apply. Restraint, layout and spacing, colour and surfaces, type, interface copy, forms, empty and loading and error states, motion. Use when designing, building or reviewing a screen, page, component, form or line of UI copy, when asked "what would Emīls do", and before calling visual work done (run CHECK.md). Not design tokens, a design system, or brand and marketing strategy.
license: MIT
metadata:
  author: EmilsK
---

# What would Emīls do

WWED for short: how Emīls Kraucis designs, written down so an agent designs like him and not like a generic model. Each line is one call in the shape *when → do → because*, with the cost where there is one. That shape lets a line fire in the right situation and carry to cases it never named. `[his call, date]` marks a thing he said; `[inferred]` marks an agent's reading of his work, not confirmed. The file changes over time and the newest wording wins. He reviewed every line on 2026-11-06. Last prune: 2026-11-06 · next pass: December 2026.

## How to use this

- Read it before the work, not after. Make the thing, then run [CHECK.md](CHECK.md), the questions in this folder, before calling it done, and say what failed.
- When reviewing against it: name the lines the work relies on and the ones it breaks, then the smallest change that would make it pass. Nothing is "approved by taste"; the report says what matches, what clashes, and what the taste does not cover. The decision stays with the person.
- When a question is open: one question at a time, the recommended option first, short trade-offs, and never a default written down as if it were decided.
- When deciding: use data when there is data, judgment when there is not, and say which, because whoever reads the decision should know how sure to be. `[his call, 2026-10-30]`

## Who

- Product designer, currently at Balsio (work messaging, Riga). Designs for iOS, macOS, Android and the web, and builds a fair share himself: React, HTML/CSS, Figma plugins, small tools, and a few sites and apps of his own. `[his call, 2026-11-06]`
- Writes English and Latvian. Friendly, low-key, specific, a bit decisive. `[his call, 2026-11-06]`
- The look: daylight through frosted glass. Quiet paper and dark ink, with colour arriving as soft light rather than paint, greys tinted the same way across the scale, a lot of space and very few lines. Round shapes, soft edges and a tint do the work that borders and shadows usually do; texture is felt, never noticed. One sans for everything. Motion slow and alive, never busy. When something feels busy it is taken away, not refined, until what is left reads calm, light and alive. `[his call, 2026-11-06; written from the path of the brand-book session, confirmed]`

## The governing rule

- When a design and the shipped thing disagree: the app, a screenshot of it, the code and the data win over a new reading of the design, because the design is only "done" when it is in the app. `[his call, 2026-11-06]`

## What good looks like

- Before adding anything (an element, a colour, a line of copy, a second logo, numbers on a list): try removing instead, because every extra thing is one more thing the reader has to think about. "Don't make me think." Restraint. `[his call, 2026-10-30]`
- When choosing between craft and decoration: fewer lines, calmer motion, warmth from colour and light rather than ornament, and nothing without a job (a border around an avatar, a highlight ring on a destructive row, a coloured arrow on a button that only needs to be found), because decoration without a job reads as noise. Restraint. `[his call, 2026-10-30 and 2026-11-03]`
- When the main thing does not stand out: quiet the neighbours first, and if it still needs a step up, weight or colour before size, because contrast is the gap, not the volume, and size-only hierarchy makes headlines huge and footnotes tiny. Restraint. `[his call, 2026-11-06]`
- When designing for a platform: make it look like that platform (iOS like the current iOS, with its glass and SF Symbols; Android like Android; web like web), and never show a capability the platform lacks, because people trust what feels native, and a promise the platform cannot keep costs that trust. `[his call, 2026-10-02; softened 2026-11-06]`
- Before inventing a pattern: check how others do it and what the platform does natively, because the common pattern wins unless there is a reason; a reason is the price of a new one. `[his call, 2026-10-30]`
- When a value is needed (size, opacity, colour, spacing): take it from the system (tokens, the set type sizes, what the code already uses, the same product on another platform), because ad-hoc numbers drift and nobody can tell them from mistakes. `[his call, 2026-10-30]`
- When a screen is "done": the edge cases are part of it, not a follow-up (empty, loading, error, long names, what a person without permission sees, and whatever a button opens next: a sheet, a picker, a confirm), because the happy path alone is not a design. `[his call, 2026-11-06]`
- Before building anything others will look at: start from the closest existing screen and its real components and text styles, and build a control once and use it twice, because reuse keeps the system one thing. A quick sketch outside the system is for private exploration; shown as an option it reads as sloppy, and a set of options that looks generated does not get a second look. `[his call, 2026-11-05 and 2026-11-06]`
- When a page has several actions: one solid primary, quiet secondaries, and plain links for the rest, because the look should say the rank. `[his call, 2026-11-06]`
- When an action needs explaining: put the explanation where the action lives (a short line under a lone button, a subtitle inside the row of one in a group), because an explanation elsewhere is not read. `[his call, 2026-10-13]`
- When an action is destructive: last, in its own group, quiet in the list and red only on the confirm step, always confirmed with "Yes, delete it" beside "No, keep it" (never Cancel beside Undo), with a short footnote, because the cost of a wrong tap is high, red on every row is noise, and a cancel of a cancel cannot be read. `[his call, 2026-10-02; red on the confirm step and the button words 2026-11-06]`
- When an action would send something in a person's name: never without their own tap, because a message they did not send is not theirs. `[his call, 2026-11-05]`
- When something needs trust: show the real thing instead of explaining it (the exact notification as a preview card, a video that is the app itself), because a picture of what will happen beats words about it. `[his call, 2026-11-03 and 2026-11-06]`
- When a setting has two options: one switch, placed where people expect settings and not at the end of the content, because that means fewer screens and no hunting. `[his call, 2026-11-05]`
- When a step could be a prompt in place (initials with a small + to add a photo): do that instead of a separate step, because every step that can go should go. `[his call, 2026-11-04]`
- When designing a picker: start empty and let people add, rather than full and making them remove, because adding is a choice and removing is a chore. `[his call, 2026-09-04 and 2026-10-30]`
- When showing data: drop the label when the format already says it (an email, a price), or fold it into the value, and keep a label that must stay as the small quiet part, because label-and-value rows give every fact the same weight. `[his call, 2026-11-06]`
- When a section needs a title in an app: a small label, not a headline, because the content should lead. `[his call, 2026-11-06]`
- When accessibility comes up: at least what keeps the thing usable for someone who needs it (Dynamic Type, reduced motion, a screen reader), and deeper where the product or its audience calls for it, because usable is the floor, not the ceiling. `[his call, 2026-11-06]`

## Layout and rhythm

- When two things sit side by side (a month name and its weekdays, an icon and its list, a date and its text, a chat title and its avatar): give them one baseline, because misaligned neighbours read as two separate things. `[his call, 2026-10-30]`
- When setting insets: one value on every side, shared by neighbours (if the sidebar uses 6 px, the banner and the popup use 6 px too), with the optical extra beside a round edge as the one planned exception, because a gap bigger on the right than on the left is a bug, not a choice. `[his call, 2026-10-30]`
- Beside a circle or a pill: add a few extra points of space to the text or element next to it, because a gap that measures even looks uneven next to a round edge. Costs: a number off the grid. `[his call, 2026-10-19 and 2026-10-30]`
- When one component serves pointer and touch: tighter and smaller for the pointer (menus like macOS), roomier and bigger for touch, because density should follow the input, not the component. `[his call, 2026-10-30]`
- When content sits in a frame: it fits (no accidental scroll for a few items, nothing cropped, nothing hanging out), because a frame that does not fit its content looks unfinished. `[his call, 2026-10-30]`
- When choosing a shape: round over square (pills, circles, avatars at radius 999 so they stay round at any size, nested corners concentric), because round reads as soft and alive; a fixed radius is replaced when the platform drops it. `[his call, 2026-10-30]`
- When tuning: one step on the scale, one or two pixels, then look again, because a jump skips the value that was right. `[his call, 2026-10-30]`
- When a control joins a row of existing controls: give it the row's size and look, and colour only the part that carries new information (a count badge, not the whole button or its arrow), because a row with one odd member draws the eye to the wrong place. `[his call, 2026-11-03]`
- When grouping with space alone: more space around a group than inside it (a label tight to its field, groups further apart), because equal gaps make the reader guess what belongs together. `[his call, 2026-11-06]`
- When two things need separating: try space, a background change or a soft shadow before a border, because borders pile up into clutter; a border is fine where the others do not do the job. `[his call, 2026-11-06; not an absolute]`
- When something feels cramped: start with far too much space and take it away until it is right, because space added bit by bit stops at "not bad". `[his call, 2026-11-06]`
- When the screen is wide: give each element the width it needs and leave the rest empty (helper text in a second column before a stretched form), because stretched content is harder to read. `[his call, 2026-11-06]`
- When a screen is dense (a table, a list of numbers): calm it by taking away, because grid lines turn a table into a spreadsheet. No vertical lines; horizontal dividers faint, or none with taller rows; row stripes only when rows are long. `[his call, 2026-11-06]`

## Colour, surfaces and images

- When text is secondary: one step back from primary (a lighter grey, or the opacity the codebase already uses), with primary text at full strength, because two steps of hierarchy are enough and "too bold, too black" is heavy. On colour, light or a photo, secondary text is a darker shade of the same hue, never the fixed grey and never reduced opacity, because text you have to work to read is just bad; soften the background before giving up the effect. `[his call, 2026-10-30 and 2026-11-06; the 60 % opacity was an Android detail, not the rule]`
- When something is hovered: the background one step darker or a hairline border, never a colour change or an underline, and no sticky hover on touch, because hover should confirm, not shout. The one exception is the quiet link in the next line. `[his call, 2026-10-30; exception 2026-11-06]`
- When most of a screen is links: mark the main ones with weight or a darker tone, not colour plus underline, and let the minor ones show themselves only on hover, because link styling on every row shouts. `[his call, 2026-11-06]`
- When adding depth: shadows soft and spread at low opacity, backdrops lightly blurred and barely tinted, dividers light, because a heavy black shadow or a grey wash is "too much". Size a shadow by how far off the page the thing sits: pressed sits lower, dragged sits higher, light comes from above, and stop well before it looks real. `[his call, 2026-10-30; height 2026-11-06]`
- When a page feels flat: a tint, a soft two-hue gradient, a low-contrast pattern or an illustration, because a change of background breaks the sameness without changing the design; breaking flatness is its job. `[his call, 2026-11-06]`
- When there is a dark mode: one set of tokens serves both modes and only the colours behind them change, each tuned so it reads in the dark, never a straight inversion, because one set of names keeps the design one thing and an inverted palette looks wrong. `[his call, 2026-11-06]`
- When a colour goes very light or very dark: raise its saturation or nudge the hue, because lightness alone washes it out. `[his call, 2026-11-06]`
- When white on a colour fails contrast: flip it, dark text of the same hue on a light tint, because a block dark enough to pass grabs the whole page. `[his call, 2026-11-06]`
- When choosing greys: tint them slightly warm or cool, the same way across the whole scale, because pure grey reads dead. `[his call, 2026-11-06]`
- When an icon is needed: one set per platform (for example Lucide on the web), sizes tuned per spot and a step bolder where they look thin, and never a glyph another platform owns (the iMessage bubble), because mixed sets look borrowed. `[his call, 2026-10-30]`
- When an icon sits beside text: soften its colour, because a solid glyph outweighs letters. `[his call, 2026-11-06]`
- When an icon or logo changes size: redraw it for that size, or set a small icon inside a coloured shape, because detail drawn for one size looks wrong at another. `[his call, 2026-11-06]`
- When images come from people: fixed frames, cropped to fit, and a faint inner shadow so a white photo does not melt into a white page, because a layout cannot depend on what someone uploads. `[his call, 2026-11-06]`
- When adding a picture outside the product (a site, a post, a deck): only where it carries a fact, proof or clarity that words cannot (the real product as a screenshot, real people and places as your own photos, a plain diagram for a concept), all with one treatment (same crop, same window chrome). Never to break up text, never stock or generic start-up illustration, because a bought-looking picture breaks trust and dates fast. Test: delete it; if the page loses nothing, leave it out. `[his call, 2026-11-06]`

## Type

- When setting type: one sans, few sizes with a clear hierarchy; on phones body text one step below the browser default while inputs stay at 16 px, because many sizes read as no system and inputs under 16 px zoom the page. `[his call, 2026-10-30; one sans 2026-11-06]`
- When text needs a step down: a lighter colour or a smaller size, never a thinner weight, because thin type disappears at UI sizes. `[his call, 2026-11-06]`
- When a headline, button or short paragraph wraps: no single word on the last line (rewrite, adjust the width, or balance with `text-wrap: balance`), and headline lines close to the same length, because an orphan reads as careless. `[his call, 2026-10-30]`
- When a paragraph could run wide: cap it near 45 to 75 characters even inside a wider container, because a long line is hard to follow back. `[his call, 2026-11-06]`
- When text must truncate: design the cut (a fade where it reads better than an ellipsis, the meaningful part kept such as the email domain, a trailing icon after the ellipsis, a quote as wide as its line and two lines at most), because a default ellipsis loses the part people needed. `[his call, 2026-10-30]`

## Words

- When writing copy: plain language, B1 English, no jargon, nothing that reads "AI-ish", because plain lines are read by everyone, translate well and are never the thing people notice. `[his call, 2026-10-29; reworded 2026-11-06]`
- When capitalising in English: Title Case only for actions (buttons, menu items), sentence case for everything else, because the case then tells you what you can tap; in a language that does not capitalise this way (Latvian), sentence case everywhere. `[his call, 2026-10-12; Latvian 2026-11-06]`
- When the look is modern and the words formal ("please", "kindly", "successfully"): fix the words as you would say them across a desk, because people read one personality. `[his call, 2026-11-06]`
- When tempted by a joke or a clever line: only where the brand has a reason, never on a daily screen, never about the person's trouble, and never when they are under pressure, where the plainest, driest message is the kindest; the plain fact first with the wit on top, because the fact must land even when the joke does not. `[his call, 2026-11-06]`
- When labelling a button or a link: the one button that decides the outcome says what they get, every other button keeps the standard word, and a link says where it leads, never "Read more", because the label is what they decide on. `[his call, 2026-11-06]`
- When stating a limit: say what is possible, not what is not ("up to 30 nights"), because the possible is what they came for. `[his call, 2026-11-06]`
- When copy could change with the data ("Marta joined", "9 joined"): one line for every case and one shape for every count, because one line needs no logic and reads the same at any count. `[his call, 2026-11-06]`
- When writing copy about privacy or data: it stays true to what the backend really does, however nice the other line reads. `[his call, 2026-11-03]`
- When writing an intro or permission screen: a short headline plus three one-line points, under the graphic, not above it. `[his call, 2026-10-30]`
- When filling a mock with content: realistic names and chats, never "Acme", never a feature the product does not have, never a specific real person, because fake content hides real problems and a real person is a privacy risk. `[his call, 2026-10-30]`
- When the product is localised: leave room for the longest language and let every word show in full, and accept that the hand-tuned line breaks and word choices of the English will not survive every language. `[his call, 2026-11-06]`

## Forms and fields

- When a field needs a label: outside the field, always visible, never as a placeholder, because it vanishes the moment they type; grey text inside the field only when it does a job (a question, an example), never to fill space. `[his call, 2026-11-06]`
- When a field needs more than a label (a format, a length, whether it is optional, why you ask, or the few words people stall without): say it beside the field, in the order label, help, control, visible before and while they type, never only in a placeholder or a tooltip, so plainly that "this field is required" never appears. Nothing important sits under the submit button. Costs: words. `[his call, 2026-11-06]`
- When a form checks a field: on leaving the field the first time, then as they type once it has shown a problem, and everything on submit with the first problem focused, because checking too early nags and too late wastes the work. Never on the first keystroke and never only on submit. Live feedback while typing (password strength, a code, a name that is taken) is status, not a problem. `[his call, 2026-11-06]`
- When something is missing or wrong: show it where it is (a lone empty field shakes), and when the content is wrong rather than missing, a short line says what is wrong, because a shake alone says no without saying why. `[his call, 2026-11-06]`

## States and messages

- When a list is empty: say what will appear here and give the first step, never only what is missing, and hide the tabs, filters and sort that act on nothing, because the empty screen is the first one a new person meets. Keep the voice positive: being early is a fact, not a lack. A search with no result is the same: say so plainly, then a way forward, never "try again". `[his call, 2026-11-03 and 2026-11-06]`
- When people wait: make it clear something is loading (a spinner in or beside the button that started it), and on a longer wait something that changes and names what is being done for them, because a blank wait reads as broken. `[his call, 2026-11-06; no strong preference beyond this]`
- When writing an error: what went wrong, then how to continue, with no "error", "failed" or "invalid", because the person is already stuck; when the failure is ours (connection, server), say so, so they do not try to fix it. `[his call, 2026-11-06]`
- When telling someone it worked: scale it to the weight of the act, a tick that fades for a small one, a human line plus the next step for a big one, never "completed successfully". `[his call, 2026-11-06]`

## Motion

- When adding motion: ambient motion slow and minimal (a drifting gradient, a ring), functional motion quick and continuous (a chevron rotates, a copy button becomes a checkmark, an error shakes), because motion should explain state, not perform. Nothing pops, jumps, flickers or loads white before it animates. An animation never papers over a layout problem. `[his call, 2026-10-30]`
- When tempted by sound or haptics: none by default, a haptic on an error at most, because both interrupt, and an error is the one moment worth an interruption. `[his call, 2026-11-06]`
