# Features to ask Claude Design for

Each numbered item is written so you can paste it straight into the Design chat. Marked **★** = the ones that carry the argument. Do the ★ items first; the rest are polish.

---

## The one idea that ties the whole page together

**★ 1 — The interruption.**

> At three points while the reader is scrolling through the analysis, make an unrelated ordinary social post slide in from the edge of the screen — a recipe, a gym log, a holiday photo — hover for a few seconds, then drift away. It should not block the text. The reader should notice it without having asked for it.

This is the strongest thing you can do to this page. The reader experiences incidental exposure while reading about incidental exposure. It is an argument, not an ornament — and it is the kind of thing a teacher remembers.

**★ 2 — The nineteen dots.**

> Create a grid of 19 small dots representing the 19 survey respondents. Reuse the same grid in several sections, re-colouring the dots each time to show a different distribution: how often they meet unsought content, where it came from, whether it changed their view.

One visual device, four uses. It keeps the sample size honest and visible instead of hiding it behind percentages, which is exactly the criticism your teacher would otherwise make.

---

## Hero

**★ 3.** > Make the background feed scroll on its own, and accelerate slightly as the reader scrolls, so it feels like it cannot be kept up with. The title card should stay fixed while the feed keeps moving behind it.

**4.** > Add a small counter in the corner of the hero that increments as the feed scrolls — posts passed. Keep it subtle, monospace, low opacity.

**5.** > Give the feed posts a slight parallax so they respond to cursor movement.

---

## Video

**★ 6.** > Have the video enter as one card in the feed, then expand to full width when it reaches the centre of the screen. Desaturate everything around it while it is centred.

---

## Research question

**★ 7.** > At the research question, stop everything. Full viewport, near-black, no motion in the background, the question alone in large serif. This should feel like silence after noise.

**8.** > Let the research question type itself in, one line at a time, when it enters the viewport.

*(8 is nice but do not scroll-lock the reader to make it happen — forcing people to wait is the fastest way to make them leave.)*

---

## Literature cards

**★ 9.** > Make the four literature findings into cards the reader clicks to open. Label the first three ESTABLISHED and the fourth OPEN. Style the OPEN card differently — dashed border, accent colour — so it reads as the unresolved one.

**10.** > When the term "incidental news exposure" appears in the body text, let the reader hover it to see a short definition in a tooltip.

---

## Methodology

**11.** > Animate the two numbers — 19 and 3 — counting up when the cards enter the viewport.

**12.** > Introduce the 19-dot grid here for the first time, as the visual for the survey card.

---

## Analysis

**★ 13.** > Give each of the four analysis sections a large section number, 01 to 04, that sticks to the side of the screen while the reader is inside that section.

**★ 14.** > Set each section's opening statement very large, alone on the screen, before the explanation begins.

**15.** > Make every percentage count up from zero when it enters the viewport.

**★ 16.** > Present the interview quotes as message bubbles. Show a typing indicator for a moment, then resolve it into the quote.

**★ 17 — The centre of the page.** > For the seven respondents who stopped because the subject concerned them personally: show seven dots turning the same colour one by one, then the identical answer they all gave appearing beneath. Give this its own full-width panel, isolated from everything around it.

---

## Charts

**★ 18.** > Horizontal bars, animating in from the left when scrolled to. Top bar in the accent colour, all others muted grey. Percentage at the end of each bar, monospace.

**★ 19.** > On chart 2, bracket the two "No" bars together with a 74% label so the total reads at a glance.

**★ 20.** > When the reader hovers a bar, show the raw count behind it — "7 of 19".

*(20 matters more than it looks. It pre-empts the obvious objection that percentages on nineteen people are misleading, and it shows you knew that.)*

---

## Navigation

**21.** > Add a slim scroll progress bar fixed to the top of the page.

**22.** > Add a small section index down the right edge — one dot per section, the current one filled, clickable.

**23.** > Put an estimated reading time under the title.

---

## Limits

**★ 24.** > For the limits section, drain the design. No cards, no motion, no accent colour, plain type on plain ground. The visual collapse should feel deliberate.

The limits section argues that you are inside your own sample. Having the design fall away at exactly that point makes the argument twice.

---

## Footer

**25.** > Make the reference list an expandable block at the foot of the page.

**26.** > Add the three authors' names, the course, the teacher and the date.

**27.** > Add a short, clearly marked note declaring the use of AI in producing this website.

*(27 is not optional — your syllabus requires a declaration and a critical reflection on the limitations. Putting it on the page itself is the cleanest way to satisfy it.)*

---

## Optional, only if you have time

**28.** > Add a small interactive before chart 1: ask the reader "what would make you stop on a post?", offer the same options our respondents had, and once they answer, reveal how the 19 answered.

Engaging, and it makes the reader a twentieth data point. But it is the most work on this list and the page is already strong without it.

---

## Tell it NOT to do these

> Do not scroll-jack or trap the reader in any section. Do not autoplay anything with sound. Do not fabricate notifications, follower counts or engagement numbers that could be mistaken for real platform data — the invented posts must read as obviously fictional. Do not use more than three typefaces. Do not add parallax to the reading sections; keep motion in the feed areas only. Every animation must respect prefers-reduced-motion, and the page must stay readable with motion off.
