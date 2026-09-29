# Claude Design prompt — group research website

---

Build a single-page research website for a university project in digital culture. It must work as a piece of academic work and as a designed object: the reader should scroll to the end.

## The concept

The page is built as **a feed that resolves into a document**.

It opens as an infinite social feed — ordinary posts, holiday photographs, recipes, gym logs, a poll — scrolling on their own. The research content arrives *between* them, unasked. This is not decoration: the subject of the research is information that reaches people without being sought, so the page enacts what it describes.

As the reader descends, the feed slows, thins and finally stops. From the research question onward, the page becomes a clean reading document. The argument must never be hard to read. The feed language returns only at section breaks and in the quote cards.

Do not let the metaphor overwhelm the text. The top third is immersive; the rest is legible.

## Visual system

- Dark, high-contrast ground. Near-black background, off-white text, one saturated accent used sparingly for data and emphasis.
- Type: a high-contrast serif for headlines (large, confident), a clean neutral sans for body, monospace for numbers, labels and figures.
- Motion: scroll-triggered reveals, counters that animate once, cards that lift and expand on interaction. Everything must respect `prefers-reduced-motion`.
- Cards everywhere: the literature findings, the method, the interview quotes and the examples are all cards the reader can open or flip.
- Sticky slim progress bar at the top or bottom, plus a section index the reader can jump from.
- Fully responsive. On mobile the feed becomes one column.

---

# CONTENT

Use this text exactly. Do not rewrite it, do not add headings, do not invent data.

## Hero

Full viewport. A live self-scrolling feed of invented ordinary posts behind or beside the title. The title arrives into the feed as if it were itself a post that the reader did not ask for.

> # Encountered, Not Sought
> ### Incidental news exposure as an agent of political socialisation
>
> Hanna Sára Jordanics · Lina [SURNAME] · [THIRD NAME]
> Digital Culture — Sciences Po Menton — September 2026

## Hook and video

The feed slows. One post remains, centred, and expands to full width: the video.

Subheading above it, large:

> ### In September 2022, videos of women cutting their hair reached millions of feeds that had never asked for them.

Below the video, a small caption line in monospace: `Source: [OUTLET, DATE]`

Then, as the feed falls away:

> Almost no one who saw this video had searched for it. Many did not know, at the moment it began playing, what it referred to or where it had been filmed — it arrived between a recipe and a friend's holiday photograph, and it carried a political claim with it.
>
> That situation is the object of our research. Political information reaches young people without being sought, and it reaches them constantly; what this encounter produces is far less clear.

## Research question

The feed stops entirely. Full viewport, near-empty, centred. This is the page's silence.

> ## What role does incidental news exposure play in political socialisation?
>
> — What does this exposure produce: recognition, knowledge, opinion, or action?
> — What becomes of this information once encountered: does it circulate back into the family and the peer group?

## What is incidental news exposure

Clean reading column.

> Incidental news exposure refers to encountering news or political information while online for a different reason — entertainment, messaging, browsing. The term was introduced by Tewksbury, Weaver and Maddex in 2001, before algorithmic feeds existed, to describe users who met news while doing something else online.
>
> We study it because most young people do not go online to inform themselves. If political information still reaches them, it reaches them by another route. Understanding that route means understanding one of the ways political opinions are formed today.

Then, as **four cards the reader opens** — three headed `ESTABLISHED`, the fourth `OPEN`:

1. **Exposure is widespread.** Across a range of national contexts, a majority of users report meeting political content they did not seek, and the more time spent on social platforms, the more frequent the encounter.
2. **Exposure is not random.** Goyanes (2020) shows that a user's media preferences, habits of use and levels of trust condition what reaches them: the feed delivers what the user is already disposed to receive.
3. **The effects are unevenly distributed.** Valeriani and Vaccari (2016) find that accidental exposure can raise political participation among the least politically interested, while other work associates the belief that "news finds me" with lower political knowledge rather than higher.
4. **The mechanism remains contested.** Wieland and Kleinen-von Königslöw (2020) propose that incidental contact opens several distinct paths of processing, most of which do not pass through any change of opinion. This is where our own data intervenes.

## Methodology

Two cards side by side, each with an animated counter.

**Card 1 — `19` survey responses.** An online questionnaire, respondents mainly Sciences Po students. It measured frequency of unsought exposure, the form and source of the content encountered, what made respondents stop on it, and what the encounter produced. All percentages on this page refer to this sample of 19.

**Card 2 — `3` semi-structured interviews.** Conducted face to face, following the same sequence: media habits, one specific incidental encounter, what it produced, and whether it circulated afterwards. Interviewees are quoted anonymously.

Below both:

> We applied both instruments to a single case — feminist content — in order to observe the mechanism on a defined subject rather than in the abstract.

---

# THE ANALYSIS

Four numbered sections, `01` to `04`. Each: a large statement, then explanation, then the data, then the case. Percentages set in monospace and visually emphasised.

## 01 — Incidental news exposure constitutes a principal channel of political socialisation

Political socialisation is usually attributed to institutions: the family, the school, the media. Our data indicates that for young users, a substantial share of political content arrives through none of these, but through the feed itself — and that this arrival is frequent rather than occasional.

**95%** of our respondents do not use social media primarily to inform themselves; they cite entertainment, contact with others, or personal interests. **84%** encounter political or social content they were not looking for at least once a day, and **68%** several times a day. Exposure therefore does not depend on any intention to be informed.

The mechanism is the recommendation page. **53%** of the feminist content our respondents described reached them through a stranger's post on their For You or Explore page, against **5%** through someone they personally know. **58%** arrived as short video. The user selects neither the subject nor the source.

Eslen-Ziya (2013) documents how social media served the Turkish feminist movement as a channel of diffusion, allowing its claims to reach audiences beyond existing activist networks. Valeriani and Vaccari (2016) argue, across three countries, that accidental exposure to politics online can function as a participation equalizer. Both support the conclusion our data points to: exposure that is not sought is not, for that reason, without political effect.

## 02 — The role of personal resonance in determining what reaches the user

Exposure is not chosen, but neither is it indifferent. Our data shows that attention is given when the content meets something the user already carries.

**Chart 1 here** — *What made you stop on it rather than scroll past?*

Every respondent reported at least one action following such an encounter — watching to the end, reading the comments, sharing; none selected scrolling past alone. The reason given for stopping is, however, concentrated: **37%**, the largest single response, answered "the subject concerns me personally."

Goyanes (2020) identifies media preference, use and trust as antecedents of incidental exposure: what a user already prefers and trusts conditions what reaches them. Our sample is consistent with this. **63%** already follow accounts on feminism or women's rights, and only **5%** found the content they encountered entirely new.

> Three interview quote cards, styled like messages:
>
> One interviewee stopped on a post recommending books by Algerian women because of her own connection to the subject.
>
> A second stopped on a video about Gisèle Halimi because she had studied Halimi in a literature course — the encounter was prepared by an institutional source outside the platform.
>
> A third stopped on an association's post because of the image, which represented *"diverse categories of women."*

Incidental exposure is therefore unsought at the level of intention, and conditioned at the level of the process.

## 03 — Reinforcement rather than introduction, and cumulative rather than immediate effect

It follows from the preceding point that incidental exposure reaches users who are already disposed toward the subject. Its effect is consequently one of reinforcement rather than discovery, and it operates over time rather than within a single encounter.

**Chart 2 here** — *Did it change how you see any aspect of feminism?*

**74%** of respondents report no change: **53%** state that the content confirmed what they already thought, **21%** report no effect. **16%** report a change. Asked more generally how far the first content they see on an unfamiliar subject shapes their opinion, only **11%** answered that it largely forms it.

**The single most significant result concerns the relation between the two.** Among the **37%** who stopped on the content because the subject concerned them personally, not one reported a change of view — and all of them gave the *same* answer: *"No, it confirmed what I already thought."* Seven respondents, one response. What secures attention is precisely what makes conversion unlikely.

> Give this result its own full-width panel. It is the centre of the page.

The interviews situate the effect elsewhere. One interviewee described a change in her sources rather than her opinions: *"I used to follow big info accounts but through time I changed and I started following small creators who are less Americanized."* A second reported a conceptual rather than an evaluative shift, toward intersectionality and the exclusion of women of colour from mainstream feminism. A third described a cumulative process beginning in adolescence: *"consuming this as a young girl makes you more conscious about patriarchy."*

Wieland and Kleinen-von Königslöw (2020) model several distinct paths of news processing following incidental contact, most of which do not pass through opinion change. Our data corresponds: the effect is real, but it consists in a progressive reconfiguration of the information environment, which in turn determines what will be encountered subsequently.

## 04 — The circulation of incidental content across generations and genders

Incidental exposure becomes socialisation at the point where the content leaves the screen. Our data shows that this circulation is limited in volume, purposive in character, and not confined to peers.

Engagement remains largely internal to the platform: **53%** go to the comments, while only **16%** send the content to someone and **16%** search for further information. Circulation is therefore the exception rather than the rule.

Where it occurs, it takes distinct forms. One interviewee shared her post within her family, including with her father — a transmission across both a generation and a gender, and in the opposite direction to the descending model of political socialisation. A second did not discuss her encounter with family or friends at all, but raised it in academic settings, through an institutional rather than personal channel. A third shared hers deliberately, so that friends would attend the event it announced.

A further case indicates that exposure may itself be produced intentionally. One interviewee reported a friend whose elder sister deliberately populated her feed with feminist accounts until she began following them independently, and who now considers this beneficial. The feed here operates as an instrument of socialisation employed by a person, not only by a platform.

---

## Limits

Deliberately plain. No cards, no motion, no accent colour. The contrast is the point.

**The sample is not representative.** Nineteen survey responses and three interviews, drawn overwhelmingly from Sciences Po students, cannot support inference beyond this group. Percentages are reported for readability; each respondent represents roughly five points.

**The respondents were known to us.** Interviewees and most survey respondents were recruited through our own networks. Proximity to the researcher affects what people report, particularly on a subject where respondents may anticipate an expected answer.

**Our respondents were already disposed toward the subject.** Almost two thirds follow accounts on feminism or women's rights. Our hypothesis concerning rejection or backfire effects could therefore not be tested: we did not reach respondents indifferent or hostile to feminism.

**The choice of subject is itself a selection.** We selected feminism because it interests us, and we recruited within networks that share that interest. This is the mechanism described in section 02, applied to our own method: our exposure to the subject, like our respondents', was conditioned by dispositions we already held. The limitation is not external to our analysis — it is an instance of it.

---

## References

An expandable list at the foot of the page. [PASTE FULL BIBLIOGRAPHY]

---

# CHART DATA

Two charts only. Horizontal bars, monospace labels, percentages at the end of each bar, animating in on scroll. Sorted by size. Highlight the top bar in the accent colour; the rest in muted grey. n = 19 stated on both.

**Chart 1 — "What made you stop on it rather than scroll past?"**

| Response | % |
|---|---|
| The subject concerns me personally | 37 |
| I don't know, I just did | 21 |
| I was surprised or shocked | 11 |
| It was well made, or funny | 11 |
| I disagreed with it | 5 |
| Someone I trust had shared it | 5 |
| I didn't stop — I scrolled past | 5 |
| No answer | 5 |

**Chart 2 — "Did it change how you see any aspect of feminism?"**

| Response | % |
|---|---|
| No — it confirmed what I already thought | 53 |
| No effect | 21 |
| Yes, slightly | 11 |
| Yes, clearly | 5 |
| I don't know | 5 |
| No answer | 5 |

Group the two "No" bars visually so the 74% reads at a glance.

---

# RULES

- Use the text above verbatim. Do not paraphrase, do not add transitions, do not add conclusions that are not there.
- Invent no data, no quotes and no citations.
- The invented posts in the hero feed must be visibly ordinary and fictional — no real names, no real accounts, no real brands.
- Total body text is under 2,000 words and must stay that way; the assignment caps at 4,000.
- Every animation respects `prefers-reduced-motion`.
- Accessible contrast throughout; the page must be readable with motion disabled and with JavaScript degraded.
