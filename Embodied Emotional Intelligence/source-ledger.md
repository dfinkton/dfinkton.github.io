---
title: "Embodied Emotional Intelligence — Source Ledger"
subtitle: "What each verified source supports, and what it cannot"
date: 2026-08-06
status: internal working document
---

# Source Ledger

One entry per source that has been verified against its primary text. The entry records
what the source actually measured, what it supports, and — where a specific overreach was
caught — what it cannot support. Sources recur across lessons (Killingsworth returns in
States of Mind, Watkins and Nolen-Hoeksema are the core of Rumination, Lindsay is the
spine of Observation), so **check here before re-verifying a source, and add an entry
after verifying a new one.** An entry here means the primary text was read or checked
directly in a drafting session; it does not mean every number in the paper was audited —
only the ones the entry states.

## Mark every entry with how deeply it was verified

Added Aug 2026 after a thin entry — "Older adults, anxiety, 7 trials, program-independent" —
produced two errors in Lesson 1. It read as authoritative and could not support a sentence.
**A one-line entry is a pointer to a source, not a licence to write specifics from it.**

Tag each entry with one of these, so a later session knows what it can lean on:

- **`full text read`** — the PDF or full article was read. Specifics are safe to write from
  the entry, within what the entry actually states.
- **`abstract only`** — abstract or publisher page checked. Safe for the headline finding
  and the design; **go read the paper before writing sample sizes, effect sizes, control
  conditions, or any subgroup result.**
- **`secondary source`** — verified through reporting, a review citing it, or a syndicated
  copy rather than the original. Say which. Usable, but flag it in the prose decision and
  replace with the primary when it can be got.

**If an entry carries no tag, treat it as `abstract only`.** Two of Lesson 1's worst errors
came from writing prose off an untagged one-line note, and from copying a verb ("pooled")
off the citation sitting next to it in the lesson — a systematic review became a
meta-analysis because the entry didn't say which it was.

## Every result gets its five coordinates

Added 13 Aug 2026, after Darryl caught two failures in one pass: publication years were
being ignored (so a 2020 meta-analysis was discussed as though it postdated a 2021 review
that cites it, and a 2021 single-author paper was attributed to the authors of a 2025 one),
and results were being written as verdicts on treatments — *"meditation doesn't move
alexithymia"* — rather than on what was actually tested.

**No treatment does or doesn't work. A treatment at a dose, in a population, against a
comparator, on a measured outcome, at a timepoint, did or didn't move.** Drop any of those
five and the entry is unusable — worse, it reads as authoritative while licensing a claim
the study never made.

Every result recorded in this ledger carries:

1. **Publication year, in the citation, always.** And where a paper's own included studies
   span years, record that range too — a 2021 meta-analysis of trials published 2001–2020
   is describing a twenty-year-old evidence base.
2. **Intervention and dose** — what was done, how long, how often.
3. **Population** — diagnosis, age, sex, country, and whether clinical or community.
4. **Comparator** — waitlist, active therapy, no control at all. An uncontrolled pre-post
   change is not an effect size against anything and must never be set beside one that is.
5. **Outcome instrument and timepoint** — which scale, which subscale, measured when.

Two consequences that have already bitten this project: the same paper often gives
different answers on different subscales, so *"the intervention worked"* is almost never a
sentence this ledger can write; and **findings that appear to contradict each other usually
differ on one of the five coordinates** rather than being a real disagreement, which is
information worth keeping rather than a conflict to resolve.

## Fix errors by deleting them

When an entry turns out to be wrong, **delete the wrong text and write the correct text in
its place.** No *"this entry previously said,"* no *"correction to the above,"* no
superseded notes left in as sediment. A ledger that records its own edit history stops
being readable, and the corrections start outnumbering the findings. Git holds the history;
this file holds what is currently true.

## Full title, and the evidence itself — not my summary of it

Set by Darryl, 18 Aug 2026: *"we need to have a rule of always naming the full paper title in
the ledger, and save the raw data / methods / stats that we need. otherwise we are storing your
interpretations without the evidence. instead, we want the evidence no matter what. and then if
we add an interpretation then that is a fine addition, not the standalone info."*

**Every entry carries the full paper title.** Author-year alone is how three bad citations
survived in the claims register until 18 Aug — "Ciarrochi 2003," "Weihs 2012" and "Rowsell
2016" each had a finding attached and no title. Two turned out to be the wrong paper and one
did not exist. **A title is checkable in seconds; an author-year plus my summary is not.**

**Then the evidence, before any reading of it:** sample size and composition, what was
measured and with which instrument, the design, the comparator, the timepoints, and the actual
numbers with their intervals. Quote the paper's own sentences where the wording carries the
finding.

**Interpretation is an addition on top, and is marked as one.** "Use it for" and "cannot
support" lines are mine and are useful, but they sit under the evidence and never replace it.
An entry that gives only what I concluded is an entry that cannot be checked, and cannot be
re-used by anyone who reads the paper differently.

## This file records sources, not rules for writing

Added 18 Aug 2026, after Darryl: *"you are writing all kinds of rules that are just wrong.
that is making this harder."* He was right, and the cost was concrete — a standing note
written here on 17 Aug ("emotional awareness has to be the measured variable") was wrong,
and reading it back a day later produced a misread of what he had asked for.

An entry says what a source measured, what it supports, and what it cannot support. Those
are facts about papers. **Rules about how to write the lessons belong in `lesson-format.md`
and `verification-checklist.md`, and go in only when Darryl has agreed to them.**

The process rules that remain in this file are kept because he set them, and each one names
him. When quoting any constraint back in conversation, say whose it is — "I wrote a note
saying X," not "the ledger forbids X." Otherwise my own prior opinion returns dressed as
evidence and is hard to argue with.

The exception is narrow and worth keeping: where a *published source* is itself commonly
miscited, record what it cannot support — *don't cite Seah & Coifman for self-injury*. That
is a fact about the literature a future session needs. What this ledger got wrong last
Tuesday is not.

Currently covers Lesson 1 (Focus and Attention, verified July–August 2026) and Lesson 2
(Emotional Awareness, broad literature search and pressure-test pass, 2026-08-09 through
2026-08-10, including a full-text pass on 8 supplied PDFs on 2026-08-10 — see notes on
each entry for the handful of sources still flagged `needs follow-up`).

---

## Mind-wandering and attention training

**Killingsworth & Gilbert, 2010** ([Science](https://www.science.org/doi/10.1126/science.1192439)) —
Experience sampling, 2,250 adults, phone pings. Minds elsewhere in 46.9% of samples.
Pleasant wandering left people no happier than being present; neutral/unpleasant left
them worse. Time-lagged analysis: wandering preceded the mood dip, not the reverse.
**Read the topic split carefully — an earlier version of this note framed it wrongly.**
Pleasant (42.5%) is the largest single category, but it is not a majority: 57.5% of
wandering goes somewhere neutral (31%) or unpleasant (26.5%). Saying minds "go somewhere
pleasant more often than somewhere unpleasant" is true of the pairwise comparison and
misleading about the whole, because it implies wandering is mostly pleasant. It isn't.
**Exact figures confirmed against the PDF, Aug 2026.** Of wandering samples: pleasant
42.5%, neutral 31%, unpleasant 26.5% (these sum to 100 — they are shares of wandering,
not of all samples, despite the paper's looser "of samples" phrasing). Happiness versus
current activity: pleasant b=−0.52, **not significant** (so "no happier" is exact, not a
hedge); neutral b=−7.2, P<0.001; unpleasant b=−23.9. **Do not lump neutral and unpleasant
together** — unpleasant is more than three times worse, and an earlier Lesson 1 sentence
flattened them into one "considerably less happy." Also avoid "far more often" for
42.5 vs 26.5; it is roughly 1.6x, and the paper's own comparison is pleasant against
neutral and unpleasant combined.

**Mrazek and colleagues, 2013** ([Psych Science](https://journals.sagepub.com/doi/10.1177/0956797612459659)) —
RCT, undergraduates, two weeks mindfulness training vs nutrition class. Fewer off-task
thoughts; gains in working memory and **reading comprehension** (not "verbal reasoning" —
that mislabel was caught and corrected), concentrated in participants most distracted at
baseline.

**Hasenkamp and colleagues, 2012** ([NeuroImage](https://pubmed.ncbi.nlm.nih.gov/21782031/)) —
14 practitioners, mean ~1,400 lifetime hours, self-caught button-press during 20-min
breath session in fMRI. ~15.5 wanderings per session (~once every 80s). Four phases
(wander / notice / shift / sustain) mapped to distinct networks (DMN / salience /
executive). **Cannot support:** faster or more efficient re-engagement with practice.
The authors call that reading "necessarily speculative"; wandering count did not
correlate with practice hours (r=-0.14, p=0.64); no novice comparison group; the design
(fixed analysis windows) cannot measure episode duration. Widely over-cited for a
duration claim it disclaims — including by a published field review.

**Slagter and colleagues, 2007** ([PLoS Biology](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.0050138)) —
Attentional blink. 17 practitioners before/after three-month retreat (10–12 hr days) vs
23 novices tested across the same months. Retreat group caught the second target more
often without losing the first; novices improved less. Self-selected retreatants, not
randomized.

**Brandmeyer & Delorme, 2018** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/27815577/); author PDF at sccn.ucsd.edu) —
Probe-caught (random 30–90s intervals), experts vs non-experts, one-hour sit, n=24 after
one exclusion (12 per group). **Quantified in the text (added Aug 2026, full PDF read):**
experts averaged 75.4% meditation trials / 24.6% mind-wandering trials (SE 4.4,
p=0.00014); non-experts 42.7% / 57.3% (SE 6.2, ns within group). Between groups the gap
is 32.7 points, p=0.00038. Also lower "depth" of wandering — a 0–3 immersion rating at
the probe, **not** a duration measure (depth 1.14 vs 1.59, p=0.03).
**Read the groups correctly:** "expert" = daily practice of 2+ hours for a year or more
(mean 14.8 h/week); "non-expert" = trained and familiar with the techniques but
practicing irregularly (mean 3.2 h/week). **This is heavy vs light practice, not
meditators vs non-meditators** — do not describe the comparison group as people who have
never meditated. **Cannot support:** episode duration or "catching faster" — "truncate"
and "faster" appear nowhere in the paper; duration is named in the intro as an open
question and never measured. A circulating summary attributing a duration finding to this
paper is fabricated.

**Jha, Krompinger & Baime, 2007** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/17672382/)) —
Beginners after eight weeks improved orienting (redirecting attention once wandered);
experienced practitioners after a one-month retreat improved alerting (readiness for
what's in front of them), scaling with months of prior practice. Different capacities on
different timelines.

**2021 mind-wandering review** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/34560133/)) —
24 studies; sustained practice reduces mind-wandering frequency.

## The frequency-vs-duration question (investigated August 2026, mostly unused)

The settled conclusion after checking five papers directly: **practice reduces how often
the mind wanders (well-evidenced, multiple methods); no verified evidence shows each
episode gets shorter or the return gets faster/easier.** Total time wandering can drop
from frequency alone. Lesson 1 was edited to claim frequency only.

- **Rodriguez-Larios and colleagues, 2021** (NeuroImage 245:118669, PDF read in full) —
  EEG, 29 meditators (>3 yrs) vs 29 matched controls, probe-caught. Fewer MW trials in
  meditators (p=0.0026), depth trend (p=0.06). The "quickly disengaged" line in the
  Discussion is the authors' explicit speculation about an absent alpha-power effect,
  not a measured result.
- **Weng and colleagues, 2018** (bioRxiv 461590, preprint, not peer-reviewed; PDF read
  in full) — EMBODY: ML decoding of fMRI into breath/MW/self states, second-by-second;
  8 meditators (mean 3,495 lifetime hrs) + 6 usable controls. First direct duration
  measure found: mean MW event 8.1s. **Duration metrics did not correlate with lifetime
  hours** ("no other EMBODY metrics... were significantly correlated"). What did:
  % time on breath (rho=0.71) and % time in self-referential processing (rho=-0.71).
- **Pagnoni, Cekic & Guo, 2008** (PLoS ONE 3(9):e3083) — closest real evidence for
  faster recovery. Zen meditators (>3 yrs daily, n=12) vs controls (n=12); lexical
  decision task intruding on breath focus; meditators showed a reduced post-stimulus
  "tail" of default-network activity in the 6–14s window (group main effect F(1,22)=12.3,
  p=0.002). It is a magnitude-in-fixed-window measure of an *imposed* interruption, not
  a timed return from spontaneous wandering; paper never says "faster" or "recover."
- **He, Chen & Zhang, 2024** (PMC10967797) — checked and irrelevant: university
  students, SART, no meditation component.

## Clinical outcomes

**Goyal and colleagues, 2014** ([JAMA Int Med](https://jamanetwork.com/journals/jamainternalmedicine/fullarticle/1809754)) —
47 RCTs, 3,515 people, screened from ~19,000; active comparison groups only, no
waitlists. Anxiety d=0.38 (8 wks) / 0.22 (3–6 mo); depression d=0.30 / 0.23; pain
d=0.33. The field's benchmark active-controlled numbers.

**Cipriani and colleagues, 2018** ([Lancet](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(17)32802-7/fulltext)) —
Antidepressants vs placebo, 522 trials, 116,000+ people: d≈0.30. Used as the comparison
scale for Goyal's depression effect.

**Hofmann & Smits, 2008** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/18363421/)) — CBT
for anxiety, intention-to-treat: g=0.33. Comparison scale for Goyal's anxiety effect.
PMID sourced from Hofmann 2010's own reference list.

**Hofmann, Sawyer, Witt & Oh, 2010** ([APA](https://doi.org/10.1037/a0018555); PDF read in full) —
39 studies, 1,140 patients with a diagnosed condition. **Pre-post within-patient, not
controlled** — runs higher than Goyal by design: anxiety g=0.63, depression g=0.59;
anxiety/mood-disorder subgroup g=0.97 / g=0.95, held at 12-week median follow-up.
Reports **Hedges' g, not Cohen's d** — a d/g mislabel here was caught and fixed.

**Hoge and colleagues, 2013** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/23541163/); *J Clin
Psychiatry* 74(8):786–792) — 93 adults with DSM-IV generalized anxiety disorder randomized
to 8-week MBSR or Stress Management Education (SME), an attention-matched control of
didactic classes on stress physiology, sleep, nutrition, time management, exercise — **no
meditation content**. Response (CGI-I of 1 "very much improved" or 2 "much improved"):
**66% (29/44) MBSR vs 40% (14/35) SME, p=0.025**; RR 1.65 [1.04–2.60], NNT 3.9.
**Critical detail added Aug 2026 — the earlier entry omitted it:** MBSR did **not** beat SME
on the trial's pre-specified **primary** outcome, the Hamilton Anxiety Rating Scale. It won
on secondary measures only (CGI-S, CGI-I, BAI). The 66%-vs-40% figure everyone quotes is a
secondary outcome. Never cite it without knowing that.
**Removed from Lesson 1 (Aug 2026):** dropped from the diagnosed-populations entry because
it shows MBSR works *within* a diagnosed group against an alternative — it never compares
diagnosed to non-diagnosed people, so it cannot support a "works even better in diagnosed
people" claim. Kept here in case a future lesson needs a straight GAD result.

**Kuyken and colleagues, 2016** ([JAMA Psychiatry](https://jamanetwork.com/journals/jamapsychiatry/fullarticle/2517515)) —
Individual patient data, 9 trials: MBCT completers relapsed less over the following year
than people on **other treatments** (usual care, antidepressants) — 38% vs 49%.
**Cannot support:** any within-MBCT "kept up vs stopped practicing" comparison; that
framing misstates the design and was caught and corrected in lesson 1.

**Goldberg and colleagues, 2020** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC7554248/)) —
Veterans with diagnosed PTSD: gains in symptoms and day-to-day functioning.

**Kabat-Zinn, 1982** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/7042457/)) and
**Kabat-Zinn and colleagues, 1992** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/1609875/)) —
Founding chronic-pain and anxiety studies. 1992: 22 patients; 18 reached at three years,
improvement still significant (82%). **No comparison group in either** — durable
improvement in participants, cannot isolate the technique as the ingredient.
**Recurring error to watch (caught again in Lesson 1, Aug 2026):** 82% is the *follow-up
rate* — the share of the original cohort the researchers managed to reach. It is not the
share of patients who improved. "82% were still significantly improved three years later"
is wrong; the correct form is "18 of the original 22 were reached, and their improvement
was still significant."

**Strauss, Cavanagh, Oliver & Pettman, 2014** ([PLoS ONE 9(4):e96110](https://doi.org/10.1371/journal.pone.0096110)) —
12 RCTs, 578 participants with a *current* anxiety or depressive disorder. MBCT
depression g=−0.73 [−1.36, −0.09], significant; MBSR anxiety g=−0.55 [−1.18, 0.09] and
primary symptom severity g=−0.75 [−1.81, 0.31], both non-significant. **Do not read this
as "MBCT beats MBSR."** It is confounded by indication: the MBCT trials were depression
trials and the MBSR trials were anxiety trials — the authors state no depression-focused
MBSR trials existed to include. It compares MBCT-on-depression with MBSR-on-anxiety.

**Haller, Breilmann, Schröter, Dobos & Cramer, 2021** ([Sci Rep 11:20385](https://doi.org/10.1038/s41598-021-99882-w)) —
23 RCTs, DSM-5 anxiety disorders only. Against CBT as the common comparator: MBCT
comparable, MBSR significantly lower (SMD=0.50 [0.17, 0.83] favoring CBT). Against TAU
both beat it. **Cannot support "MBCT outperforms MBSR":** the two were never run head to
head; this is an indirect comparison across separate trials, 3 MBCT vs 8 MBSR, anxiety
disorders only. Cut from Lesson 1 for that reason.

**Hoge and colleagues, 2025** ([J Affect Disord 384:163–172](https://pubmed.ncbi.nlm.nih.gov/40324655/)) —
The one clean test of delivery format. MBSR taught live over videoconference vs MBSR
taught in person, for diagnosed anxiety disorders; non-inferiority demonstrated within
the pre-specified margin of −0.40 (95% CI −0.34 to 0.25). **The one exception:** in-person
had greater impact on social anxiety than its videoconference version. Note the trial's
main arm was MBSR vs escitalopram — the format comparison is the second phase, added
when the pandemic forced remote delivery.

**Delivery format — what cannot be claimed (settled Aug 2026).** There is **no
head-to-head trial of an app against a teacher-led course.** A widely repeated line that
apps are "less potent than in-person" rests on comparing app effect sizes against an
in-person figure of d≈0.89, which is not active-controlled and so not comparable. Compare
like with like instead: app trials (**Gál, Ștefan & Cristea, 2021**, *J Affect Disord*
279:131–142 — stress g=0.46, depression g=0.33, anxiety g=0.28, well-being g=0.29) land
in the same range as Goyal's active-controlled in-person numbers (anxiety d=0.38,
depression d=0.30). **So: say the formats all seem to work and that nobody has compared
them directly.** Do not rank them. This correction was caught by DF after the "apps work
less strongly" claim was drafted into Lesson 1.

**Sommers-Spijkerman, Austin, Bohlmeijer & Pots, 2021** ([JMIR Ment Health 8(7):e28168](https://doi.org/10.2196/28168)) —
97 trials, 125 comparisons of *online* MBIs. Pre-post: depression g=0.34, stress g=0.44,
mindfulness g=0.40, anxiety g=0.26; well-being significant only after removing outliers
or low-quality studies. **The guidance finding (used in Lesson 1):** guided beat unguided
on **stress only** — guided g=0.61 [0.43, 0.82] vs unguided g=0.34 [0.21, 0.47], P=.02.
Guidance did *not* significantly moderate depression, anxiety, well-being, or mindfulness.
Note the paper is internally inconsistent here: Results give 0.61 vs 0.34, the Discussion
gives 0.42 vs 0.21 for the same comparison. Direction is identical (guided ≈ double), so
the lesson says "roughly doubled" rather than quoting a number. **Also the direct test of
program type:** intervention type was *not* a significant moderator — the authors'
conclusion is that "MBSR, MBCT, ACT, and hybrid MBIs are equally effective in improving
mental health." This is the strongest available evidence against ranking MBCT over MBSR.
Caveat: online delivery throughout; 34% of studies at high risk of bias; publication bias
indicated for every outcome except stress.

**Hilton and colleagues, 2017** ([DOI](https://doi.org/10.1007/s12160-016-9844-2); PDF read) —
38 RCTs, 3,536 chronic-pain patients across conditions. Pain SMD=0.32, no difference by
condition; depression SMD=0.15 with zero heterogeneity across 12 trials.

**Dunning and colleagues, 2019** ([Wiley](https://acamh.onlinelibrary.wiley.com/doi/10.1111/jcpp.12980)) —
**33 RCTs, >3,600 children and adolescents**; the 17 active-controlled trials are a subset
analyzed separately, *not* the scope of the review (an earlier Lesson 1 sentence said
"restricted their meta-analysis to the 17 trials" — wrong, corrected Aug 2026). Active
subset: depression d=0.47, mindfulness d=0.42, anxiety/stress d=0.18. Interventions were
programs built for young people — school courses (Learning to BREATHE, Mindfulness in
Schools Programme) adapted from MBSR/MBCT, plus mindfulness-based yoga, Soles of the Feet,
and author-created variants.
**Cannot support — two separate prohibited comparisons, both attempted and both cut:**
(1) "same kind of active control as Goyal" — Dunning's active arms were mostly
attention-placebo, Goyal's were matched treatments. Cut from Lesson 1 once, then
reintroduced Aug 2026 as "the same kind of trials find in adults" and cut again. Do not
compare these two effect sizes as if the designs match.
(2) Comparing Dunning's depression figure to the Cipriani antidepressant or Hofmann &
Smits CBT benchmarks — the CBT benchmark is for *anxiety*, and both cross
population/intervention/comparator lines.
**Consequence for the headline:** Dunning studied only children and adolescents. It makes
no adult comparison, so it cannot on its own support "works even better in kids and teens
than in adults." That claim needs its own source or a weaker headline.

**Ye and colleagues, 2024** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/38799491/)) —
5 RCTs, MBCT for late-life depression/anxiety: g=0.53 / g=0.43. Small base.

**Hatch, Webber, Rej, Finlayson & Kessler, 2023** ([T&F](https://tandfonline.com/doi/abs/10.1080/13607863.2022.2102140);
*Aging & Mental Health* 27(6):1045–1055; PDF read in full Aug 2026) — **A systematic review
with narrative summary, NOT a meta-analysis.** They screened 2,709 studies, included 7 RCTs,
355 participants total (individual samples 36–141), and explicitly did not pool results
statistically — do not write "pooled" for this one. Interventions were MBSR and MBCT,
several modified for older adults, plus derivatives (MAPS, BREATHE). Comparators varied:
attention control, treatment-as-usual, and in one case no active control group. Outcomes
were pre-post change on anxiety scales.
**The program-independence line is verbatim from the abstract:** "Regardless of the
mindfulness-based meditation intervention used, a reduction in symptoms of anxiety in
participants was reported post-intervention." Authors' own conclusion is hedged —
"appear to be promising" — and they call for more RCTs.
**Year:** cite as 2023 (print issue June 2023). The PDF's 2022 is the online-first date.

**Gliske and colleagues, 2026** ([DOI](https://doi.org/10.1007/s12671-026-02917-4); PDF read) —
Meta-review, 17 systematic reviews, perinatal. Fear of childbirth clearest (SMD 0.71 and
0.73 in the two reviews measuring it); anxiety improved in 9/9 reviews, depression
10/11; stress inconsistent — moved in struggling samples, floor effects in healthy ones.

## What drifting costs

**LaFreniere & Newman, 2020** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/32402257/)) —
29 GAD patients logged worries 10 days, followed 30: 91.4% never came true; modal
individual result 100%. Clinical worriers — measures the worry that brings people to
treatment.

**Nolen-Hoeksema, 2000** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/11016119/)) —
Rumination predicted later depressive symptoms, new episodes, and anxiety.

**Dittmar and colleagues, 2014** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/25347131/)) —
259 samples: materialism ↔ lower wellbeing. Modest, correlational, strongest for risky
spending and harsh self-judgment.

**Watkins, 2008** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC2672052/)) —
Concrete repetitive thought helps; abstract-evaluative harms; abstract rumination slowed
mood recovery vs both concrete thinking and plain distraction.

## Dose and format

**Basso and colleagues, 2019** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/30153464/)) —
13 min/day vs podcast control. Attention, memory, mood improved at 8 weeks, **not at 4**.
Recruited 76, finished 42 — result rests on completers.

**Schumer, Lindsay & Creswell, 2018** ([APA](https://doi.org/10.1037/ccp0000324); PDF read) —
65 RCTs of brief training (single session to two weeks): g=0.21, faded by the day after
training ended; publication-bias-corrected g=0.04, not reliably different from zero.
Brief training alone is not a lasting intervention.

**Fincham and colleagues, 2023** ([DOI](https://doi.org/10.1007/s12671-023-02119-2)) —
161 people, daily practice two weeks, ~10-min vs ~30-min sessions: no difference in
well-being, distress, or mindfulness.

**Cearns & Clark, 2023** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC10548318/);
also [JMIR 2023;25:e43358](https://www.jmir.org/2023/1/e43358), PDF read in full) —
280,000 real app sessions, 10,000+ people. Session length barely moved mood; days per
week did — each extra day raised mood; 4–7 days/week more than twice the long-term
retention of once-weekly. Nonlinear crossover: before ~20th session, short/medium
sessions tied to higher mood; after, 21–30-min sessions ahead for mood and recovery
speed; after ~80 sessions, shorter sessions ahead again for day-to-day mood stability.

### The floor question: none of the duration studies measured below ~5 minutes

Checked August 2026 when deciding what daily dose to recommend. **Every source this
lesson uses for "frequency beats duration" bottoms out around 5–10 minutes.** None of
them can speak to one-minute or seconds-long sessions:

- **Fincham 2023** compared ~10 min vs ~30 min. Nothing below 10 was tested at all.
- **Cearns & Clark 2023** never reports a category below **5–10 minutes** — that band is
  the *reference group* in every comparison in the results. Sessions were trimmed at 30
  minutes and harmonized to the nearest 5 minutes. Sub-5-minute sessions never appear as
  their own category.
- **Bowles & Van Dam 2025** collected duration in bands (0–15, 15–30, 30–60, 60+ min)
  and used the **midpoint** — so a 2-minute session and a 14-minute session are
  arithmetically identical in that analysis. It cannot distinguish "duration doesn't
  matter" from "duration doesn't matter above ~5 minutes."

**Consequence for the lesson:** the Overview's "a session can even be seconds long" is
carried by Mingyur (teacher-quotation standard), not by Fincham/Cearns, even though those
two citations sit in the same sentence. Darryl's resolution, August 2026: the short
durations are where you *start* to build the habit, not where you land — so the claim is
about onboarding, not about efficacy at that dose. Do not extend Fincham or Cearns to
defend sub-5-minute practice as effective.

**Why the recommendation is "ten minutes":** 10 is the lowest duration ever tested
head-to-head against a substantially longer one and found equivalent (Fincham). 13 is the
lowest with a clean active-controlled beginner RCT showing real gains (Basso). 5 appears
only as the bottom edge of a bin, never isolated, never in a trial — printing it as a
target would make the weakest-supported number the headline.

**Bowles & Van Dam, 2025** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC12336962/)) —
2–4 year follow-up: practice frequency mattered ~2.5x more than session duration.

**Carmody & Baer, 2009** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/19309694/)) —
Across MBSR programs, more class hours did not produce bigger effects.

**Parsons and colleagues, 2017** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/28527330/)) —
28 studies of 8-week MBCT/MBSR: assigned ~45 min/day six days a week, completed ~30;
closeness to target correlated with outcome.

**Zainal & Newman, 2023** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/36645098/)) —
App prompting 5x/day for two weeks, GAD, vs self-monitoring control: d≈0.3–0.4. Sample
mostly white and female.

**Lim & Dinges, 2010** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC3290659/)) —
70 sleep-deprivation studies, 1,533 people, six cognitive domains: lapses of simple
attention took the largest hit; reasoning accuracy did not move.

**Anderson & Farb, 2018** ([Frontiers](https://www.frontiersin.org/journals/psychology/articles/10.3389/fpsyg.2018.02521/full)) —
82 beginners, three anchors: 49% preferred breath, 30% phrase, 21% image; 56% ended up
preferring a different anchor than predicted.

**Anchor EEG comparison** ([PMC8967094](https://pmc.ncbi.nlm.nih.gov/articles/PMC8967094/)) —
Retrospective, 34 adults, 3-min sessions, consumer EEG: breath/mantra held calm longer
than external point. Weak; cite only as "anchors have been compared," not as a ranking.
**Removed from Lesson 1 (Aug 2026).** The entry was almost entirely methodology critique
of a weak study, and once every Evidence paragraph got a scannable headline, this one's
headline had to announce its own uselessness ("too small to settle anything"). Its only
real function was preempting a reader who found the study elsewhere — not worth a slot.
Anderson & Farb already carries the "no anchor is best for everyone" claim on its own.

## Side effects and limits

**Britton and colleagues, 2021** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/35174010/)) —
96 MBSR/MBCT completers, 44-item interview by a non-teacher. 58% reported an unpleasant
meditation-related experience; 37% life-impacting; 57% of longest experiences under an
hour; 6–14% lasting (definition-dependent). Four experiences (executive dysfunction,
insomnia, emotional blunting, disturbed sense of self), each <5% prevalence, raised
lasting-effect risk 6–14x; common experiences (anxiety, distortions, resurfacing
memories, 10–25%) did not. Informal-practice frequency correlated with life-impacting
events (13.5 vs 4.3 sessions/wk) — direction open. **Caution:** the 83% figure counts
*changes attributed to meditation* including neutral/positive ones; it is not a harm
rate and was misused as one for weeks before being caught.

**Farias and colleagues, 2020** ([Wiley](https://onlinelibrary.wiley.com/doi/10.1111/acps.13225)) —
83 studies: adverse events 8.3% overall; 3.7% in experimental vs 33.2% in observational
studies. Studies that ask systematically find ~10x more than those that wait for
complaints. Psychotherapy comparison rates: 42–51% new/worsened symptoms, 3–14% lasting.

**Van Dam and colleagues, 2018** ([Sage](https://journals.sagepub.com/doi/10.1177/1745691617709589)) —
"Mind the Hype" — definitional sprawl, small samples, weak controls, harm rarely
measured, press ahead of findings. Sympathetic critics; not arguing the practices fail.

**Khoury and colleagues, 2013** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/23796855/)) —
209 mostly weakly-controlled studies: anxiety g=0.89, depression g=0.53–0.69. Use as the
contrast showing what happens without real comparison groups, not as effect estimates.

**Grossman and colleagues, 2004** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/15256293/)) —
Field's original meta-analysis, d=0.54 from 7 true RCTs.

**Foale and colleagues, 2024** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/38267955/)) —
Low-income populations: 12 of 112 candidate studies met inclusion; 10 of 12 US-based.

**DeLuca and colleagues, 2018** ([Springer](https://link.springer.com/article/10.1007/s12646-018-0452-z)) —
Ethnoracial minorities underrepresented in mindfulness RCTs within Western countries.

## Mechanism and specificity

**Lindsay and colleagues, 2018** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/29040891/)) —
153 stressed adults, 14-day smartphone programs: monitoring+acceptance vs monitoring
only vs coping control, same instructor, "mindfulness" never spoken. Combined training
lowered lab stress response; monitoring alone level with control — **not worse than
control** (authors state this directly; do not write "sensing without accepting is worse
than not sensing"). One outcome, one contrast, 14 days.

**Valk and colleagues, 2017 (ReSource)** ([Science Advances](https://www.science.org/doi/10.1126/sciadv.1700489)) and
**Trautwein and colleagues, 2020** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/31450018/)) —
~330 people, three 13-week modules in rotated order, each serving as the others' active
control. Presence→attention, Affect→compassion, Perspective→theory of mind (weakest);
cortical thickness changed module-specifically and tracked individual behavioral gains.
Carries the series thesis. Assigned practice was frequent short daily sessions — an
earlier "practice frequency" figure was misquoted and corrected.

**Lutz and colleagues, 2013** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC3787201/)) —
Heat-pad anticipation, experts ≥10,000 hrs vs novices. Same intensity ratings; lower
unpleasantness; quieter anticipation (amygdala/pain regions, scaling with lifetime
hours); faster physiological recovery **from the pain stimulus** — not from
mind-wandering; do not analogize across (that overreach was made and retracted).
Novices showed gradual *increase* in anticipatory activity over rounds (the full text
confirms this direction; an abstract-based challenge to it was wrong).

### Practice-type specificity (researched August 2026, Lesson 1 "The Practice")

The claim these support: attention is not one skill, and which mode you train decides
what you get. All four verified against primary sources after a supplied citation list
turned out to be partly unreliable (see "Rejected" below).

**Fox and colleagues, 2016** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/27032724/); PDF read in full) —
78 fMRI/PET studies; ALE meta-analysis of 257 foci from 31 experiments, 527 people.
Four categories with enough studies to analyze (focused attention, mantra recitation,
open monitoring, loving-kindness/compassion), three more suggestive (visualization,
sense-withdrawal, non-dual). Authors' own summary line is the one the lesson uses:
activation patterns are "congruent with the psychological and behavioral aims of each
practice" — the machinery matched the job. Also: "distinct meditation styles recruit
largely non-overlapping neural networks"; "convergence is the exception rather than the
rule." Activations d=0.59, deactivations d=-0.74. **Cannot support:** insula as a
compassion-specific signature — insula is the *one* region recruited by all four
categories ("Only a single area (insular cortex) was recruited by all four meditation
categories"), i.e. the paper's convergence finding, not a specificity example. A
supplied summary had this backwards. Compassion's somatosensory cluster is real but
rests on the weakest slice (N=5 experiments, authors flag the low power). Mantra→Broca's
area is clean and verified, including for silent recitation, but was cut from the draft
as an example arriving from nowhere for this reader.

**Carter and colleagues, 2005** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/15936259/); full text
obtained 2026-08-11, Current Biology 15(11):R412–R413, PDF read directly) —
76 Tibetan monks total in the study (5–54 yrs training, including three "retreatist"
meditators with 20+ yrs in isolated retreats), tested at/near their Himalayan, Zanskar
and Ladakhi retreats. **The one-point-vs-compassion comparison — the thing this lesson
cites — used 23 of those 76, not the full 76.** Binocular rivalry induced via
head-mounted goggles (horizontal/vertical gratings to each eye). Within-subject: most of
the 23 served as their own controls, doing both meditation types.

Exact findings: compassion meditation ("a non-referential contemplation of suffering
within the world combined with the emanation of loving kindness") produced "no
observable change in rivalry rate." One-point meditation ("through the maintained focus
of attention on a single object, the mind is calmed") produced "extreme increases in
perceptual dominance durations," reported by **50% of monks** after a period of
one-point practice. Separately, during one-point meditation itself, "three (including
two of the 'retreatists') reported complete perceptual stability throughout the entire
5 minute meditation period" — i.e. 2 of the 3 retreatists plus one non-retreatist, not a
clean experience-predicts-stability story. Authors' own causal framing: "the finding
that the increase in prolongation/stabilization was specific to only one of the
meditation types... suggests that the effect is real, rather then simply reflecting
miscommunication or a general incapability to perform the task."

Not part of this comparison, don't conflate: a separate motion-induced-blindness
experiment (different paradigm) found the single most experienced retreatist (25 yrs)
sustained a disappearance for 723 seconds during active suppression — a striking number,
but from a different task and a sample of one, not usable as general evidence.

**Valentine and Sweet, 1999** ([DOI](https://doi.org/10.1080/13674679908406332)) —
Concentrative vs mindfulness practitioners, Wilkins' counting test. Both beat controls;
long-term beat short-term. Mindfulness practitioners beat concentrative practitioners on
**unexpected** stimuli, with no difference on expected ones. Abstract-level
verification only.

**Koch and Krenn, 2021** ([DOI](https://doi.org/10.1016/j.psychsport.2021.101925); PDF read in full) —
N=75 elite athletes, and the elite bar is real: "only included if they were either part
of the active national team or competed in the highest Austrian league." Open-skill
(American football, basketball, canoe slalom, handball, Olympic sailing) vs closed-skill
(archery, athletics, cross-country skiing, marathon, shooting, swimming, track-bike,
triathlon). **Three of five tests significant, two not** — state the pattern, not a
blanket claim: Trail Making F(3,70)=2.55, p=.03; flanker-switching variant F(3,69)=3.04,
p=.02; 2-back F(3,70)=3.05, p=.02. Design Fluency ns (p=.09); standard flanker ns
(p=.25). So the advantage sits on switching/reacting, not on plain inhibition. Authors'
own caveats, both load-bearing: "effect sizes were small throughout the analyses
restricting the generalizability of the findings" (partial η² ≈ .10–.13), and elite
status is hard to standardize across sports. Cross-sectional — cannot rule out
self-selection into reactive sports. Lesson gives it **one sentence**, deliberately.

**Slagter and colleagues, 2007** — see the entry above under mind-wandering. Added a
second use in Lesson 1 body text for open awareness. **Nuance to preserve:** the paper
does *not* call the retreat practice "open monitoring." It describes Vipassana as
beginning with "focusing or stabilizing concentration on an object such as the breath,"
then broadening to "a non-reactive form of sensory awareness or 'bare' attention." FA
sliding into OM, not pure OM. P3b mechanism verified: reduced T1-elicited P3b after
retreat, and the individuals with the largest decrease showed the greatest T2
improvement (r=-0.68, p=0.001).

### Rejected for this section (checked, do not reuse)

- **Heuschkel & Kuypers, 2020** — a psilocybin/depression review. Nothing to do with
  meditation practice-type specificity. It was supplied as the citation anchoring
  "well-documented phenomenon"; it does not support that or anything nearby.
- **Jha, Krompinger & Baime, 2007 relabelled as FA-vs-OM** — the paper uses neither
  term. It describes *both* groups as concentrative: MBSR participants "naive to
  mindfulness techniques" in a course that "emphasized the development of concentrative
  meditation skills," and retreat participants "experienced in concentrative meditation
  techniques." Its variable is dose/experience, not technique type. Already cited
  correctly elsewhere in Lesson 1 (orienting vs alerting) — leave that use alone.
- **Amihai & Kozhevnikov, 2014** ([PLoS ONE](https://doi.org/10.1371/journal.pone.0102990)) —
  **verified and legitimate**, just unused. Vajrayana (Deity, Rig-pa) vs Theravada
  (Kasina, Vipassana), pre/post meditation on mental rotation and visual memory.
  Vajrayana improved (MRT Deity F(1,14)=19.36, p<0.001; VMT Deity F(1,14)=26.41,
  p<0.001), Theravada did not (F<1 throughout). Cut only to avoid a fourth citation in
  one paragraph and because its arousal/visualization axis needs its own setup.
  Available if that paragraph ever expands.

**Standing lesson from this pass:** a supplied reading list arrived with real, findable
papers carrying an FA/OM specificity narrative bolted on whether or not the paper framed
it that way, plus one citation that was simply the wrong paper. Verify every claim
against the primary source before drafting, regardless of how confident the summary
sounds or how legitimate the surrounding citations are.

### Attention is ancestral (researched August 2026, Lesson 1 opener to "The Practice")

Replaced a framing that called attention practice "thousands of years old," which made
attention read as a human cultural invention. The point is the opposite: the equipment
predates humanity by a very long way.

**Knudsen, 2018** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC6204111/)),
*Trends in Neurosciences* 41(11):789–805 — carries the **attention-specific** half.
"The midbrain stimulus selection network, which monitors the environment continuously
for behaviorally relevant stimuli, appeared already well differentiated at the beginning
of vertebrate evolution." Hub is the optic tectum (superior colliculus in mammals),
"a conspicuously laminated structure even in the earliest vertebrate species." Forebrain
attention networks are the later, more elaborated layer (most developed in primates);
the midbrain spatial-attention network is the ancient one (most elaborated in birds).
**Gives no figure in millions of years** — do not attribute the number to this paper.

**Isa, Marquez-Legorreta, Grillner & Scott, 2021** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC8190998/)),
*Current Biology* 31(11):R741–R762 — carries the **number**. "The fundamentals of the
retino-thalamic and retino-colliculo-thalamic pathways are shared across 450 million
years of the vertebrate history, spanning from cyclostomes to mammals among modern
species." Cyclostomes = lampreys and hagfish, "the oldest group of extant vertebrates."
Tectum/SC "evolutionarily conserved among all vertebrates, but tailored to the sensory
specialties of each lineage."

**The stitch, and why the lesson says "at least":** the 450-million-year figure is
attached to the *visual pathways running through* the superior colliculus, not stamped
on the word "attention." Knudsen supplies the attention claim, Isa supplies the span.
Two sources doing two jobs in one sentence — a fair synthesis, not one paper's headline.
Darryl's "at least 450 million years old" is the correctly calibrated phrasing: 450 My
is the span the fundamentals are *shared across*, so the wiring is at minimum that old.
Do not tighten "at least" to "is."

**Craik, Govoni, Naveh-Benjamin & Anderson, 1996** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/8683192/)),
*JEP: General* 125(2):159–180 — **verified but currently unused.** Four experiments,
divided attention crossed with encoding vs retrieval. "At encoding, DA was associated
with large reductions in memory performance, but small increases in RT... In contrast,
DA at retrieval resulted in small or no reductions in memory." The asymmetry is the
useful part: splitting attention while taking something in costs you most of it;
splitting it while reaching for what you already know costs little. Verified for a
"you learn what you attend to" beat that was cut to keep the opener from bloating.
Available if that argument ever gets its own paragraph.

### Open lead — your attention defaults were installed by your history

**Darryl's argument, August 2026, not yet placed in any lesson.** Where you have put
attention before shapes where it goes now, automatically. If you grew up somewhere
dangerous, your attention learned to hunt for danger, and it keeps doing it after the
danger is gone. That makes deliberate attention practice matter *more* for people with
that history, not less — you are working against an installed default you did not
choose. Candidate homes: Lesson 1 The Challenge (already runs the stuck-alarm and
hypervigilance material), or its own beat; also relevant to Rumination (6) and
Judgment (7).

**Le Pelley, Mitchell, Beesley, George & Wills, 2016** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/27504933/)),
*Psychological Bulletin* 142(10):1111–1140 — carries **one arm** of that argument. Four
findings: attention is biased toward stimuli that reliably predict their consequences
(learned predictiveness, after Mackintosh 1975); that bias is stronger for predictors of
high-value outcomes (learned value); the competing Pearce–Hall uncertainty account gets
less support; and — **the load-bearing one here** — learned predictiveness and learned
value modulate "both deliberate attentional focus, and more automatic attentional
capture," which the authors say "does not appear to fit the traditional view of attention
as being either goal-directed or stimulus-driven," naming it "derived" attention. So:
learning installs attentional pulls that operate below deliberate control. Abstract-level
verification only.

**What this paper cannot carry, and the gap that has to be filled elsewhere:**
- **Nothing developmental.** No childhood, no early-life timing, no critical periods.
  Within-experiment associative learning in adults. "What happened early in your life"
  is not this paper's claim.
- **Nothing about trauma or danger.** The learned-value work is built largely on reward
  (points, money). Threat generalizes in principle but was not tested. The literature to
  chase for that arm: **Bar-Haim, Lamy, Pergamin, Bakermans-Kranenburg & van IJzendoorn,
  2007**, *Psychological Bulletin*, threat-related attentional bias meta-analysis —
  **unverified lead, not yet checked against the primary text.**
- **The compounding loop is an inference, not a finding.** "Attention shapes what you
  learn → what you learn shapes attention → repeat" requires gluing Craik 1996 (one arm)
  to Le Pelley 2016 (the other). Neither paper tests the full cycle. Honest as Darryl's
  framing with each arm cited for its own half; **not** honest stated as established.

**Do not reuse the earlier misreading:** Le Pelley was first reached for as a source for
"attention enables learning" and set aside as the wrong direction. That judgment was
right about *that* claim and wrong as a verdict on the paper — it is the correct source
for learning→attention, which is a distinct and useful claim for this curriculum.

## Long-term practice and expertise

**Brefczynski-Lewis and colleagues, 2007** ([PubMed](https://pubmed.ncbi.nlm.nih.gov/17596341/)) —
Inverted-U in sustained-attention regions: ~19,000-hr practitioners more activation than
novices; ~44,000-hr practitioners less. Basis for the "holding attention stops costing
what it did" claim, stated as "seems to."

**Lutz, Greischar, Rawlings, Ricard & Davidson, 2004** ([PNAS 101:16369](https://pmc.ncbi.nlm.nih.gov/articles/PMC526201/)) —
8 long-term Tibetan practitioners (Nyingmapa/Kagyupa, 10,000–50,000 lifetime hours over
15–40 years, mean age 49) vs 10 controls (mean age 21 — the age gap is a real confound,
note it if the claim ever gets load-bearing). **The controls were not untrained:** "no
previous meditative experience but had declared an interest," then given instruction and
asked to practice one hour daily for the week before recording. Never describe them as
people who had never meditated — the contrast is decades against one week, which is the
more interesting framing anyway. Practice was *compassion /
loving-kindness*, *not* breath-focus — say so, or the reader will assume attention
training produced this. Findings: adjusted average variation in gamma activity >30-fold
greater in practitioners during meditation; and the group difference was already present
in the **resting baseline before meditation began**, with relative gamma correlating with
lifetime hours at that baseline (r=0.79, P<0.02) — the trait-not-state point Lesson 1 uses.
**Correction (Aug 2026):** earlier note here said Ricard's status as a subject couldn't be
supported, since the paper itself never names subjects. DF confirmed he was a subject as
well as a co-author, corroborated by multiple secondary sources (matthieuricard.org's own
description of the paper, among others). Lesson 1 now states this directly.

## Teachers and quotations (verified wording)

**Yongey Mingyur Rinpoche, *The Joy of Living* (2007)** — Epigraph ("The expectations
you bring...") and the waterfall passage ("I was horrified to find myself experiencing
more thoughts...") both verified verbatim against the full text on archive.org. Watch
OCR line-wrapping when grepping book scans. "Short times, many times" corroborated
across Tergar teaching materials (teacher-quotation standard, not research standard).

**Matthieu Ricard, *YES! Magazine* (2009)** — Eagle/crows passage verified against the
published interview. **Link note (Aug 2026):** could not locate the original yesmagazine.org
URL for this 2009 piece ("Cultivating an Eagle Mind," Winter 2009 issue) — it does not
surface in search and may no longer be live on their site. Linked instead to a syndicated
copy at awakin.org, which carries the same verified text. Replace with the original if
it's ever found.

**Levenson, Ekman & Ricard, 2012** ([PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC3742737/); *Emotion* 12(3):650–658, DOI 10.1037/a0027472) —
Case study, Ricard named as subject and co-author, 40+ years practice. Four physiological
channels (heart rate, finger pulse, skin conductance, general movement) plus FACS facial
coding, across open-presence meditation, focused meditation, a distraction control, and an
unanticipated 115-dB/100-ms acoustic startle. **Key result: his response magnitude was
similar to 12 age-matched controls** — not eliminated. Both meditation types reduced
responses relative to the distraction condition (p<.05); open presence reduced them more
than focused concentration. **This corrects a widely circulated myth**, not this paper's
own claim: an earlier informal Ekman observation (reported via Goleman's *Destructive
Emotions*, describing "Lama Öser") became "a monk has no startle reflex at all." Ekman has
publicly corrected this, quoted in *The Chronicle of Higher Education*'s "The Monk and the
Gunshot": "People heard me talk about the fact that I couldn't see the startle, and they
just assumed that he eliminated it. It's a very popular finding, and people like to write
about it, but it's wrong." **Sourcing note:** the Chronicle piece itself returned a 403 on
direct fetch; the quote is corroborated verbatim across two independent secondary sources
(consistent wording, both attributing it to Ekman by name), which clears this project's
bar for usable-but-flagged. Confirm the quote's exact sequencing (both sentences run
together, no material omitted) if it's ever quoted again — verified Aug 2026.

**Ricard's own account of the practice** — verified against primary interview transcripts,
Aug 2026. "Emotionally it's me, me, me all day long. It makes you not really happy, and
quite miserable some times" — [Today.com interview](https://www.today.com/kindness/secrets-kindness-matthieu-ricard-worlds-happiest-man-t53146).
"We do exercise every morning, twenty minutes, to be fit. We don't sit for twenty minutes
to cultivate compassion," plus chess/piano and "potential vs. actualized" analogies — [On
Being interview with Krista Tippett](https://onbeing.org/programs/happiness-is-practice-not-pleasure-matthieu-ricard/).
"Afflictive mental states... begin with self-centeredness, with an increase in the gap
between self and others" — his own piece for *YES! Magazine*, syndicated on DailyGood.
**Cannot support:** "it literally rewired his brain to be happy" — that phrasing came from
a secondary source DF supplied and does not trace to Ricard or to any of the neuroscience
papers; dropped rather than used. Also cannot support any specific numeric ranking of
Ricard's own frontal-asymmetry score against other tested subjects (the widely repeated
"beat 150 subjects" claim) — not found in any peer-reviewed source; not used in Lesson 1.

**Matthieu Ricard, *New York Times Magazine* (2023)** — On the "happiest man in the
world" label, interviewed by David Marchese: "It's a big joke. We cannot know the level
of happiness through neuroscience." He rejects the label consistently across interviews
(elsewhere: "a nonsense idea"). Use it whenever the label appears — the lesson should
never repeat the media framing without his objection to it.

**Sallatha Sutta** (Thanissaro Bhikkhu translation, accesstoinsight.org) — second arrow.

**Darshan Mehta / Harvard Health** ([link](https://www.health.harvard.edu/mental-health/meditation-techniques-how-to-meditate-for-stress-sleep-and-focus)) —
Waterfall corroboration from a clinical source; quoted phrases verified against the page.

---

# Lesson 2 (Emotional Awareness) — research pass, August 2026

Two passes: an initial broad literature search, then a pressure-test pass that assumed
nothing in the notes file or the project introduction was correct until checked. Entries
marked **full text read** were verified directly (in several cases by downloading the
PDF and reading it as a file, since web-fetch tools frequently choked on PDF binaries
that Read handled fine — that trick is worth repeating). Entries marked **needs
follow-up** were only reached through a review's citation or a secondary summary.

## Emotion differentiation and granularity

**Barrett, Gross, Christensen & Benvenuto, 2001** ([Cognition & Emotion](https://www.affective-science.org/pubs/2001/01MaprelationDiffReg.pdf) 15(6):713–724; PDF read in full) —
The founding differentiation-regulation study. N=53 (19 men), college students, 14-day
diary of most-intense daily emotion. Differentiation = correlation among same-valence
emotion words across days (not the ICC method later papers use). Negative-emotion
differentiation × intensity predicted more frequent regulation (b=−8.47, p<.02);
positive-emotion differentiation was **unrelated** to regulation — an asymmetry the
later Kashdan/Pond/Demiralp studies all replicate. **Correlational, and the design
cuts against easy causal readings the field usually gives it**: regulation was measured
by recall of the *preceding* two weeks, before the diary period used to compute
differentiation — done deliberately to avoid shared-method inflation, but it means
regulation was measured chronologically first. The authors' own Limitations section
raises the reverse-causal story explicitly: "it is also possible that more frequent
emotion regulation allows for finer grained differentiation." **Cannot support:** the
"~30% more strategies" figure attributed to this paper by Kashdan et al. 2015 — that
number doesn't appear in Barrett et al.'s text; it's a visual read of Figure 1 at one
specific (high-intensity) point, not something the original authors report as a headline
statistic. Use the regression stats above instead, or cite it only as "more regulation
strategies," unquantified.

**Kashdan, Barrett & McKnight, 2015** ([SAGE](https://journals.sagepub.com/doi/10.1177/0963721414550708); PDF read in full) —
Review, not new data. Synthesizes: Kashdan and colleagues 2010 (ecological momentary
assessment, underage drinkers, N=106, 3-week handheld self-monitoring — corroborated
across multiple secondary sources, primary PDF not obtained) — high differentiators
drank ~40% less alcohol when stressed before a drinking episode; Pond and colleagues
2012 — high differentiators 20–50% less likely to retaliate aggressively; Kashdan and
colleagues 2014 (*PLoS ONE*, verified below) — less insula/anterior-cingulate activity
to social rejection in high differentiators, worst outcomes when paired with low
self-esteem; Demiralp and colleagues 2012 (verified below) — MDD patients showed lower
negative-emotion differentiation than healthy adults even accounting for their more
intense daily distress; Kashdan & Farmer 2014 — social anxiety disorder patients
differentiate emotions less across contexts. Also cites links to autism spectrum (Erbas
2013), eating disorders (Selby 2013), borderline personality disorder (Suvak 2011).
**Caution:** the abstract's "self-injurious behavior" clause has no specific study cited
for it anywhere in the review's body — it reads as inferred from the BPD/eating-disorder
literature, not a direct finding. Don't cite self-injury to this paper. **Update after
reading Seah & Coifman's full text (below): that paper isn't the fix either** — the one
self-injury study inside it (Zaki et al. 2013, N=63 BPD patients) wasn't independently
significant (r=−.09, ns). For a real, well-powered self-injury claim, use Norman et al.
2020 further down (alexithymia — a related but distinct construct from differentiation,
23 studies, N=8,724, g=0.57).

**Pond, Kashdan, DeWall, Savostyanova, Lambert & Fincham, 2012** ([Emotion](https://pubmed.ncbi.nlm.nih.gov/22023359/); PDF read in full) —
Three daily-diary studies, undergraduates, N=628 total. Study 1 (n=199, 25 days): high
differentiators showed 17% fewer aggressive tendencies than low differentiators on
days with more anger. Study 2 (n=186, 21 days): high differentiators reported fewer
provocation episodes and 43% less aggression when provoked and angry. Study 3 (n=243,
25 days): 16% less aggression when angry; the differentiation-x-anger interaction on
aggression was partially mediated by daily emotional control. **Correlational** — the
authors state directly that "findings may not reveal causal relationships"; also a
heavy reliance on single-item daily measures.

**Kashdan, DeWall, Masten, Pond and colleagues, 2014** ([PLoS ONE](https://journals.plos.org/plosone/article?id=10.1371%2Fjournal.pone.0090651); full text read) —
fMRI, N=25 (small — treat effect sizes cautiously), healthy undergraduates, Cyberball
exclusion paradigm. Low-self-esteem × low-differentiation interaction predicted
stronger rejection response in dorsal ACC (β=0.41, p=.02) and bilateral anterior insula
(p≤.02); low differentiators with low self-esteem drove the effect, high differentiators
showed no self-esteem effect at all. Authors did not measure behavioral or physiological
(cortisol) consequences — brain signal only.

**Demiralp, Thompson, Mata and colleagues, 2012** ("Feeling Blue or Turquoise?"; [Psych Science](https://journals.sagepub.com/doi/abs/10.1177/0956797612444903); full text read) —
N=106 (53 diagnosed MDD via SCID-I, 53 healthy controls, matched), 7–8 day experience
sampling, 8 prompts/day, differentiation via Pearson correlation among same-valence
emotion words (Tugade/Fredrickson/Barrett method). MDD group had lower **negative**-emotion
differentiation than controls, F(1,98)=7.18, p<.01, d=−0.54 — no group difference on
positive-emotion differentiation. Effect survived controlling for emotional intensity and
variability, so it isn't just "depressed people feel more/more variably." Correlational;
authors explicitly flag that self-report measures of one's own differentiation ability are
known to be biased, which is why the field prefers this correlation-based objective index.

**Seah & Coifman, 2022**, "Emotion Differentiation and Behavioral Dysregulation in
Clinical and Non-Clinical Samples: A Meta-Analysis," *Emotion* (PDF obtained, full text
read — upgraded from the abstract-only pass this entry originally recorded). 17 samples,
N=2,182. Overall r=−.15 [−.21,−.09], p<.001; Q=28.48, p=.03, I²=43.8%. **Correction to
what this entry said before:** this is a meta-analysis of maladaptive behavior broadly
(binge eating, aggression, substance relapse, treatment non-adherence, self-injury, and
others, pooled together), not a self-injury-specific meta-analysis — and the one
self-injury study inside it (Zaki et al., 2013, N=63 BPD patients) was **not
independently significant** on its own (r=−.09, 95% CI [−.40, .24], p=.59). **Don't cite
this paper for the self-injury claim specifically** — pointing here for self-injury, as
this entry previously advised, was itself an overreach. For self-injury, Norman et al.
2020 below (alexithymia, a related but distinct construct) is the well-powered,
self-harm-specific source. What this paper *does* support well: negative emotion
differentiation is broadly protective against dysregulated behavior as a class, the
effect holds after controlling for mean negative affect (partial r=−.09, p=.023, from
the 11 studies with data to compute it), and it doesn't depend on clinical status
(Q=.01, p=.91) or on how distressed people are (mean-NA moderation ns). Funnel plot
symmetric; trim-and-fill found 2 possibly-missing studies and barely moved the estimate
(r=−.14); fail-safe N=187 against only 17 known studies — publication bias unlikely.
Entirely correlational; authors are explicit that "more research is needed to establish
causality."

**Thompson, Springstein & Boden, 2021**, "Gaining Clarity About Emotion Differentiation"
([Wiley](https://compass.onlinelibrary.wiley.com/doi/10.1111/spc3.12584); PDF read in
full) — The field's own methodological self-critique, and the most important corrective
to how confidently this literature should be cited. Reviewed 73 articles (82 studies,
2001–2019). Key findings that should shape how the lesson hedges:
- **Methods barely agree with each other.** Differentiation is measured five different
  ways (EMA 39% of studies, daily diary 14%, standardized-stimuli tasks 19%, global
  self-report 12%, related-construct proxies 6%), and cross-method correlations are weak
  — the Photo Emotion Differentiation Task and EMA-based differentiation correlate only
  r≈.22, "suggesting they measure somewhat different constructs."
- **The textbook definition and the actual measurement contradict each other.** A person
  who says "I was angry, worried, and disappointed" (three specific words) is described
  in every textbook example as *high* differentiation — but the standard ICC/correlation
  scoring would likely rate that moment as *low* differentiation, because those three
  ratings covary together at that timepoint. The authors give this exact example. This is
  a real, unresolved measurement problem, not a minor technicality.
- **Positive-emotion differentiation is a much weaker, less-studied effect** than
  negative-emotion differentiation — consistent with what Barrett 2001, Demiralp 2012, and
  Kashdan 2014 (above) each independently found.
- **At least one documented exception exists**: generalized anxiety disorder is *not*
  significantly related to lower negative-emotion differentiation (Decker et al. 2008) —
  worth knowing before implying differentiation deficits are universal across
  psychopathology.
- Their own recommendation: don't present differentiation research as a settled,
  unified finding — it's a real and replicated effect on outcomes, measured by
  inconsistent and only weakly-convergent methods.

## Affect labeling

**Lieberman, Eisenberger, Crockett, Tom, Pfeifer & Way, 2007** ([SAGE](https://journals.sagepub.com/doi/10.1111/j.1467-9280.2007.01916.x)) —
fMRI; **needs follow-up** for the primary Methods section (multiple PDF fetch attempts
failed to extract readable text) — but N=30, right-handed, native-English-speaking,
ages 18–36 is corroborated across several independent secondary sources including a
UCLA lab site. Affect labeling, versus other forms of encoding negative images, reduced
amygdala/limbic response and increased right ventrolateral prefrontal cortex (RVLPFC)
activity; the RVLPFC-amygdala relationship was mediated by medial PFC. **Cannot
support:** a claim about reduced subjective distress — this is a brain-signal finding,
not a self-report outcome. The paper frames it as a candidate neurocognitive pathway,
not a demonstrated feeling of relief.
- **Real-world follow-up complicates a simple "labeling reduces distress" claim.** Niles,
  Craske, Lieberman & Hur, 2015 ([Behaviour Research and Therapy](https://escholarship.org/uc/item/91f398qp); full text read), N=100 public-speaking-anxious adults randomized to
  exposure-plus-affect-labeling vs. exposure alone: labeling improved *physiological*
  recovery (heart rate, skin conductance) but produced **no benefit on self-reported
  anxiety** — and participants who used *fewer* labels showed better self-reported
  improvement than heavy labelers. The authors' own read: labeling may change how
  distressed you are by a felt-experience measure without changing what you report, or
  self-report may need a longer follow-up than physiology to catch up. Bottom line for
  the lesson: affect labeling's evidence base is strongest for physiological/brain
  measures, thin-to-contrary for subjective distress — don't claim labeling makes people
  *feel* less anxious in the moment; that's the one outcome this literature doesn't
  clearly support.

**Searched properly under the term "affect labeling" on 2026-08-10, after Darryl pointed
out that much of this literature lives under that name and the ledger had only reached
it through Lieberman 2007.** Three additions below, and they converge on one conclusion
that matters for the whole lesson.

**Kircanski, Lieberman & Craske, 2012**, "Feelings Into Words: Contributions of Language
to Exposure Therapy," *Psychological Science* 23(10):1086–1091 (full text read via PMC,
PMCID PMC4721564) — **the strongest behavioral affect-labeling result there is, and the
one already referenced unverified in the lesson-2 notes file.** N=88 spider-fearful
adults (mean age 20.5, 82% female), randomized to four conditions during live-spider
exposure: affect labeling (describe your fear in emotion words), reappraisal (describe
the spider in neutral words), distraction (talk about your house), or exposure alone.
At a **one-week posttest using a different spider in a different room**, the
affect-labeling group showed greater reductions in skin conductance than reappraisal
(d=0.85, p=.005), distraction (d=0.74, p=.017), and exposure alone (d=0.64, p=.044).
Dose-response: within the labeling group, the more fear/anxiety words a person used, the
larger their drop in fear responding (r=−.288, p=.019). Approach behavior went the same
direction but only marginally (vs. distraction, p=.054). **Critically — and consistent
with everything else in this section: "no significant between-group differences emerged
at any timepoint" for self-reported fear.** Authors' own limits: the reappraisal
instruction was thin compared to real CBT, the exposure-alone group may have labeled
silently anyway, and experimenters weren't blind to condition.

**Torre & Lieberman, 2018** — the field's framing review. Full entry sits below under
*The moderator that resolves the labeling contradiction*, where the provided-versus-
self-generated distinction is set out. The "implicit regulation" framing is the authors'
interpretive claim, not a measured result.

**Nook and colleagues, 2021, replicated by Ariely, Mokady, Reggev & Anholt, 2026**,
"Affect Labeling and Reappraisal as an Emotion Regulation Strategy," *Affective Science*
(full text read via PMC, PMCID PMC13269579) — **a real complication, and the reason not
to teach labeling as a universal first step.** Two pre-registered experiments (N=111,
N=115), 2×2 design crossing naming and reappraisal while viewing negative images.
**Labeling a feeling first made subsequent reappraisal less effective, not more**
(interaction ηp²=.14 and .07, both p<.01; reappraisal alone beat naming-then-reappraisal
at d=1.32 and d=0.86). Authors' reading: labeling may "solidify emerging emotions and
limit emotional regulation flexibility." They note this replicates Nook et al. 2021 and
contradicts the intuitive hypothesis that naming sets up reappraisal. Also: all effects
had washed out by a 1–2 day follow-up. Limits the authors state: participants *typed*
rather than spoke the labels, which may intensify rather than defuse; standardized
images aren't personally relevant material; a different design might separate the two
steps in time and get a different result.

**Burklund, Creswell, Irwin & Lieberman, 2014**, "The common and distinct neural bases of
affect labeling and reappraisal in healthy adults," *Frontiers in Psychology* 5:221 (full
text read, open access, Darryl-supplied) — **the study that corrects the overstatement I
made in this section an hour earlier; see the correction note below.** N=39 healthy adults
aged 55–75 (M=64.65, 31 of 39 female), scanned at baseline before an MBSR program, viewing
aversive IAPS images under four conditions: observe, label, reappraise, shape-match
control. **Two things make it the most directly relevant affect-labeling study in this
ledger:** (1) participants labeled *their own emotional response*, not the emotional
content of an external face or scene — the first study to test the personally-relevant
version neurally, and the version this lesson actually teaches; (2) it directly compares
labeling against reappraisal, psychology's most-studied regulation strategy, in the same
people.
- **Self-report DID move.** Unpleasantness ratings: observe 2.24, label 1.96, reappraise
  1.75. Label vs. observe t(36)=3.59, **p=.001**.
- **Reappraisal beat labeling on self-report** (t(36)=3.02, p=.005) — but the authors note
  this difference "may not represent meaningful experiential differences," and flag a
  demand-characteristic problem: the reappraisal instruction explicitly told people the
  goal was to feel better, the labeling instruction did not.
- **Amygdala reduction was equivalent.** No significant difference between labeling and
  reappraisal in amygdala or any other limbic region — on the neural measure, labeling
  matches reappraisal rather than trailing it.
- **Labeling produced *stronger* prefrontal activation than reappraisal** (bilateral
  VLPFC and DLPFC), which survived masking out motor-response activity. The authors are
  careful: do not read this as more regulation, since amygdala didn't differ and
  reappraisal won on self-report.
- **People good at one strategy were good at the other** — label and reappraise
  self-report reductions stayed correlated controlling for observe ratings (pr=.46,
  p=.005). Relevant to The Benefit.
- Limits the authors state: no task-adherence check; the two conditions used different
  response modes (button-press choice vs. free-form thought); the labeling condition was
  **choosing among three supplied words** (Sad / Anxious / Disgusted / Other), which is
  recognition, not the harder job of generating a name from scratch; sample skewed female
  and unusually healthy; older-adult range limits generalization (though they argue it
  usefully shows these mechanisms are stable late in life).

**CORRECTION to what this section said earlier today.** I wrote that affect labeling
"reliably does NOT move what people say they feel," citing "three independent studies." That
was wrong twice over: only *two* studies had actually measured self-report and found nothing
(Niles 2015, Kircanski 2012 — Lieberman 2007 carried no self-report measure at all), and
Burklund 2014 plus Lieberman et al. 2011 both *did* find self-report reductions. The honest
picture is **mixed, and it splits by paradigm:**
- **Labeling reduces self-reported distress when people view aversive images in a lab**
  (Burklund 2014; Lieberman et al. 2011, cited there, not independently read).
- **It does not when people confront the thing they actually fear** — no self-report
  difference at any timepoint with a live spider (Kircanski 2012), none with real
  public-speaking anxiety, where heavier labelers reported *worse* improvement (Niles 2015).
- **The physiological and neural effect is the consistent one across both paradigms.**
  Amygdala down (Lieberman 2007, Burklund 2014), skin conductance down a week later in a
  new context (Kircanski 2012), faster autonomic recovery (Niles 2015).
- **And it can interfere with a different strategy** if used first (Nook 2021, Ariely 2026).

**How to use this in the lesson:** the defensible claim is that naming settles the body and
opens options — you can act on a specific feeling in a way you cannot act on "bad." Do not
promise it makes distress *feel* smaller in the moment when something real is in front of
you; that is where the two exposure studies came up empty, and real life is the exposure
condition, not the picture-viewing one. This still cuts *toward* the Challenge draft's
framing (cost = lost options, not extra suffering) — but the earlier flat claim that
labeling never moves self-report should not be repeated anywhere.

## Bodily awareness of emotion

**Nummenmaa, Glerean, Hari & Hietanen, 2014** ([PNAS](https://www.pnas.org/doi/10.1073/pnas.1321664111); PDF read in full) —
Five experiments, 701 participants across the body-mapping experiments (773 total
including a separate 72-person recognition-test experiment), self-report body-coloring
task (emBODY). Distinct bodily-sensation maps per emotion; classifiers distinguished
emotions above chance (72%/38% mean accuracy, one-out/complete classification, for
basic emotions against 50%/14% chance). Maps concordant across Finnish, Swedish, and
Taiwanese samples (mean rs=0.70, West European vs. East Asian). **Authors' own caveat:**
cannot rule out that the maps reflect learned conceptual/linguistic association rather
than actual physiological patterning, and the study cannot establish a direct link
between the maps and an underlying physiological activation pattern. **Not yet cited
anywhere in the lesson 2 notes**, despite being the single best-evidenced source for the
"locate it in the body" / body-mapping practice the notes already teach — this is a gap,
not a contradiction.

## Interoception (theoretical framework, not a measured claim)

**Craig, 2009**, "How do you feel—now? The anterior insula and human awareness"
(*Nature Reviews Neuroscience*; confirmed via secondary summary, paywalled — **needs
follow-up** if the lesson leans on it directly) — Theoretical review/synthesis, not new
experimental data. Proposes the anterior insula as the site where interoceptive signals
become subjective feeling and self-awareness, built on prior neuroimaging literature.
**Caution:** this is Craig's hypothesis, framed by commentators as a model with an
evidence base but needing further confirmation, not an established, directly-tested
result. Don't cite it as if the insula-as-feeling-seat claim were settled.

## Basic-emotion-systems vocabulary

**Panksepp**, *Affective Neuroscience* (1998); corroborated via [Montag & Panksepp,
2018 review](https://pmc.ncbi.nlm.nih.gov/articles/PMC6344464/) (*Frontiers in
Neuroscience*) — Seven primary emotional systems (SEEKING, FEAR, RAGE, PANIC/GRIEF,
PLAY, CARE, LUST), evidenced by direct electrical stimulation, lesion, and
pharmacological studies across mammalian brains — not inference from behavior alone.
**Caveat the field itself raises:** whether these subcortical, cross-species systems
map onto human *conscious* emotional categories the way everyday words (anger, fear,
sadness) imply is unresolved — most animals may lack the reflective awareness needed to
equate their affect states with human felt experience. The exact number of genuinely
distinct systems is also still argued. Treat as an organizing vocabulary, not a settled
taxonomy — consistent with the notes file's own framing that the Barrett/constructionist
disagreement with this view is "real and unresolved." (Barrett's own constructed-emotion
theory — core affect plus learned concept, assembled fresh each time rather than fired
from a fixed circuit — was only checked against secondary summaries, not her primary
papers/book; the notes' one-paragraph paraphrase of it is consistent with those summaries
but hasn't been checked against her original text.)

## Two claims pressure-tested with new searches (not in the original citation list)

**Emotion duration — "a strong feeling usually dies down... within minutes."** Checked
directly against **Verduyn, Delvaux, Van Coillie, Tuerlinckx & Van Mechelen, 2009**
(*Emotion*; two studies, PDFs read in full) and the closely related **Verduyn, Van
Mechelen, Tuerlinckx & Scherer, 2013** line of work. Study 1 (N=59, diary, fear/anger/joy):
median duration 16 min (fear), 22 min (anger), 26 min (joy); 80% of episodes ended within
the first hour. Study 2 (N=43, diary, anger/gratitude/joy/sadness): median duration 11–20
min; 80% ended within 30 min. **This genuinely supports the notes' claim** — unlike the
mind-wandering duration claim cut from Lesson 1, this one has real primary data behind it,
in the same rough magnitude ("minutes," not hours, for the typical case). Two important
qualifications before stating it flatly: (1) there's a long right tail — episodes tied to
more important/intense-onset situations last substantially longer, and some ran past the
study's 1–2 hour measurement ceiling entirely; (2) **the rumination half of the claim is
also directly supported and is the stronger finding**: both physical *and* merely mental
"reappearance" of the eliciting situation significantly prolonged the episode for every
emotion tested (mental-contact β=0.86–1.04, p<.001 across anger/joy/gratitude/sadness) —
so "not fed by rehearsing the story" is doing real causal work in this data, not just
flavor text. Caveat: small samples (N=59, N=43), Belgian university students, self-report
of subjective duration only.

**Emotions "blend."** This is a live, unresolved scientific dispute, not settled fact —
checked against **Larsen, 2017**, "Holes in the Case for Mixed Emotions" (*Emotion
Review*; full text read). Some theories treat positive and negative affect as two
separate systems that can co-activate (supporting "blends"); others treat them as
opposite poles of one bipolar dimension (ruling out true simultaneity). Larsen's
critique: studies claiming to find simultaneous mixed emotions may actually be capturing
rapid oscillation between emotions, conceptually-related ambivalence, or a demand
characteristic of being asked "do you feel both X and Y?" — and he argues the competing
hypotheses "may not be entirely falsifiable," i.e. this may never fully resolve
empirically. The notes' plain-language framing ("anger sitting on top of fear") doesn't
overclaim a mechanism, so it isn't contradicted by this — but it is worth knowing the
underlying science is contested, not consensus, if the lesson ever cites a specific study
for it.

---

# Lesson 2, Challenge-section pass — 2026-08-10

Prompted by pressure-testing the draft "Challenge" argument specifically: is there a
*strong, clearly demonstrated* cost to lacking emotional awareness, or were we reaching?
This pass found the strongest evidence in the whole Lesson 2 research to date, mostly
outside the granularity literature above — in alexithymia (the clinical construct for
difficulty identifying/describing one's own emotions) and in two papers Darryl supplied
directly as PDFs.

## Interpersonal effects — supplied PDFs, full text read

**Erbas, Sels, Ceulemans & Kuppens, 2016**, "Feeling Me, Feeling You" (*Social
Psychological and Personality Science*; PDF supplied, full text read) — N=98 (49
Belgian couples), 7-day experience sampling, 10 signals/day. Negative-emotion
differentiation correlated with accuracy reading a partner's *valence* (r=.30, p<.01;
confirmed in multilevel models, males B=.24 p=.014, females B=.19 p=.026). **Narrower
than the headline claim it's often used for:** null for arousal accuracy, and null for
"pattern accuracy" (tracking a partner's mood *changing* over time) — only for how close
you land on their average state. Positive-emotion differentiation unrelated to either
accuracy measure. **Correlational, direction untested** — the authors say so explicitly:
"it is not possible to draw conclusions on the direction of the relationship."

**Erbas, Ceulemans, Kalokerinos, Houben, Koval, Pe & Kuppens, 2018**, "Why I Don't Always
Know What I'm Feeling" (*JPSP*; PDF supplied, full text read) — N=200 first-year
students (190/177 retained at waves 2/3), three-wave measurement-burst design over a
year, well-powered by design. Real, specific finding: stress on one day predicts *lower*
negative-emotion differentiation the *next* day (p=.010), holding even after controlling
for that day's own stress (p=.009). Robustness check ruled out the obvious confound —
anger, anxiety, sadness, depression, and loneliness all predicted differentiation
*concurrently* but **none of them predicted it prospectively the way stress did**, so
this isn't just "feeling bad in general." **Important complication if this gets cited:**
the authors explicitly resist framing this as dysfunction — no well-being measure
consistently moderated the effect, and their discussion argues reduced differentiation
under acute stress may be an *adaptive simplification* (narrowing attention to cope)
rather than a malfunction. Don't cite this as "you're broken exactly when it matters
most" — the honest framing is "the skill moves with your state, and whether that's good
or bad is still open."

## Alexithymia and depression — upgraded confidence

**Liu, He & Hou, 2025**, "The effect of alexithymia on depression: evidence from
meta-analysis," *Frontiers in Psychology* 16:1465286 (PDF downloaded and read in full,
2026-08-10 — upgrading the earlier two-web-fetch pass. Every number below is confirmed
against the paper's own tables. **The numbers held; my confidence in the paper did
not.** See the quality flags at the end of this entry.)

**Headline results, confirmed:** 35 studies, N=23,085 (sample sizes 40–10,908, 53.2%
female), 2001–2023, Chinese and English databases, random-effects. TAS-total with
depression r=0.455 [0.417, 0.491]. I²=87.995% (substantial). Egger's test β=0.045,
p=0.951 — no detected publication bias; funnel plot symmetric. Sensitivity analysis
dropping the smallest study barely moved it (r=0.456). Eastern samples r=0.498 (16
studies) vs Western r=0.416 (19 studies), non-overlapping CIs. Subject group mattered
(Q=9.999, p=0.007): mental-disorder r=0.470, no-impairment r=0.461, physical-impairment
r=0.366. Measurement tool did **not** matter, for either construct — depression scale
Q=6.892, p=0.229; alexithymia scale Q=0.031, p=0.861. Gender (β=−0.139, p=0.107) and
publication year (β=0.001, p=0.792) both null.

**Correction to how this entry read before — the subscale split rests on a smaller
base.** DIF r=0.411 [0.357, 0.463], DDF r=0.331 [0.268, 0.391], EOT r=0.120 [0.080,
0.159] come from **30 studies and 7,885 participants**, not the full 23,085. Anything
written as though the twenty-three-thousand-person dataset establishes the
identify/describe-vs-external-thinking split is overstating it. Same ordering appears in
the SEM (DIF R²=0.670, DDF R²=0.293, EOT R²=0.158).

**The pattern replicates independently, which matters more than this paper does.**

**Li, Zhang, Guo & Zhang, 2015**, "The association between alexithymia as assessed by the
20-item Toronto Alexithymia Scale and depression: a meta-analysis," *Psychiatry Research*
227:1–9, doi 10.1016/j.psychres.2015.02.006, PMID 25769520 — **abstract verified directly
via PubMed; full text paywalled at Elsevier** (ScienceDirect 403s, ResearchGate is
request-only, Semantic Scholar has no open copy — chased 2026-08-10 and stopped rather
than routing around the paywall). Confirmed from the authors' own abstract: 3,572
subjects, 20 study groups, 19 studies. "Medium relationships were observed between
depression and TAS-total score (TAS-TS), DIF, and DDF," and "a weak relationship between
EOT and depression."

**That is the replication the Liu et al. claim needed.** An earlier, independent,
Western-only meta-analysis, different research group, reproduces the exact pattern the
lesson leans on: identifying and describing feelings track with depression at medium
strength; externally-oriented thinking only weakly. The body claim does not need the
third decimal place, so abstract-level verification is sufficient here — same tier the
Lesson 1 ledger uses for Lieberman 2007.

The total-score figure of **r=0.459** comes from Liu et al.'s description of this paper,
not from the abstract, so it is secondary — cite the *pattern* to Li et al. and leave the
precise coefficient to Liu et al., where it is primary-verified.

**Do not record** the "patient r=0.39, community r=0.41, student r=0.46" breakdown that
turns up in search summaries alongside this paper. It could not be traced to either
paper's verified text and may be a search engine conflating a third source.

**A genuine disagreement between the two meta-analyses, worth knowing before either gets
cited on measurement:** Li et al.'s abstract reports *stronger* correlations when
depression was measured by self-report than by the clinician-administered Hamilton scale
— i.e. the instrument matters. Liu et al. tested the same thing and found it did **not**
matter (Q=6.892, p=0.229). Both cannot be right. Neither paper's measurement-tool claim
should be treated as settled, and the lesson has no reason to make one.

**Quality flags — real ones, found only by reading the full text:**
- **Word-substitution errors throughout.** "Alexithymia" is replaced by "narrative
  affective disorder," "narrative dysphoria," or bare "dysphoria" in much of the
  Discussion and Limitations, and twice by clinically unrelated terms — "elevated levels
  of **dysarthria**" (a motor speech disorder) and "underestimation of **dysgraphia**"
  (a writing disorder). Reads like an uncorrected find-replace or translation artifact.
  The abstract says "whereas whereas."
- **One citation is simply wrong.** The claim that Eastern cultures show higher
  alexithymia than Western ones is supported with "Dion, S. (1996). Why is secession
  difficult in well-established democracies? Lessons from Quebec" — a political science
  paper on Quebec sovereignty, cited for a cross-cultural emotion claim.
- **An impossible sample size.** The meta-analytic SEM reports "N = 245.388" — with a
  decimal point. It cannot be 245,388 (larger than the whole dataset) and 245 is too
  small for 14 pooled studies. The earlier version of this ledger entry recorded that
  figure uncritically; it should not be cited.
- **Internally contradictory effect range.** Section 3.2 says individual study effects
  "ranged from 0.313 to 0.462." Their own Table 2 runs 0.210 to 0.650.
- **Apparent double-counting, against their own stated criteria.** Inclusion criterion
  (3) requires independent samples with no duplication, yet Oakley et al. (2022) appears
  as five separate rows, and rows 26 and 34 both report n=179, same subject status, same
  study — differing only in depression measure (BDI r=0.220 vs BDI-II r=0.490). That
  looks like one 179-person sample entered twice.
- **They upgrade their own effect size rhetorically.** Cohen puts r=0.455 between
  moderate and high; the paper reaches for Gignac & Szodorai's more lenient benchmark to
  call it "highly positive," and the Conclusion promotes DIF/DDF from "moderate" (as the
  Results section has it) to "strong."
- Table typos compound the impression: "Sirodff" for Radloff (CES-D), "HMAD" for HAMD,
  "Aexithymia," and two different Flaherty references (1988 and 1998) used
  interchangeably for the same point.

**How to use it:** the r≈0.46 total-score figure is safe — it is stable under their own
sensitivity analyses, shows no publication bias, is invariant to measurement instrument,
and matches an independent 2015 meta-analysis. The DIF/DDF-over-EOT split is probably
also safe for the same replication reason, but cite it to the 7,885-participant
subanalysis rather than the headline N. Do not cite this paper's SEM, its effect-size
range statement, or its cross-cultural claims. **Correlational** — the authors call
alexithymia a "vulnerability" and never claim to have established direction.

**One tension worth carrying into The Benefit and The Practice:** this literature treats
alexithymia as a *stable personality trait* (publication year null over 22 years; the
authors cite Saarijärvi 2006 finding EOT unchanged across five years in depressed
outpatients, and Hemming 2019 on trait stability). Erbas et al. 2018 above shows
differentiation moving day to day. Different constructs and different timescales, but
if the lesson claims this is trainable, that claim answers to the trait-stability
literature and should be sourced to intervention studies rather than to either of these.

**A third meta-analysis, read for the anxiety question below but reporting depression
numbers too — a useful cross-check, not a replacement for Liu or Li.** Yeung,
Kiropoulos et al. 2026 (full entry under "Low emotional awareness and anxiety" below)
found, for major-depression-type groups vs. controls, TAS-total SMD=1.26–1.28 (large,
k=8–17 depending on how depressive disorders are grouped) — consistent in *direction
and size-class* with this section's g/r-based numbers, though not directly comparable
(SMD vs. r are different metrics). Their symptom-severity correlation, TAS-total
r=.32 [.22, .41], runs a bit **lower** than both Li et al. 2015 (r≈.43 by Yeung et
al.'s own citation) and Liu et al. 2025 (r=.455) — same direction, real numeric spread
across three independent meta-analyses (.32 to .455). Their DDF-severity correlation
(r=.51, k=11) is notably **higher** than Li's DDF figure (.343) — the opposite
direction of spread. EOT is again the weak subscale (r=.13, ns-adjacent). **Net: three
independent meta-analyses now agree depression correlates with alexithymia at a
real, moderate size and that DIF/DDF carry it while EOT doesn't — but the exact
coefficient moves around by as much as .32–.46 depending on which meta-analysis you
read, which is itself worth knowing before citing a single decimal to three places.**

## Alexithymia and relationships

**Humphreys, Wood & Parker, 2009**, "Alexithymia and satisfaction in intimate
relationships," *Personality and Individual Differences*, 46, 43–47 (PDF supplied, full
text read) — the best-controlled source on this question now in the ledger. N=158
undergraduates (34 male, 124 female), all in relationships ≥3 months. SEM with a
negative-affect control variable included specifically to rule out "alexithymic people
are just in a bad mood": alexithymia → relationship satisfaction β=−0.52, alexithymia →
sexual satisfaction β=−0.51, both significant; **negative affect's own paths to both
satisfaction measures were non-significant** — the alexithymia effect survives
controlling for current mood, it isn't a mood artifact. Good model fit (CFI=0.955).
Correlational, cross-sectional, one relatively young/short-duration sample (mean
relationship length 17.6 months) — authors flag that findings may not hold the same way
in longer-term relationships.

**Frye-Cox & Hesse, 2013**, "Alexithymia and marital quality: the mediating roles of
loneliness and intimate communication," *Journal of Family Psychology*, 27(2), 203–211,
DOI 10.1037/a0031961 — **still needs follow-up** (only reached through other papers'
citations of it, never the primary text itself). N=155 couples, dyadic design; loneliness
and intimate communication fully mediated the alexithymia–marital-quality link. Lower
priority now that Humphreys above gives a cleaner, primary-verified, mood-controlled
number — chase this only if the mediation mechanism itself (loneliness, specifically)
becomes something the lesson wants to name.

**Panahi, Hoseinzadeh, Razaghpour & Hosieni, 2018**, "Formulating a model for the
relationship between alexithymia, social support, loneliness, and marital satisfaction,"
*Journal of Family Medicine and Primary Care*, 7(5), 1068–1073 (PDF supplied, full text
read) — N=108 Iranian couples (216 individuals), path analysis. The direct path from
alexithymia to marital satisfaction was **not significant and was dropped from the
model** — the entire effect ran through loneliness (alexithymia → loneliness β=0.34 →
marital satisfaction β=−0.45; indirect effect −0.15). This is the same shape of finding
as Frye-Cox & Hesse (mediated, not direct), from an independent, non-Western sample —
worth citing as convergence on the *mechanism* (loneliness carries the effect) rather
than as a second data point on the raw correlation, which this study doesn't report
directly. Self-report, cross-sectional, translated instruments, small regional sample —
treat as supporting, not load-bearing.

**Besharat, Naghshineh, Ganji & Tavalaeyan, 2014**, "The Moderating Role of Attachment
Styles on the Relationship of Alexithymia and Fear of Intimacy with Marital
Satisfaction," *International Journal of Psychological Studies*, 6(3), 106–117 (PDF
supplied, full text read) — N=688 Iranian married university students, the largest
sample in this cluster. Alexithymia correlated with marital satisfaction at r=−.49
(women) and r=−.45 (men), both p<.001; regression β=−.302, p<.001. Avoidant attachment
style significantly moderated the relationship (ΔR²=.01, p=.02) — alexithymia's cost is
larger for people who are also avoidantly attached. Cross-sectional, self-report,
culturally specific sample, short marriages (M=3.2 years) — same limits as the other
sources in this cluster.

**Read together, these four give a real number to check the rejected Pakistan paper
against:** Humphreys (β=−.52/−.51, Canadian students), Besharat (r=−.45/−.49, Iranian
married adults), Frye-Cox & Hesse and Panahi (both mediated through loneliness rather
than direct). Four independent samples, three different countries, converging on a
moderate effect somewhere around r/β = −.45 to −.55. That range is what makes the
rejected paper's r=−.78 stand out — not just against big meta-analyses on an adjacent
question, but against direct replications of this exact question.

**Milioni, Tsaousis & Zisopoulos, 2023**, "Alexithymia and romantic relationship
satisfaction: the mediating role of emotional regulation and empathy," *Current
Psychology* — **not yet read**, surfaced via reference-list mining. Reported as
longitudinal, which would make it the best-designed source on this specific question if
it holds up, but four converging cross-sectional sources above already give a stable
effect-size estimate — lower priority to chase unless the lesson specifically wants
longitudinal evidence.

**Rejected: Fatima, Yasir, Ayub & Aleem, 2024/2026**, "The Relationship Between
Alexithymia and Marital Satisfaction Among Married Individuals," *Pakistan Journal of
Positive Psychology*, 3(3), 72–78 (PDF supplied, full text read) — **do not use.** N=300,
Pakistan, cross-sectional survey, reports r=-.78 between the Perth Alexithymia
Questionnaire and the Couples Satisfaction Index. Three independent problems, not one:
(1) an effect of that size is far outside what this literature produces anywhere —
compare r=.455 and g=0.57 in the two large meta-analyses above, both from tens of
thousands of participants; (2) the paper's own reference list cites Frye-Cox & Hesse
2013 under a title and page range that don't match what the actual paper's DOI resolves
to; (3) the text reports the "positive feelings" subscale correlation as identical to
three decimal places to the total-scale correlation (both -.78), which real, distinct
measures don't produce. Could not confirm or deny the journal's indexing status either
way (checked DOAJ and Beall's list, found nothing conclusive) — that suspicion is
dropped for lack of evidence, but the three problems above stand on their own regardless
of the journal or the country, and are sufficient alone to disqualify this paper.

## Alexithymia and self-harm, and adolescent development

**Norman, Oskis, Marzano & Coulson, 2020**, "The relationship between self-harm and
alexithymia: a systematic review and meta-analysis," *Scandinavian Journal of
Psychology* (PDF obtained, full text read in full, including forest plots and subgroup
tables) — 23 studies in the meta-analysis, **N=8,724**. Medium effect, g=0.57 [0.46,
0.69], Z=10.57, p<.001. Publication bias formally ruled out (symmetric funnel plot,
Begg & Mazumdar p=.206; trim-and-fill changed nothing). Effect driven by DIF (g=0.61)
and DDF (g=0.41); **EOT not significant** (g=0.10, CI crosses zero) — the same
identify/describe-drives-it-but-EOT-doesn't pattern as the depression meta-analysis
above, an independent convergence worth noting. **Adolescent-specific finding:**
significantly larger effect in adolescents (g=0.69, Mage≤18, 10 studies, n=5,972) than
adults (g=0.48, 13 studies; Q*=4.43, p=.035); the DIF subscale alone showed the same
age gradient (p=.021). The single longitudinal study in the whole set (Garisch & Wilson
2015, N=566 adolescents) found alexithymia predicted self-harm five months later, not
the reverse — the only real temporal-precedence evidence in either direction, and it's
adolescent data. **Caveat the authors themselves state:** heterogeneity across the 23
studies was high (I²=70.2%), and the field hasn't done enough longitudinal work to call
alexithymia a confirmed risk factor rather than a correlate — "this cannot be
interpreted as causation."

**Hemming, Taylor, Haddock, Shaw & Pratt, 2019**, "A systematic review and meta-analysis
of the association between alexithymia and suicide ideation and behaviour," *Journal of
Affective Disorders*, 254, 34–48, PMID 31103905 (full text read via PMC — open access,
not paywalled after all; upgraded from an abstract-only pass). 34 studies, N=10,104,
adult samples (16+), clinical and general population, English-language only.
**Two separate effects, not one — and they run in opposite directions from what a quick
skim suggests:**
- **Suicide ideation: r=0.54 [0.40, 0.65] — large** (16 studies), bigger than this
  ledger's depression figure (r=0.455, Liu et al. 2025) and comparable to Norman et
  al.'s self-harm g=0.57 above.
- **Suicide behaviour: r=0.25 [0.16, 0.34] — small** (16 studies).
This is the opposite gradient from what "suicidal ideation" and "self-harm/behaviour"
sound like they should produce if lumped together as one severity ladder — *ideation* is
the strongly-linked outcome here, *behaviour* the weakly-linked one. **Do not cite a
single number for "suicidality"** — ideation and behaviour are two different effect
sizes here, and self-harm (Norman et al., g=0.57) is a third, related but distinct
outcome again.

**Subscale breakdown — mostly the familiar pattern, with one real exception.** For
suicide *behaviour*: DIF r=0.16, DDF r=0.15, EOT r=0.00 (ns) — same
identify/describe-drives-it-EOT-doesn't shape as depression and self-harm above. For
suicide *ideation*, though: DIF r=0.41, DDF r=0.43, **EOT r=0.28 — not null this time**,
the one place in this whole ledger where externally-oriented thinking shows a real
association with an outcome. Worth flagging as a genuine exception, not smoothing it
into the usual pattern.

**Two quality flags found only by reading the full text:**
- **Six studies from one Italian research group (De Berardis and colleagues) drove a
  meaningful chunk of the headline number.** Removing that cluster drops the ideation
  effect from r=0.54 to r=0.41 — still a real, moderate effect, but the "large effect
  size" framing depends partly on one lab's output.
- **The authors' own multivariate check undercuts the behaviour effect specifically:**
  when studies controlled for other variables (depression, hopelessness, etc.), results
  for suicide *behaviour* were mixed enough that the authors concluded outright "the
  relationship between suicide behaviours and alexithymia is not robust." Ideation held
  up better under the same kind of check (one exception: Wood et al. 2010 found it
  dropped to non-significant once depression/hopelessness/worthlessness were
  controlled).
- Heterogeneity was severe throughout (I²=95% for ideation, 85% for behaviour, all
  subscale analyses also exceeded 75%) — age (≤25 vs >25) and Eastern-vs-Western
  location were tested as moderators and explained none of it (both p>.19). Egger's test
  flagged possible publication bias for the behaviour studies specifically (β=2.15,
  p=.016), not for ideation (p=.065).
- Sample: 10 of the underlying studies had fewer than 100 participants each
  (underpowered, risk of Type II error in the individual studies feeding the pool);
  under-16 samples were excluded by design, so this doesn't extend to children.

**How to use it:** cite ideation (r≈.41–.54 depending on whether the single-lab cluster
is included) as the stronger, more robust claim; treat the behaviour correlation (r=.25)
as real but explicitly flagged by its own authors as fragile once other variables are
accounted for. Correlational throughout — cross-sectional design dominates the
underlying studies, and the authors call for longitudinal work to establish direction.

**Nook, Sasse, Lambert, McLaughlin & Somerville, 2018** — full entry is under "Young
children, and the full lifespan arc" below, since it anchors that arc as well as this
adolescent point; the short version: N=143, ages 5.78–25.91, differentiation dips to a
low point around age 15.7 then climbs back.

**Read together**, these two give the strongest version of a demonstrated Challenge
available so far: the skill is developmentally at its lowest point around adolescence
(Nook), and that is also where the measured cost of lacking it is largest (Norman et
al.'s significant age moderation on self-harm). This is a materially stronger evidentiary
base than the granularity-only literature earlier in this ledger, where effect sizes
were mostly small (r≈.15–.30) and the field's own methodological critique (Thompson et
al. 2021, above) urges caution about overclaiming.

## Young children, and the full lifespan arc

Prompted by the question of whether the developmental story extends earlier than Nook's
5-year-old floor, and later than his 25-year-old ceiling. It does, on both ends, and all
four studies below (two supplied as PDFs, fully read) now chain into a single arc.

**Nook, Sasse, Lambert, McLaughlin & Somerville, 2018**, "The Nonlinear Development of
Emotion Differentiation," *Psychological Science* (WebFetch of full text, detailed —
not a downloaded-PDF read) — N=143, ages 5.78–25.91. Emotion differentiation follows a
**U-shaped** developmental curve: relatively high in childhood, drops through
adolescence, rises again into adulthood (quadratic effect β=0.32, p<.001; low point
≈age 15.7). Mediated by young children's tendency to report feeling one emotion at a
time rather than several at once — not explained by intensity differences or careless
rating. Correlational; the authors' own sample has a built-in floor (participants had to
understand the emotion-word vocabulary used in the task).

**Widen & Russell, 2008**, "Children Acquire Emotion Categories Gradually," *Cognitive
Development*, 23, 291–312 (PDF supplied, full text read — upgraded from an earlier
abstract-only pass) — N=168 children, ages 2–5 (Young: 24–47mo; Older: 48–65mo), plus 24
adults as a comparison ceiling. Two tasks: free labeling of six facial expressions, then
a categorization ("box") task. Their **Differentiation Model**: emotion categories start
broad — organized mainly by valence — and narrow gradually across the preschool years.
**Exact acquisition order and ages**, from which labels children spontaneously produce:
happiness alone first (mean age 30.2 months) → happiness+anger or happiness+sadness
(35.4–35.7mo) → happiness+anger+sadness (41.2mo) → adding fear or surprise (50.5mo) →
adding the other of the two (53.1mo) → adding disgust last (only 7 of 168 children
reached this level). 81% of children fit this exact sequence. **An important
self-correction inside the paper itself**, worth carrying into anything that cites it:
their earlier (2003) claim that later-emerging categories (fear, surprise, disgust)
start out *narrower* than early ones (happiness, anger, sadness) turned out to be an
artifact of the labeling task specifically — well-practiced early labels get used more
often when a child is unsure what they're looking at, making those categories look
broader than they are. The categorization task, which doesn't have that bias, showed
all four tested categories (happiness, anger, sadness, fear) were **equally broad** at
first and narrowed at similar rates. The broad-to-narrow trajectory itself replicated in
both tasks; only the "some categories start broader than others" detail didn't hold up
under their own re-test. Cross-sectional; the authors note a longitudinal follow-up was
underway at time of writing (not this paper).

**Russell & Widen, 2002**, "Words versus faces in evoking preschool children's knowledge
of the causes of emotions," *International Journal of Behavioral Development*, 26(2),
97–103 (PDF supplied, full text read) — a related, useful complication for any framing
that leans on facial expressions as the foundation of young children's emotion
knowledge. N=160, ages 3–4. Children generated stories about why a character felt a given
emotion, cued either by a word ("scared") or a photo of the matching facial expression.
**No "Face Superiority Effect" was found — the reverse.** Overall accuracy was higher in
the word condition than the face condition (.44 vs .32 by strict scoring, .64 vs .51 by a
looser plausibility scoring), and the word's advantage over the face was specifically
and significantly larger for **fear and disgust** (p<.001 both) — the same two emotions
Widen & Russell's other paper found emerge latest. The authors argue this challenges the
common assumption ("perceptual bedrock hypothesis") that kids learn emotion concepts by
first recognizing faces and building outward from there — for the hardest emotions,
being told the word outperformed being shown the face. N=160, cross-sectional, lab task
with posed rather than naturalistic expressions.

**Carstensen, Pasupathi, Mayr & Nesselroade, 2000**, "Emotional Experience in Everyday
Life across the Adult Life Span," *JPSP*, 79(4), 644–655 (PDF supplied, full text read —
upgraded from an abstract-only pass) — N=184 (31% African American, 69% European
American), ages 18–94 (M=55), one week of experience sampling, 5 signals/day, 19 emotion
terms rated each time. **Exact stats, not just direction:**
- Frequency of positive emotion: flat across age, no significant effect.
- Frequency of negative emotion: quadratic, F(2,182)=6.0, p<.01 — declines from 18 to
  about 60 (simple r=−.29, p<.01), then the decline stops (r=.14, ns from 60 on).
- **Differentiation** (their measure: number of eigenvalues >1 from each person's
  19×19 emotion-correlation matrix across the week; average 5.8, range 2–9): correlated
  with age at r=.28, p<.01, linear, no quadratic falloff — held across ethnicity,
  gender, and socioeconomic status, and wasn't explained by personality, health, or
  verbal fluency.
- Differentiation's other correlates: unrelated to overall mental health (r=−.07);
  negatively related to how *often* both negative (r=−.30) and positive (r=−.22)
  emotions were felt, and to the *intensity* of negative emotion specifically (r=−.16);
  negatively related to neuroticism (r=−.19).
- **A second, separate measure worth its own line — "poignancy":** the within-occasion
  correlation between positive and negative affect, i.e. how much pleasant and unpleasant
  feelings show up *at the same moment*. Averaged r=−.35 across the sample (feelings
  mostly don't co-occur), but this became reliably *less negative* with age (r=.26,
  p<.01 for the age relationship) — under 60, the average within-person correlation was
  −.42; over 60, it was −.25. This is a direct, quantitative measurement of "mixed
  emotions becoming more common," specifically tied to age rather than to the
  differentiation measure above (the two were only modestly correlated, r=.23, and each
  held up controlling for the other) — a genuinely different angle on the
  emotions-blend question than Larsen's skepticism above, since it isn't asking whether
  blending is *real* so much as measuring how much of it there is and finding it scales
  with age.
- Framed within socioemotional selectivity theory (shrinking time horizons shift
  priorities toward emotionally meaningful engagement). Cross-sectional — the authors
  themselves flag that "any and all claims about age change based on cross-sectional
  designs must be tempered accordingly." This is the study Kang & Shaver 2004 and
  Kashdan et al. 2015 (above) are quietly leaning on when they assert granularity
  "improves as adults age" — cite it directly instead of through those intermediaries.

**The full arc, chained across four studies now in this ledger:** broad, valence-only
categories in toddlers and preschoolers (Widen & Russell, ages 2–5) → those categories
sharpen through mid-childhood → differentiation dips to its lowest point around age
15.7 (Nook et al., ages 5–25) → rises back through the twenties and continues rising
across adulthood, with negative-emotion frequency also easing until roughly 60
(Carstensen et al., ages 18–94). No single study spans the whole range — this is four
different samples with four different methods stitched together, not one longitudinal
cohort — so treat the shape of the curve as the best current synthesis, not a single
demonstrated fact, until same-cohort longitudinal data exists.

## Low emotional awareness as a transdiagnostic risk factor (adolescents)

Prompted by a Harvard Brain Science Initiative summary Darryl surfaced
(brain.harvard.edu/hbi_news/emotional-awareness-and-mental-health/), which names exactly
one study — checked directly against that study's full text (nihms-1584875.pdf,
Darryl-supplied), not just the summary, since the summary undersells what's actually in
it.

**Weissman, Nook, Dews, Miller, Lambert, Sasse, Somerville & McLaughlin, 2020**, "Low
Emotional Awareness as a Transdiagnostic Mechanism Underlying Psychopathology in
Adolescence," *Clinical Psychological Science* 8(6):971–988, PMID 33758688 (full text
read, upgraded from the abstract-only pass). Two studies, both using a bifactor
"p-factor" model of general psychopathology (Caspi et al. 2014's approach) built from
depression, anxiety, externalizing, and (Study 2 only) PTSD measures.

**Study 1** (N=120, ages 7–19, community sample recruited around Harvard/University of
Washington, 62 female). Emotional awareness = 12-item Alexithymia Questionnaire for
Children (externally-oriented-thinking subscale dropped for low reliability in kids).
Age alone: only marginal (r=.19, p=.056). But a significant age×sex interaction
(B=1.53, p=.024): emotional awareness worsened with age in **females** (r=.39, p=.004)
and not in **males** (r=−.05, p=.752). Low emotional awareness correlated with the
p-factor at r=.49 (p<.001), holding controlling for age/sex/interaction (B=.04, p<.001).

**Study 2** (N=259 analyzed of 262 enrolled, ages 8–16, 118 female; recruited
specifically for variation in violence exposure — shelters, CPS-mandated programs,
high-crime-rate neighborhoods, alongside schools and clinics for comparison).
Emotional awareness = 8-item EESC Poor Emotional Awareness subscale — **a different
instrument than Study 1**, so treat the two studies as a conceptual replication, not a
literal one. Violence-exposed youth had meaningfully worse emotional awareness than
non-exposed (d=.59, p<.001), robust controlling for income and race (B=4.51, p<.001).
Same age×sex pattern as Study 1 replicated (B=.963, p=.009): worsens with age in
females (r=.35, p<.001), flat in males (r=.01, p=.878). EA–p-factor concurrent
correlation r=.52 (p<.001).

**The longitudinal piece (~22-month follow-up, 76.4% retention, 198 of 259):** low
emotional awareness at baseline predicted the **p-factor at follow-up**, controlling
for baseline p-factor itself and the full covariate set (B=.019, p=.011) — i.e. it
predicts *change*, not just co-occurring symptoms. Two mediation results, both with
bootstrapped 95% CIs excluding zero: (1) violence exposure → lower emotional awareness
→ higher p-factor at follow-up, indirect effect .07 [.01, .15], true for the whole
sample; (2) age → lower emotional awareness → higher p-factor at follow-up, indirect
effect .02 [.002, .04], **but only when the age-path is allowed to differ by sex** — the
moderated-mediation model fit significantly better than the plain mediation model
(χ²=123.37, p<.001), and the effect is specific to females.

**What this adds that nothing else in the ledger covers:** every other source above
treats one outcome at a time (depression, self-harm, differentiation) or is
cross-sectional. This is (a) longitudinal, with awareness measured before the rise in
symptoms it predicts, (b) transdiagnostic by design — general psychopathology, not one
disorder — and (c) the only source in the ledger tying low emotional awareness to
**trauma/violence exposure** specifically.

**Caveats, now checked against the actual method, not just the abstract:**
- **Entirely self-report**, both the emotional-awareness measure and (mostly) the
  psychopathology measures. The authors flag this themselves and call for
  behavioral/ecological (EMA-style) measures of emotional awareness as a needed check.
- **Study 1 is cross-sectional** — the authors explicitly say the design "leaves the
  direction of this relationship unclear: low emotional awareness could also be a
  shared consequence of many forms of psychopathology symptoms." Only Study 2's
  follow-up wave supports a predictive/mediating claim.
- **Violence-exposed and non-exposed groups differed on income and race**, not just
  violence history — controlled statistically, but the authors say confounding "cannot
  be entirely ruled out."
- **The bifactor/p-factor model itself is contested** — the authors cite a 2019 paper
  showing its fit indices are biased in its own favor relative to other model types.
  They also had to bin continuous symptom scores into deciles to get the model to
  converge at these sample sizes (120 and 259).
- **"Transdiagnostic mechanism" is the authors' interpretation of a mediation model in
  observational data**, not an experimentally demonstrated mechanism — treat the
  causal-sounding language as their reading, not settled fact.
- The sex-specific age effect is real and consistent across both studies, but the paper
  itself flags it as an open question *why* — one candidate they raise (girls'
  friendships depend more on emotion-identification skill, per Rowsell et al. 2014) is
  speculative, not tested here.

**How this connects to what's already here:** read alongside Nook et al. 2018 (this
ledger, above) — overlapping author team (Nook is a co-author on this paper too),
complementary claims. Nook 2018 shows *differentiation* dipping to its low point around
age 15.7 in both sexes; Weissman 2020 shows that low *emotional awareness* (a related
but not identical measure) predicts *rising psychopathology* over the same
developmental window, but **only in females** — a sex split Nook's differentiation
curve doesn't report. Different constructs, worth keeping distinct.

**Leads surfaced from this paper's own reference list, relevant to open ledger gaps:**
- **Alexithymia and anxiety specifically** — resolved below, see "Low emotional
  awareness and anxiety." Hendryx, Haviland & Shaw, 1991 (below) turned out to be weak;
  Weissman 2020's own data (above) turned out to be the better source.
- **Alexithymia and addiction/substance use** (open task): Rybakowski, Ziółkowski,
  Zasadzka & Brzeziński, 1988, alexithymia prevalence in male alcohol-dependent
  patients (*Drug and Alcohol Dependence*); Taylor, Parker & Bagby, 1990, alexithymia in
  men with psychoactive substance dependence (*American Journal of Psychiatry*) —
  neither yet obtained, both directly on-topic and more clinical than Kashdan's EMA
  drinking study.
- **Facial-expression/empathy reading** (open task): Grynberg, Chang, Corneille,
  Maurage, Vermeulen, Berthoz & Luminet, 2012, "Alexithymia and the Processing of
  Emotional Facial Expressions (EFEs): Systematic Review," *PLoS ONE* — a systematic
  review, likely the single best source to chase for that gap; also Collin, Bindra,
  Raju, Gillberg & Minnis, 2013, "Facial emotion recognition in child psychiatry: A
  systematic review," and Nook, Lindquist & Zaki, 2015 (already partially in this
  ledger's orbit via the Nook name, but this specific paper — concepts shaping facial
  emotion recognition — not yet checked).

## Low emotional awareness and anxiety

Prompted by the pasted search-result claim that low emotional awareness/alexithymia
correlates with "severe anxiety" — checking whether that holds up as its own claim,
distinct from depression and from the GAD-is-an-exception finding already in this
ledger for *differentiation* (Thompson et al. 2021, citing Decker et al. 2008).

**The best-verified source turned out to be one already in this ledger.** Weissman et
al. 2020 (full entry above) measured anxiety directly with the SCARED (a validated
child/adolescent anxiety measure spanning panic/somatic, generalized anxiety, separation
anxiety, social phobia, and school phobia) in Study 1's community sample. Their own
**Table 1** (N=102 with valid data on both measures) reports low emotional awareness
correlated with anxiety at **r=.62** — the single strongest zero-order correlation
anywhere in their whole intercorrelation table, stronger even than emotional
awareness's correlation with depression (r=.51) in the same table. This is a real,
primary-verified, non-alexithymia-specific-instrument number that directly answers the
claim.

**Correction, once full text was obtained (Darryl supplied the PDF): this entry was
wrong to dismiss it.** Hendryx, Haviland & Shaw, 1991, "Dimensions of Alexithymia and
Their Relationships to Anxiety and Depression," *Journal of Personality Assessment*
56(2):227–237, PMID 2056418 (full text read) — N=110 freshman medical students (40
women, 70 men), tested a week before final exams. TAS factored into four dimensions
(Identify Feelings, Daydreaming, External Thinking, Communicate Feelings); only the two
"feelings" factors related to mood at all — Daydreaming and External Thinking were
unrelated to both depression and anxiety, a sixth independent replication of the
DIF/DDF-drives-it-EOT-doesn't pattern found everywhere else in this ledger. **The real
finding, from two nested structural-equation models:** in the depression-only model,
depression → Identify Feelings (β=.515, p<.01) and depression → Communicate Feelings
(β=.394, p<.01), good fit (χ²=82.89, df=78, p=.331). Adding anxiety changed the
picture substantially: anxiety → Identify Feelings (β=.459, p<.01) **exceeded**
depression's own direct effect on the same factor (β=.244, p<.01) once anxiety was in
the model, and the depression→Communicate-Feelings path **disappeared entirely**,
replaced by a direct anxiety→Communicate-Feelings path (β=.409, p<.01) — anxiety
essentially absorbed depression's apparent effect on the ability to communicate
feelings. Good model fit (χ²=132.41, df=119, p=.189). **The authors' own conclusion:
anxiety is a stronger predictor of the feelings-related alexithymia dimensions than
depression is** — not just correlated with it, but doing more of the modeled work.
**Caveats that still apply:** N=110 is below the 200 the authors themselves cite as the
threshold for confident factor-analytic conclusions (Comrey, 1988); nonclinical,
narrow, high-stress population (medical students pre-finals), not "classical
psychosomatic" patients; single self-report measures throughout; correlational — the
authors explicitly flag causal inference from this data as unresolved. Their own
interpretation is that this looks like **state alexithymia** — a transient response to
generalized anxiety/stress rather than the trait-level construct — which extends the
trait-vs-state tension already flagged under the Liu et al. 2025 depression entry and
Erbas et al. 2018 above.

**Upgraded to full text, 2026-08-10 (Darryl supplied the PDF) — this is now the
strongest source in the cluster.** **Yeung, Kiropoulos, Nguyen, Liu, Widjaja, Dang,
Fuller-Tyszkiewicz & Krug, 2026**, "Is Alexithymia a Transdiagnostic Factor Across
Depressive, Anxiety, and Eating Disorders in Adults? A Meta-Analytic Review," *Clinical
Psychology: Science and Practice*, 33(2), 123–145, DOI 10.1037/cps0000288 (full text
read). PRISMA-registered (PROSPERO CRD42021279900), 69 studies, adults only (18+),
**every clinical diagnosis confirmed via a standardized tool (SCID or equivalent)** —
studies without one were excluded, a stricter bar than most sources already in this
ledger.

**Anxiety-disorder group vs. controls (Table 2, k=14):** TAS-total SMD=0.97 [0.64,
1.30], p<.0001 — a **large** effect, bigger than this ledger's other alexithymia
group-difference numbers. DIF SMD=0.96 [0.63, 1.30] — also large. DDF SMD=0.44 [0.23,
0.64] — moderate. **EOT SMD=0.07 [−0.15, 0.30], ns** — the pattern holds a seventh
independent time. High heterogeneity (I²=82.6% for TAS-total) not resolved by age or
gender as moderators.

**Symptom-severity correlations (Table 4, k=13):** TAS-total r=.39 [.30, .46], with
notably *low* heterogeneity for this cluster (I²=21.5%, vs. 80%+ almost everywhere
else in this ledger) — a more stable estimate than most. DIF r=.41, DDF r=.25, EOT
r=.03 (ns). The paper's own discussion states directly: **"the correlation between
alexithymia and symptom severity was strongest in ADs (r=.39), followed by EDs (r=.37)
then DDs (r=.32)"** — anxiety is the *strongest* of the three disorder categories in
this dataset, not merely comparable to depression.

**The one caveat that matters most for how this gets cited: "anxiety disorders" here is
overwhelmingly panic disorder.** Of the anxiety-disorder study-groups (Table 1): 12
panic disorder, 4 social anxiety, 2 generalized anxiety, 3 mixed. The authors state
this themselves as a limitation: "the investigation of alexithymia was grossly
underrepresented among ADs, where most studies investigated alexithymia in panic
disorder... understanding the relationship between [social/generalized anxiety] and
alexithymia is important" — i.e., they're flagging the same gap this ledger would
otherwise have to. Table 3's disorder-specific breakdown (≥3 studies required) could
only run for panic disorder among the anxiety group: TAS SMD=0.77 [0.41, 1.13],
DIF=0.9, DDF=0.37, EOT=0.11 (ns) — moderate, not large, once narrowed to this one
diagnosis specifically. **Do not extend this paper's "large effect" headline to
generalized or social anxiety without noting it's built almost entirely on panic
disorder data.**

**Other caveats, from the authors' own discussion and limitations sections:**
significant publication bias detected for the group-difference (SMD) analyses overall,
though Egger's test for the anxiety-disorder TAS-total comparison specifically was
only marginal (p=.06), not significant, and null for the AD subscales; almost entirely
cross-sectional (only 2–3 studies in the whole 69-study review had longitudinal data);
"our results cannot confirm... the direction of causality." The theoretical framing
they lean on — the **"stress-alexithymia hypothesis"** (Martin & Pihl, 1985): that
alexithymia amplifies psychological symptoms specifically *under stress* — is worth
knowing, since it lines up with the state-alexithymia thread already running through
Hendryx et al. 1991 and Liu et al. 2025 in this ledger.

**A fourth source, and the most rigorous of the four — not an alexithymia study at all,
but a differentiation study using a clinically diagnosed anxiety-disorder sample.**
**Kashdan & Farmer, 2014**, "Differentiating Emotions Across Contexts: Comparing Adults
With and Without Social Anxiety Disorder Using Random, Social Interaction, and Daily
Experience Sampling," *Emotion* 14(3):629–638, PMID 24512246 (full text read via PMC,
open access — PMCID PMC4191833). N=85 (43 SAD, 42 healthy controls), **SAD diagnosed
via SCID-I plus the SAD module of the Anxiety Disorders Interview Schedule** — a real
clinical diagnosis, not a self-report cutoff. 14 days of concurrent experience
sampling (random prompts, self-initiated social-interaction logs, end-of-day diary).
**Negative-emotion differentiation was worse in the SAD group** in random prompts
(d=0.63, p<.01) and social interactions specifically (d=0.60, p<.05); end-of-day was
weaker, trend-level only (d=0.40, p<.10 — the authors note retrospective reports over
longer intervals show weaker effects generally). **Positive-emotion differentiation
showed no group difference** — the same negative-only asymmetry Barrett et al. 2001
and Demiralp et al. 2012 (both above) independently found. **Held up after controlling
for emotion intensity, emotion variability, and comorbid depression/anxiety
diagnoses** (8 of the 43 SAD participants also met criteria for MDD/dysthymia, 19 had
another anxiety disorder) — so this isn't just depression or generalized distress
riding along with the SAD diagnosis. This is differentiation, this lesson's own central
construct, showing a real deficit tied to a specific, clinically diagnosed anxiety
disorder — independent confirmation of the anxiety claim from a completely different
methodological tradition than the alexithymia literature above.

**How to use it:** four independent sources now converge on the anxiety claim, across
two constructs. **Yeung et al. 2026 is now the load-bearing one for a general
alexithymia-anxiety claim** — full-text verified, PRISMA-registered, large effect
(SMD=0.97), strongest of the three disorder categories on symptom-severity correlation
(r=.39) — but cite it as **panic-disorder-dominant evidence**, not as evenly covering
"anxiety" in the everyday sense the lesson likely means (generalized worry, social
anxiety). For that broader, non-panic-disorder version of the claim, Kashdan & Farmer
2014 (clinically diagnosed *social* anxiety disorder specifically, differentiation
construct, d≈0.6) is the better fit and fills exactly the gap Yeung et al. flag in
their own limitations. Weissman et al. 2020 (r=.62, youth, general anxiety symptoms via
SCARED) and Hendryx et al. 1991 (anxiety > depression as a predictor, medical students)
round out the picture across ages and constructs. Four sources, three populations, two
constructs (alexithymia and differentiation), all pointing the same direction — this is
now one of the best-evidenced claims in the whole ledger.

## Alexithymia and substance use — replaces the Kashdan drinking study as the load-bearing source

Prompted by the pasted search-result claim that people who can't identify feelings
"often rely on addictive behaviors ... to numb or manage unlabelled internal distress."
Kashdan et al. 2010 (the EMA underage-drinking study cited secondhand in the
"Emotion differentiation and granularity" section above) has never been obtained in
primary form across multiple sessions. This search finds something better anyway.

**Honkalampi, Jokela, Lehto, Kivimäki & Virtanen, 2022**, "Association between
alexithymia and substance use: A systematic review and meta-analysis," *Scandinavian
Journal of Psychology* 63(5):427–438 (full text read via PMC — open access). 52
studies (50 cross-sectional, 2 longitudinal), **N=22,712**, PubMed and Web of Science,
2000–2019, all using the TAS-20.

**Headline: d=0.62 [0.49, 0.76]** — substance users score meaningfully higher on
alexithymia than non-users. I²=92.1% (very high). **Subscale breakdown — the same
identify/describe-drives-it-EOT-doesn't shape found independently in the depression,
self-harm, and suicide-ideation/behaviour meta-analyses above, now a fourth
replication:** DIF d=0.64, DDF d=0.44, EOT d=0.19 (all still nominally significant, but
EOT is the weakest by a wide margin every single time this subscale split gets tested).

**The moderator analyses matter more than the headline number for how this lesson
should use it:**
- **By population, the effect is large where it's most clinically relevant and weak
  exactly where Kashdan's abandoned study was looking:** clinical samples d=0.83 (very
  strong), general population d=0.51, **student samples d=0.28** (interaction
  p=.049). Kashdan et al. 2010 studied underage-drinking college students specifically
  — the population this meta-analysis finds the *weakest* alexithymia-substance link
  in. Even if that paper is ever obtained, it was looking in the wrong place for a
  strong effect.
- **By sex:** samples that were majority-male showed d=0.85 vs. d=0.44 for others
  (p=.004) — a real, large moderator, not a minor detail.
- Substance type (alcohol vs. illicit drugs): no significant difference (p=.375), but
  the authors could only test this crudely — insufficient data to break out individual
  drugs beyond alcohol.
- Age and region: neither was a significant moderator.

**Caveats the authors state themselves:** overall study quality rated "poor or fair,
mainly because of the cross-sectional design" — only 2 of 52 studies were longitudinal,
so **direction is essentially untested** at the field level; alexithymia measured by
self-report throughout; unmeasured confounding "cannot be ruled out." Egger's test
found no publication bias (B=1.07, p=.42), funnel plot symmetric — so the size of the
effect isn't an artifact of missing null studies, even though it can't establish
causation.

**How to use it:** this is now the load-bearing source for an addiction/substance-use
claim — better-powered, more current, and more honestly caveated than anything reached
via Kashdan's EMA study or the Rybakowski 1988 / Taylor 1990 single-clinical-sample
studies surfaced from Weissman's reference list (both now superseded; not worth
separately chasing). Say "substance users show meaningfully higher rates of difficulty
identifying and describing feelings, especially in clinical populations," not "people
self-medicate with addiction because they can't name their feelings" — that stronger,
causal-sounding version is not what a cross-sectional literature can support yet.

**One downstream-consequence study, supplied as a PDF, worth a short note rather than
its own section:** **Evren, Cinar, Evren, Umut, Can & Bozkurt, 2015**, "Relationship
Between Alexithymia and Aggression in a Sample of Men with Substance Dependence,"
*Bulletin of Clinical Psychopharmacology* 25(3):233–242 (full text read) — N=200 male
inpatients (100 alcohol, 100 drug-dependent), post-detoxification. DIF specifically
(not DDF, not EOT) predicted total aggression and every aggression subscale
(physical, verbal, anger, hostility) in hierarchical regression, **even after
depression and trait/state anxiety were entered first** — i.e. DIF's link to
aggression isn't just riding on top of mood. Correlational, cross-sectional, all-male
treatment-seeking sample — doesn't generalize beyond that population, and the authors
themselves discuss whether the DIF measured here is trait or the "state" alexithymia
of early detox. Useful only as a downstream-consequence data point (alexithymia →
aggression *within* a dependent population), not as evidence for the
alexithymia-causes-addiction direction — different claim, don't conflate them.

**Two further supplied PDFs reviewed and not written up separately — they corroborate
rather than extend what's above:** Evren, Can, Evren & Çakmak, 2002 (*Bulletin of
Clinical Psychopharmacology* 12(4):165–173, full text read), N=82 male alcohol
inpatients vs. 48 controls, replicates the basic elevated-alexithymia-in-alcohol-
dependence finding (56.1% vs. 25% by cutoff, OR=3.83) and additionally links
alexithymia to erectile dysfunction (OR=3.17) — likely one of the 52 studies already
pooled inside Honkalampi et al. 2022's meta-analysis given the overlapping search
window, so it doesn't add new territory, just a visible example of what's in that
pool. Boiko, 2021 (*Ukrainian journal*, N=28 men in detox), a narrow regression study
on which psychosocial-adaptation traits (emotional comfort, internality) predict
alexithymia severity *within* an already-dependent population — a different, more
specific question than this ledger's claim, small sample, not load-bearing for
anything the lesson would say.

## Reading emotions in others: facial expressions and vocal tone

Prompted by the pasted search-result claim about "empathy breakdown" from
difficulty reading facial expressions and vocal tones in others. This ledger already
has one narrow source on reading a *partner's mood* (Erbas et al. 2016, above — valence
only, r=.30, null for arousal/pattern). This is the broader claim: reading emotion
*expressions* — faces and voices — in people generally.

**Grynberg, Chang, Corneille, Maurage, Vermeulen, Berthoz & Luminet, 2012**,
"Alexithymia and the Processing of Emotional Facial Expressions (EFEs): Systematic
Review, Unanswered Questions and Further Perspectives," *PLoS ONE* 7(8):e42429 (full
text read, open access) — 24 studies, clinical and healthy populations, both behavioral
and neuroimaging. High alexithymia associated with real difficulty recognizing
emotional faces, and — a genuinely important control — in the 7 clinical studies that
checked it, **diagnostic-group differences in face-reading disappeared once alexithymia
was statistically controlled for.** That reframes the claim: it isn't "depression" or
"autism" or whatever diagnosis that predicts poor face-reading, it's the alexithymia
riding along with the diagnosis. Deficits showed up across all six basic emotions plus
neutral, worst for sadness (found in 45.5% of the studies that tested it) and anger
(36.4%), and were more pronounced for degraded or briefly-presented faces than for
long, clear looks. 17 neuroimaging studies found reduced amygdala/fusiform/insula/
superior-temporal activation during face processing, holding after controlling for
depression and anxiety.

**The authors' own limitations matter for how strongly this can be cited:**
- **"None of the studies reported effect sizes"** — a systematic review, not a
  meta-analysis, and by the authors' own admission no pooled quantitative estimate is
  possible from this literature yet. Cite this as "well-documented, direction and
  breadth established" — not with a number.
- The authors themselves say it would be "premature to conclude that alexithymia is
  associated with a deficit in processing a particular emotion" — the sadness/anger
  percentages above are descriptive counts of how many studies found *something*, not
  effect-size rankings.
- Mechanism (perceptual vs. semantic-level impairment, verbal ability as a mediator) is
  unresolved; the authors call for eye-tracking and effect-size-reporting studies as
  next steps.

**Vocal tone/prosody is a different, much thinner, and genuinely contested
literature — do not fold it into the facial-expression finding as if it were the same
claim.** No meta-analysis found. One directly relevant, frequently-cited primary study
(Swart and colleagues, on affective prosody recognition in spoken Dutch sentences) found
**no significant difference** between high- and low-alexithymia groups on the prosody
task specifically — a real null, not corroborating evidence. Other studies report
accuracy deficits across emotion categories generally. A 2024 paper directly on this
tension ("Literally or prosodically? Recognising emotional discourse in alexithymia,"
*Cognition & Emotion*) exists but is paywalled (Taylor & Francis 403) and was not
obtained. **Net honest read: the facial-expression deficit is real and reasonably
well-documented (though unquantified); the vocal-tone deficit is not established the
same way and the literature is mixed.** Don't claim both with equal confidence.

**Independent confirmation from the differentiation literature, not alexithymia.**
Grynberg et al. 2012 above is entirely an alexithymia literature — worth checking
whether this lesson's *own* central construct (differentiation) shows the same pattern
independently, since it's a different measure with different populations.
**Israelashvili, Oosterwijk, Sauter & Fischer, 2019**, "Knowing me, knowing you:
emotion differentiation in oneself is associated with recognition of others'
emotions," *Cognition & Emotion* 33(7):1461–1471, PMID 30734635 (abstract verified via
PubMed; full text paywalled — Taylor & Francis 403s, ResearchGate 403s, chased and
stopped). Two studies, N=363 and N=217. People who score higher on their own
negative-emotion differentiation are **more accurate recognizing others' facial
expressions**, replicated across both studies with different recognition-task designs
(Study 2 varied how much emotional information was available in the stimuli). No exact
effect size visible in the abstract. This is a genuine second line of evidence for the
same face-reading claim, independent of the TAS-20/alexithymia construct — the two
literatures converge.

**How to use it:** "difficulty reading emotion in others' faces" is now supported from
two independent constructs and literatures — Grynberg et al. 2012 (alexithymia,
well-documented but unquantified) and Israelashvili et al. 2019 (differentiation,
two-study replication, also unquantified in what's verified). Vocal tone remains the
weaker, contested claim either way — don't extend either literature's confidence to it.

## Somatic translation: misreading emotional arousal as physical illness

The biggest gap identified in the earlier lit-review audit, and possibly the most
relevant one to this lesson specifically. Alexithymia was coined by Sifneos in 1973
studying psychosomatic patients, and the TAS-20's DIF subscale is explicitly built to
capture *difficulty distinguishing emotions from bodily sensations* — the somatic
confusion isn't an adjacent finding, it's built into the construct this whole ledger has
been citing all week. Directly relevant to the lesson's own "locate it in the body"
practice, and to Nummenmaa et al. 2014 above (already flagged as an uncited gap for
that same practice).

**De Gucht & Heiser, 2003**, "Alexithymia and somatisation: A quantitative review of the
literature," *Journal of Psychosomatic Research* 54(5):425–434, PMID 12726898,
DOI 10.1016/S0022-3999(02)00467-1. **UPGRADED 20 Aug 2026** — Darryl supplied the
ScienceDirect landing page, whose section snippets carry the design and the headline figure.
Results tables remain paywalled. `abstract + section snippets read`

**The numbers this entry previously lacked:** **16 publications yielding 18 study samples**,
found via Medline and PsycLIT, restricted to studies using one of the three versions of the
TAS. **Mean correlation between total alexithymia and somatic symptom reporting, all samples
combined and weighted by sample size, r = 0.23** — the authors' "small to moderate." All but
two samples found a significant positive correlation. People with a somatoform condition
scored higher than healthy controls at moderate-to-large effect sizes; comparisons against
other medical and psychiatric conditions were **inconclusive**, which the authors attribute
either to confounding or to the association being non-specific.

**Two author-stated limits, and the second one constrains the lesson's wording.** Only **one
prospective study** existed, so verbatim: "the presence of only one prospective study does
not allow to draw conclusions on alexithymia as a predisposing factor for somatisation."
And: the questionnaires used **"can only check for symptoms, not whether these symptoms are
medically explained or not,"** so "it is not possible to draw conclusions on somatisation
properly defined." **Cannot support "medically unexplained symptoms" — what was measured is
symptom reporting.**
A meta-analytic review (Medline/PsycLIT search, meta-analytic technique applied to
pool results — exact study count not visible in the abstract). Findings, in the
authors' own words: **"a small to moderate relationship was found between general
alexithymia and somatic symptom reporting"**; DIF showed the strongest association;
**EOT was "virtually unrelated"** — the fifth independent replication in this ledger of
the same DIF/DDF-drives-it, EOT-doesn't pattern (after depression, self-harm, suicide
behaviour, and substance use). Comparing somatoform-diagnosed patients to healthy
controls specifically: "significantly more alexithymic, with effect sizes ranging from
moderate to large."

**The authors' own caveats matter a lot here, more than in most entries in this
ledger:**
- **The measurement can't actually distinguish "somatic misattribution" from "genuinely
  ill":** their own words — symptom questionnaires "can only check for symptoms, not
  whether these symptoms are medically explained." So this literature cannot cleanly
  separate the claim "alexithymic people misread emotional arousal as illness" from
  the much less interesting claim "alexithymic people also happen to report more
  physical symptoms," possibly for entirely separate reasons.
- **Comparisons against psychiatric/other medical controls were inconclusive** — the
  alexithymia-somatization link isn't obviously specific to somatic illness as opposed
  to illness or distress generally.
- **"Only one prospective study"** existed at time of review — direction/causality is
  essentially untested at the field level. This is a correlational claim through and
  through, and the reverse-causation risk is real and specific: being chronically ill,
  or worried about being ill, plausibly changes how a person reports and attends to
  their emotions, independent of any baseline "awareness" deficit.

**The interoception mechanism — how this might actually work, not just that it
correlates.**

**Herbert, Herbert & Pollatos, 2011**, "On the Relationship Between Interoceptive
Awareness and Alexithymia: Is Interoceptive Awareness Related to Emotional Awareness?"
*Journal of Personality* 79(5):1149–1175, PMID 21241306 (abstract verified via PubMed;
full text not obtained). N=155 healthy nonclinical adults (88 women, 67 men), using a
well-validated heartbeat-perception task as the interoceptive-accuracy measure, plus
TAS-20 and BDI-II. **Interoceptive accuracy was inversely associated with alexithymia
across the whole sample** — people worse at accurately sensing their own heartbeat
scored higher on alexithymia. One sex-specific detail: interoceptive accuracy predicted
the EOT subscale specifically only in men. Correlational, cross-sectional, small
specialized task (heartbeat counting) as the only interoception measure — doesn't by
itself prove *misattribution* to illness, just the underlying deficit in reading one's
own bodily signals accurately that would make such misattribution plausible.

**A convergent pattern worth naming explicitly, echoing the Grynberg et al. 2012 face-
reading finding above:** a separate line of work (Brewer, Happé, Cook & Bird, 2015,
cited in Weissman et al. 2020's reference list, not independently verified here) argues
that interoceptive impairment tracks *alexithymia specifically*, not autism — i.e. once
again, when a diagnosis and alexithymia co-occur, it looks like alexithymia is the
operative variable, not the diagnosis riding alongside it. Same shape of finding twice
now (facial-expression reading, interoception) — worth naming as a pattern if the lesson
ever needs to justify why it treats emotional-awareness deficits as doing real causal
work rather than just correlating with whatever else is going on.

**How to use it:** the somatic-misattribution claim is real, historically foundational
to the construct, and mechanistically plausible via interoception — but weakly
quantified (small-to-moderate correlation, per De Gucht & Heiser) and the reverse-
causation risk is more serious here than almost anywhere else in this ledger, by the
reviewing authors' own admission. State it as "people who struggle to name their
feelings often experience emotional distress as physical symptoms instead" without a
specific number, and don't claim direction.

## Chronic-tension physical symptoms: sleep, headaches, GI, blood pressure

Prompted by the pasted search-result claim that chronic, unacknowledged emotion
correlates "strongly" with high blood pressure, insomnia, GI distress, and headaches —
four different organ systems bundled into one sentence. Checked each separately,
since bundling them implied a uniformity the evidence doesn't actually have.

**Sleep/insomnia — solid.** **Alimoradi, Jafari, Potenza & Pakpour, 2022**, "Is
alexithymia associated with sleep problems? A systematic review and meta-analysis,"
*Neuroscience & Biobehavioral Reviews* 133:104513 (abstract/summary verified via
PubMed and secondary source; full text not independently read). 26 studies/24 papers,
**N=7,546**, 12 countries. Overall r=0.44 [0.31, 0.56]. **Patient populations showed a
larger effect (r=0.55) than healthy populations (r=0.30)** — consistent with the same
pattern found in the Honkalampi substance-use meta-analysis above (clinical samples
show bigger effects than general-population ones). Also reported: alexithymia
associated with increased light sleep and decreased deep sleep on objective measures in
at least some included studies, and a sex-specific finding (significant in female
patients, not male, in adolescent insomnia specifically) — flagged here as a detail
requiring the primary text to confirm, not verified beyond the secondary summary.

**Headaches/migraine — solid, and it slightly breaks the usual subscale pattern.**
**La Touche, Fernández-Pérez, and colleagues, 2021**, "Alexithymia and facial emotion
recognition in patients with craniofacial pain..." *PeerJ* 9:e12545 (full text read via
PMC, open access). 10 studies, N=1,228 craniofacial-pain patients (craniofacial pain
here = TMJ disorders [2 studies], migraine [6 studies], tension-type headache [2
studies] — broader than "headache" alone but migraine-dominated). TAS-total SMD=0.46
[0.22, 0.71] vs. controls — moderate. **Subscale split doesn't match the usual
pattern**: DIF significant and largest (SMD=0.39), but **DDF was not significant**
(SMD=0.15, ns) and EOT not significant (SMD=0.12, ns) — DDF's non-significance here is
an exception to what depression, self-harm, suicide, and substance-use all showed
above, worth flagging rather than smoothing over. Alexithymia also correlated with
anxiety (SMD=0.31) and depression (SMD=0.37) within patients — both small. High
heterogeneity throughout (I²=80–87%). All 10 studies rated "very good" on Newcastle-
Ottawa. Cross-sectional; authors state this "prevents cause-effect inference." (This
paper also independently corroborates the facial-emotion-recognition finding from the
Grynberg et al. 2012 entry above, with its own large effect SMD=−1.17, though from only
2 studies.)

**GI distress — solid on the group difference, but with a complicating twin finding.**
**Ismaiel, Foucambert, Ismaiel, Leucuta, Popa, Baban & Dumitrascu, 2024**, "Silent
Struggles Within: Alexithymia Unveiled in Irritable Bowel Syndrome," *Journal of
Neurogastroenterology and Motility* 30(4):387–396 (full text read via PMC, open
access). 7 studies (6 quantitative), N=1,513, 65% female. TAS-20 mean difference
IBS-vs-healthy-controls: **8.06 points [2.55, 13.57], p<.05** — meaningfully higher in
IBS. Very high heterogeneity (I²=95.88%, only 5 contributing studies — authors say
interpret cautiously). **The complicating finding: no significant difference in TAS-20
scores between IBS and inflammatory bowel disease** (MD=0.88 [−2.54, 4.30], ns, only 2
studies). IBD is an organic, autoimmune bowel disease, not a "functional"/psychosomatic
one — if alexithymia were specifically about *misattributing* emotional distress as GI
symptoms in the absence of real pathology, IBS should plausibly show more alexithymia
than IBD, not the same amount. It doesn't, in what little data exists. This is the same
caution the De Gucht & Heiser entry raises in general form: this literature cannot
cleanly separate "misattributing emotion as illness" from "having a chronic illness,
of almost any kind, correlates with alexithymia for other reasons." Authors explicit:
observational design, "unable to confirm or negate causality"; neuroticism, anxiety,
and depression not controlled for in most included studies.

**Blood pressure/hypertension — real but the shakiest of the four.** **Di Tella,
Benfante, Airale, Castelli & Milan, 2023**, "Alexithymia and Hypertension: Does
Personality Matter? A Systematic Review and Meta-analysis," *Current Cardiology
Reports* (full text summary verified; not independently read in full). 13 studies;
the specific prevalence comparison (hypertensive vs. non-hypertensive) drew on only
**5 studies**, N=3,498 vs 3,000. Pooled OR=3.15, but with a **wide confidence interval,
1.14–8.74** — the lower bound is barely above "no effect," which is a materially
weaker result than the tight, well-powered estimates everywhere else in this cluster
(compare Honkalampi's substance-use d=0.62 [0.49, 0.76] or Alimoradi's sleep r=0.44
[0.31, 0.56]). I²=87.5%, high heterogeneity. No publication bias detected (Egger's
p=.33), but that doesn't fix the small-study, wide-CI problem. Meta-regression found
alexithymia prevalence has been *declining* in newer studies (p<.05) — worth knowing
if this claim is used, since it suggests the effect may be partly a measurement-era
artifact. Authors state directly they cannot address whether hypertension (or its
treatment, e.g. beta-blockers) might itself change alexithymia scores, rather than the
reverse.

**How to use this whole cluster:** treat sleep and headache/migraine as the two
best-supported chronic-tension claims (solid N, moderate effect, real meta-analyses);
GI distress as real but complicated by the IBS-vs-IBD null, which argues against a
clean psychosomatic-misattribution story; and blood pressure as the weakest of the
four — real enough to mention, too fragile (wide CI, 5 studies) to lean on. **Don't say
"correlates strongly" across all four as a single claim** — the pasted search result's
framing flattens a real gradient from moderate-and-well-powered (sleep, headache) to
weak-and-fragile (blood pressure), and ignores a genuine complication (GI) that argues
against the simplest version of the misattribution story.

## Is it trainable? — the intervention evidence, and a problem for this lesson

The question the Challenge section creates and the Benefit/Practice sections have to
answer. Every large source in this ledger is cross-sectional and treats alexithymia as a
relatively stable trait, so trainability needs its own evidence rather than a quiet
borrow from the correlational literature.

**Mazza, Davis, Johnson, Larkin & Cole, 2026**, "Identifying therapies to effectively
reduce alexithymia: A systematic review and meta-analysis," *Journal of Affective
Disorders* 400:121167 (full text read, open access CC-BY, Darryl-supplied).
PRISMA-registered (PROSPERO CRD42021221765), grey literature deliberately included to
limit publication bias. 59 studies in the systematic review (4,809 participants); 53
effect sizes from 47 studies (**N=3,368**) in the meta-analysis. Adults only.

**Headline: it is trainable. g = −0.52 [−0.71, −0.34], p<.001** — a medium effect for
psychological intervention vs. control (passive, waitlist, treatment-as-usual, or active).
Substantial heterogeneity (Q=188.18, I²=72.37%).

**Two findings here are awkward for this lesson specifically, and both need to be faced
rather than buried in Evidence.**

**(1) The facet that carries almost every outcome in this ledger is the facet
interventions failed to move.** Difficulty *identifying* feelings: **g=−0.06, p=.43 —
not significant.** Difficulty describing feelings: g=−0.39, p<.001. Externally oriented
thinking: g=−0.45, p<.001. So interventions shifted describing and external-orientation,
but not identifying. DIF is the subscale that drives the depression link, the self-harm
link, the suicide link, the substance-use link, the somatization link, and the
aggression link everywhere above. **The lesson's core promise — that you can get better
at telling which feeling arrived — is the one thing this meta-analysis did not
demonstrate.** Caveats the authors themselves press hard, and they matter: this rests on
a **subset of only 16 effect sizes (N=1,215)**, heterogeneity was high (Q=77.15,
p<.001), and the TAS-20 subscales have known psychometric problems — DIF in particular
overlaps with general-distress measures (Preece et al. 2020) and has been argued to
track negative affect rather than alexithymia proper (Marchesi et al. 2014). The authors
say plainly that "firm conclusions cannot be drawn from this limited and varied pool of
effects," and they deliberately used total score as their primary outcome for exactly
this reason. **Treat it as a serious flag, not a verdict — but do not write a Benefit
section that promises improvement in identifying feelings without acknowledging it.**

**(2) Meditation-based interventions were the *weakest* category tested.** g=−0.14, CI
[−1.17, 0.797] — crosses zero, not significant (k=3, N=437). The authors call this
"unexpected." Given Lesson 1 is an attention-practice lesson and Lesson 2 presumably
builds on it, this is directly relevant: **whatever attention training does, reducing
alexithymia is not clearly one of its effects.** Two mitigations worth carrying: the
authors note this conflicts with Norman, Marzano, Coulson & Oskis 2019, a
mindfulness-specific review that found a moderate effect, and they attribute the gap to
different categorization decisions (one arts-plus-mindfulness study they filed under
arts therapy, Norman filed under mindfulness); and the meditation subgroup had only 3
effect sizes, so it is underpowered even if its combined N is respectable. Also, the
overall moderation test across intervention types was **not** significant (QM(6)=10.10,
p=.12), so "meditation is worse than CBT" is not established — only that meditation's
own confidence interval includes zero.

**What did clear zero:** integrative interventions g=−0.69 [−1.15, −0.22] (the largest,
and with minimal heterogeneity — the authors' headline recommendation), CBT and
third-wave g=−0.66 [−1.14, −0.18], arts therapies g=−0.38 [−0.67, −0.09]. Expressive
writing (−0.28), psychodynamic (−0.42) and psychoeducation (−0.46) all had CIs crossing
zero. What "integrative" meant in practice, per the authors' own inspection of those
studies: psychoeducation plus body-based exercises plus a therapeutic relationship plus
group mirroring, with awareness of internal states *and* the ability to communicate them
to others — i.e. combining several of the things this curriculum teaches separately,
rather than any single technique.

**Other things that did NOT matter:** whether alexithymia was the primary or a secondary
outcome (g=−0.52 vs −0.41, p=.41); number of sessions (β=0.09, p=.51); randomization
(−0.50 randomized vs −0.62 not, ns); study quality (−0.54 high vs −0.40 moderate, ns).
The dose-insensitivity is notable against Lesson 1's frequency-over-duration material —
different question, but don't let the two get conflated.

**Publication bias was detected.** Egger's t=−2.87, **p=.006** — larger studies found
smaller effects, indicating missing small null studies. So g=−0.52 is probably an
overestimate. Other limits the authors state: only 14 of 59 studies reported
race/ethnicity and 73% of those participants were White/European/American; no included
study examined autistic participants; almost all outcomes were TAS-20 self-report, which
is a real problem when the construct being measured is *unawareness of one's own
feelings* (they cite Waller & Scheidt 2004 on this); most samples had only moderate
alexithymia, so it's unknown whether interventions work for people scoring high.

## Trait vs. state, and the clinical-to-general-reader bridge — resolved

**These two open questions both get answered by the field's own framing, and Mazza et al.
2026 states it most cleanly. Neither needs to be left hanging in the lesson.**

**On trait vs. state — it's both, and the field has a settled way of saying so.** The
resolution, in Mazza et al.'s words: alexithymia is "a relatively stable trait, meaning
that higher levels of alexithymia can be reduced through psychological intervention,
however levels of alexithymia tend to remain elevated compared with the general
population." So: real disposition, genuinely movable, rarely erased. That is fully
consistent with everything else in this ledger — Liu et al. 2025's publication-year null
and five-year EOT stability (trait), Erbas et al. 2018's day-to-day movement with stress
(state), Hendryx et al. 1991's state-dependent dimensions, and the stress-alexithymia
hypothesis both Hendryx and Yeung invoke.

The field also has a named distinction that maps directly onto this lesson's most humane
paragraph — **primary vs. secondary alexithymia** (Messina et al. 2014, cited in Mazza et
al.): *primary* is developmental, arising from early trauma, caregiver interaction and
genetic difference; *secondary* develops in response to trauma across the lifespan and is
understood as a regression in affective function. Primary is framed as a vulnerability
*for* mental ill health; secondary as a consequence *of* experience. **This is the exact
shape of the Weissman et al. 2020 finding** (violence exposure → lower emotional awareness
→ rising psychopathology) and it gives the "none of that is a character flaw, it was
learned somewhere it made sense" paragraph a formal name in the literature.

**On the clinical-to-general-reader bridge — the extension is defensible, and here is the
evidence for it.** Mazza et al. state directly that alexithymia "is not a diagnosis, but a
subclinical construct that presents over both clinical and subclinical populations," and
that "a continuum view is widely held within the literature where alexithymia ranges
between high and low levels" (citing Hogeveen & Grafman 2021; Keefer et al. 2019; Parker
et al. 2008 — the last being a taxometric investigation, i.e. a formal test of whether the
construct is categorical or dimensional, which found dimensional). Prevalence: roughly
**10% of the general population**, 30–50% in clinical samples. Twelve of their 59 studies
used nonclinical samples.
- Converging evidence already in this ledger that the relationship is the same in and out
  of clinical populations: **Seah & Coifman 2022 found the effect did not depend on
  clinical status at all** (Q=.01, p=.91) — the single best piece of evidence for the
  bridge; Honkalampi et al. 2022 found it in general population (d=0.51) and students
  (d=0.28) as well as clinical samples (d=0.83); Alimoradi et al. 2022 found it in healthy
  (r=.30) as well as patient samples (r=.55); Weissman et al. 2020 used a community
  sample throughout.
- **How to say it in the lesson:** the same pattern shows up below clinical severity, just
  smaller. That framing is supported. What is *not* supported is importing a clinical
  effect size and implying it describes an average reader — the size shrinks
  substantially outside clinical samples (0.83 → 0.51 → 0.28 across Honkalampi's three
  population types), so name the direction, not the magnitude.

## Beyond therapy — does training work outside a clinical setting?

Darryl's challenge: the "Is it trainable?" section above answers only for psychotherapy
(Mazza et al. 2026). He asked for the full range of things shown to build this skill —
"whatever is shown to work" — and an honest read on what it works for and how well,
specifically rejecting two possible conclusions in advance: that people who lack this
skill can never gain it, and that gaining it doesn't change outcomes. Five sources, none
of them therapy, each verified against its own full text.

**Classroom curriculum — real effect, but on the classroom, not directly on the child.**
**Hagelskamp, Brackett, Rivers & Salovey, 2013**, *American Journal of Community
Psychology* 51:530–543 (full text read, open access). Two-year cluster-randomized trial,
62 urban schools, 144 fifth/sixth-grade classrooms, comparing RULER (a curriculum built
entirely around teaching an emotion vocabulary — the "Feeling Words Curriculum") against
standard instruction. Blind-rated classroom quality rose in RULER schools: emotional support g=0.48, p=.043;
instructional support g=0.71, p=.005; classroom organization g=0.56, p=.026 — moderate to
large by convention — and the gain in instructional quality ran **through** the earlier
gain in emotional climate (84% of the effect on instructional support, 81% of the effect
on organization, was mediated by Year-1 emotional-support gains, both indirect-effect CIs
excluding zero). **What this study does not show:** it measured the classroom's emotional climate by
independent observation, not each student's own emotion vocabulary or differentiation.
The authors say so directly in their limitations: "further analysis must examine RULER's
impacts on students' (and teachers') emotional literacy skills" — that direct test is
future work, not this paper. Use this for "a structured emotion-vocabulary curriculum
changes something real and observable," not for "children's own differentiation improved
by X amount."

**Brief, self-directed concept learning — small, but a direct hit on differentiation
itself.** **Vedernikova, Kuppens & Erbas, 2021**, "From Knowledge to Differentiation,"
*Frontiers in Psychology* 12:703757 (full text read, open access, PMC8662934). N=120
adults split 60/60. Five days of online, unsupervised learning: text definitions,
situational examples and images for 12 emotions, with a comparison exercise on day 5.
Negative emotion differentiation rose in the experimental group and not the control,
η²p=0.174 (medium), p<.001, and the gain was still there a month later (p=.015) with no
further training in between. Downstream effects on distress or wellbeing were, in the
authors' own words, "very inconsistent" — trending the right direction but not clearly
established in this sample. **Read this as: differentiation itself is directly teachable
in days, without a therapist, and the gain outlasts the teaching. Whether that specific
gain moves mental health was not demonstrated here either way** — underpowered to show
it, not shown to be absent.

**Mindfulness, tested directly on differentiation rather than on alexithymia.**
**Guendelman, Lutz, Koenig, Bayer & Dziobek, 2025**, *[title on emotion differentiation
and heart-rate variability]*, full text read, open access (PMC12263662). N=68 healthy
adults with no meditation history, randomized to 8-week MBSR or a reading-and-discussion
control. This matters against Mazza et al.'s finding above that meditation was the
*weakest* category for reducing alexithymia (g=−0.14, ns) — Guendelman measured a
different thing, differentiation via momentary self-report (mDES), not the TAS-20. Result:
negative emotion differentiation rose significantly more under MBSR, χ²=4.21, p=.04,
medium effect; positive differentiation did not move (ns). But change in differentiation
did **not** correlate with change in depression, stress, wellbeing, mindfulness, or
self-compassion (all ns, r's from −.13 to .29) — the authors attribute this partly to being
underpowered for that specific test at N=68. **So: mindfulness moved the skill itself in 8
weeks. It did not, in this trial, show that the moved skill changed how people felt.**
That is a real, stated gap, not a hidden one — say both halves.

**A trained gain generalizing to real downstream behavior, outside the lab's own outcome
measure.** **Cameron, Payne & Doris, 2013**, "Morality in High Definition," *Journal of
Experimental Social Psychology* 49:719–725. Two experiments: one measured people's
existing emotion differentiation, one trained/manipulated it directly. In both, people who
differentiated finely (naturally or after training) discounted an irrelevant disgust cue
when making an unrelated moral judgment; people who didn't, let the incidental disgust
bias the judgment. **Verification note:** the exact effect sizes and p-values for
Experiment 2 (the trained-manipulation one, which is the one that answers "if you train
it, does the behavior change") could not be obtained — ScienceDirect, Academia.edu (403),
ResearchGate and the UNC dissertation repository (bot-blocked) were all dead ends, per
this ledger's standing rule against routing around paywalls. The qualitative finding
above is independently confirmed across the paper's own abstract and two independent
secondary summaries, so it's usable, but don't state a specific number for this one. If
you can get the PDF into downloads, I can pull the exact stats.

**Free, self-directed practice, pooled across the largest sample of anyone above.**
**Frattaroli, 2006**, "Experimental Disclosure and Its Moderators," *Psychological
Bulletin* 132:823–865 (full text read). Meta-analysis of 146 studies, N=10,994 — this is
expressive writing: sitting alone and writing about an emotionally significant experience,
no instructor, no curriculum, most protocols under an hour total. **Overall effect: r=.075
[.052,.098], p=3×10⁻⁹** — small, but the confidence interval clears zero by a wide margin
at this sample size. Broken out: subjective sense of benefit was largest (r=.159);
reported illness behavior/doctor visits r=.072; psychological health r=.056 (general
distress carried most of that, r=.102); physiological measures r=.060 (immune markers
r=.099); work/school/relationship functioning r=.046; **health behaviors themselves did
not move, r=.007, ns** — disclosure changes how people feel and function, not whether they
exercise or see a doctor. Under the best-studied conditions (three-plus sessions, private,
paid, directed prompts) the effect roughly doubles toward r≈.20 — still well under formal
psychotherapy's r=.322, but achieved with nothing but a notebook. **The one finding that
answers Darryl's question most directly: alexithymia did not significantly moderate the
effect.** People who came in worse at identifying and describing their own feelings
benefited from expressive writing about as much as people who didn't — the practice was
not gated by the starting skill.

**A correction to how the age-curve finding gets used above.** Nook et al. 2018 and
Carstensen et al. 2000 are cross-sectional: older people differentiate more finely than
younger people, on average, at one point in time. Neither study tests why. **"No
intervention at all" overstates what this shows** — it means no *researcher-administered*
program, not that nothing was learned. It's also in tension with this lesson's own claim
that formal teaching stops around second grade and whatever people carry afterward they
"mostly picked up by accident" — accident isn't absence of input, it's uneven, informal
input: more hard situations lived through, more or less reward for naming things
depending on who was around. That is a plausible reading of why the population average
rises with age, but it is a reading, not something either study measured directly, and it
implies real variance between individuals rather than a guarantee that time alone does
this for everyone.

**Downstream outcomes from trained differentiation — checked directly rather than assumed
absent.** The two studies above that moved differentiation without showing a mental-health
correlation (Vedernikova, Guendelman) are not the whole literature, and it would be wrong
to generalize from them to "training the skill hasn't been shown to change outcomes."
Two further sources close that gap, one cleanly and one conditionally:

- **Kircanski, Lieberman & Craske, 2012**, "Feelings Into Words," *Psychological Science*
  23:1086–1091 (full text read, open access, PMC4721564). RCT, N=88 spider-fearful adults,
  four conditions (affect labeling, reappraisal, distraction, exposure alone) during a
  brief live-spider exposure. At 1-week follow-up, the affect-labeling group showed a
  significantly larger drop in physiological fear response (skin conductance) than every
  other condition (d=0.64–0.85, p's .005–.044) and marginally more approach behavior than
  distraction (p=.054) — more steps toward touching the spider. This is differentiation-
  adjacent training (putting a specific word on the fear in the moment) changing a real,
  physiological and behavioral outcome, not just a self-report measure of the skill itself.
  Limitation the authors state: affect labeling didn't reduce *reported* fear more than
  the other conditions, only the physiological/behavioral measures; experimenters were not
  blind to condition.
- **Matt, Seah & Coifman, 2024**, "Effects of a brief online emotion word learning task on
  negative emotion differentiation, emotional self-efficacy, and prospective distress,"
  *PLOS ONE* (full text read, open access, PMC10901351). N=118, a design close to
  Vedernikova's. Overall, the intervention did not significantly beat the neutral control
  on differentiation (p=.174) or on distress at 1-week or 2-month follow-up — a real null,
  stated plainly. But among participants who engaged more with the task, post-task
  differentiation significantly predicted lower distress a week later (b=−.10, 95% CI
  [−.22,−.01]). **Read this as: the causal chain from training to differentiation to less
  distress does show up, conditional on the training actually landing** — a brief,
  low-engagement task that doesn't move the skill also doesn't move the outcome, which is
  a dose-response finding, not a failure of the idea.

**What this section is for in the lesson.** The developmental data show the skill rising
with age on average, most plausibly through accumulated, informal, unevenly-distributed
experience rather than through nothing at all. Mazza et al. 2026 shows formal
psychotherapy moves it, medium effect, though not on every facet. The five non-therapy
sources above show the same is true outside a clinic, at every scale from a school
curriculum to a five-day online task to a single afternoon of labeling a feeling out loud
during exposure to a spider — and two of those show the trained gain reaching a real
outcome beyond the training itself (a spider-fearful person's physiological fear response
and approach behavior; a college student's distress two months out, conditional on the
training actually engaging them). **Nothing found in this pass supports the idea that
people who don't currently show this skill can't gain it, or that gaining it doesn't
change anything downstream.**

---

# Lesson 2, practice-side landscape pass — 2026-08-13

Darryl's framing, and it reorganizes the whole lesson: **a practice cannot be called
effective without naming the outcome it moved.** The prior passes ranked practices without
that, and produced a flat contradiction — labeling aloud was simultaneously the strongest
result in the ledger (Kircanski) and a failure (Kircanski). Both true, on different
outcomes. Every entry below is filed as *practice × outcome*, and outcomes that did **not**
move are recorded deliberately, because the nulls are what stop the lesson overpromising.

Outcome columns agreed for this lesson: the skill itself · present-moment subjective
distress · present-moment physiology · behaviour in the moment · downstream low mood,
depression, anxiety and stress · social and interpersonal outcomes · interaction with other
regulation strategies. Practices in scope: affect labeling aloud · vocabulary/concept
learning · expressive writing · body mapping · mood tracking · emotion-and-sensation-centred
mindfulness · emotional communication · structured therapy.

**Scope note on this pass:** this is a landscape sweep of reviews and meta-analyses, run to
find where the evidence is before committing drafting effort. Several key sources are
paywalled and are tagged accordingly — they are **not** cleared for writing specifics from.

## The moderator that resolves the labeling contradiction

**Torre & Lieberman, 2018**, "Putting Feelings Into Words: Affect Labeling as Implicit
Emotion Regulation," *Emotion Review* 10(2):116–124 — **SAGE full text reached through a
fetch-and-summarize pass, not read directly as a PDF.** Safe for the structure of the
argument; **re-check any figure against the PDF before it goes in prose.**

The field's framing review. Two things in it matter more than anything else found in this
pass.

**(1) Provided labels and self-generated labels behave differently, and that difference
maps onto the contradiction in this ledger.** Their reading of the literature: studies
that *supply* a label produce **immediate** effects; studies where the person *generates*
their own label produce **delayed** effects and can produce a **temporary increase in
distress** first. They state the mechanism behind this difference "remains unknown and, as
of yet, untested."

Set against what this ledger already holds, the fit is close:
- **Burklund 2014 supplied the words** — participants chose among Sad / Anxious /
  Disgusted / Other, which the entry above already flags as recognition rather than
  generation. Immediate self-report reduction (p=.001). *Provided → immediate.*
- **Kircanski 2012 and Niles 2015 had people generate their own** — no immediate
  self-report benefit in either, but skin conductance down a week later in a new room
  (Kircanski) and faster autonomic recovery (Niles). *Self-generated → delayed.*

**Primary text read 13 Aug 2026 — Torre, J. (2016), UCLA dissertation, "How Putting Feelings
into Words Reduces Our Emotional Experiences" (the *Emotion Review* paper is its background
chapter). The mapping above is the authors' claim, not my inference.** Torre states it
directly: the studies showing delayed effects "in most cases (cf. Tabibnia et al., 2008)…
required participants to **generate affect labels themselves rather than have them be
provided**," and "the only cases where affect labeling significantly **increased** self-reported
affect or autonomic arousal during the initial exposure also adopted a paradigm that required
participants to self-generate and verbalize" (Mendolia & Kleck 1993; Ortner 2015). Tabibnia
2008 is the exception he flags himself.

**And it is no longer untested.** Study 3 of the dissertation ran it: **N=20 fMRI**, One Label /
Two Labels / Free Response / Observe on aversive IAPS images. Provided labels deactivated the
right amygdala where self-generation did not — **laterobasal t=2.930 p=.004, whole-amygdala AAL
t=2.497 p=.011, centromedial t=2.150 p=.023.** Free Response vs Observe moved only the left
superficial amygdala (p=.008). All three raised vlPFC — the control machinery engaged for
self-generation and failed to bring the amygdala down.

**Two limits that matter more than the p-values.** The "Free Response" condition was
**constrained to five words** (angry/scared/sad/disgusted/happy) chosen mentally in advance, so
it tests retrieval-from-a-small-set, not open generation — Torre says so. And **the delayed
benefit was never measured**; outcomes are immediate amygdala activity only. **The trade-off
that the whole distinction turns on has still not been tested in a single study with a
follow-up.** See [[P4b]].

**Additional result from the same dissertation, Study 1 — see [[P4d]]:** abstraction and
intensity were varied independently (abstract words pre-rated mid-scale between low and high on
a 57-person MTurk sample, so the two are not confounded). **Basic words beat fine-grained ones**
— Specific > Abstract produced *more* amygdala activity (left laterobasal t=2.590 p=.009, left
AAL t=1.910 p=.036) — **while intensity did nothing** in the predicted direction. This is the
only experimental granularity result in the project and it favours coarser vocabulary.

**What this opens is a design decision, not a finding about a lesson that exists.** Nothing
has been drafted for The Practice yet. If the moderator is real, then supplying a
vocabulary to choose from and asking someone to generate a name from scratch are two
different practices with different time courses — the first buying immediate relief, the
second buying a delayed physiological effect at the cost of a possible worse-before-better
opening. A lesson could teach either, or both in sequence, and the promise it makes in
What to Expect has to match whichever it teaches.

Worth noting the raw material currently pulls both ways: the notes file's practice line is
"name it, locate it, rate it 1–10" (generation), while the Panksepp seven-system material
moved into those notes is a supplied vocabulary (recognition). That tension is unresolved
and is now a known fork rather than an oversight.

**(2) People mispredict this practice, specifically and directionally.** Participants
correctly predicted reappraisal would make them feel better, and **incorrectly predicted
affect labeling would make them feel worse** — and kept predicting it after experiencing
the reduction. This is the authors' basis for calling labeling *implicit* regulation. It
is also the best available answer to "why doesn't everyone already do this," and it is a
finding about the reader rather than about a clinical population.

**Where Torre & Lieberman are softer than this ledger has been:** they read the
self-report literature as generally showing reductions, with exceptions. This ledger's
own reading — mixed, splitting by paradigm — came from the primary studies and should
stand. Their review is the field's advocacy piece for the construct; note the direction
of its lean.

## Practice → outcome, what this pass established

**Emotion-and-sensation-centred mindfulness → body awareness. Small-to-medium, and the
cleanest methods of anything in this pass.** Meta-analysis of mindfulness meditation
training on self-reported interoception, *Scientific Reports* 2025 (PMC12592345; **full
text fetched and summarized, not directly read**). 29 RCTs, N=2,191 (77.8% female, mean
age 32.8). **g=0.31 [0.21, 0.42]**, low-to-moderate heterogeneity, **no publication bias
detected** (Egger p=0.41) — which almost nothing else in this lesson's evidence base can
say. Mindfulness-based programs g=0.41 beat body-based interventions g=0.19 (p=.048).
Psychological distress moved g=0.28 across 24 studies.
- **Nothing moderated it:** not practice dosage, session attendance, intervention
  duration, clinical status, study quality, control type, or preregistration. The
  dose-insensitivity echoes Mazza 2026's null on session count. Two independent
  meta-analyses now find that how much you do it doesn't predict how much it moves.
- **Gap:** no child or adolescent studies exist — which is the population where this
  ledger's self-harm and differentiation-trough findings are strongest.
- **Reconciles with Mazza's meditation null.** Meditation did not move TAS-20 alexithymia
  (g=−0.14, ns); it does move self-reported interoception (0.31) and differentiation
  (Guendelman). Three measures, three answers. Consistent with the ledger's standing
  warning that TAS-20 subscales and momentary measures are not the same instrument.

**Expressive writing → downstream depression, anxiety, stress. Real, small, delayed, and
it can make things worse first.** Guo, 2023, *British Journal of Clinical Psychology*
62:272–297 — **`secondary source`, paywalled (402), known only through search summaries.
Do not write specifics from this entry.** 31 experimental studies, N=4,012, restricted to
RCTs with long-term follow-up. **g=−0.12 [−0.21, −0.04]** — smaller than Frattaroli's
pooled r=.075 converts to, and on a harder subset. The effect **emerged at follow-up
rather than post-test**, and short intervals between sessions (1–3 days) beat medium or
long ones (Gdiff=−0.18, p=.01). Secondary summaries also report **short-term effects that
are non-significant or negative** — increased distress, negative mood and physical
symptoms, decreased positive mood immediately after writing.
- **This is the same delayed/worse-before-better shape as self-generated affect
  labeling**, arrived at independently, in a different practice, at N=4,012. Two
  independent literatures pointing at the same arc is the strongest structural finding of
  this pass, and it is the one that should shape What to Expect.
- **Needs the PDF.** Frattaroli 2006 (already `full text read`) and Guo 2023 disagree in
  emphasis and must be reconciled before either is written from.

**Emotional communication → social outcomes. The axis exists, it is quantified, and this
pass could not verify it.** Three sources, all paywalled, all `secondary source` — flagged
here so the gap is visible rather than forgotten:
- **Chervonsky & Hunt, 2017**, "Suppression and Expression of Emotion in Social and
  Interpersonal Outcomes: A Meta-Analysis," *Emotion* (PubMed 28080085). 43 papers, 105
  effect sizes. Suppression → poorer social wellbeing (worse first impressions, lower
  social support, lower social satisfaction, poorer romantic relationship quality).
  Expression of **positive and general/nonspecific** emotion → better social outcomes.
  Expression of **anger** → worse. Expression of negative emotion generally → worse, but
  "very small and mixed." **This last split is the one that matters for the lesson** —
  it cuts against any simple "name it and say it" instruction, and it is exactly the
  distinction the lesson would get wrong by default.
- **Emotional intelligence ↔ romantic relationship satisfaction**, *Personality and
  Individual Differences* 2022 meta-analysis: **r=.373** across 90 effect sizes from 78
  samples. Larger than any single relationship finding already in this ledger
  (Humphreys β=−0.52 is a different metric; Besharat r=−.45 to −.49 is comparable and
  smaller). Construct is EI, not differentiation or alexithymia — a third construct,
  and the bridging problem gets worse with each one added.
- **Alexithymia → interpersonal problems**: converging reports that the reliable
  associations are with **cold/distant** and **nonassertive** interpersonal styles
  specifically, carried by difficulty identifying and difficulty verbalizing feelings.
  Sources are primary studies (BMC Psychiatry 2023) rather than a meta-analysis; no
  pooled estimate located.

**Emotion regulation strategies on a common metric — located, not obtained.** Webb, Miles
& Sheeran, 2012, "Dealing With Feeling," *Psychological Bulletin* 138:775–808.
`secondary source`. 306 experimental comparisons. Headline: cognitive change beat
attention deployment and response modulation. **Whether affect labeling appears in the
taxonomy at all is unknown and is the question worth answering** — it would place this
lesson's core practice against reappraisal on one scale, which nothing else can do. Note
the published critique: Augustine & Hemenover, 2013, *Psychological Bulletin*, alleging
errors, omissions, inconsistent inclusion criteria and subjective effect-size selection.
Obtain both or use neither.

**Emotional intelligence training → outcomes. Numbers exist; quality looks poor.**
`secondary source` throughout. Hodzic et al. 2018 (*Journal of Occupational Health
Psychology*-adjacent, "Can emotional intelligence be trained?") reported around g=0.46. A
2025 nursing meta-analysis reports SMD=1.76 for EI itself (16 trials, N=1,155),
SMD=−1.51 for stress (4 trials), SMD=2.72 for communication skills (4 trials), and a
non-significant effect on resilience. **Effect sizes of 1.76 and 2.72 on self-report
measures from four-trial pools are not credible at face value** and the reviews themselves
cite high heterogeneity, low methodological quality, self-report reliance and absent
active controls. Recorded so a later session does not mistake the size for strength.

## Documented as not moved, or not established

Kept deliberately, per Darryl: these guide drafting even though most will not appear in
the lesson.

- **Immediate subjective relief from self-generated labeling.** Null in both real-exposure
  studies, and Torre & Lieberman independently predict a temporary *increase*.
- **Short-term outcomes from expressive writing.** Non-significant to negative.
- **Meditation → TAS-20 alexithymia.** g=−0.14, ns (Mazza 2026).
- **Dose, everywhere.** Session count null in Mazza 2026; every dosage moderator null in
  the 2025 interoception meta-analysis. No source in this ledger yet establishes that
  more practice produces more of this skill. That is a direct problem for the
  lesson-format requirement to state a dose, and it should be said plainly rather than
  filled with a number borrowed from Lesson 1.
- **Mood tracking, pooled.** No meta-analysis or pooled estimate exists. Two primary
  studies do (Widdershoven 2019, Hoemann 2021, below), so the practice is evidenced but
  not summarised. Across the notes file's three-part practice line: the vocabulary half
  is supported (Vedernikova 2021), locating in the body is descriptive only (Nummenmaa
  2014, no intervention), and rating intensity rests on those two primary studies.
- **Body mapping as an intervention.** Still zero. Nummenmaa maps where people report
  feeling things; no study trains it and measures anything. The nearest evidence is the
  interoception meta-analysis above, which is a different practice.
- **Resilience** from EI training. ns.
- **Health behaviours** from expressive writing. r=.007, ns (Frattaroli, already in
  ledger).
- **Positive-emotion differentiation.** Null wherever measured — now five independent
  sources.

## What to get next, in priority order

1. **Webb, Miles & Sheeran 2012 PDF** — the only route to placing labeling against
   reappraisal on one metric.
2. **Chervonsky & Hunt 2017 PDF** — the social-outcome axis has no verified quantified
   source without it, and its positive-vs-negative expression split is the finding most
   likely to change what The Practice tells a reader to say out loud.
3. **Guo 2023 PDF** — needed to reconcile with Frattaroli and to confirm the
   worse-before-better short-term pattern rather than relying on a search summary.
4. **Torre & Lieberman 2018 PDF** — to confirm the provided-vs-self-generated moderator
   directly, since the whole practice framing now leans on it.
5. **Emotional granularity scoping reviews, 2025** — *Journal of Psychiatric Research*
   190:277–295, and Dunning et al., *Journal of Adolescence* (adolescent depression and
   anxiety specifically). Both paywalled. Would update the Class A picture and the
   adolescent material.

---

## Granularity searched under its own name — and it deflates the whole picture

Added the same day, after Darryl asked directly whether emotional granularity had been
checked. It had been searched, but one thread was left hanging: a summary referencing
*meta-analytic* evidence on granularity that no entry in this ledger identified. Chasing
it produced the most important calibration finding in the Lesson 2 research so far, and it
cuts **against** the size this lesson has been assuming.

**O'Toole, Renna, Elkjær, Mikkelsen & Mennin, 2020**, "A Systematic Review and
Meta-Analysis of the Association Between Complexity of Emotion Experience and Behavioral
Adaptation," *Emotion Review* 12:23–38 (`abstract only` — SAGE abstract page fetched and
summarized; **the PDF is needed before any figure here goes into prose**). 27 studies,
organised as trait and state × clinical and nonclinical.

**The number: trait emotion differentiation and behavioral adaptation, r ranging .06 to
.15 — the authors' own word is "negligible to small."** Findings between undifferentiation
and well-being at trait level were primarily small or non-significant; state-level
patterns were inconclusive, and only 4 studies assessed state complexity at all. The
authors critically question the theoretical assumptions behind the complexity indicators
and behind "behavioral adaptiveness" itself.

**Why this matters more than any single entry above.** Set the two differentiation
meta-analyses side by side: O'Toole r=.06–.15, Seah & Coifman r=−.15. They agree. Now set
that against the alexithymia numbers this ledger has been leaning on: depression r=.32–.46,
sleep r=.44, suicidal ideation r=.54, anxiety SMD=0.97.

**The construct measured from behaviour gives small effects. The construct measured by
asking people to rate their own emotional awareness gives large ones.** That is the exact
pattern predicted if TAS-20 difficulty-identifying-feelings partly measures general
negative affect (Preece et al. 2020; Marchesi et al. 2014, both already cited in the Mazza
entry). It does not prove the alexithymia literature is confounded — but the two
literatures are now quantitatively inconsistent in a way that has a ready explanation, and
this ledger should stop treating them as mutually corroborating. They agree on direction
and disagree on size by roughly a factor of three.

**Consequence for drafting:** the Challenge draft's cost paragraphs are built almost
entirely on the large alexithymia figures. Nothing there is misreported, but the
impression the section leaves — that this is a large effect — is not what the
behaviourally-measured literature says. This needs a decision before The Benefit is
written, not after.

**Nook, E. C., 2021**, "Emotion Differentiation and Youth Mental Health: Current
Understanding and Open Questions," *Frontiers in Psychology* 12:700298 (full text fetched
and summarized). Single-authored narrative review. Erik Nook is also a co-author on
Dunning et al. 2025, which cites this paper.

Counted **seven published studies** on youth emotion differentiation across ages 5–25, of
which roughly **4 of 10 comparisons were significant.** Dunning et al. 2025 searched to
June 2024, restricted to ages 14–25, and found 40 studies — the two counts describe
different searches with different inclusion criteria at different times, not a
disagreement. Prospective depression associations went non-significant once baseline
symptoms and mean negative affect were controlled. Positive-emotion differentiation:
null again. Three problems the authors raise that this ledger had not recorded:
- **Vocabulary size is an uncontrolled third variable.** Differentiation scores may
  partly index verbal ability. This is directly threatening to a lesson whose proposed
  practice is learning emotion words — the training could move the measure without
  moving the thing.
- **Potential circularity:** low engagement with the research task produces artificially
  low differentiation scores, and low engagement also tracks with psychopathology.
- **No study tests whether an intervention targeting differentiation in youth works.**
  One adult training result is named (Emotion Regulation Therapy improving negative
  emotion differentiation); the authors describe this line as just beginning.

**A further null, recorded because it was found while chasing the above.** Hamilton,
Lakhan & Rutter, 2025, *Journal of Emotion and Psychopathology* (landing page read;
N=109 college students, 14-day EMA): latent negative and positive affect *variability*
predicted depression, anxiety, stress and neuroticism, while **granularity was not a
significant predictor.** One small study, but it is a direct head-to-head in which
granularity lost to a simpler measure.

**Mood tracking has no pooled estimate but does have direct primary evidence** — see
Widdershoven 2019 and Hoemann 2021 in the time-and-duration pass below.

---

# Lesson 2 — what "emotional awareness" is measured with, and why it decides everything

Read this before any other Lesson 2 entry. **"Emotional awareness" is not one construct
with one evidence base.** It is at least four, measured four ways, and they do not agree
with each other. Almost every apparent contradiction elsewhere in the Lesson 2 material
turns out to be two instruments disagreeing rather than two findings disagreeing.

## The four measures

| Construct | Instrument | Type | What it asks |
|---|---|---|---|
| Alexithymia | TAS-20 | self-report | rate your own difficulty identifying and describing feelings |
| Emotional awareness | LEAS | **performance** | describe how you and another would feel in a scenario; scored on complexity |
| Emotion differentiation | ICC from EMA or picture task | **derived from behaviour** | rate several emotion words repeatedly; score is how much they covary |
| Interoception | MAIA / heartbeat tasks | **both, and they split** | see Garfinkel below |

## The two instruments that both claim this construct correlate at r = −0.12

**Maroti, Lilliengren & Bileviciute-Ljungar, 2018**, "The Relationship Between Alexithymia
and Emotional Awareness: A Meta-Analytic Review of the Correlation Between TAS-20 and
LEAS," *Frontiers in Psychology* (**UPGRADED 21 Aug 2026 — full text read**, Darryl located
the PDF). 21 studies, 28 independent samples, **N=2,857**, 57% female.

- **Pooled r = −0.122 [−0.180, −0.064]**, Z=−4.092, p<0.001. Adjusted for publication bias
  via trim-and-fill (four studies trimmed), **−0.092**. Heterogeneity moderate: Q=52.32,
  p=0.002, **I²=48.39**.
- No moderation by sample type (healthy, psychiatric, medical), age (meta-regression
  intercept=−0.063, p=0.648), or percentage female (intercept=−0.230, p=0.145).
- Authors' conclusion: the two "measure different aspects of emotional functioning" and
  "alexithymia and emotional awareness are distinct constructs." They recommend using both,
  never interchangeably.
- **CORRECTION, 21 Aug 2026.** This entry previously stated as this paper's finding: "TAS-20,
  but not LEAS, correlates with negative affect — and controlling for negative affect
  rendered TAS-20 associations non-significant while leaving LEAS unaffected." **That is not
  a result of this meta-analysis.** The paper states plainly, as one of its own limitations,
  that "distress/negative affect... was not used as a covariate" in the analysis. The
  negative-affect claim appears only in the discussion, where the authors cite *other*
  papers (Lane et al. 2015b for the TAS-20 link; Bydlowski 2005, Subic-Wrana 2005, Consoli
  2009 for LEAS being unaffected) as a possible explanation for the weak correlation. Do not
  cite this paper for that comparison.

**What this actually establishes, and no more.** Several large associations in the Lesson 2
material below — depression, sleep, suicidal ideation, anxiety — are measured with the
TAS-20 rather than the LEAS. Whether TAS-20 scores substantially track general distress
rather than a distinct construct is a real concern, but **not one this meta-analysis
tested or established** — see `claims-register.md`'s M3 entry, tagged "SUPPORTED — but not
by Maroti." The strongest single piece of evidence for it, Leising, Grande & Faber 2009
("The Toronto Alexithymia Scale (TAS-20): a measure of general psychological distress"), is
itself unread — known only via Maroti's citation of it. **Until that paper and the three
negative-affect-control studies are read directly, this stays a named, plausible concern,
not a demonstrated one.**

## The same split appears on the non-verbal side

**Garfinkel, Seth, Barrett, Suzuki & Critchley, 2015**, "Knowing your own heart:
distinguishing interoceptive accuracy from interoceptive awareness," *Biological Psychology*
104:65–74 (`secondary source` — abstract and summaries only, **not obtained**). N=80,
normative sample. Three dimensions:

- **Interoceptive accuracy** — objective performance, e.g. heartbeat detection
- **Interoceptive sensibility** — self-reported belief about your own body awareness
- **Interoceptive awareness** — metacognitive: how well your confidence tracks your accuracy

**All three were distinct and dissociable**, and accuracy was only partly predicted by the
other two. Correspondence between dimensions emerged only among the people already highest
in accuracy.

**And the objective measure largely fails to predict psychopathology.** From reviews
located but not yet obtained (`secondary source`, all need retrieval): heartbeat perception
is *not* systematically impaired in anxiety or depression; a meta-analysis of 40 studies
found no overall effect for trait anxiety, **r=0.03, N=2,130**; a recent meta-analysis found
non-significant correlations between heartbeat-counting performance and depression, anxiety
and alexithymia. Roughly **35%** of people can accurately perceive their own heartbeat at
rest at all.

Meanwhile *self-reported* interoception does relate to anxiety (systematic review and
meta-analysis located, paywalled, not obtained), and self-reported interoception moves with
mindfulness training at g=0.31.

## The LEAS literature — the closest thing to this lesson's actual subject

**Lane, R. D. & Schwartz, G. E., 1987**, "Levels of emotional awareness: a
cognitive-developmental theory and its application to psychopathology," *American Journal
of Psychiatry* 144:133–143 (`secondary source` — the 1987 original has not been obtained;
the model below is taken from the 2021 review, which is by Lane and colleagues).

**Lane and colleagues, 2021**, "Levels of Emotional Awareness: Theory and Measurement of a
Socio-Emotional Skill," *Journal of Intelligence* 9(3):42 (full text fetched and
summarized, open access, PMC8395748; **get the PDF before printing figures**). The field's
comprehensive synthesis. There are now **230 papers using the LEAS**.

### The model, and why it matters here

Emotional awareness is proposed as a cognitive skill developing through levels, patterned
on Piaget. **The bottom two levels are pre-verbal, which is exactly the part of the
question the rest of this ledger cannot address:**

| Level | What awareness consists of | Example |
|---|---|---|
| 1 | **Bodily sensations** | sleepy, dizzy, sick — physical experience, no emotion label |
| 2 | **Action tendencies** | "feel like punching a wall," "feel like crying" — valence only, good/bad |
| 3 | A single specific emotion | "angry" |
| 4 | Blends of emotion | "sad yet hopeful" |
| 5 | Blends, for self and another simultaneously | "I'd feel sad and angry; they'd feel relieved" |

The authors are explicit that these are **"modes of functional organization that can shift
in either direction at any time,"** not fixed stages, and that higher levels modulate lower
ones.

Two things in the notes file already assert this model without knowing it: *"emotions are
physical before they are verbal"* is Level 1, and *"they blend"* is Level 4. The Challenge
draft's line about people who feel it in the body with no name available is Level 1–2
functioning described from the inside.

### The measurement trade

**LEAS is a performance measure** — 20 emotion-evoking scenarios, written responses, scored
by trained raters (a digital scorer, POES, exists but is English-only).

- **Its advantage over TAS-20:** LEAS "fails to show correlations with either trait affect
  intensity or indices of negative affect." This is the direct answer to the distress
  confound above.
- **Its own confound is verbal.** Higher levels require more words by construction.
  **Word-count correlations with LEAS range from none (Lane et al. 1990) to r=0.48–0.71
  (Barchard & Picker 2018), depending on sample.** Correlations with verbal ability are
  small-to-moderate. In children, verbal skill significantly predicted LEAS-C scores.
- **The authors' defence is partly theoretical and should be labelled as such:** they argue
  controlling for word count "may remove substantive variance," since being able to give a
  fuller answer is itself part of emotional awareness, and language shapes emotional
  experience rather than merely reporting it. Their empirical support is that LEAS retains
  significant partial correlations with other emotion measures after accounting for word
  count.

**So the two flagship instruments each carry a different confound: TAS-20 with distress,
LEAS with verbal fluency.** Neither is clean, and they correlate at r=−0.12.

### What LEAS scores are associated with

Reported by the 2021 review as "small-to-moderate magnitude," and **the review gives almost
no r values for the health outcomes**, which is itself a finding about a 230-paper
literature.

- **Emotion recognition in others** — better recognition of faces, scenes and written
  descriptions (Lane et al. 1990, 1996, 2000b; Wright et al. 2017). Converges with
  Israelashvili 2019 and Grynberg 2012 elsewhere in this ledger.
- **Resting heart-rate variability** — higher LEAS, greater cardiac parasympathetic tone
  (Verkuil et al. 2016).
- **Buffering under induced sadness** — low-LEAS participants' well-being dropped during a
  sad mood induction; high-LEAS participants' ratings stayed stable regardless of mood
  (Ciarrochi et al. 2003).
- **Interpersonal** — empathy, help-seeking for emotional problems, actual social support
  received, interpersonal closeness. In **460 breast cancer patients**, higher LEAS went
  with greater satisfaction and security in relationships (Weihs et al. 2012).
- **Somatic symptom reporting** — greater *differentiation* in how symptoms are reported
  (Lane et al. 2011).
- **Emotional intelligence** — small: MSCEIT subscales r=0.20–0.35; total r=0.26 in one
  underpowered neuroimaging sample (N=26).
- **Personality** — positive with openness to experience; no reliable relation to the other
  Big Five dimensions.

### Three findings that cut against "more awareness is better"

The authors state plainly that **higher emotional awareness "is not necessarily better in
an absolute sense."**

1. **Generalized anxiety disorder** — higher emotional awareness correlated with *greater*
   anxiety (Novick-Kline et al. 2005). Note this is the second GAD anomaly in this ledger;
   Thompson 2021 records GAD as not significantly related to lower differentiation either.
2. **Marriage** — in 56 couples, higher LEAS in women predicted *lower* relationship
   quality, which reversed when partners' scores converged (Croyle & Waltz 2002). Small
   study; the convergence finding is the interesting part.
3. Greater affective priming effects (Suslow et al. 2001), and awareness of a partner's
   mixed feelings disrupting stability.

### Trainability — asserted, not quantified

The review states psychoeducation and psychotherapy "can promote this type of emotional
learning in adulthood and improve emotional awareness," citing six studies (Burger 2016;
Montag 2014; Neumann 2017; Radice-Neumann 2009; Subic-Wrana 2005; Killgore 2020).
**It reports no effect sizes and no sample sizes for any of them.** Those six are the
next thing to retrieve if the lesson wants to claim awareness is trainable on a measure
that isn't confounded with distress.

One related trial found separately: an emotional-awareness skills training RCT in **44
adults with schizophrenia** (22 intervention, 22 control) reduced TAS-20 difficulty
identifying and difficulty describing feelings and raised communication-skill scores —
**but it measured TAS-20, not LEAS**, so it inherits the distress confound.

### Two open questions the authors raise that bear directly on this lesson

- **Whether LEAS predicts clinical outcomes systematically "remains to be shown"** —
  current evidence is scattered across condition-specific studies.
- **"Few direct tests of the relationship between emotional awareness scores and these
  other measures [of emotion differentiation] have been performed to date."** The two
  literatures this ledger has been treating as one have barely been compared to each other.

And one finding worth carrying into any description of what low awareness looks like:
**seven distinct computational mechanisms can each produce a low-emotional-awareness
profile** (Smith et al. 2019b,c). "Low emotional awareness" is not one thing, which is the
formal version of the Challenge draft's paragraph about different people having different
versions of the problem.

## The pattern, stated once

**Self-report measures of emotional awareness produce moderate-to-large associations with
mental health. Performance and behaviour-derived measures produce small or null ones.** It
holds on the verbal side (TAS-20 r≈.32–.55 versus differentiation r≈.06–.15) and on the
non-verbal side (self-reported interoception versus heartbeat accuracy at r=0.03). The
most economical explanation is shared method variance with distress, and Maroti et al.
provide direct evidence for it.

Two readings remain open, and the lesson's honesty depends on which is right:
1. Self-report is inflated by distress, and the real effect of emotional awareness on
   outcomes is small.
2. Self-report captures something performance tasks miss — how a person experiences their
   own emotional life — and heartbeat-counting accuracy was never a good proxy for
   emotional awareness in the first place.

**Nothing found so far settles this.** It is the central open question of the lesson.

---

# Lesson 2, time-and-duration pass — 2026-08-13

Darryl's question: learning to name feelings presumably doesn't work quickly, so what has
been run over longer periods, and what does DBT show? Two sources he supplied were read in
full. **The answer is not the expected one, and it is the most decision-relevant finding
of the day.**

## Widdershoven and colleagues, 2019 — the study closest to what this lesson would teach

**Widdershoven, Wichers, Kuppens, Hartmann, Menne-Lothmann, Simons & Bastiaansen, 2019**,
"The Effect of Self-Monitoring Through Experience Sampling on Emotion Differentiation in
Depression," *Journal of Affective Disorders* 244:71–77 (**full text read** — author
preprint supplied by Darryl and read in full). Derived from Kramer et al. 2014's trial.

N=79 outpatients with SCID-diagnosed major depressive disorder, mean age ~48, all on
antidepressants or mood stabilizers. Randomized to ESM (n=30), ESM-with-feedback (n=25) or
control (n=24); the two ESM arms were combined (n=55) after confirming no difference
between them (F=0.00, p=.963 negative; F=0.27, p=.603 positive). Everyone did a 5-day
baseline and 5-day post assessment. **The intervention was six weeks of rating twelve
specific emotions — eight negative, four positive — ten times a day, three days a week.**
Nothing else. No teaching, no vocabulary instruction, no therapy content.

- **Negative emotion differentiation improved.** ESM group baseline M=0.17 → post M=0.37,
  t(54)=−3.17, p=.003, **d=0.43**. The control group did not move (t(23)=−0.41, p=.683,
  d=0.08). Controlling for baseline, group added 6.7% of explained variance, F(1,76)=6.14,
  **p=.015**, B=0.25 [0.05, 0.45].
- **Positive emotion differentiation: upward trend, underpowered, not significant.**
  ESM group t(54)=-1.52, **p=.136, d=0.20**, 95% CI [-0.21, 0.03]. Control t(23)=0.60,
  p=.558, d=0.12. Baseline explained 16.3% of post variance, F(1,77)=14.98, p<.001; adding
  group added 3.6%, **F(1,76)=3.40, p=.069**. The authors' own words: "some (nonsignificant)
  improvement." **State it as a trend the study lacked the power to detect, not as a null.**

**The twelve adjectives, and the practice set is not the assessment set.**
- **Assessment periods (5-day baseline and 5-day post), 12 items.** Negative (8): down,
  irritated, lonely, restless, agitated, suspicious, guilty, anxious. Positive (4): cheerful,
  satisfied, enthusiastic, relaxed. Rated 0-7.
- **The 6-week practice itself used 10 items** — verbatim: "All these adjectives except for
  'restless' and 'agitated' were also included in the 6-week ESM period." So six negative and
  four positive during the practice.

**Baseline emotion differentiation (1 - ICC, Fisher-Z; higher = more differentiated), ESM
group vs control:** Negative **0.17 (0.37)** vs 0.04 (0.27), t=2.22, p=.141. Positive
**0.12 (0.35)** vs 0.06 (0.36), t=0.47, p=.496. **Positive started slightly lower than
negative — there was no ceiling.**

**Baseline item means (ESM vs control), 0-7 scale:** lonely 2.60/2.37 - down 2.86/3.08 -
irritated 2.69/2.81 - anxious 1.97/1.89 - suspicious 2.00/2.15 - guilty 2.14/2.34 -
restless 3.37/3.55 - agitated 3.03/3.14 - relaxed 4.06/3.94 - satisfied 3.67/3.48 -
enthusiastic 2.91/2.74. No significant group differences on any item.

**Depression was measured (HDRS-17) and tested as a predictor.** Adding HDRS change to the
model explained an additional 3.3% of negative differentiation, **F(1,75)=3.05, p=.085**, and
3.5% of positive, **F(1,75)=3.44, p=.068**; group remained significant for negative in that
step. **The differentiation gain was not explained by symptom change.**
- **No dose-response.** Number of completed reports added nothing: ΔR²=.04, p=.117 for
  negative; ΔR²=.00, p=.801 for positive. Participants completed a mean of 149.76 beeps
  (SD=21.33, range 87–224).
- **The authors' own reading of that null is the useful part:** there may not have been
  enough variance to detect it, and *"possibly, thinking about specific emotions for 87
  times is already sufficient to improve emotion differentiation with only a very small
  additional effect of filling in more measurements beyond that point."* Speculation, and
  labelled as such — but it is the only quantitative anchor anywhere in this ledger for
  how much repetition this takes.
- Limits the authors state: the ESM group also had weekly researcher meetings the control
  group didn't (though neither meeting focused on specific emotions or differentiation);
  unknown whether gains generalize past the 12 emotions probed; unknown whether the gain
  persists or whether it moves depressive symptoms — they say directly that future work
  should establish *"after what period of ESM changes become apparent."*

**What this study does and does not show, stated flat.** It shows the practice moves
negative emotion differentiation in this population. **It does not show that moving
differentiation changes anything else.** The authors could not test it: verbatim, "the most
substantial improvements in depressive symptoms in the sample occurred after post
assessment," and they call for future studies to "investigate if the improvement in negative
emotion differentiation is actually accompanied by a decrease in depressive symptoms.

**Why this matters for the lesson.** It is a controlled comparison, in a clinical sample,
where the intervention *is* the practice — repeatedly naming and rating specific emotions —
and the outcome is the skill itself, measured behaviourally rather than by self-report of
one's own awareness. Nothing else in this ledger has that combination.

## Hoemann, Barrett & Quigley, 2021 — the same effect in healthy adults, with a warning

"Emotional Granularity Increases With Intensive Ambulatory Assessment: Methodological and
Individual Factors Influence How Much," *Frontiers in Psychology* 12:704125 (**full text
fetched and summarized, not directly read** — re-check figures before printing). N=50
healthy Boston adults (54% female, mean age 22.5), ~14 days of assessment spread over 3–4
weeks, mean 8.65 prompts per day, plus physiological monitoring and end-of-day diaries.

- Granularity rose over the study: **positive t(49)=3.54, p<.001, d=0.50; negative
  t(49)=2.26, p≤.03, d=0.32.**
- **The moderator cuts against the obvious reading, and it cuts on the side that matters.**
  Positive granularity rose with *more* daily prompts responded to (β=0.32). **Negative
  granularity fell with more daily prompts (β=−0.53, >99% probability)** and with longer
  event descriptions (β=−0.21).
- The authors lean toward genuine skill development over measurement artifact, and state
  their protocol is "an upper bound of study complexity" — they cannot say which element
  did the work.

## The dose finding, which is now the strongest cross-cutting result in this research

Four independent sources, different practices, different populations, all pointing the
same way:

| Source (year) | Intervention & dose range tested | Population | Comparator | Outcome measure | Dose finding |
|---|---|---|---|---|---|
| Mazza et al. **2026** | mixed psychological therapies; session count varied | adults, mostly moderate alexithymia | controlled (passive, waitlist, TAU, active) | TAS-20 total | sessions β=0.09, p=.51, ns |
| Interoception meta **2025** | mindfulness & body-based, 29 RCTs | adults, mean age 32.8, 78% female; no under-18s | controlled | MAIA and similar self-report | practice dosage, attendance, duration all ns |
| Widdershoven **2019** | ESM self-monitoring, 87–224 reports over 6 weeks | 55 adults, SCID MDD, on medication, mean age 48 | 24 no-ESM controls | negative ED (ICC from EMA) | reports p=.117, ns — but range restricted, all ≥87 |
| Hoemann **2021** | ambulatory assessment, ~8.65 prompts/day, ~14 days | 50 healthy Boston adults, mean age 22.5 | none — within-subject only | granularity (ICC) | prompts/day β=−0.53: negative granularity **fell** |
| Rozakou-Soumalia **2021** | DBT, 10–24 weeks, 1–2 sessions/week | 669 adults, mostly BED, mostly female | waitlist or active therapy | emotion regulation scales | duration not tested as a moderator |

And Guo 2023 found that what *did* matter for expressive writing was **spacing** — short
intervals of 1–3 days between sessions beat longer ones (Gdiff=−0.18, p=.01) — not amount.

**Read together: this appears to take weeks rather than sessions, and more per day is not
better and may be worse for the negative side.** That is a real, defensible, and
counterintuitive finding, and it is the opposite of the "it must take a long grind"
intuition. Six weeks at three days a week moved it in depressed adults; five days moved it
in healthy adults (Vedernikova); eight weeks of MBSR moved it (Guendelman). Nothing shows
that piling on more within a day helps.

**Caution before this becomes a dose instruction.** Three of the four are null results,
and a null is not evidence of no relationship — Widdershoven's own restricted range (87 to
224 reports, everyone above the likely threshold) is the obvious alternative explanation,
and they say so. Hoemann's negative-prompt finding is a single β from one 50-person study
and is the only *positive* evidence that more is worse. The defensible statement is that
no source in this ledger shows more practice producing more skill, not that more practice
is useless.

## DBT — two papers, both eating-disorder populations

**Read the population line before anything else here.** Every DBT result in this ledger
comes from adults being treated for an eating disorder — mostly binge eating disorder,
mostly women, in clinics. Nothing in it was measured in a general-population reader, and
one of the two papers measures no emotional-awareness outcome at all. Treat this as
evidence about a clinical treatment for a specific illness, not as evidence about learning
to name feelings.

### Rozakou-Soumalia, Dârvariu & Sjögren, 2021 — DBT and emotion *regulation*

*Journal of Personalized Medicine* 11:931, published 18 Sept 2021 (**full text read**, open
access CC-BY, Darryl-supplied). PROSPERO CRD42021223633. The 11 included studies were
published **2001–2020**. **It measures no alexithymia and no emotion differentiation
outcome** — the constructs are emotion-regulation questionnaires, which are a different
thing from knowing which feeling you are having.

- **Population:** 669 adults aged 18–65. 8 of 11 studies binge eating disorder (recurrent
  episodes of eating unusually large amounts with a sense of loss of control, without
  purging), 3 bulimia, 1 anorexia. Majority of studies exclusively female; those including
  men were still >85% women. 6 of 11 studies conducted in the USA. **No adolescents — the
  authors state that no relevant adolescent study was found.**
- **Dose:** 10 to 24 weeks, one or two sessions per week.
- **Comparator:** waitlist in 6 studies, active therapy in 5 (CBT, CBT+, behavioural
  treatment plan, active comparison group therapy, supportive group therapy).
- **Design:** 10 RCTs (one breached randomisation), 1 non-randomised controlled trial.
  Quality rated intermediate overall — 3 studies low risk of bias, 4 unclear, 3 high.
- **Note their effect-size convention is not Cohen's.** They use Kinney et al. 2020: ≤0.31
  small, 0.31–0.55 medium, >0.55 large. Do not rank their figures against Cohen-scaled
  ones elsewhere in this ledger without saying so.

**Results, by outcome:**

| Outcome | g / MD | 95% CI | p | I² |
|---|---|---|---|---|
| Primary ER (one measure per study) | −0.69 | [−1.22, −0.16] | 0.01 | **90%** |
| Overall ER (all measures, adjusted) | −0.42 | [−0.68, −0.16] | 0.001 | 53% |
| General ER | −0.70 | [−1.23, −0.18] | 0.009 | 89% |
| **Eating-specific ER** | **−0.15** | **[−0.51, 0.21]** | **0.41 — ns** | 69% |
| Depressive symptoms (adjusted) | −0.28 | [−0.46, −0.11] | 0.001 | **0%** |
| Severity of ED symptoms (adjusted) | −0.83 | [−1.33, −0.32] | 0.001 | 80% |
| Objective binge episodes | −0.27 | [−0.45, −0.09] | 0.003 | 85% |
| BMI | −1.93 | [−3.42, −0.44] | 0.01 | 32% |

**The g=−0.69 headline is the least reliable number in the paper** — one measure per
study, I²=90%, CI running from −1.22 to −0.16. The most reliable is the *smallest*:
depressive symptoms, g=−0.28, I²=0%.

**The comparator finding decides what this paper supports:** *"DBT showed improvements in
all outcomes when compared to wait list, whereas
in active therapy studies superiority of DBT transpired only in depressive symptoms."*
Waitlist-versus-active-therapy subgroup differences ran three-fold and ten-fold. So against
another real therapy, DBT did not beat the comparison on emotion regulation. The individual
studies bear this out: Telch 2001, Hoffman 2006, Safer 2010 and Lammers 2020 each found no
significant group difference on their emotion-regulation measures, and in Navarro-Haro 2020
the *control* (TAU-CBT) significantly beat DBT on the Emotional Eating Scale.

Other stated limits: publication-bias assessment was funnel plots inspected visually with
no asymmetry test, which the authors call "hypothetical"; meta-regression found no single
variable explaining heterogeneity, with a BMI-and-age model reaching R²=91% but only BMI
significant.

### Zompa, Cassioli, Rossi and colleagues, 2025 — the one that measures alexithymia

*Nutrients* 17:2003, published 14 June 2025 (**full text read**, open access CC-BY,
Darryl-supplied). Florence, Italy; enrolment Oct 2016 – July 2021.

- **Design: non-randomized, naturalistic, and there is no control group.** The mediation is
  of *time*, not of a treatment effect against a comparator — a correlation between change
  scores with no counterfactual. The authors state this and call for randomised trials.
- **Population:** 170 adults with DSM-5 binge eating disorder in an acute phase; 153 women
  and 17 men; mean age 40.2 (SD 15.4); mean BMI 32.9; mean illness duration 16.1 years;
  39.6% comorbid mood disorder, 13.6% anxiety disorder. **Dropouts were excluded from
  analysis** — these are completer figures.
- **Dose:** 16 weeks, one 1-hour group session per week. Two DBT modules only — Emotion
  Regulation (8 sessions) and Distress Tolerance (8 sessions). The Emotion Regulation module
  explicitly includes *"the identification and labelling of emotional states."*
- **Confound the authors name:** everyone was simultaneously in a multidisciplinary program
  with nutritional counselling and psychiatric consultations. DBT was not isolated.
- **Outcomes:** TAS-20, DERS, and Binge Eating Scale, at baseline and end of treatment only.

**Pre-post within-subject changes (Cohen's d, no control group):**

| Measure | Change | Cohen's d | Significance |
|---|---|---|---|
| Binge Eating Scale total | −5.39 | −0.69 | p<0.001 |
| DERS total | −11.15 | −0.41 | p<0.001 |
| DERS lack of emotional awareness | −1.23 | −0.41 | p<0.01 |
| DERS lack of emotional clarity | −1.36 | −0.26 | p<0.01 |
| DERS impulse control difficulties | −1.33 | −0.16 | **ns** |
| **TAS-20 total** | **−3.42** | **−0.30** | p<0.05 |
| **TAS-20 difficulty identifying feelings** | **−2.04** | **−0.27** | **p<0.01** |
| TAS-20 difficulty describing feelings | −0.44 | −0.13 | **ns** |
| TAS-20 externally oriented thinking | −0.87 | −0.22 | **ns** |

**This is the single most important finding for Lesson 2, because it points the opposite
way to Mazza et al. 2026 on the exact facet the lesson depends on.** Mazza (2026,
meta-analysis, 47 studies, adults, mixed interventions, controlled comparisons) found
interventions moved externally oriented thinking (g=−0.45) and difficulty describing
feelings (g=−0.39) but **not** difficulty identifying feelings (g=−0.06, ns). Zompa (2025,
single uncontrolled cohort, 170 BED patients, 16 weeks of DBT emotion-regulation and
distress-tolerance modules) found the reverse: difficulty **identifying** feelings moved
(d=−0.27, p<0.01) while describing and external orientation did not.

**Do not treat that as Zompa refuting Mazza.** They differ on four of the five coordinates:
Mazza pools controlled trials of many intervention types, Zompa is one uncontrolled cohort
of one intervention; Mazza's samples were mostly moderately alexithymic, Zompa's are
chronically ill BED patients with a mean 16 years of illness; Zompa has no comparator, so
regression to the mean, the concurrent nutritional and psychiatric care, and completer-only
analysis all remain live. **What it does establish is a testable hypothesis worth stating:
an intervention that explicitly teaches identifying and labelling emotional states moved the
identifying facet, where the pooled average of interventions that mostly don't teach it did
not.** That is the shape of a real finding and it needs a controlled trial, which does not
appear to exist.

**Mediation results**, recorded with the caveat above: indirect effect via ΔDERS −0.68
[−1.20, −0.31]; via ΔTAS −0.59 [−1.33, −0.20]; total effect −7.53, p=0.002; direct effect
−6.27, still significant, so **partial mediation only**. Path coefficients: time→ΔTAS −2.49
(SE 0.79); ΔTAS→ΔBES 0.24 (SE 0.05). **Mediator and outcome were measured at the same two
timepoints**, so temporal precedence between the change in naming and the change in
symptoms is not established even within this design.

### Still not retrieved

- Reilly, Brown, Arunagiri, Kaye & Wierenga, **2022**, "Exploring Changes in Alexithymia
  throughout Intensive Dialectical Behavior Therapy for Eating Disorders," *European Eating
  Disorder Review* 30:193–205. Cited by Zompa as ref [60].
- A 2025 randomised trial of DBT in autistic adults without intellectual disability
  (PubMed 40203811). A search summary reported that a decrease in alexithymia mediated the
  improvement in emotion dysregulation; **unverified, do not use until read.** Worth
  getting — Mazza 2026 states no intervention study in its pool included autistic
  participants.

## Papers to request next, with full titles

1. "Suppression and Expression of Emotion in Social and Interpersonal Outcomes: A
   Meta-Analysis" — Chervonsky & Hunt, 2017, *Emotion*.
2. "Dealing With Feeling: A Meta-Analysis of the Effectiveness of Strategies Derived From
   the Process Model of Emotion Regulation" — Webb, Miles & Sheeran, 2012, *Psychological
   Bulletin* 138:775–808.
3. "A Systematic Review and Meta-Analysis of the Association Between Complexity of Emotion
   Experience and Behavioral Adaptation" — O'Toole, Renna, Elkjær, Mikkelsen & Mennin,
   2020, *Emotion Review* 12:23–38.
4. "Dialectical Behaviour Therapy Improves Emotion Dysregulation Mainly in Binge Eating
   Disorder and Bulimia Nervosa: A Systematic Review and Meta-Analysis" (PMC8470932).
5. "Group Dialectical Behavior Therapy for Binge Eating Disorder: Emotion Dysregulation
   and Alexithymia as Mediators of Symptom Improvement" (PMC12195722).
6. "The delayed, durable effect of expressive writing on depression, anxiety and stress: A
   meta-analytic review of studies with long-term follow-ups" — Guo, 2023, *British Journal
   of Clinical Psychology* 62:272–297.
7. "Putting Feelings Into Words: Affect Labeling as Implicit Emotion Regulation" — Torre &
   Lieberman, 2018, *Emotion Review* 10(2):116–124.
8. "Enhancing academic performance and social and emotional competence with the RULER
   feeling words curriculum" — Brackett, Rivers, Reyes & Salovey, 2012, *Learning and
   Individual Differences* 22(2):218–224. **New priority** — cited by Dunning et al. as
   teaching emotion words for *20–30 minutes per week*, which is the only per-week dose
   figure found anywhere in this research.

## Dunning and colleagues, 2025 — read in full, and it supersedes the secondary summary above

"What Role Does Emotional Granularity Play in Adolescent Depression and Anxiety? A Scoping
Review," *Journal of Adolescence* (**full text read**, PDF supplied by Darryl). 34
manuscripts, 40 studies, **N=5,656**, ages 14–25. Funded by a Wellcome "Active
Ingredients" commission. Corrects the earlier entry, which came from a different Frontiers
review and undercounted the literature at seven studies.

- **"The literature search yielded no randomised controlled trials, cohort studies,
  intervention studies or pre-post studies."** Not one, across 40 studies. And **no study
  used a clinically depressed or anxious adolescent sample.**
- **Depression:** 10 studies, 8 significant, r=.15 to .35. **Anxiety:** only 2 studies
  directly, one significant one not; 4 more on stress, all significant. Range across
  significant anxiety-domain studies r=.10 to .54. So in adolescents the depression link is
  the better-evidenced one — **the reverse of the adult alexithymia picture**, where
  anxiety leads. Worth holding against the Challenge draft, which leads on anxiety.
- **Emotion regulation:** 23 measures across 8 studies, 15 significant, 8 not, r=.10 to
  .49. **Moderation** (does granularity change the regulation→symptom link): only 4
  studies, 3 yes and 1 no — the authors call it "sparse and inconsistent."
- **A finding that inverts the mechanism story.** Kalokerinos et al. 2019, two
  experience-sampling studies: people with *lower* granularity used cognitive reappraisal
  and social sharing **more**, not less. The authors' reading is a "scattergun" approach —
  low granularity doesn't stop you selecting strategies, it stops you selecting the right
  one. This directly contradicts the intuitive "can't name it, so can't act" framing, and
  it is a better story than the one the lesson would reach for by default.
- **And a straight contradiction in the adult data**, which the authors flag: Werner-Seidler
  et al. 2020 found depression associated with *higher* diversity of negative emotional
  experience — the reverse direction. Not resolved.
- Cross-method correlations between granularity measures: r=.10 to .45. Consistent with
  Thompson 2021's r≈.22.
- All studies from high-income countries; most university students.
- **Training:** Vedernikova 2021 is essentially the only one, plus Cameron 2013's induction
  and a schizophrenia face-recognition pilot (Silver et al. 2004). No adolescent training
  study exists.
- **Adolescents with lived experience of depression/anxiety were interviewed** (24
  contributors, 12 focus groups). Unprompted, they named keeping a diary, talking to family
  or friends, and watching how others articulate feelings. One said the diary "helped them
  better label their emotions, even if it did not make much of an active difference to
  their mood" — which is, in a sentence from a teenager, the exact split this ledger found
  across Kircanski, Niles, Guendelman and Vedernikova. Another named anger as hardest to
  catch because an argument is "not conducive to slowing down." A third, on positive
  emotions: "if I'm feeling good, I don't tend to question it that much." Usable as
  illustration if the lesson wants a voice that isn't a researcher's, and it is a published,
  citable source rather than an invented vignette.

# If-then planning, venting, and social sharing — sources for Lessons 8, 19 and 25

*(Researched during the Lesson 2 pass, 2026-08-13. Retitled after the scope audit: this material
is not about emotional awareness. Claims live in `notes/08-fear-and-anger.md`,
`notes/19-overriding.md` and `notes/25-talk-about-it.md`; sources stay here.)*

Six papers Darryl supplied, all **read in full**. This pass moved the lesson's centre of gravity:
the strongest technique in the emotion-regulation literature is if-then planning, its headline
effect size is much smaller than everyone quotes, and the specific form this curriculum needs is
the one form nobody has tested. Full analysis in `claims-register.md` at P20a-0 through P20a-3
and P4c.

## Sheeran, Listrom & Gollwitzer, 2024 — the number that replaces d = .65

**"The when and how of planning: Meta-analysis of the scope and components of implementation
intentions in 642 tests," *European Review of Social Psychology* 36(1):2334563.**
`primary text read`. Inclusion period 1994–2019.

- **Raw d = .36. Bias-corrected (RoBMA) d = .15, 95% CI [.08, .22].** Egger's b = 1.06 —
  "substantial" small-study bias by Doucouliagos & Stanley's benchmark.
- **Affect regulation subset: d = .66, k = 26, I² = 6.3%** — the least heterogeneous cell in the
  paper, and the one that concerns us.
- **Self-specified cues: d = .16.** Provided cues .31–1.17. The strongest single design finding.
- "Wait before responding" .66; "keep calm" .69; **reappraisal .36.**
- Median N: 30 treatment / 28 control. These are small studies; the funnel asymmetry follows.
- **31 child effect sizes at d = 0.43 [0.27, 0.59]** — but **no bias-corrected estimate for the
  child subset was published.** Flagged by Breitwieser & Reinelt 2026 below.
- Contradicts Webb 2012's control-condition ordering (goal intention .41 vs no instruction .30 —
  the reverse of Webb's .53 vs .91). **Do not treat the Webb comparison structure as settled.**

## Gollwitzer & Sheeran, 2006 — where d = .65 came from

**"Implementation Intentions and Goal Achievement: A Meta-Analysis of Effects and Processes,"
*Advances in Experimental Social Psychology* 38:69–119.** `primary text read`.
**Note: the downloaded file is misnamed `GollwitzerSheeran2016.pdf`. It is 2006.**

- **d = .65, 95% CI [.60, .70], k = 94, N = 8,461.** Q(93) = 173.46, p<.001.
- **Their only publication-bias check is published (.65) vs unpublished (.67), p = .22. No funnel
  plot, no Egger's test.** That comparison cannot detect a small-study effect — it compares two
  sets of small studies to each other. This is the whole methodological distance between .65 and .15.
- Reassuring: objective (.67) matched self-report (.63); experimental (.65) matched correlational (.70).
- **Read the k column.** Every d above 1.0 rests on 3–5 tests: conserving self-regulatory
  capability **1.28 on k=3, N=93**; blocking detrimental self-states 1.10 (k=5); environmental
  1.12 (k=3); prosocial 1.01 (k=5). The populated cells — laboratory k=38 (.70) and health k=23
  (.59) — are the honest estimates.
- Same for the component-process table: if-component **d = .80 on k=6, N=327**, and **four of six
  entries are single studies** (cue accessibility .95, N=40).
- **Children/young adults: k = 2, d = .47.** Superseded by Breitwieser & Reinelt below.
- **Not superseded — the failure conditions.** Plans fail when the cue rarely occurs, occurs where
  you cannot act, the response is not instrumental or performable, or either half is vague ("eat
  healthily"/"tomorrow" leaves the person "no better off than having merely formed the goal
  intention"). Requirements: **precise, viable, instrumental.** Their own caveat: how often
  everyday plans meet these is "an empirical issue" — unknown.
- **Rehearsing the cue–response link is not a formality.** Milne & Sheeran 2002c: rehearsing the
  *link* → **87%** acted; writing the same plan as a **reminder note → 40%**; control 20%.
- **Commitment is not the mechanism.** No pre/post increase in commitment or self-efficacy across
  several studies; Sheeran & Orbell 2000 raised screening attendance 33% from a ceiling of
  4.60/4.63 on 1–5 scales.
- **But the plan is inert without the goal** — effects appear only when the superordinate goal is
  active. A plan for a goal the person does not hold does nothing.
- **Anger appears twice, both hypothetical.** Appendix I: *"if I feel my anger rise, then I will
  tell myself to stay calm and not aggress back"* — an illustration of the format. Future
  directions proposes a therapist-perspective plan for "an obnoxious person" and flags it as new work.
- **The passage that matches this curriculum's architecture, flagged as untested** (p.107, via
  Mischel & Shoda): a person who "knows what kind of social situations elicit aggressive
  responses in him" can "tailor his implementation intentions to those critical situations…
  specify implementation intentions **exactly where they are needed.** Exploring interactions
  between chronic and strategic situation–behavior links constitutes a **promising direction for
  future studies.**" Whether anyone has since done it is **`UNSEARCHED`**.

## Breitwieser & Reinelt, 2026 — if-then plans in children, and the cue-type hole

**"The effectiveness of implementation intentions in children: A systematic review and
meta-analysis," *British Journal of Psychology*, DOI 10.1111/bjop.70065.** `primary text read`.
**Registered Report, open access** — hypotheses and bias analyses accepted before results existed.
The strongest-designed meta in this ledger.

- **k = 52 effect sizes, 42 studies, N = 12,957, mean age 10.67 (range 4.5–12.99), 1975–2025.
  g = 0.31, 95% CI [0.21, 0.41].** I² = 65.2%.
- **THE FINDING FOR THIS LESSON: internal cues k = 1, external cues k = 45.** Verbatim: "we
  hypothesized that implementation intentions based on external cues… would be more effective than
  those based on internal cues (e.g. 'if I feel stressed'), **which require introspection and are
  often less specific or salient.** However, **only one study used an internal cue** (Mau et al.
  2019, Study 2), thus preventing any conclusions." The field's preference for external cues is
  **theoretical convention** (Gollwitzer 1999), not a tested comparison. Then-component: internal
  k=9 vs external k=32, ns (b=−0.19, p=.257).
- **The estimate is unstable in both directions.** Drop 7 outliers → **g = 0.18**, and I² collapses
  **65.2% → 9.0%**. Drop 2 influential cases → 0.22. **Drop high-risk-of-bias studies → g = 0.47
  (ITT) / 0.52 (per-protocol).** Both are true; the point estimate is not well determined.
- **Bias methods disagree, and this matters.** Egger's t(50) = 3.15, p = .003; **PET-PEESE →
  0.15** (identical to Sheeran 2024's correction, from an independent corpus). But **3PSM 0.38,
  p-curve 0.35, p-uniform-star 0.39, z-curve 0.35**, and 3PSM found no significant selective
  reporting (LRT=0.96, p=.327) — **36 of 52 effects were non-significant.** Against that, z-curve
  ODR 0.35 exceeded EDR 0.23. Their caveat: p-curve and p-uniform-star are not robust above
  I²=50%, and it is 65%. **Report the range, not 0.15 alone.**
- **Risk of bias: zero of 52 effects rated low risk** on the per-protocol question (19 some
  concerns, 33 high). ITT: 2 low, 27 some concerns, 23 high.
- **Moderators.** Mean age **−0.05 g per year, p = .022** (robust). Clinical/ADHD stronger
  (−0.38, p=.002 with influential cases removed). **More than one plan is worse (−0.24, p=.022).**
  Pre-structured planning sheet beat a bare if-then sentence (+0.32, p=.014, k=4). Gender p=.960;
  lab vs field p=.141; time to outcome p=.449.
- **No decay detected — but 35 of 52 measured within 24 hours**, and the long-follow-up studies
  used booster sessions. The authors refuse to claim durability. So do we.
- **Plan quality is the whole ballgame.** Two studies evaluating self-created plans found if-then
  plans "were only effective when the plans were of **high quality**" (Beall 2011; Schaaf et al.
  2025). Experimenter-provided beat self-created descriptively; **experimenter assistance during
  planning did nothing** (b=0.11, p=.703). Fourth independent line converging on
  **provide the structure**.
- **The meta-strategy gap, named:** "the distinction between simply *having a plan* and learning to
  use the *strategy of planning*… **a significant gap in the literature: How can children be taught
  to use implementation intentions as a flexible form of self-regulatory control?**" What it
  requires: "**monitoring one's own behaviour, identifying the best strategy for a given goal and
  context and translating that insight into a well-formed if-then plan.**" This is the EEI
  sequence, posed as an open question in 2026 — twenty years after Gollwitzer & Sheeran framed the
  same gap. Only **Schaaf et al. 2025** (*Contemporary Educational Psychology* 83:102422,
  micro-randomised trial, mobile app) and **Schunk et al. 2022** (*Nature Human Behaviour*
  6:1680–1690, classroom workbooks, N=572) have attempted it. **Both worth getting.**
- **Commitment barely measured**, and the authors flag why it bites in classrooms: "children may be
  asked to pursue goals with **limited intrinsic relevance**," unlike adult volunteers.
- **Coverage: only 2 of 42 studies targeted anything interpersonal** (Bleize 2022, cyber-aggression
  conformity; Mauduy 2023, bullying bystanders). **Emotion regulation is not a domain in this
  literature at all.** Ceiling effects are a live explanation for nulls in typically-developing
  children — Higgins & Conner had only 3 of 53 controls take up smoking.
- **Mischel & Patterson 1975/1976** ("Mr. Clown Box," ages 4.5–4.75) are included as early if-then
  work and **predate Gollwitzer by two decades**, with effects of 0.80/0.86/0.63.

## Schweiger Gallo, Keil, McCulloch, Rockstroh & Gollwitzer, 2009 — the experiment underneath

**"Strategic Automation of Emotion Regulation," *Journal of Personality and Social Psychology*
96(1):11–31.** `primary text read`. Three experiments; the one both metas lean on for emotion.

- **Manipulated: one sentence of self-talk.** Goal intention ("I will not get frightened!") vs that
  goal plus an if-then plan ("And if I see a spider, then I will ignore it!") vs no instruction.
- **Measured: SAM self-report sliders after sub-second pictures**, plus 129-sensor EEG in Study 3.
  **No behavioural measure, no follow-up, all-female samples, N = 54 / 68 / 34.**
- **Study 1 (disgust):** control 7.13, goal 6.89, **if-then 5.43** (p<.01 vs both). **Control vs
  goal t<1 — the goal alone did nothing.** Neutral and pleasant pictures unaffected: the effect was
  specific to the stimulus named in the "if."
- **Study 2 (spider fear), the striking result:** spider-fearful people with a plan rated spider
  pictures **18.33**; people with **no spider fear** rated them **18.13** — no difference (ts<1.2).
  Untreated fearful controls 22.51 (vs no-fear controls, t(30)=4.55, p<.01).
- **Study 3 (ERP):** P1 amplitude at 60–150 ms went from **+2.51 (control) to −1.07 (plan)** at
  right occipital. **The difference appears about 100 ms after the picture** — before deliberate
  control is possible (conscious inhibition shows after ~300 ms). Not eye movements; ocular
  electrodes checked.
- **Where it is weaker than the abstract suggests:** the **P1 omnibus tests were marginal** —
  parietal F(2,31)=3.17, **p=.06**; occipital F(2,31)=2.79, **p=.08**. Only right-hemisphere
  follow-ups reached p<.05, at **~11 per cell**. On right parietal, plan and goal did not differ
  (t<1.4). **The slow wave (552–752 ms) separated *both* self-regulation groups from control** —
  so goal intentions did change brain activity, just late, with no benefit on any outcome.
  Study 2 had a commitment confound (ignore-plan 7.41 vs goal 6.25, p<.05; survived covarying).
- **The misprediction appears again.** Study 1: goal-intention participants thought they had done
  **better** than if-then participants (6.61 vs 5.22, t(34)=1.91, p=.07) while doing nothing. All
  groups reported the same difficulty, help and success. **The thing that worked did not feel like
  it was working** — "commonly escape introspection."
- **It is the if-then link, not the advice. Bayer & Gollwitzer (2007)** ran the control: goal
  intention **plus information about the very strategy** performed **as poorly as the bare goal.**
- **Anger is explicitly untested.** "It should also be possible to ad hoc regulate other important
  daily emotions, such as anger" — a discussion sentence. Everything here is disgust and spider
  fear: stimulus-driven withdrawal emotions with **no action tendency toward another person.**

## Nils & Rimé, 2012 — the venting myth, and a claim I had backwards

**"Beyond the myth of venting: Social sharing modes determine the benefits of emotional
disclosure," *European Journal of Social Psychology*, DOI 10.1002/ejsp.1880.** `primary text read`.

- N=89 (53 female), mean age 20.5. **Listeners were the participants' own intimates** — 69% close
  friend, 21% partner, 10% sibling — coached into a role, blind to hypotheses (compliance 5.83/7).
  **2×2: socio-affective (empathic) vs neutral × cognitive reframing vs none.** Stimulus: a
  9-and-a-half-minute film (child prostitution testimony, livestock abuse, Nazi camp footage).
  Measured after the conversation and **again at 48 hours after re-watching.** ~22 per cell.
- **Correction to this ledger's earlier reading: empathic listening did not buffer distress. It
  raised emotional impact** — 7.01 vs 6.23, F(1,85)=4.09, p<.05. Their Hypothesis 1 predicted
  exactly that: such conditions "temporarily **enhance** rather than dampen emotional arousal."
- What empathy *did* produce, **Time 1 only**: proximity 6.46 vs 5.95 (p<.05), loneliness 30.60 vs
  35.09 (p<.05). **Both gone at 48 hours.** No effect on either worldview measure (Fs<1.0).
- **The misattribution result.** At 48 hours the empathic group rated the conversation as more
  beneficial (4.51 vs 3.96, p<.10) on three items: it *made me feel better*, *enabled a different
  perspective*, *reduced my negative feelings*. Verbatim: "**In fact, neither a change in
  perspective nor a reduction of negative feelings resulted from the socio-affective conditions.
  That participants in these conditions reported the opposite subjective impressions supports our
  speculation that the venting hypothesis originates from a misattribution.**" They got closeness
  and read it as recovery.
- **Cognitive reframing worked and held:** emotional impact **5.70 vs 7.08 at 48 hours,
  F(1,77)=7.43, p<.01**; beliefs about human nature **3.86 vs 3.41, F=8.65, p<.01**; negative
  affect 2.24 vs 2.55, p<.05. **No interaction anywhere** — the two modes are independent channels.
- **What "cognitive work" consisted of, operationally:** the listener first called the feelings
  "completely normal and legitimate," then supplied **specific factual counter-evidence** — the
  footage contributed to changed paedophilia law in Thailand, closure of the cattle markets shown,
  the Nuremberg conviction of 80 Nazis, and humans also build vaccines and MSF. **Validate, then
  inform. Not reassurance.**
- **Design limit this ledger must respect: there is no no-conversation condition.** All four cells
  held a 5–10 minute conversation; the "control" is *neutral listening*. **The claim "simply
  verbalizing an emotion exacerbated its negative effects" requires a comparison this experiment
  did not run** — it comes from Mendolia & Kleck (1993) and Lepore et al. (2000, 2004). What this
  study shows is narrower: **empathic sharing produced more self-reported upset than neutral
  sharing, and factual reframing produced less.**
- **Independent replication of the pattern: Lepore, Fernandez-Berrocal, Ragan & Ramos (2004)** —
  challenging vs validating confederate vs alone vs no-talk. **Only the challenging condition
  produced superior recovery.**
- **Their sequencing recommendation:** "soon after experiencing an emotion… people are **not open to
  changing their perspective**," so socio-affective first, cognitive later. **Their inference from
  the timing literature, not something this study tested.**
- **A quote previously attributed to this paper is not in it** — the "perpetual cycle… unchanged
  appraisal… continue to fuel sharing" phrasing. Their version: relief "is bound to be evanescent.
  It will dissolve in hours, leaving the emotional impact of the episode to resurface **together
  with a renewed need to share.**" The other wording may be Rimé 2009. **Unverified; do not quote.**
- **It cannot test the boundary hypothesis.** The stimulus is atrocities by strangers on film.
  There is no boundary available to set and no action tendency that could complete, so the design
  cannot separate "the appraisal must change" from "the boundary must be set."
- Limits: N=89, ~22/cell, Belgian, laboratory-induced; confederates were psychology students
  role-playing on their own friends and family. Authors: limited by "artificial,
  laboratory-induced, emotional experiences."

## Bushman, 2002 — venting at a pillow, and two things not in the paper

**"Does Venting Anger Feed or Extinguish the Flame? Catharsis, Rumination, Distraction, Anger, and
Aggressive Responding," *Personality and Social Psychology Bulletin* 28(6):724–731.**
`primary text read`. Corrections recorded because both errors were mine.

- **A "154-study review" attributed to Bushman is not in this paper.** He cites **Geen & Quanty
  (1977)**. Marked unsourced; do not repeat the attribution.
- **"Doing nothing beat venting" is overstated** — the distraction-vs-control contrast was
  **ns on both measures.**
- Geen & Quanty's moderators are the theoretically interesting part: venting reduced arousal **only
  when expressed directly at the provocateur, and only when retaliation was not expected.** That is
  what "the boundary got set, and it was safe to set it" would predict — **flagged as a prediction
  Darryl's action-tendency frame makes, not a tested moderator.** Hitting a pillow sets no boundary
  with anyone.

# Lesson 2 — reading others, and the body-scan question — 2026-08-13 (second pass)

Darryl's scope ruling: Lesson 2 is **awareness only** — sense and feel your own emotions, notice them
in others, mentalize, ask clarifying questions, categorise with the seven names. **No action
tendencies, no arousal dimension (Lesson 5), no what-the-emotion-wants.** These three searches were
run to close the gaps that ruling exposed.

## 1. Reading emotion from faces — the construct is contested, and the numbers matter

**Barrett, L. F., Adolphs, R., Marsella, S., Martinez, A. M., & Pollak, S. D. (2019). "Emotional
Expressions Reconsidered: Challenges to Inferring Emotion From Human Facial Movements."
*Psychological Science in the Public Interest* 20(1):1–68.** DOI 10.1177/1529100619832930.
**Full-text HTML fetched and queried; the 68-page PDF was also downloaded but could not be
page-read (no poppler). Treat the figures below as `fetched from full text, not read end-to-end` —
re-verify before printing.**

- **Reliability is weak.** Meta-analytic **average r = .31**, and the proportion of episodes in
  which the target facial configuration actually appeared was **.22, range .11–.35.** Authors:
  "people moved their faces in ways that were **not consistent** with the hypotheses of the common
  view."
- **Specificity is "largely unknown"** — most studies never report false-positive rates. A Duchenne
  smile can signal submission or affiliation rather than happiness.
- **The methodological finding that bears on our own design rule:** when participants **choose from
  a provided list of emotion words**, accuracy is "moderate to strong"; with **free labeling** it
  falls to "weak to moderate" (their Table 3).
- **What they say is needed for accurate inference:** situational context, body movement, voice,
  temporal context (what happened moments before), social context (who is present, the
  relationship).
- **Their terminology recommendation:** say **"a scowl," not "an expression of anger"**; "a smile,"
  not "an expression of happiness."

**How this changes our position.** The ledger already establishes that *individual differences* in
face-reading are real, from two independent constructs — Grynberg 2012 (alexithymia) and
Israelashvili 2019 (differentiation). **Barrett does not contradict that; he attacks the validity of
the task those studies use.** Both can be true: some people score better on a face-recognition task,
*and* the task may not measure reading real emotion. This is [[M2]] again — lab task versus life.

**And it inverts the provided-versus-generated rule in one specific place.** For *your own*
experience, provided words help ([[P4b]]: Torre, Sheeran, Breitwieser). For *reading someone else*,
Barrett treats the provided-word-list boost as an **artifact that inflates apparent accuracy.**
So handing someone seven categories will make them feel and appear better at reading other people
without necessarily making them better. **Combined with the misprediction cluster — three studies
where people could not tell whether an emotional intervention had worked — the honest design
conclusion is that categories are for your own experience and for communicating, and that reading
another person should route through asking rather than inferring.** Which is where Darryl had already
landed independently.

## 2. Does a body practice improve emotion *identification*, or only body awareness?

This was the crux question. **The answer is: nobody has tested it properly at the level of a single
practice, and the one pilot that tried is too weak to count.**

**"Quadratic Relationship Between Alexithymia and Interoceptive Accuracy, and Results From a Pilot
Mindfulness Intervention," *Frontiers in Psychiatry* 11:132 (2020).** PMC7076086, PMID 32210852.
**Full text fetched and queried. Author list not captured — verify before citing.**

**Do not cite this as evidence that body scan fails.** N=76 undergraduates (66% women, mean age
19.70), screened to exclude any history of depression, anxiety or substance use. The intervention
was **a single 10-minute audio recording** of a body scan; the control was **a single 10-minute
reading from a natural history textbook.**

- Interoceptive accuracy improved — **in both groups.** Main effect of time F(1,70)=12.22, p<.001,
  **η²=0.15**; **interaction F(1,70)=0.02, p=.88, η²=0.00.** The body scan did not beat the natural
  history textbook. The authors attribute the gain partly to **practice effects on the heartbeat
  task.**
- **No group differences on affect labeling or granularity**, all small and null: consistent affect
  label d=0.18, p=.42; negative granularity d=0.15, p=.72; **positive granularity d=0.00, p=.90.**
- Authors' own reading: the dose "may have been insufficient," the screened sample restricted
  variance, and they were underpowered.

**Two things in this paper are worth more than its intervention.**

**(a) The quadratic finding, and it is important for this lesson.** Adding a quadratic term
significantly improved fit over linear: **ΔR² = 0.14, p = 0.002**; quadratic **β = 2.62, p = 0.002**;
model R²=0.17, p=.017, f²=0.20. **Elevated alexithymia was associated with either relatively HIGH or
relatively LOW interoceptive accuracy.** Their conclusion: "greater interoceptive accuracy is **not
necessarily** associated with better outcomes," and "a subset of individuals with heightened
alexithymia may be characterized by **increased** interoceptive accuracy, which could also be
maladaptive."

**This maps directly onto the somatic-translation cluster already in this ledger** — people who read
bodily arousal as physical illness are noticing the body *more*, not less, and misreading it.
**Implication for the practice: a body scan is the right practice for one half of the population and
possibly the wrong one for the other half.** The lesson should distinguish *noticing* the signal from
*interpreting* it, because the second is where the failure lives. This is a genuine and previously
unstated design constraint.

**(b) A methodological bomb for the whole interoception literature.** The authors note that when
participants are explicitly instructed to count **only felt** heartbeats rather than estimated ones,
**interoceptive accuracy drops by 50%.** Their own participants were not so instructed, and could
have used pulse or estimation. **This applies to the 5-day biofeedback result already in this ledger
— re-check whether that trial constrained estimation before treating it as an objective gain.**

## 3. The properly-dosed trial — and its second arm is Darryl's lesson

**Silveira, S., Godara, M., Faschinger, A., & Singer, T. (2023). "Reducing alexithymia and
increasing interoceptive awareness: A randomized controlled trial comparing mindfulness with dyadic
socio-emotional app-based practice." *Journal of Affective Disorders.***
ScienceDirect S0165032723010704. **`abstract and secondary summaries verified; full text 403s at
ScienceDirect and was not obtained. No exact statistics captured — do not print numbers from this
until the PDF is in hand.`** Part of the CovSocial project (ClinicalTrials NCT04889508).

**N = 285 adults. Two arms, both app-delivered, both ~12 minutes daily, ~10 weeks, both with weekly
online coaching:**
- **MB** — attention-focused mindfulness (solo)
- **SE** — partner-based **socio-emotional "Affect Dyad"**

**Results, as reported in the abstract:**
- **Both** arms reduced emotion-processing difficulty on the **TAS-20.**
- Both improved interoceptive awareness immediately after daily practice and after the intervention
  period — **but SE outperformed MB on the EMA assessments.**
- **Only the Dyad practice increased "body listening" and the self-regulatory facets of the MAIA
  over time — and the self-regulatory change explained the decrease in alexithymia.**
- Their framing: "**Body awareness practiced in the Affect Dyad informed affect awareness and
  regulation.**"

**This is the single most decision-relevant source found for Lesson 2.** It is a properly dosed,
randomised, N=285 test of exactly the two candidate practices, and **the partner-based practice beat
the solo one on the mediating variable.**

### The Affect Dyad protocol, operationally
From the Mind & Life Institute's description of the Singer-lab dyads (`secondary source, verify
against the primary training manual before adapting`):

- **10–12 minutes, daily.** Two phases, a gong marking the turn at about 2.5 minutes.
- **The listener asks two questions in sequence.** Verbatim:
  1. *"Describe a situation within the last 24 hours in which you experienced a difficult emotion,
     and how did it feel in your body?"*
  2. *"Describe a situation within the last 24 hours in which you felt grateful, and how did that
     feel in your body?"*
- **The listener's job is non-judgmental awareness and empathic listening**, thanking the speaker
  between questions. Whether the listener speaks otherwise is not specified in this source.
- **Roles then swap. Partners are randomly assigned and change every week**, deliberately, to widen
  the sense of shared humanity.
- Comparative evidence cited: dyads produced larger effects than solo mindfulness on social
  outcomes — more positive thoughts about others, more social connectedness, less loneliness,
  reduced hormonal response to social stress — **where attention-based solo practice did not.**

**Why this matters so much.** Every component Darryl specified for this lesson is in this protocol,
and it has been run: *"how did it feel in your body"* is the body scan; naming the difficult emotion
is the categorising; doing it with a partner is noticing another person's emotional world; and the
listener's question **is** the clarifying question. It is brief and daily, which matches the dose
finding in this ledger (weeks not sessions, frequent not long). **Note that the second question is
about gratitude, which is Lesson 4** — so the protocol as written spans two lessons.

## Also closed: the Nummenmaa gap

This ledger has flagged for some time that **Nummenmaa et al. 2014** (*PNAS*, 701 participants,
emBODY body-mapping, maps concordant across Finnish, Swedish and Taiwanese samples at mean rs=0.70)
is "the single best-evidenced source for the 'locate it in the body' practice the notes already
teach" and was **not cited anywhere in the Lesson 2 notes.** With the lesson now defined as
body-first noticing plus coarse categorisation, **Nummenmaa is the empirical backbone of the
practice** and should be cited in it. Keep the authors' caveat: the maps may reflect learned
conceptual or linguistic association rather than physiological patterning, and the study cannot
establish a link to an underlying activation pattern.

## Silveira, Godara, Faschinger & Singer, 2023 — upgraded to primary, 2026-08-14

**"Reducing alexithymia and increasing interoceptive awareness: A randomized controlled trial
comparing mindfulness with dyadic socio-emotional app-based practice."** *Journal of Affective
Disorders* **341:162–169**, 15 Nov 2023. **DOI 10.1016/j.jad.2023.08.093.**
`primary text read — abstract, introduction, and the alexithymia results section, Darryl-supplied.
Methods and full results sections are behind the paywall and were NOT read; the DIF numbers are
truncated mid-sentence in what is available.`

### Three corrections to what this ledger said yesterday

**1. It is not a two-arm trial.** There is a **waitlist control (WC)**, plus a fourth condition
labelled **WSE** whose definition is not visible in the accessible text. **Do not describe the design
until the methods section is obtained.** All reported contrasts are *against waitlist*, not SE vs MB
head-to-head — so "the dyad beat mindfulness" is an inference from two separate comparisons, not a
direct test, **except** for the EMA interoceptive-awareness measure where the authors state SE
outperformed MB.

**2. We now have effect sizes.**

| Outcome | SE (Affect Dyad) vs WC | MB (mindfulness) vs WC | WSE vs WC |
|---|---|---|---|
| **TAS-20 total** | β=−3.93, **p=.002, d=−0.39** | β=−2.92, **p=.020, d=−0.29** | β=−2.52, p=.175, **ns** |
| **Difficulty Describing Feelings** | β=−1.92, **p<.001, d=−0.50** | β=−1.39, **p=.003, d=−0.37** | p=.122, **ns** |

DIF numbers are cut off mid-sentence in the accessible text. **The dyad is larger on both visible
outcomes, and largest on describing feelings — which is what the authors predicted**, since the Dyad
explicitly asks you to describe.

**3. They abstained from objective measures entirely.** Verbatim: "while we **abstained from
interoceptive accuracy measures**, we used a multi-method approach to interoceptive awareness." So
every interoception outcome here is self-report or EMA. Combined with [[M2]], this caps how strongly
it can be cited. **Sample is subclinical** — their own stated limitation.

### The practice, from the primary text
"a guided daily practice with a partner, in which **the listener asks the speaker to describe
difficult feelings and feelings of gratitude experienced in the past day, and how these felt in the
body. After about 5 min roles are switched.**" (Kok & Singer, 2017a/b.) This confirms the Mind & Life
secondary description, including that the gratitude question is part of the protocol — **so the
protocol as written spans Lessons 2 and 4.**

### Declared conflict of interest — record it
**Tania Singer was scientific and curriculum advisor to Humanize (2021–2023)**, a start-up
commercialising modified and extended versions of the dyad programs, including the Affect Dyad, on a
digital platform. Approved by the Max Planck Society and openly declared. **This is the practice we
are considering adopting, developed and evaluated by the same person who advises the company selling
it. Not disqualifying — but it belongs next to the effect sizes.**

### The finding that reframes the body-scan question

From their introduction, citing **Bornemann et al. 2015** (3 months of mindfulness practice, MAIA):
changes appeared on attention regulation, body trusting, and mind–body integration — and the
authors' reading is the important part:

> "particularly **embodied processes relevant to coping and emotion regulation** are promoted by
> mindfulness practice, **and not aspects of noticing bodily signals**, that is, interoceptive
> awareness in its most common conception."

**A body practice appears to move the regulatory facets, not the noticing facets.** That is the
opposite of the intuitive account, and it matters for a lesson whose whole job is noticing. It also
converges with the quadratic finding already recorded here: **noticing is not the deficit; interpreting
is.**

### A better trainability lead than the one this ledger has been ranking first

Also from their introduction:
- **8-week programs did NOT change heartbeat detection** (Melloni et al. 2013; Parkin et al. 2014).
- **The ReSource project found training-related change in heartbeat perception after 6 and 9 months**
  across attention-based, socio-emotional and socio-cognitive practices — "alterations in objective
  accuracy measures **take time**."
- **And those interoceptive-accuracy increases were directly linked to reductions in alexithymia —
  Bornemann & Singer, 2017.**

**This is what [[P6]] needs: an objective measure, moved by training, linked to the alexithymia
outcome.** It is a specific, titled, identifiable lead, unlike the bare "Killgore 2020" this ledger
has been calling its highest-value retrieval. **Reprioritise accordingly.**

**And it splits the dose finding by measure type.** This ledger's conclusion — weeks rather than
months, more per day not better — was built entirely on **self-report** outcomes. For **objective**
interoceptive accuracy the picture is different: nothing at 8 weeks, change at 6–9 months.
**Subjective awareness moves in weeks; objective accuracy appears to take months.** That is a real
qualification and it was not previously stated here.

### Named leads worth chasing, from the reference and citing lists
- **Bornemann & Singer (2017)** — interoceptive accuracy gains linked to alexithymia reduction.
- **Bornemann et al. (2015)** — MAIA changes after 3 months.
- **"Alexithymia: Toward an Experimental, Processual Affective Science with Effective
  Interventions," *Annual Review of Psychology*, 2025** — a current major review of exactly [[P6]].
- **"Effects of a Body-Based Mindfulness Program on Alexithymia, Dispositional Mindfulness, and
  Distress Symptoms: A Pilot Clinical Trial," *Behavioral Sciences*, 2025** — directly the
  body-scan question.
- **"Interoceptive Ability and Emotion Regulation in Mind–Body Interventions: An Integrative
  Review," *Behavioral Sciences*, 2024.**
- **Lukas et al. (2019)** — a 14-day smartphone skills training improved emotion recognition in
  alexithymia.
- **Trevisan et al. (2019)** meta-analysis — alexithymia associates with interoceptive *sensibility*
  (subjective) and **less consistently with interoceptive accuracy** (objective). This is [[M2]]
  again, inside interoception.
- **CovSocial preregistration: osf.io/3nsjc** — may contain the methods and the WSE definition.

### Process note
**Torre & Lieberman (2018) has been in the Downloads folder since 13 Aug and I listed it as an
unobtained SAGE wall.** I did not check the folder before producing that list. Separately, Darryl's
point stands: **for any paper whose title is known, the abstract is obtainable online** — so
"blocked" should mean "the abstract is insufficient and the full text is paywalled," not "I have not
looked."

## Petzold, Silveira, Godara, Matthaeus & Singer, 2023 — the companion paper. Full text read.

**"A randomized trial on differential changes in thought and affect after mindfulness versus dyadic
practice indicates phenomenological fingerprints of app-based interventions."**
*Scientific Reports* **13:13843.** DOI 10.1038/s41598-023-40636-1. **Open access, CC-BY. `primary
text read in full`**, Darryl-supplied. Same trial as Silveira et al. 2023 (CovSocial phase 2,
NCT04889508, ethics #EA4/081/21). R code and results at **osf.io/vcasn**.

### WSE is now defined — and it matters
93 participants were randomised to waitlist control, **of whom 59 chose to continue with the
socio-emotional Dyad after the first posttest (WSE).** So **WSE is a second, independent run of the
Dyad**, not a different condition. Where SE and WSE agree, the Dyad result has been replicated
within the same trial. This resolves the gap flagged in the Silveira entry above.

**Analysed n: SE 71, MB 82, WSE 59.** Randomised 1:1:1 from 620; 285 allocated.

### The protocol, verbatim from the primary text
- **12-min partner-based exercise, two randomly matched participants**, roles of speaker and
  listener. Appointments scheduled in-app; push notification 10 minutes before.
- **Question 1 (asked by the listener):** *"Please tell me about a situation of your last 24 h, in
  which you experienced a difficult emotion, and how it felt in your body."*
- **After elaborating for 2.5 min**, the listener says: *"Thank you for sharing. Now, please tell me
  about a situation of your last 24 h, in which you felt grateful and how that felt in your body."*
- **After one minute of silence, the roles are switched** and the procedure repeats.
- **The Dyad starts and ends with a period of silence "to drop everything shared and heard."**
- The listener is instructed to **listen non-judgmentally and empathically.**
- **Six days per week**, plus **two hours of weekly online coaching** with a trained teacher on the
  seventh day, groups of 14–24.
- **Scaffolding before any practice began: 2.5 h formal introduction plus two 2.5-hour
  group-specific onboarding webinars.** ~7.5 hours of teaching before day one. **This is not a
  standalone app.**

**Compliance was high, and higher for the Dyad: SE 87.9% (SD 9.05), WSE 89.5% (SD 7.82),
MB 82.3% (SD 18.5).** Note the variance: the Dyad's SD is roughly half the mindfulness arm's.
**Having a partner waiting appears to make people show up more reliably.**
**But dropout ran the other way: SE 24/95 (25%) vs MB 15/97 (15%).** The partner requirement is
both the adherence mechanism and the attrition cost. Technical pairing failures caused disconnects
and crashes, which the authors say "may have led to frustration and discouragement."

### Results — immediate state change (Cube of Thought and Affect Grid, b, pre→post practice)

| Dimension | **SE (Dyad)** | MB (mindfulness) | **WSE (Dyad, replication)** |
|---|---|---|---|
| Future-related | −0.54 | −0.39 | −0.48 |
| **Past-related** | **+0.78** | −0.08 *ns* | **+1.03** |
| **Self-related** | **+0.98** | +0.44 | **+1.11** |
| **Other-related** | **+0.51** | **−0.65** | **+0.41** |
| **Positive** | **+0.75** | +0.06 *ns* | **+0.70** |
| Negative | −0.15 | −0.22 | −0.11 *ns* |
| Affect valence | **+0.94** | +0.60 | +0.72 |
| Affect arousal | +0.31 | **+0.50** | +0.16 |

Differential contrasts vs MB were substantial for past (SE b=0.86 [0.6,1.13]), self (0.54
[0.27,0.81]), **other (1.16 [0.94,1.39])** and positive (0.69 [0.54,0.85]). **No differential effect
on negative thoughts** (SE b=0.07, CI crosses zero).

### Four findings that bear directly on Lesson 2

**1. Solo mindfulness *decreased* other-related thoughts (b = −0.65), where the Dyad increased them.**
If this lesson wants people to notice emotions in other people, **a solitary attention practice
appears to move that capacity in the wrong direction.** This is the clearest evidence yet for the
dyadic format over the solo one for the other-people half of the lesson.

**2. Talking about a difficult emotion did not increase negative thinking.** Negative thought content
was essentially unmoved in both Dyad runs **despite the practice explicitly asking people to
elaborate a situation that evoked a difficult emotion.** The authors' reading: "acceptance of
challenging situations without focusing on the negative experience itself." **This partially answers
the Nils & Rimé worry** that empathic sharing amplifies the emotion — different measure (thought
content vs. upset ratings) and different design, so not a refutation, but it points the other way.

**3. The Dyad's fingerprint overlaps rumination on two of three dimensions.** It raises **past-**
(+0.78/+1.03) and **self-related** (+0.98/+1.11) thought — and by the paper's own citations, the MDD
profile is *negative, self- and past-oriented* thought. What saves it is the third dimension:
valence went **positive** and negative thought did not rise. **So the practice is safe on this
evidence, but it is safe by one dimension, and that dimension is the one to watch.** Cross-reference
Lesson 6. The authors argue the past/self increase is simply the task working — you cannot recall a
situation from the last 24 hours without thinking about your own past.

**4. THE CAVEAT THAT MUST TRAVEL WITH EVERYTHING ABOVE. "10 weeks of daily app-based practice did
not yield longitudinal changes."** All highest-density intervals for change over time fell at least
partially within the region of practical equivalence — "**no conclusive evidence for lasting changes
over time.**"

**So: the practice reliably shifts your state every single time you do it, and after ten weeks the
baseline had not moved on these measures.** The sister paper found TAS-20 *did* drop (SE d=−0.39,
DDF d=−0.50). **Two papers, one trial, opposite conclusions about durability — because they measured
different things.** The honest statement is: **reliable immediate state change, demonstrated
trait-level change on the alexithymia questionnaire, and no accumulation in thought content or
affect over ten weeks.** The authors call for research on "thresholds of dosage and duration."
They also flag they may have been underpowered for the longitudinal test despite ~10,000 data points.

### Sample — read this before generalising
Mean age **43.3 / 43.5 / 44.6**; **70–78% female**; Berlin residents; net income above the Berlin
average for 63–70%; 17–18 years of education. **Excluded:** psychology education (n=53), formal
meditation experience (n=91), current psychiatric diagnosis (n=165), chronic illness or pain
(n=117), current yoga with a strong meditation component (n=95), **TAS-20 > 60**, PHQ-9 > 19,
GAD-7 > 15. **This is a screened, subclinical, meditation-naïve, highly educated, middle-aged,
mostly female, urban German sample. There is no adolescent or young-adult evidence here at all.**

Other limits the authors state: single Likert items for each dimension; self-report throughout;
a possible confound from the weekly coaching sessions, whose content differed by arm and whose
sequence may explain the longitudinal decline in mindfulness's self-related effect.

**Same declared conflict of interest as the sister paper** — TS advised Humanize (2021–2023), which
is commercialising extended versions of the Affect Dyad.

### Provenance note
The Affect Dyad derives from the **ReSource project** (Singer et al. 2016) and **Kok & Singer 2017**
(*JAMA Psychiatry* 74:126, contemplative dyads over 9 months, social connectedness). Its
socio-emotional framing rests on **Panksepp's care-system** (ref. 30 in this paper is Panksepp 2011,
"The basic emotional circuits of mammalian brains") — **the same source this curriculum uses for the
seven names.** The practice and the vocabulary share a theoretical parent.

# Two process rules, added 2026-08-14 at Darryl's instruction

## Rule: first pass comes from the abstract itself, never from a summary tool
Several sources this session were first seen through a search tool's synthesised summary rather than
through the abstract. That inserts an interpretive layer between me and the source, and this project
has already recorded a case where such a summary **invented findings** (Tugade & Fredrickson).
**Search to locate the paper; then read the abstract directly.** Europe PMC's REST API
(`ebi.ac.uk/europepmc/webservices/rest/search?query=...&resultType=core&format=json`) returns the
verbatim abstract and the full author list, and should be the default first stop.

## Rule: do not let the most recently read paper become the verdict
Darryl, 14 Aug: *"when you read one paper you are over anchoring to it. different papers say
conflicting things all of the time. you have to be able to document and track the full body of
literature without being swayed by a single trial so much."*

**The pattern, visible in one session.** Silveira's abstract → "the single most decision-relevant
source found for Lesson 2." Petzold's full text → an immediate swing to the caveat. The Aaron pilot →
treated as answering the crux, then discounted on dose. Each new read reset the position instead of
adding one point to a distribution **that already existed in this ledger.**

**Consequence:** for any question this file has more than two sources on, the entry must carry a
**synthesis table across sources**, ranked by evidential weight, before any single-study conclusion.
The section below is the first one built that way, and it is the corrective case.

---

# Does body awareness give you emotional awareness? The whole body of evidence

Built 14 Aug 2026 from every source in this ledger that bears on it, weakest design at the bottom.
**Read the top row first.** All abstracts below were read directly.

| # | Source | Design & N | What it measured | Result |
|---|---|---|---|---|
| 1 | **Trevisan, Altschuler, Bagdasarov, Carlos, Duan, Hamo, Kala, McNair, Parker, Stahl, Winkelman, Zhou & McPartland, 2019**, *J. Abnormal Psychology* 128(8):765–776, PMID 31380655 | **meta-analysis, 66 independent samples, N=7,146** | alexithymia × interoceptive awareness | **r = −.162, p=.001, 95% CI [−.252, −.068]** — small. Strength and **direction** "heavily influenced by" accuracy-vs-sensibility and objective-vs-self-report. **Moderate in psychiatric/developmental samples; NON-SIGNIFICANT in healthy, typically developing samples.** |
| 2 | **Bornemann, Herbert, Mehling & Singer, 2014**, *Frontiers in Psychology* 5:1504, PMID 25610410 | ReSource, **n=148**, 3 months of daily **"Body Scan" and "Breath Meditation"**, retest control; MAIA validated on n=1,076 | 8 MAIA facets | **5 of 8 improved.** "The strongest changes were observed for the **regulatory** aspects… **No significant changes were observed for the Noticing aspect (becoming aware of bodily changes), which is the aspect that is predominantly assessed in other IA measures.**" Lowest-baseline participants changed most. **Practice duration only weakly predicted change; self-reported liking and degree of integration into daily life predicted change on most scales.** |
| 3 | **Bornemann & Singer, 2017**, *Psychophysiology* 54(3):469–482, PMID 27925645 | ReSource, cohorts n=77, 79, 78; retest control n=84; **9 months** | **heartbeat perception accuracy (objective)** + TAS | Increased **steadily**; significant at **6 months d=.173** and **9 months d=.273**. Changes were "concomitant with and **predictive of** changes in emotional awareness." Their own line: **"The effect takes longer than the 8 weeks of typical mindfulness courses to reach meaningful magnitude."** TAS>60 excluded. |
| 4 | **Silveira, Godara, Faschinger & Singer, 2023**, *J. Affective Disorders* 341:162–169 | RCT, N=285, 10 weeks, dyad vs solo vs waitlist | TAS-20, MAIA, EMA — **all self-report; accuracy measures deliberately omitted** | TAS-20 **dyad d=−0.39, mindfulness d=−0.29**; DDF −0.50 / −0.37. Only the dyad raised body listening and self-regulation MAIA. |
| 5 | **Petzold, Silveira, Godara, Matthaeus & Singer, 2023**, *Scientific Reports* 13:13843 | same trial | thought content, affect | Reliable **immediate** state change every session; **no conclusive longitudinal change over 10 weeks.** |
| 6 | **Interoception meta, 2025** (in this ledger) | **29 RCTs**, adults mean age 32.8, 78% female, **no under-18s** | MAIA-type self-report | **practice dosage, attendance and duration all ns** |
| 7 | **Aaron, Blain, Snodgress & Park, 2020**, *Frontiers in Psychiatry* 11:132, PMID 32210852 | n=76 undergrads, **one 10-minute** body scan vs a natural-history recording | heartbeat detection, affect labeling, granularity | Accuracy rose **in both arms** (η²=.15, interaction p=.88). **No group difference on labeling or granularity.** Alexithymia × accuracy **quadratic p=.002**; × sensibility **linear p=.040**. Authors: improvements "may require longer or **more interactive** intervention approaches." |
| 8 | **Quinto, Russo, Scafuto, Innamorati, Montecucco & Ghiroldi, 2025**, *Behavioral Sciences* 15(1):55, PMID 39851859 | **pilot**, n=73, mean age 40.1, body-based mindfulness vs **waiting list**, **one-week** post-test | TAS-20, Symptoms Questionnaire, FFMQ | TAS-20 and distress both reduced; FFMQ observing, acting-with-awareness, non-reacting improved. **No effect sizes or p values in the abstract.** Waitlist only — no active comparator. |

## What the body of evidence actually supports

**1. The underlying correlation is small, and it is absent in the population this curriculum is for.**
Row 1 is the heaviest evidence here — 66 samples, N=7,146 — and it says **r = −.16 overall and
non-significant in healthy, typically developing people.** Body awareness and emotional awareness
are meaningfully linked in clinical populations and barely or not at all in everyone else.
**Any claim that noticing your body will teach you your emotions is, for a general-audience lesson,
resting on a null.** This finding was in reach the whole time I was oscillating between single trials.

**2. Body practices move the regulatory facets, not the noticing facet.** Row 2 is the direct test —
three months of literal body scan — and **Noticing did not move**, while the self-regulation facets
moved most. Row 4 independently found the dyad moving **body listening and self-regulation**
specifically. **Two sources, same conclusion: these practices change how you use the body, not how
well you detect it.**

**3. Objective accuracy is trainable, but slowly and modestly.** Row 3: **d=.173 at six months,
d=.273 at nine.** And it did predict emotional-awareness change, which is the one clean
noticing→awareness link in this table. But 8-week courses show nothing (row 7 and the studies row 3
cites). **This is the honest ceiling on trainability claims.**

**4. Self-reported alexithymia moves fairly readily** (rows 4 and 8, d≈0.3–0.4) — but on
questionnaires, over weeks, against waitlists. Row 5 shows the same trial finding **no** accumulation
on a different outcome. [[M2]] applies: self-report moves, performance measures move less.

**5. There are two ways to fail, and one involves noticing the body more.** Row 7's quadratic
finding, plus **Trevisan, Mehling & McPartland, 2021**, *Autism Research* 14(2):240–247, PMID
33336935 — which distinguishes **"reduced adaptive forms of interoceptive attention"** from
**"heightened maladaptive forms of interoceptive attention related to anxiety-induced
somatization."** And **Luminet & Nielson, 2025**, *Annual Review of Psychology* 76:741–769, PMID
39322432, calls for exactly this distinction: "distinguishes between **emotion deficits and emotion
over-responding, including when over-responding is functional.**" **Three independent sources
converge: the deficit model is incomplete, and a body scan aimed at "notice more" is the wrong
prescription for one whole subgroup.** This is the somatic-translation cluster in this ledger,
arriving from three new directions.

**6. Dose behaves the same way here as everywhere else in this project.** Duration only weakly
predicted change (row 2); dosage, attendance and duration all ns (row 6). **What did predict change
in row 2 is new and worth keeping: liking the practice, and integrating it into daily life.**
Nothing else in this ledger has identified those as predictors.

## What this means for Lesson 2, stated conservatively
A body-directed practice is defensible as **the way to make an emotion concrete and locatable** —
[[Nummenmaa 2014]] supports the body-mapping paradigm across three cultures — and as a route to the
**regulatory** capacities that later lessons need. It is **not** well supported as a route to better
*detection* of emotion, and the population-level link it would depend on is null in non-clinical
people. **The lesson can teach locating and naming without claiming that it sharpens perception.**

## Also read directly, 14 Aug — for the record
- **Israelashvili, Oosterwijk, Sauter & Fischer, 2019**, *Cognition & Emotion* 33(7):1461–1471, PMID
  30734635, DOI 10.1080/02699931.2019.1577221. Abstract read in full. **Study 1 N=363**: higher
  negative-emotion differentiation → more accurate recognition of others' facial expressions.
  **Study 2 N=217** replicated with tasks varying the amount of emotional information. **No effect
  sizes in the abstract** — full text still needed for numbers. Note the tension with
  **Barrett et al. 2019**: this measures accuracy on a face-recognition task whose construct
  validity Barrett attacks. Both entries must be read together.
- **Luminet & Nielson, 2025** (above) — a current *Annual Review* on alexithymia definition,
  etiology, measurement, vulnerability and **treatment**. **This is the review to read before any
  further claim about [[P6]] trainability**, and it supersedes chasing the unidentified
  "Killgore 2020" lead.

# Bornemann, Herbert, Mehling & Singer 2014 — FULL TEXT READ 14 Aug 2026. Foundational for Lesson 2.

**"Differential changes in self-reported aspects of interoceptive awareness through 3 months of
contemplative training."** *Frontiers in Psychology* **5:1504**, published 06 Jan 2015,
DOI 10.3389/fpsyg.2014.01504, PMID 25610410. Open access CC-BY.
**`primary text read in full` — every number below is from the paper.**
**No conflict of interest declared** (unlike the CovSocial papers).

*Citation note: the journal cites it as 2015 (Front. Psychol. 5:1504); the DOI and most indexes say
2014. This ledger previously recorded it as "Bornemann et al. 2015" from a secondary citation inside
Silveira's introduction. **Use 2014 with the DOI.***

## Design
ReSource **Presence** module. **Training n=152 → 148 completed; retest control n=80** (same testing,
no intervention). Groups did not differ at baseline on age, sex, SES or any MAIA scale. MAIA
validated separately on **n=1,076** (mean age 38.7). Training group mean age 41.6; control 42.3.
T0→T1 interval **113.6 days** (control 113.0, ns).

**The practice, exactly.** Opens with a **3-day silent retreat**. Then **weekly 2-hour classes for 13
weeks** with experienced teachers (**nine teachers**, Theravada, Tibetan and secular backgrounds),
plus home practice **5×/week for 30 min — 20 min Body Scan + 10 min Breath Meditation**, delivered by
platform and phone app with guided audio, which is how practice time was tracked.
**Actual adherence: BoS 4.6×/week (SD 1.09), BrM 4.33×/week (SD 1.04); 11.6 of 13 classes attended;
total practice 36.48 hours (SD 10.85).**
**Body Scan content:** attention guided systematically from toes to head, attending to sensations in
each part, returning whenever the mind strays.

## THE FULL RESULTS TABLE — all eight scales, group × time interaction

| MAIA scale | Sample item | F(226) | p | d (Fig. 2, control-subtracted) |
|---|---|---|---|---|
| **Self-Regulation** | "When I feel overwhelmed I can find a calm place inside" | **53.61** | **<.001** | **0.72** |
| **Attention Regulation** | "I can refocus my attention from thinking to sensing my body" | **42.65** | **<.001** | **0.54** |
| **Body Listening** | "**I listen for information from my body about my emotional state**" | **35.56** | **<.001** | **0.40** |
| **Trusting** | "I feel my body is a safe place" | **14.90** | **<.001** | **≈0.29** (4th bar) |
| **Emotional Awareness** | "**I notice how my body changes when I am angry**" | **4.34** | **.04** | **≈0.17** (5th bar) |
| Not-Distracting | "I distract myself from sensations of discomfort" | 2.46 | .12 | ns |
| Not-Worrying | "I start to worry that something is wrong if I feel any discomfort" | 1.79 | .18 | ns |
| **Noticing** | "I notice changes in my breathing…" | **0.59** | **.44** | **ns** (0.19 un-subtracted) |

Effect sizes computed as the standardised training change **minus** the same measure in the control
group (Cohen 1988). Only Self-Regulation, Attention Regulation and Body Listening are given numerically
in the text (0.72 / 0.54 / 0.40); Trusting and Emotional Awareness are read off Figure 2 and are
**approximate — do not print them as exact.** In the training group alone, **all eight scales rose**
(intra-individual t-tests, all ps ≤ .013); the control group moved on none (all ps ≥ .11). **The
interaction is what matters.**

## This tempers what this ledger said yesterday. Three corrections.

**1. Emotional Awareness moved — but it is the WEAKEST of the five, and it barely cleared.**
**F = 4.34, p = .04.** The paper's summary sentence "all Fs ≥ 4.34, all ps ≤ 0.04" is describing
*this scale*: **Emotional Awareness IS the threshold case.** Its effect size is roughly **0.17**
against Self-Regulation's **0.72**. Yesterday's framing — "the subscale named Emotional Awareness
moved, so the lesson's target moved" — was true and overstated. **The target moved least.**

**2. Body Listening is the better result for this lesson, and I had underweighted it.**
Its item is "**I listen for information from my body about my emotional state**" — arguably closer to
what Lesson 2 teaches than the Emotional Awareness scale — and it moved **robustly: d=0.40,
F=35.56, p<.001.**

**The distinction is informative and worth carrying into the lesson design.** The scale measuring
*passive registration* of the body–emotion link (Emotional Awareness, "I notice how my body changes
when I am angry") barely moved. The scale measuring *actively consulting* the body for emotional
information (Body Listening) moved solidly. **Consistent with the whole pattern here: deliberate use
moves; passive detection doesn't.** A practice framed as *go and ask your body* has better support
than one framed as *become more sensitive.*

**3. Noticing's null is not a reliability artifact.** The authors attribute the Not-Worrying and
Not-Distracting nulls partly to poor internal consistency (**α = 0.65 and 0.56**). **Noticing's α is
0.76 — acceptable** (Emotional Awareness 0.86, 5 items). So the Noticing null stands on its own.

## Baseline dependency — relevant to who this practice is for
**For every scale, initial score correlated negatively with change**, from **−0.18 (Body Listening)
to −0.44 (Noticing)**, all significant. **People who started lowest gained most.** Authors' caveat:
this may be inflated by regression to the mean.
**No sex or age effects on change** (all ps ≥ .11 and > .09), **except** women improved slightly more
on Emotional Awareness, t(146)=1.99, **p=.048**.

## The predictor table — the most actionable finding in this ledger

Table 5, Pearson r with baseline-corrected change:

| Predictor | Noticing | Not-Dist | Not-Worry | Attn Reg | **Emot Aware** | Self-Reg | Body List | Trusting |
|---|---|---|---|---|---|---|---|---|
| **Total practice time** (n=147) | .08 | .05 | .09 | **.18\*\*** | **.12 ns** | **.22\*\*** | .15 ns | **.20\*** |
| **LikingPractice** (n=142) | **.19\*** | .04 | .13 | **.39\*\*\*** | **.31\*\*\*** | **.43\*\*\*** | **.30\*\*\*** | **.39\*\*\*** |
| **PracticeUse** (n=140) | **.34\*\*\*** | **.29\*\*\*** | .09 | **.40\*\*\*** | **.23\*\*** | **.32\*\*\*** | **.36\*\*\*** | **.35\*\*\*** |
| **MeditationWorthwhile** (n=144) | **.20\*** | .08 | **.19\*** | **.23\*\*** | **.20\*** | **.36\*\*\*** | .15 | **.21\*** |

\*p<.05, \*\*p<.01, \*\*\*p<.001. **LikingPractice** = enjoyment + looking forward to it.
**PracticeUse** = ease of integrating into everyday life + usefulness rating.

**The sentence to remember, verbatim:** "**total practice time… is never a significant predictor of
change on any of the MAIA scales when entered into the regression together with the more evaluative
questions**." Combined, the three appreciation variables explained **26% of the variance in
Self-Regulation change, F(3,135)=15.80, p<.001**, all predictors p ≤ .047.

**Note also: PracticeUse predicted Noticing change (r=.34\*\*\*) even though Noticing showed no group
effect.** Integration into daily life tracked change on the one facet the training as a whole did not
move.

## The authors' own conclusion — quotable, and it endorses the lesson's design
"mental training that involves focus on body sensations improves several aspects of IA, and
particularly that it **strengthens participants' use of body sensations to become more aware of
emotions and to regulate distress. Such a training program thus seems advisable as a way to foster
emotional clarity and well-being in healthy individuals.**"

And on mechanism: Attention Regulation = they can direct attention to the body; Self-Regulation =
they use that to regulate distress; Body Listening = they use it "to gain insight into their
emotional-motivational state." Emotional Awareness "**forms the basis for** the deliberate use of the
body for insight" captured by Body Listening.

## Their argument against demand characteristics — worth borrowing
They raise it themselves, then answer it: participants did **not** report gains in Noticing, "which is
**the most obvious skill expected to have increased** after 3 months of bringing attention to the
body." Instead they reported Self-Regulation, "a strategy which has **not** been actively encouraged
in the training, but which participants seem to incidentally adopt." **"This speaks against the
adherence to obvious expectations but rather suggests that participants report on their actual
experience."** The pattern of nulls is itself the validity evidence.

## Limitations the authors state
- **All self-report.** "It is not clear to which extent self-reported IA corresponds to IA as assessed
  through objective measures." Mehling's own words, quoted by them: the MAIA "is largely capturing
  intra- rather than interindividual variability."
- Possible change in how participants *understand* the items after training (Grossman 2008).
- **Healthy participants only** — psychologically and physiologically screened. "It remains an open
  question how a contemplative intervention as that of the current study affects body awareness in
  participants with mental or physical problems." **This is the same screened-healthy limitation as
  the CovSocial trials, and it compounds [[A3]]: the population where the body–emotion correlation is
  null is the population studied here.**
- Regression to the mean may inflate the baseline-dependency finding.

## Convergent validity worth noting for the lesson
Table 4: **Emotional Awareness correlates .56\*\*\* with FFMQ Observing** and **.43\*\*\* with the
Private Body Consciousness Scale** — its two highest. Noticing correlates .51\*\*\* with Observing and
.42\*\*\* with PBCS. **Trusting and Not-Worrying are the only scales strongly negatively correlated
with trait anxiety (−.44 and −.43).** Emotional Awareness's correlation with trait anxiety is
**.06, ns** — i.e. noticing the body–emotion link is not itself anxiolytic, which is a useful
corrective to any implied promise.

## Cross-references
Directly supports and qualifies [[A4]]. Compounds [[A3]] (Trevisan 2019: r=−.16, null in healthy
samples — and this study is healthy-only). The dose nulls match [[P3]] and the ledger's dose table.
The "liking and integration beat duration" result is **new to this project** and has no counterpart
elsewhere in the file.

# Two corrections, 14 Aug 2026 — both about overstatement

## Rule: stop collapsing findings to their most absolute form

Darryl: *"you are saying never and that is way too big of a conclusion… i dont understand why you keep
being so extreme. things are not so absolute in research."*

**The pattern, from this session alone.** "The cleanest meta in the register" (Webb 2012 — now known
to have a published critique). "Never a significant predictor" (the authors' word, scoped to one
regression). "Null in healthy samples" (accurate, but led with, rather than *small overall and
moderated by population*). "The target moved least" — a turn after saying the target had moved.
"This is your lesson, already built and tested."

**The mechanism:** I reach for the strongest available formulation, usually by quoting a source's
most quotable sentence, and then have to walk it back when the next paper arrives. That is not only
an anchoring problem; it is a calibration problem. **Findings arrive with ranges, moderators and
disputes, and I keep discarding those to produce a headline.**

**Three concrete fixes, applied from here:**
1. **Record the point estimate with its range, its moderator, and its dispute — in the same
   sentence.** Not as a caveat further down.
2. **Never quote a paper's most absolute sentence as this file's conclusion.** If the paper says
   "never," check what it is scoped to and what the same paper's other analyses show.
3. **Before calling any meta-analysis clean or best, search for published comments and replies.**
   This is checkable and I had not been doing it. See below for why it matters.

---

## Correction 1: "never a significant predictor" was scoped, and the same paper contradicts it

**What I reported:** Bornemann et al. 2014 — "total practice time is **never** a significant predictor
of change on any of the MAIA scales."

**AMENDED 14 Aug after Darryl's clarification: "they said never in their study. not never in the
world."** He is right, and my first version of this correction was itself an overcorrection. The
authors' "never" is properly bounded — it means *zero of our eight scales reached significance in
this model*, which is an accurate summary of their own results and a legitimate use of the word.
**They did not overstate. I did, by stripping the scope clause so the sentence read as "practice
duration does not matter."** The fault is mine at the level of quotation, not theirs at the level of
inference. Recorded because the overcorrection is the same failure as the original: reaching for the
strongest available reading in either direction.

**The scope clause I dropped.** The full sentence ends:
"**when entered into the regression together with the more evaluative questions.**" And the same
paper's own Table 5 shows that in **bivariate** correlation, total practice time **did** significantly
predict three of eight scales:
- **Attention Regulation r = .18, p < .01**
- **Self-Regulation r = .22, p < .01**
- **Trusting r = .20, p < .05**

The authors also **explain** the weak dose relationship rather than asserting its absence: "This may
have to do with the generally strong adherence of all ReSource participants to the required daily
practice, resulting in **low variance of practice hours**." And they cite contrary evidence directly:
Carmody & Baer 2008, Pace et al. 2009 and Rosenzweig et al. 2010 (longitudinal dose effects), plus
Fox et al. 2012 and Lazar et al. 2005 (lifetime practice hours predicting interoceptive ability and
brain structure).

**The calibrated statement.** In this sample, practice duration predicted three of eight facets
weakly (r ≈ .18–.22) and lost significance when liking and daily-life integration were included in
the same model. Practice-hour variance was restricted by high adherence, which the authors offer as
a likely reason. Appreciation measures were the stronger predictors here. **Other studies in this
literature do find dose effects, and this project's broader dose finding remains "no source here
shows more practice producing more skill" — not "practice duration does not matter."**

---

## Correction 2: Webb, Miles & Sheeran 2012 has a published critique. It is not "the cleanest meta."

**Augustine, A. A., & Hemenover, S. H. (2013). "Accuracy and generalizability in summaries of affect
regulation strategies: Comment on Webb, Miles, and Sheeran (2012)." *Psychological Bulletin*
139(3):725–729.** PMID 23607433, DOI 10.1037/a0030026. **Abstract read verbatim; full text not yet
obtained.** Brought to this project by Darryl, 14 Aug.

I called Webb 2012 "the cleanest meta in the register," on the basis of Egger's p=.44 and a fail-safe
N of 9,285. **Those statistics address publication bias only.** They say nothing about inclusion
criteria, control conditions or effect-size selection — which is precisely what this comment
attacks.

**Their charges, verbatim from the abstract:** "there are a number of **errors and omissions** in this
new meta-analysis that could lead to misconceptions regarding both our previous work and the state of
the affect regulation literature." They examine "the impact of **methodological issues, inconsistent
inclusion criteria, variance in manipulations, and what we perceive to be a subjective and
inconsistent selection of effect sizes** on the accuracy and generalizability of Webb and colleagues'
estimates of affect regulation strategy effectiveness."

**From the visible full-text page:**
- **The comparator drives the number.** Augustine & Hemenover 2009 selected studies permitting
  calculation of **within-person change** caused by using a strategy; Webb et al. compared
  **post-regulation affect for one strategy against post-regulation affect for another.** Their
  objection: "the effect sizes drawn from these studies are **entirely dependent on the referent
  chosen for comparison** to the affect regulation attempt."
- **An exclusion they call unexplained.** Footnote: "It is unclear why Webb et al. (2012) decided not
  to include the work of **Lazarus and colleagues** in their meta-analysis, as these studies utilize
  exactly the methodology which was targeted in their meta-analysis."
- **An ecological-validity objection:** in the Lazarus paradigm participants are forewarned of an
  affective stimulus and told how to process it. "However, it would be very unusual for someone to be
  forewarned of an affective episode in daily life."

**There is a reply, and it must be read before concluding anything. PMID 23607434**, same journal,
same issue, **pages 730–734**, DOI 10.1037/a0030447, May 2013. **Do not record this dispute as
settled in Augustine & Hemenover's favour — I have read one side of a two-sided exchange.**

**What this does to [[P21]].** P21 is the "three operations with three signs" claim — using a feeling
as a cue **+0.44 to +0.86**, reliving it **−0.14**, analysing why **−0.34** — and this register has
leaned on it heavily, including in the Lesson 2 audit and in the material relocated to Lesson 19.
**If effect sizes in that meta are "entirely dependent on the referent chosen," those three numbers
are comparison-dependent, not absolute.** The *ordering* may well survive; the magnitudes are less
secure than presented. **P21 should be re-tagged from `VALIDATED — no publication bias` to
`SUPPORTED — magnitudes disputed in print; comment and reply both need reading`.**

**And a gap this exposes: Augustine & Hemenover (2009)** is a prior meta-analysis of affect
regulation strategies, using a different and arguably more ecologically defensible method, and **it is
not in this ledger at all.** Exact citation not yet obtained — **retrieve it.** Having two
independent meta-analyses of the same literature that disagree on method is exactly the kind of
distribution this file should be built on rather than a single "cleanest" source.

## Purpose rule, added 14 Aug 2026 — the one that governs the others

Darryl: *"i think you are trying to get far more out of these papers than you can. i only care about
figuring out what works for what outcomes in the context of embodied emotional intelligence. i don't
need to make a claim about who has a 0.10 higher SMD."*

**He is right, and it explains most of the churn in this file.** The Webb/Augustine exchange cost
three turns — I called the meta "cleanest," un-called it, flagged a dispute across four files, then
the reply resolved it as an ordinary methods disagreement. **Zero change to what the lesson teaches.**

**The question this file exists to answer:** for each thing a lesson might have someone do, does the
evidence support doing it, and what is the honest caveat? **Direction and robustness matter.
Third-decimal magnitudes and inter-team priority disputes do not.**

**What this changes in practice:**
- Record the direction, the rough size band (small / medium / large), the population, and the
  caveat. Stop tracking whether one team's estimate is 0.10 above another's.
- When two sources disagree on magnitude but agree on direction, **record the agreement and move on.**
- Reserve methodological adjudication for cases where the dispute would **change whether we teach
  something** — e.g. Trevisan's null in healthy samples, which does change what can be promised.
- **Resolution of the Webb exchange for this project's purposes:** Webb et al. replied that the
  criticisms rest on misunderstandings of inclusion criteria or on disagreements about decisions
  "crucial to the validity of meta-analysis," and presented new evidence that their estimates
  **predict emotional outcomes over one year.** That predictive claim is the only part with decision
  value. **Use the ordering; stop arbitrating the numbers.**

## Durability — separating three questions I had been blurring, 14 Aug 2026

Darryl: *"collapsed longitudinally with continued practice? without? you are being way too vague."*
He is right. I had been using Compas's "longitudinal collapse" as though it spoke to whether the
benefits of a practice last. **It cannot. There is no practice in Compas.**

### What Compas's longitudinal analysis actually is
**Compas et al. 2017**, 212 studies, N=80,850 — a meta-analysis of **observational** studies.
The longitudinal subset is **17 studies** in which a **coping style was measured at Time 1 and
symptoms at Time 2.** No intervention, nothing trained, nothing to continue or discontinue.
Emotion regulation × internalising **r = −.08, p = .52**; primary control **−.07, p = .58**;
secondary control **−.00, p = .90**. Survivors: disengagement **+.18**, avoidance **+.08** (lost
significance after trim-and-fill), and **social support coping +.12, p<.001 — more support-seeking,
*more* internalising symptoms over time.**

**The authors' own reading, which is the precise one:** factors associated with lower symptoms
"**may only be correlates of symptoms when measured at the same point in time.**"

**So the correct statement is:** *a coping style you can measure in someone today does not predict
their symptoms later.* That is a claim about the **predictive validity of a trait-like measure**, not
about the durability of a trained skill. **Stop citing it as evidence that benefits fade.**

### What this file actually knows about durability, split properly

**With continued practice — mixed, and it depends on the measure:**
- **Objective interoceptive accuracy kept climbing.** Bornemann & Singer 2017: heartbeat perception
  **d = .173 at 6 months, .273 at 9 months** of continuous ReSource practice — and **nothing at
  8 weeks** in the studies they cite (Melloni 2013, Parkin 2014). Gains accrued *because* practice
  continued.
- **Questionnaire alexithymia dropped.** Silveira 2023: TAS-20 over 10 weeks of daily practice
  (dyad d=−0.39, solo d=−0.29).
- **Thought content and affect did not accumulate.** Petzold 2023, same trial, same 10 weeks of daily
  practice: **every session produced a state shift; the baseline did not move.** "No conclusive
  evidence for lasting changes over time."
- Bornemann 2014 (3 months) and Widdershoven 2019 (6 weeks) measured **pre–post only.**

**Without continued practice — almost entirely unmeasured.** Only three post-cessation data points
exist in this file, and **all three follow single-session interventions:**
- **Kircanski:** skin-conductance benefit still present at **1 week** after one exposure session.
- **Nils & Rimé:** at **48 hours**, the factual-reframing effect held; the empathic-listening effects
  had vanished.
- **Naming-before-reappraising experiments:** effects "washed out in 1–2 days."

**The one multi-week practice with a real follow-up is Smith et al. 2024** — 6 months, **N=94**,
sustained in the training group while the placebo group declined. **Whether those participants kept
practising is not something I have established. Do not claim either way until the full text is read.**

### The honest gap statement
**For every multi-week practice in this project, what happens after someone stops is unmeasured.**
The gains that have been demonstrated were demonstrated *while practice was ongoing*. That is a real
limitation and it should be stated in the lesson rather than smoothed over — but it is a **gap**, not
a finding of decay. **"We don't know" is the accurate claim, not "it fades."**

## P7 resolved: body mapping as an intervention — searched 14 Aug 2026, no trials exist

Europe PMC, query combining ("body map" OR "body mapping" OR "bodily maps") AND (emotion OR
"emotional awareness" OR alexithymia) AND (intervention OR training OR trial OR randomi*).
**Twelve results, every one descriptive, correlational or theoretical.** No study taught participants
to locate emotions in the body and measured emotional awareness, alexithymia, differentiation or
interoception as an outcome.

**P7 moves from `UNSEARCHED` to `SEARCHED — no intervention evidence exists`.** This is now a
documented absence with a query behind it, unlike the two false absences of 13 Aug. It does **not**
mean body mapping is ineffective; it means **nobody has tested it as a taught practice.** Nummenmaa
2014 remains solid and remains descriptive.

**Three results worth keeping anyway:**
- **Zhong S, Tang X, Cheng X & Pan Y (2026), "Bodily maps of subject-specific feelings and academic
  emotions among high school students," *BMC Psychology* 14(1):499**, PMID 41776592. Correlational —
  **but it is the only body-map data in an adolescent sample this project has seen.** Open access;
  retrievable without help.
- **Ortin-Peralta A, Gulbas LE, Espinosa-Polanco M, Baroni A & Miranda R (2026), "Body Mapping as a
  Tool to Capture Children's Expressions of Their Suicide Ideation or Attempts," *J. Clinical Child &
  Adolescent Psychology* 55(4):715–730**, PMID 41849649. Body mapping used as an **assessment** tool
  with children, motivated explicitly by "developmental differences in identifying, recalling, and
  verbally describing internal states." Relevant to why a body-first route might suit young people
  who cannot yet verbalise — but it is assessment, not training.
- **Guerra RF & Tavares H (2025), "Theory and conception of Somatopsyche Psychiatric Intervention,"
  *Frontiers in Psychiatry* 16:1644739**, PMID 40904567. A body-mind intervention framework —
  **theoretical, preliminary implementation only.** Not evidence.

# Smith et al. 2024 — full text read 14 Aug 2026. The youngest sample in this project.

**"Improvements in Mindfulness, Interoceptive and Emotional Awareness, Emotion Regulation, and
Interpersonal Emotion Management Following Completion of an Online Emotional Skills Training
Program."** Smith R, Persich MR, Chuning AE, Cloonan S, Woods-Lubert R, Skalamera J, Berryhill SM,
Weihs KL, Lane RD, Allen JJB, Dailey NS, Alkozei A, Vanuk JR, Killgore WDS. *Emotion* (2024)
**24(2):431–450**, DOI 10.1037/emo0001237, PMID 37535567. Darryl-supplied. `primary text read in full`

## Design
**N=448 randomised** (234 training / 214 placebo) → **326 completed** (168/158) → **94 at 6-month
follow-up** (55/39). **Ages 18–40, mean 23.7 (SD 5.5)** — **the youngest sample anywhere in this
project.** 72.1% female, 60.9% White, 69.9% students. Paid up to **$600**.

**10–12 hours of online modules**, assigned day by day, over either **1 week (compressed)** or
**3 weeks (distributed)**. Missing two days of modules meant removal from the study.
**A genuinely matched placebo** taking the same 10–12 hours with the same tiered structure, teaching
external-world observation — identifying a plant from its leaves, food chains.

## CORRECTION to this morning's P7 search
I searched for body mapping as *the* intervention and recorded "no intervention evidence exists."
**Too clean. Body mapping is a component here, inside a randomised placebo-controlled trial.** The
Tier 1 "emotion tracking" tool has participants **draw where they feel sensations in their body** for
a specific situation, alongside the situation, their interpretation, what they wanted to do and what
they did — **explicitly built on Nummenmaa et al. 2014 and Hietanen et al. 2016.**

**Accurate statement: no trial has tested body mapping as a standalone practice; it has been used as
one component of a multi-component program that produced small improvements against placebo.**
Component-level attribution is impossible from this design.

**New source it hands us: Hietanen J, Glerean E, Hari R & Nummenmaa L (2016), "Bodily maps of
emotions across child development," *Developmental Science* 19(6):1111–1118.** Body mapping **in
children** — directly relevant to this project's adolescent gap, and previously unknown here.

## What moved — every effect size small (ηp² = 0.01–0.02)

| Measure | F | p | ηp² | Training | Placebo |
|---|---|---|---|---|---|
| **LEAS total** (performance-based) | 7.2 (1,305) | **.008** | 0.02 | **+1.21, p<.001** | −0.16, p=.68 |
| **LEAS self** | 4.48 | **.035** | 0.01 | **+1.27, p<.001** | +0.23, p=.53 |
| **MAIA total** | 6.05 | **.014** | 0.02 | +1.30, p<.0001 | +0.12, p=.71 |
| MAIA **emotional awareness** | 6.58 | **.011** | 0.02 | +0.26, p<.001 | +0.01, p=.92 |
| MAIA **not-distracting** | 5.19 | **.023** | 0.01 | +0.17, p=.028 | −0.09, ns |
| MAIA **self-regulation** | 4.57 | **.033** | 0.01 | +0.33, p<.001 | +0.10, ns |
| **FFMQ total** | 7.78 | **.006** | 0.02 | +5.41, p<.001 | +1.34, p=.21 |
| FFMQ **describing** | 7.3 | **.007** | 0.02 | +1.43, p<.001 | +0.20, ns |
| **DERS total** (difficulty ↓) | 5.78 | **.017** | 0.02 | −5.26, p<.001 | −1.33, ns |
| DERS **awareness** / **clarity** | 4.35 / 8.46 | **.038** / **.004** | 0.01 / 0.02 | −0.68 / −1.04 | ns / ns |
| **ERQ suppression** (↓) | 5.5 | **.02** | 0.02 | −0.78, p=.015 | +0.30, ns |
| **MEOS poor skills** (↓) | 6.11 | **.014** | 0.02 | −0.55, p=.005 | +0.15, ns |

## What did NOT move — and the first item is the finding for Lesson 2

- **LEAS *other* did not change.** The authors state it plainly: "increases in emotional awareness
  were **specific to the self**, while **other-focused emotional awareness did not appear to change.**"
  **Teaching self-awareness did not transfer to awareness of other people.**
- **Facial emotion recognition (PAT total) did not move**, p=.094. The faces-words subscale hit p=.029
  but **did not survive correction for multiple comparisons** — despite Tiers 2 and 3 explicitly
  training facial and vocal emotion recognition and its context-dependence.
- **Cognitive reappraisal did not move at all**, F=0.55, p=.458. A seventh independent null on
  reappraisal in this project.
- **STEM-B, the performance test of emotion management, showed no group effect** (p=.5999). Both
  groups improved equally.

**Read together: what this program did not achieve is reading other people and performing better in
an emotional situation. It moved self-knowledge and self-report.**

## Durability — and the answer to the question flagged yesterday
**Whether the follow-up group kept practising is not reported.** The authors say the follow-up was
included partly because gains "may be gradual as participants continue to practice," but **no
post-training adherence was measured.** Unknown, and they claim nothing either way. **Do not cite this
as evidence of durability without practice.**

What the follow-up (N=94) shows: **DERS F(2,430)=6.69, p=.001, ηp²=0.03**; training–placebo at T3
**−7.55, p=.02** — but the mechanism is **the placebo group getting worse** (+3.05 from baseline)
while training held. Same shape on STEM-B: both improved, then **placebo fell back to baseline** while
training held. The authors attribute it to COVID onset and call it "potentially protective." ICCs
post-training→follow-up were moderate: **DERS 0.72, ERQ suppression 0.67.**
**LEAS, MAIA, FFMQ, MEAQ and PAT were not collected at follow-up. The awareness measures have no
follow-up data at all.**

## Limitations, in the authors' words
- "all effect sizes observed for the significant Group × Time interactions were **either small or
  small/medium**; thus, **the magnitude of real-world benefit offered by this training program remains
  to be determined.**"
- "the large number of analyses conducted in this study… raises concerns related to multiple
  comparisons. **A replication study will therefore be needed to identify consistent effects.**"
- **Attrition ~27%, and completers were better to begin with** — higher baseline LEAS, FFMQ, MEAQ and
  emotion recognition, lower DERS and suppression. **The results describe the more-skilled subset.**
- Two baseline imbalances leaving the training group more room to improve (DERS lack of awareness,
  STEM-B; both d=.19).
- 72% female, 70% students, 61% White.

## Three design details: two worth stealing, one that cuts against us
- **Compressed beat distributed.** The 3-week schedule had **significantly more attrition**
  (χ²=12.77, p=.004), and the 1-week schedule produced **greater gains on FFMQ describing and on
  distress avoidance.** Consistent with this project's dose findings: **shorter and denser.**
- **Motivational interviewing up front** — participants named which skills mattered to them, the
  benefits they expected, and set their own goals, explicitly to maximise engagement. Converges with
  Bornemann 2014: **liking and integration predict change more than duration does.**
- **Against us: the vocabulary tool is fine-grained** — a grid of many emotion labels organised by
  valence and arousal, each with a definition. That is the opposite of [[P4d]]'s coarse-beats-fine
  result. **Both cannot be optimal. Unresolved, and worth flagging before we fix the seven.**

# The co-intervention problem — raised by Darryl 14 Aug, and it applies to every practice in the map

*"for the dyad work, did the controls also get the weekly 2 hour coaching and 7.5 hours of
onboarding? otherwise thats a ton of other treatment. not sure how you claim it was the dyad work
that moved it all"*

**He is right, and I had been attributing whole-package effects to single practices.**

## Affect Dyad (Silveira / Petzold 2023)
**Both intervention arms received the wrapper; the waitlist control received none of it.** From the
primary text: "In both mental training programs, daily app-delivered practice was conducted six days
per week and **complemented by weekly two hours of online coaching sessions** conducted by trained
meditation teachers on the seventh day," and "prior to the intervention period, all participants
received **2.5 h of formal introduction** to contemplative trainings, and **two 2.5 h long
group-specific onboarding webinars**." WSE participants received the app introduction only at
posttest 1, i.e. on crossover.

**The arithmetic:** ~7.5 h onboarding + ~20 h coaching (10 weeks × 2 h) versus ~12 h of actual dyad
practice (12 min × 6 days × 10 weeks). **More time was spent in teacher-led group coaching than in
the practice being studied.**

**Therefore: TAS-20 d = −0.39 (dyad) and −0.29 (mindfulness) are effects of the whole package against
nothing.** They cannot be attributed to the practice.

**And the SE-vs-MB contrast is better but not clean.** The authors: "Coaching sessions were
standardized and kept as consistent as possible between the two interventions. **However, they were
characterized by differences related to practice-specific focus**" — the SE coaching covered social
connectedness, empathic non-judgmental listening, interoceptive body awareness, acceptance of
difficult emotions, care and gratitude; the MB coaching covered breathing meditation, body awareness,
sensory perception and open awareness. Their explicit caveat: **"a confounding effect of the weekly
coaching session cannot be excluded."** So practice and coaching content are confounded within arm.

**What survives:** the *differential* results (other-related thoughts +0.51 vs −0.65; positive
thoughts +0.75 vs +0.06 ns) are differences between two matched-duration packages that differ in both
practice and coaching focus. **The direction is informative; the cause is not isolated.**

## Bornemann 2014 — same structure
**3-day silent retreat + 13 weekly 2-hour classes (~26 h) + ~36.5 h home practice, against a retest
control that received nothing.** So the MAIA effects (Self-Regulation d=0.72 down to Emotional
Awareness ≈0.17) are effects of **retreat + classes + practice** versus **no contact.** The body scan
is not isolated. **Nine different teachers delivered it**, which adds facilitator variance.

## Widdershoven 2019 — a smaller version of the same problem
Already recorded, and worth re-stating here: **the ESM group had weekly researcher meetings the
control group did not**, though the authors note neither meeting focused on specific emotions or
differentiation.

## Smith et al. 2024 — the exception, and why it matters
**This is the only study in the map with a genuinely matched control.** The placebo took the **same
10–12 hours**, in the **same tiered structure**, with visually parallel exercises — teaching
external-world observation instead of emotional skills. Attention, time, structure, payment and
contact were equated.
**Its effects are correspondingly small: every significant interaction ηp² = 0.01–0.02.**

**That juxtaposition is the honest lesson of this whole section.** The studies with large effects
compared a rich package against nothing. The study that matched the package produced small effects.
**Some of what looks like practice effect in the other trials is plausibly attention, teaching,
group contact and expectancy.**

## Consequence for the practice map
Every row in section A–C of the practice map must carry its comparator. Rewriting the honest claim
shape: *this package, of which the practice is one component, moved this measure against this
comparator.* **No practice in this project has been isolated except within Smith's multi-component
program, where component-level attribution is impossible by design.**

# Two practices I excluded without searching — searched 14 Aug 2026, both exclusions were wrong

Darryl: *"you keep saying the one test or no one has studied… and even excluded practices because of
it when you dont know if others have done that research because you didn't look."*
**Correct. I wrote the UNSEARCHED rule on 13 Aug and broke it three times within an hour on 14 Aug** —
"one study, one paradigm," "no practice-level evidence located," and a body-mapping absence that was
wrong anyway. Both searches below should have preceded the exclusions.

## 1. Naming a feeling during an emotional task — NOT one study. At least six experiments.

Europe PMC, affect labeling × exposure/anxiety/fear × trial/experiment.

- **Ariely et al. (2026)**, *Affective Science* 7(2):282–292, PMID 42311801. **N=226 across two
  studies.** Labelling or reappraising while viewing negative images; rated immediately and 1–2 days
  later. **"Results of both studies mirrored those of Nook et al. (2021), with affect labeling
  reducing the effectiveness of reappraisal."** → **This is an independent replication of [[Q2]],
  which this register had as "two pre-registered experiments." It now has N=226 more. Upgrade Q2.**
  **Also gives us a source we did not have: Nook et al. (2021).**
- **Chen et al. (2026)**, *Cognition & Emotion* 40(1):1–18, PMID 41555532. Labelling vs matching
  emotion images, then an interference task. **"Results showed no advantages for labelling compared to
  matching."** → a null.
- **Tabibnia et al. (2026)**, *Neuropsychopharmacology* 51(5):822–830, PMID 41407867. **N=50.**
  Labelling smoking cues vs cue matching: **lower craving, Hedges' g = −0.11** (p<.05); in the older
  subsample **g = −0.29.** → real but very small.
- **Uy et al. (2026)**, *Biological Psychiatry* 99(5), PMID 42092438. **N=193, ages 9–13 at baseline,
  longitudinal fMRI** of amygdala–VLPFC connectivity during negative affect labelling. → **the only
  developmental affect-labelling dataset this project has seen.** High-symptom group showed a
  significantly negative connectivity trajectory.
- **Li et al. (2025)**, *Brain and Behavior* 15(10):e70929, PMID 41058223. N=36 ERP. Affect labelling
  produced smaller LPP than gender labelling.
- **Thampy et al. (2026)**, *Indian J. Psychological Medicine* 48(1):70–77, PMID 40641518. **Protocol
  only, N=24 proposed** — not evidence.

**The honest position, which is better founded than my exclusion:** affect labelling reliably changes
neural and physiological measures, its effects on behavioural and self-report outcomes are **small or
null**, and its one **well-replicated** behavioural finding is a **harm** — it degrades subsequent
reappraisal. **So it stays off the recommended list, but for the right reason.**

**Also flagged: verify our Kircanski citation.** The search surfaced a *different* Kircanski paper
(PMID 41737769, cross-sectional face-emotion labelling). The exposure study this register cites is
presumably Kircanski, Lieberman & Craske (2012), *Psychological Science* — **confirm before citing.**

## 2. Training people to read others' emotions — this exists, and it works better than anything else here

- **Thomson et al. (2026), "Impact VR: Building Socioemotional Resilience in Youth with Conduct
  Disorder," *Prevention Science* 27(2):250–265, PMID 41535527. RANDOMISED CONTROLLED TRIAL,
  110 adolescents with conduct disorder, mean age 13.79, 58% male.** Brief immersive VR
  socioemotional intervention. **Emotion Recognition (ER40) total accuracy d = 0.74, p<.001; sadness
  d = 0.75; fear d = 0.54; anger d = 0.50.**
  → **This is the largest effect on reading other people's emotions anywhere in this project, from an
  RCT, in an adolescent sample.** I excluded the whole other-people half as having "no practice-level
  evidence located." That was wrong.
- **Mojarrad et al. (2026), "Arts-based empathy education in healthcare: a critical systematic
  review," *BMJ Open* 16(4):e110509, PMID 42014151. 17 studies, n=835.** **Theatre interventions mean
  d = 0.83**; poetry **d = 0.49**. Their phrasing: "**Theatre interventions, which emphasised embodied
  learning, showed patterns of large empathy effects.**" → **Embodied practice, large effects, on
  empathy. Directly on this curriculum's premise and completely absent from this ledger until now.**
- **Niazi (2026)**, *Frontiers in Psychology* 17:1762816, PMID 41858454 — hybrid narrative-scoping
  review 2014–2025 of empathy modulation. **Mindfulness programs d = 0.37**; behavioural
  interventions "exhibit the greatest scalability and sustainability."
- **Kirkegaard et al. (2026)**, *BMC Public Health* 26(1):970, PMID 41703515 — mentalization-based
  training, ~100 leaders / 700 employees, five monthly in-person plus four online modules.
  **Quasi-experimental**, so weaker.
- Two case-control studies on empathic accuracy measurement (Meins 2026 UHR psychosis, n=39/40 —
  **no group difference**; Wang 2026 schizophrenia/anhedonia) — measurement, not training.

**And this resolves a tension I could not resolve an hour ago.** Smith 2024 trained facial emotion
recognition inside a 15-lesson multi-skill program and **it did not survive correction** (PAT total
p=.094). Impact VR trained recognition as **the** target and got **d=0.74**. **Dedicated recognition
training works; recognition as one module among fifteen did not move.** That is a dose/focus finding,
not a contradiction.

**Consequence: the other-people half of Lesson 2 has better evidence than the self half in at least
one respect.** Reading others is demonstrably trainable, with medium-to-large effects, in adolescents.
**Retrieve Thomson 2026 and Mojarrad 2026 in full.**

## 3. Coarse vs fine vocabulary — the decision

Darryl: *"if one is the obvious winner, then lets use it. if not, i'll go with coarse since its less
to teach."*

**There is no obvious winner. Going coarse, per his rule.** The evidence, laid out:
- **For coarse:** Torre 2016, **N=20**, one study, fMRI outcome only — "angry" produced more amygdala
  reduction than "irritated" or "enraged," and intensity did nothing.
- **For fine:** no direct evidence. Smith 2024's program used a **fine-grained** valence×arousal grid
  and produced small effects, but it is multi-component and cannot attribute anything to the
  vocabulary. The granularity literature broadly *assumes* finer is better without testing it against
  coarser.
- **Against fine being important at all:** positive granularity has now failed **five** independent
  times; Kalokerinos found **low** granularity went with **more** strategy use that worked less well;
  Hamilton found affect variability predicted where granularity did not.
- **The one number that has actually moved anything:** Widdershoven used **12 named emotions** (8
  negative, 4 positive) and got **d=0.43** on differentiation. **Twelve is the only tested count in
  this project.**

**Decision recorded: coarse. Seven sits just below the only empirically tested count (12) and well
below the fine-grained grids. No evidence contradicts it, and it is less to teach.** Stop treating
this as an open optimisation question.

# Training people to read others' emotions — the wider search, 14 Aug 2026

Darryl: *"see if there are other interventions beyond theatre and vr that improved reading others
emotions."* There are, and the meta-analytic result splits two of his four lesson questions apart.

## The headline: recognition trains well, theory of mind barely trains at all

**Wang CM, Mudiyanselage SPK, Wang PC, Hsu CF & Tseng HH (2026), "Digital Social Cognition Training,"
*Acta Psychiatrica Scandinavica* 153(4):231–256**, PMID 41457665, DOI 10.1111/acps.70060.
**Systematic review and meta-analysis, 21 studies (17 pooled). OPEN ACCESS — retrieve directly.**

| Outcome | g | p |
|---|---|---|
| **Facial emotion recognition** | **0.92** | **<.001** |
| **Empathy** (pre-post) | **0.58** | .04 |
| **Theory of mind** | **0.22** | .05 |

By delivery format: **web-based g = 1.35 · VR g = 0.87 · computerized g = 0.75.**

**This is the most important structural finding for the other-people half of Lesson 2.**
Darryl's four questions were: sense your own emotions · notice them in others · **mentalize** · ask
clarifying questions. **"Notice them in others" (recognition) trains at g = 0.92. "Mentalize" (theory
of mind) trains at g = 0.22.** Those are not the same skill and should not be taught as though they
were.

**The limitation that bounds it: population is adults with schizophrenia-spectrum disorders.** A
recognition deficit is part of the diagnosis, so there is a great deal of room to improve. Consistent
with Bornemann's baseline-dependency result — **the lowest starters gain most** — and with [[O2]],
this is an upper bound, not a general-population estimate.

## Other intervention types that moved reading others, beyond theatre and VR

- **Web-based and computerized emotion recognition training** — the strongest formats in the meta
  above (g = 1.35 and 0.75). **Note the delivery ranking: web-based beat VR.**
- **Online self-training: Piñón-Blanco A, Vergara-Moragues E, López RV et al. (2026), "E-Motional
  Training®," *Drug and Alcohol Dependence* 282:113097**, PMID 41764907. **RCT, N=47**, substance-use
  outpatients, **12 sessions over 3 months.** Total emotion recognition **d = 0.495**, F(1,46)=4.568,
  p=.038; fear **d = 0.341**, p=.047. Trial NCT06514937. *Paywalled (Elsevier).*
- **Group-based social cognitive skills training: Otsuka S, Oe S, Yamada S et al. (2026)**, *Psychiatry
  and Clinical Neurosciences*, PMID 42487254. **Rater-blinded multicentre RCT, N=47**, 6 weeks of
  weekly 2-hour sessions, schizophrenia and/or ASD. **Facial emotion perception improved across
  diagnoses; theory of mind only trend-level, and only in ASD.** Registry UMIN000041619.
  **Same split as the meta: recognition moves, ToM doesn't.** *Paywalled (Wiley).*
- **School-based social problem-solving with SEL: Jin S, Xu S, Zhao Y, Huang H, Zhu H & Zhou C (2025),
  *Behavioral Sciences* 15(12):1708**, PMID 41464051. **Meta-analysis, 19 group-design studies,
  N=741, children with ASD. SPS competence d = 0.53**, with moderate-to-large improvements in emotion
  recognition and theory of mind. **OPEN ACCESS.**
  **And a direct contradiction of something in this ledger: "teacher-led/school-based interventions
  produced stronger effects than researcher-led."** This register currently carries Beelmann et al.
  2014 for the opposite claim (study personnel > teachers). **Unresolved — flag it.**
- **Arts / theatre: Mojarrad et al. (2026), *BMJ Open* 16(4):e110509**, PMID 42014151. 17 studies,
  n=835. **Theatre mean d = 0.83**, poetry **d = 0.49**; "theatre interventions, which emphasised
  **embodied learning**, showed patterns of large empathy effects." **OPEN ACCESS.**
- **Mindfulness for empathy: Niazi (2026)**, *Frontiers in Psychology* 17:1762816, PMID 41858454.
  **d = 0.37**; behavioural interventions have "the greatest scalability and sustainability."
  **OPEN ACCESS.**
- **tDCS (anodal, left DLPFC): Alabbad M, Nuhmani S, Ahmed R et al. (2026)**, *J. Neurodevelopmental
  Disorders* 18(1):14, PMID 41555221. 14 studies, children with ASD. "Shows promise" — **not
  quantified**, small samples, risk of bias. **OPEN ACCESS.** Not usable for this curriculum.
- **AI / robots: Tsapanou A et al. (2025)**, *Brain Sciences* 16(1):56, PMID 41594778. 8 studies,
  variable outcomes, small heterogeneous samples. **OPEN ACCESS.** Adjunct only.
- **Integrative remediation plus skills training: Visser M et al. (2025)**, *Frontiers in Psychiatry*
  16:1688937, PMID 41601483. **Pilot, N=18**, 30 biweekly sessions, 89.4% attendance. ToM r=0.61,
  hostility bias r=0.82. **OPEN ACCESS.** Pilot only.

## A whole class ruled out — useful negative evidence
**Yamada Y, Watanabe N, Tomo Y et al. (2026), *European Psychiatry* 69(1):e43**, PMID 41684115,
PMC13122521. **Network meta-analysis, 60 RCTs, 4,270 subjects.** Verbatim: **"No pharmacological
interventions have demonstrated efficacy for social cognitive impairments in schizophrenia."**
Best non-significant candidates: glycine uptake inhibitor SMD=0.46 [−0.52, 1.44]; stimulants
SMD=0.44 [−0.57, 1.45]. **OPEN ACCESS.** Irrelevant to us directly, but it is a clean demonstration
that this outcome is movable by teaching and not by drugs.

## One source in a NON-clinical sample, which most of the above are not
**Mackey M, Dunne E & Ahern E (2025), "Early Life Adversity & Social Cognition," *J. Child &
Adolescent Trauma* 18(4):925–945**, PMID 41589294. **Meta-analysis, 20 articles, 18 populations,
general adult non-clinical.** Early adversity → theory of mind **zr = −0.247, p=.002**; emotion
recognition **zr = −0.121, p<.001**. **OPEN ACCESS.** Correlational, but it identifies who arrives
with the deficit.

## What this changes
1. **Recognition and mentalizing must be separated in the lesson.** g = 0.92 versus g = 0.22, and the
   same split replicates in Otsuka's RCT.
2. **Delivery format matters and web-based led** (1.35 > 0.87 VR > 0.75 computerized) — which makes
   the practice far more portable than the VR result alone suggested.
3. **Almost all of this evidence is clinical.** Schizophrenia-spectrum, ASD, substance use, conduct
   disorder. The general-population estimate is unknown, and [[O2]] says expect it smaller.
4. **My earlier exclusion of the other-people half was wrong twice over** — first for not searching,
   and second because this is now among the better-evidenced things in the whole project.

# Thomson et al. 2026 — Impact VR. Full text read 14 Aug 2026.

**"Impact VR: Building Socioemotional Resilience in Youth with Conduct Disorder."** Thomson ND,
James JJ, Blondell V, Perera R, Hazlett L, Vrana S. *Prevention Science* (2026) **27:250–265**,
DOI 10.1007/s11121-025-01876-x. **OPEN ACCESS CC-BY.** Preregistered **NCT06301516**,
CONSORT-adherent. `primary text read in full`

**Process failure: I asked Darryl for this paper and it is open access.** He had explicitly said not
to. **Check the licence line before asking for anything.**

## Design
**110 adolescents with conduct disorder, ages 10–17, M = 13.79 (SD 2.33)**, 58% male.
**58% Black, 33% White** — recruited from a public urban healthcare network in Virginia, which the
authors reasonably present as a generalisability strength. Comorbidity high: 33% ADHD, 10% autism,
13% anxiety, 10% PTSD, 16% MDD. Block randomisation with variable block sizes; **baseline assessor
blinded to allocation.** $75 per assessment per respondent. Retention near-perfect: 55/55 and 54/55.

**Intervention: four sessions of ~25 minutes — about 100 minutes total.** Session 1 in lab, the other
three at home. (1) Foundations — basic expressions, where to look (eyes, mouth), mirroring,
static/dynamic tasks, immediate feedback. (2) Cues obscured (masks, sunglasses), regulation
strategies, time pressure. (3) Skills in social settings — role-play, empathy, perspective-taking.
(4) Complex contexts, overlapping signals, de-escalation. Each session ends with a recall task and
"Emotion in Motion," a music-synchronised matching game.

**Control: a single ~20-minute slideshow** — where to direct attention on a face, and the muscle
configurations for happiness, sadness, anger, fear and neutral, with corrective feedback.

## THE PROBLEM DARRYL WOULD CATCH: the doses are not matched, 100 min vs 20 min
The authors state it themselves: "**Because participants in the Impact VR group completed four
sessions compared to one in the control condition, it remains unclear how Impact VR would perform
relative to established treatments, and whether the observed effects reflect unique intervention
mechanisms or simply greater exposure and engagement.**" They call for "dose-matched active controls."

**So this is the same co-intervention/dose confound as the dyad trial.** I praised the active control
without checking that the two arms received comparable amounts. **An active control at one-fifth the
dose is better than a waitlist and is not a matched comparison.**

## Correction to how I reported the result
**There was no significant group × time interaction on ER40 total (p = .373).** The finding is a
**main effect of group** — Impact VR scored **5.23 points higher** on average across timepoints,
F=12.97, **p = .0005, d = 0.74.** Same structure for the subscales: all main effects, **no
interactions** (fear p=.664, sad p=.264, angry p=.157).

| Outcome | Difference | p | d |
|---|---|---|---|
| **ER40 total** | 5.23 | .0005 | **0.74** |
| Sad | 1.52 | <.0001 | **0.75** |
| Fear | 1.30 | .0001 | **0.54** |
| Angry | 0.86 | .0135 | **0.50** |
| Neutral | 0.74 | .0503 | borderline |
| Happy | — | .126 | **ns — ceiling, M=7.73/8** |
| **Peer relationships** | 6.25 | .0015 | **0.58** |
| **Parental relationships** | 7.61 | .0007 | **0.54** |
| **Social stress** | see below | .008 interaction | — |

**Social stress is the one genuine interaction (p=.008), and its shape matters:** no difference
immediately post-intervention (p=.771, **d=0.04**), then **6.66 points lower at 3-month follow-up
(p<.001, d=0.53).** The authors read this as needing time for skill transfer — consistent with
generalisation models. **A benefit that appears only at follow-up, having been absent at post-test.**

## Conflict of interest — declare it whenever this is cited
**"Dr. Nicholas Thomson is the founder and has an ownership interest in Arche XR, LLC, the
small-business sponsor for this project."** Funded by NIH R41MH133540 (an SBIR-type award). The
developer owns the company, and the company sponsored the trial. Declared openly. Same category as
the Singer/Humanize disclosure — **not disqualifying, but it belongs next to the effect size.**

## What their reference list gives us that this project has been missing

**A non-clinical emotion-recognition training study, which I said did not exist:**
**Reed Z, Suddell S, Eastwood A, Thomas L, Dwyer I, Penton-Voak IS, … Attwood AS (2023), "Assessing
the effectiveness of online emotion recognition training in healthy volunteers," *Royal Society Open
Science* 10(9):230372.** **HEALTHY VOLUNTEERS. Open access. Retrieve directly — do not ask.**

**And an outcome study, not just a skill study:**
**Wells AE, Hunnikin LM, Ash DP & van Goozen SHM (2021), "Improving emotion recognition is associated
with subsequent mental health and well-being in children with severe behavioural problems,"
*European Child & Adolescent Psychiatry* 30(11):1769–1777.** → **the only source seen so far linking
improved recognition to a wellbeing outcome.** High priority.

**Plus, on brief formats — single-session recognition training reportedly works:**
Dadds et al. 2006 (*BJPsych*, fear recognition, CU traits); Muñoz Centifanti et al. 2021
(*Brain Sciences* 11:1342); Hunnikin, Wells, Ash & van Goozen 2022 (*Development and
Psychopathology* 34(1):85–93, "Can facial emotion recognition be rapidly improved in children with
disruptive behavior?"); Hubble et al. 2015 (*PLoS ONE* 10(6):e0132035, "Improving negative emotion
recognition in young offenders reduces subsequent crime"); Preis et al. 2025 (*BJCP*, depression).
**Note the Thomson authors' own caveat: "Prior studies using static or slideshow-based training
methods have shown limited or short-term effects."**

**Two meta-analyses on the delivery format, both cited and neither in this ledger:**
- **Farashi S, Bashirian S, Jenabi E & Razjouyan K (2024)**, "Effectiveness of virtual reality and
  computerized training programs for enhancing emotion recognition in people with autism spectrum
  disorder: A systematic review and meta-analysis," *Int. J. Developmental Disabilities* 70(1):110.
- **Zhang F, Zhang Y, Li G & Luo H (2024)**, "Using virtual reality interventions to promote social
  and emotional learning for children and adolescents: A systematic review and meta-analysis,"
  *Children* 11(1):41. **Open access.**

## Honest summary for the practice map
**Reading others' emotions is trainable in adolescents in about 100 minutes, at d = 0.74 on a
standardised recognition task, with peer and parent relationship gains around d ≈ 0.55 and a social-
stress benefit that emerges by three months.** Caveats that must travel with it: **conduct-disorder
sample; control received one-fifth the dose; the recognition effect is a group main effect rather
than a differential change; happy faces were at ceiling; the developer owns the product; and nothing
is known beyond three months.**

# Simpler treatments for reading others' emotions — abstracts read verbatim, 14 Aug 2026

Darryl: *"dont index on vr. i want to see if there are simpler treatments with similar results."*
**Yes. Plain computerised training matches or beats the VR result on outcomes that matter more — and
the whole picture collapses in healthy volunteers.**

## The simple interventions, and they reach real-world outcomes

**Hubble K, Bowen KL, Moore SC & van Goozen SHM (2015), "Improving Negative Emotion Recognition in
Young Offenders Reduces Subsequent Crime," *PLoS ONE* 10(6):e0132035**, PMID 26121148,
**OPEN ACCESS (PMC4486167).**
**n=50 juvenile offenders** — 24 trained, 26 controls **matched on age, SES, IQ and lifetime crime
level**; all received statutory interventions. Plain **facial affect training**, no VR.
Verbatim: "After the training **fear, sadness and anger recognition improved significantly**… Although
crime rates dropped in all offenders in the 6 months following emotion testing, **only the group of
offenders who had received the emotion training showed a significant reduction in the severity of the
crimes they committed.**" Their own summary: "emotion recognition can be **relatively easily
improved.**"
**This is an actual behavioural outcome — crime severity — not a test score. Stronger than anything in
the VR trial.**

**Wells AE, Hunnikin LM, Ash DP & van Goozen SHM (2021), "Improving emotion recognition is associated
with subsequent mental health and well-being in children with severe behavioural problems,"
*European Child & Adolescent Psychiatry* 30(11):1769–1777**, PMID 32997168, **OPEN ACCESS
(PMC8558267).**
**n=62 children aged 7–10** with severe family adversity and behavioural problems. **Brief
computerised** training given only to the 40 who were impaired; the 22 unimpaired continued usual
care. **Teachers blind to allocation** rated mental health before and **6 months after.**
Verbatim: participants who trained "significantly improved their recognition of negative and neutral
facial expressions. Although both groups showed improved behaviour at follow-up, **the reduction in
behavioural problems was only significant in children who received the emotion training.
Post-training emotion recognition scores predicted mental health problems 6 months later
independently of initial emotion recognition ability and severity of behavioural problems.**"
Their caveat: "**further research using fully randomised designs is needed before causal conclusions
can be drawn with confidence.**"

**Hunnikin LM, Wells AE, Ash DP & van Goozen SHM (2022), "Can facial emotion recognition be rapidly
improved in children with disruptive behavior? A targeted and preventative early intervention study,"
*Development and Psychopathology* 34(1):85–93**, PMID 33432899. **Not open access.**
**n=92** children (trained n=54, mean age 8.72; comparison n=38, mean 8.95). Computerised training,
reassessed **8 weeks** later with concurrent eye tracking.
**The mechanism finding, and it overturns the most intuitive teaching move:** "Children who completed
the training significantly improved in emotion recognition; **eye gaze did not contribute to
impairment or improvement** in emotion recognition. **The training works by improving children's
ability to appraise emotional stimuli rather than by influencing their visual attention.**"

**Dadds MR, Perry Y, Hawes DJ, Merz S, Riddell AC, Haines DJ, Solak E & Abeygunawardane AI (2006),
"Attention to the eyes and fear-recognition deficits in child psychopathy," *British Journal of
Psychiatry* 189:280–281**, PMID 16946366. **Not open access.** Two pages.
**The simplest intervention on record:** the fear-recognition deficit "can be **temporarily corrected
by simply asking them to focus on the eyes of other people.**" **But: temporary; no control condition
described in the abstract; no effect sizes; and Hunnikin 2022 above found eye gaze does not explain
training gains.** So the appealing one-line instruction has the weakest support and a contradicting
mechanism study.

## And here is the finding that bounds all of it — the healthy-volunteer result is near-null

**Reed ZE, Suddell S, Eastwood A, Thomas L, Dwyer I, Penton-Voak IS, Jarrold C, Munafò MR & Attwood AS
(2023), "Assessing the effectiveness of online emotion recognition training in healthy volunteers,"
*Royal Society Open Science* 10(9):230372**, PMID 37771966, **OPEN ACCESS (PMC10523077).**
**Three online studies, one training session each, healthy volunteers, active vs sham control.**

| Study | Design | n | Effect on total correct hits |
|---|---|---|---|
| 1 | four-emotion training (angry, happy, sad, scared) | 101 | **b = 0.02 [−0.02, 0.07], p = 0.27 — null** |
| 2 | six-emotion training (adding disgusted, surprised) | 109 | **b = 0.07 [0.03, 0.12], p = 0.002 — small** |
| 3 | generalisation to untrained faces | 120 | b = −0.01 [−0.05, 0.02] — **improvement generalised** |

Their own conclusion is appropriately hedged: "Our results indicate improved ER (**as measured by our
task**), which generalizes to different facial stimulus sets. Future studies should further explore
generalizability, longer-term effects and ERT **in populations with known ER difficulties.**"

## The pattern, stated plainly

**In impaired populations — juvenile offenders, children with severe behavioural problems, conduct
disorder — plain computerised emotion-recognition training works, quickly, and reaches real outcomes:
crime severity down, behavioural problems down, mental health predicted six months out.**

**In healthy volunteers, the same kind of training produced b = 0.07 on one study and nothing on
another.**

**This is [[O2]] again, and it is the decisive caveat for a general-audience curriculum.** The
impressive numbers all come from people who started with a deficit — which also matches Bornemann's
baseline-dependency result. **Whatever this lesson teaches about reading others, the honest promise
for a general reader is small.**

## Three consequences for the lesson
1. **VR is not required.** Plain computerised training gets equal or better outcomes with far less
   apparatus, and two of the four studies reached behaviour rather than test scores.
2. **Do not teach "look at the eyes" as the mechanism.** It is the simplest and most attractive
   instruction, its only support is a two-page 2006 paper with a temporary effect, and the 2022
   mechanism study found gaze irrelevant. **What improved was appraisal, not where they looked.**
3. **Design weakness common to the van Goozen studies: allocation by impairment status, not
   randomisation.** Trained groups were the impaired ones; comparison groups were not impaired. The
   authors say so. Hubble at least matched on age, SES, IQ and prior crime.

## Retrieval status
**Open access, will retrieve directly:** Hubble 2015 · Wells 2021 · Reed 2023.
**Paywalled, low priority given the abstracts already answer the question:** Hunnikin 2022 (want the
appraisal-vs-gaze analysis in full) · Dadds 2006 (two pages, probably not worth it).

# Israelashvili et al. 2019 — full text read 14 Aug 2026. The bridge between the two halves of Lesson 2.

**"Knowing me, knowing you: emotion differentiation in oneself is associated with recognition of
others' emotions."** Israelashvili J, Oosterwijk S, Sauter D & Fischer A. *Cognition and Emotion*
(2019), DOI 10.1080/02699931.2019.1577221. **OPEN ACCESS CC-BY.** University of Amsterdam.
**No conflict of interest declared.** `primary text read in full`

**This is the paper that would justify teaching self-awareness and other-awareness in one lesson. The
honest size of that link is 4–10% of variance, correlational, direction unknown.**

## What was measured
**Emotion differentiation (ED)** — the Erbas et al. 2014 task. Rate 20 IAPS pictures on **20 negative
emotion words** (anger, anxiety, depression, disgust, embarrassment, envy, fear, guilt, inferior,
irritation, jealousy, loneliness, nervousness, rage, regret, sadness, shame, unhappiness, worry),
0–6 each, untimed. The index is the **intraclass correlation across a person's own ratings, reversed**
— high consistency across different pictures means low differentiation.
**Crucial definitional point, in their words: "emotion differentiation does not refer to the richness
of one's emotion vocabulary per se, but rather to the adequate and differentiated use of emotion
words targeted to specific situations."**
→ **This supports the coarse decision.** What is being measured is *using words discriminatingly*,
not *knowing many words*. Seven words used well is the thing this construct actually tracks.

## Study 1 — N = 363 (399 tested, ~10% excluded for uninterpretable negative ICCs)
First-year psychology students, **mean age 19**, 32% men. Observed power 0.81.
ER measure: **AERT**, 24 deliberately **low-intensity** photos (to avoid ceiling), six negative
emotions, chance 17%.

**Result: β = .145, b = 4.965 (SE 1.766), p = .005. Whole model R²adj = .043 — the model explained
4% of the variance in emotion recognition**, F(2,361)=9.131, p<.001. Bootstrapped, 5,000 samples.
Also: **ED correlated with verbal IQ, r = .118 [.013, .231], p<.05.**
An unexpected **order effect**: recognition scores were higher when the ER test came first (β=.156,
p=.003) — they attribute it to concentration, and fixed the order in Study 2.

## Study 2 — N = 217, PREREGISTERED (osf.io/y76rq)
**MTurk, US citizens, mean age 37 (SD 12), 47% men** — deliberately a different population. $3.
Three recognition tests, ER always first:

| Test | Cue | β [95% CI] | R²adj |
|---|---|---|---|
| **AERT** | face | **.250 [.120, .380]** | **.06** |
| **GERT** | face, body **and voice**, 14 emotions, chance 7% | **.235 [.104, .366]** | **.05** |
| **RMET** | **eyes only**, 4 word options, chance 25% | **.322 [.195, .450]** | **.104** |

All p < .001. **ED × verbal IQ was stronger here: r = .298 [.126, .449], p < .001.**

**Their preregistered hypothesis failed.** They predicted ED would matter most when the least
emotional information was available (RMET, eyes only). **It did not** — differences between the three
correlations were not significant, all Z < −1.5, ns. They read the null as a strength: the link
"does not rely on the specific type of task or use of more or less complex emotion labels."
**And controlling for verbal IQ, the association survived only for RMET and AERT — not GERT.**

## What the authors themselves say about the size
**"This effect was small, but robust across two samples of participants with different cultural
backgrounds, language, and age."**

## Limitations, in their words — the first one is decisive for us
1. **"The use of a correlational design allowed us to establish the relationship… However,
   experimental research will be needed to illuminate whether emotion differentiation predicts
   emotion recognition or vice versa."** → **Direction unknown. This cannot support "learn to name
   your own feelings and you will read others better."** It supports only that the two travel together.
2. **Only negative emotion differentiation was measured** — "there is presently no validated measure
   of positive emotion differentiation." → **Another entry for the positive-granularity gap**, which
   has now failed or been unavailable in six places in this project.
3. **All expressions were posed by actors.** They cite Sauter & Fischer 2018 that posed and
   spontaneous recognition overlap "considerably," but flag real-life expressions as needed.

## How this changes the lesson
**It justifies teaching both halves in one lesson, and it does not justify claiming one causes the
other.** The honest sentence is: *people who make finer distinctions among their own feelings also
tend to read others more accurately — a small but replicated association, direction not established.*

**And note what it does NOT say.** It is not an intervention. Nobody was trained. Compare with the
training evidence, where the causal claim is available but the population is impaired:
- **Israelashvili: general population (students, MTurk adults), correlational, 4–10% of variance.**
- **Hubble / Wells / Hunnikin / Thomson: causal, real outcomes, but juvenile offenders, children with
  severe behavioural problems, conduct disorder.**
- **Reed: general population, causal, and near-null (b = 0.07, and one null).**
**The three do not overlap. There is no study that is causal, general-population, and substantial.**
That is the cleanest statement of the evidence position for this lesson, and it should be said plainly
rather than papered over.

# Mentalizing — I was wrong to exclude it, and wrong about why. Searched 14 Aug 2026.

Darryl: *"most people can mentalize. look at MBT therapy or DBT. in impaired populations it can be
taught."*

**Both points correct.** I dismissed an entire established treatment modality on the strength of one
meta-analytic subgroup number (Wang 2026's ToM g=0.22 in schizophrenia-spectrum), without searching.
**And I made a ceiling error I had already caught elsewhere in the same review** — I flagged
Thomson's happy faces as unmovable because they started at 7.73/8, then read a small mentalizing
effect as evidence of untrainability rather than of a high floor.

## MBT does move mentalizing — modestly, inconsistently, and in clinical populations

- **Weijers JG, Debbané M, Ten Kate C, van Kaam F, de Winter R, Eurelings-Bontekoe E & Selten JP
  (2026), "Long-term effects of mentalization-based treatment for psychotic disorder: a 5-year
  follow-up of a multi-center, randomized-controlled trial," *Psychological Medicine* 56:e12**,
  PMID 41508857, **OPEN ACCESS (PMC12885340).** N=46 completers at 5 years (23 MBTp / 23 TAU).
  Verbatim: "MBT patients also showed a greater improvement in one aspect of mentalizing,
  **understanding of social causality** [ηp² = 0.17, p = .04], **but not other aspects of
  mentalizing.**" Other domains (SCORS, Hinting Task) unchanged.
- **Shin H, Choi W, Chung YS et al. (2026)**, pilot RCT of MBT vs structured clinical management for
  BPD outpatients, South Korea, *Borderline Personality Disorder and Emotion Dysregulation*,
  PMID 42421108. Both arms reduced suicide attempts over 12 months with **no between-group difference
  on the primary outcome**; MBT showed "consistent and sustained improvements in depressive symptoms,
  **mentalization difficulties**, and resilience." **No effect sizes given in the abstract.**
- **Spollen T, Byrne G, Hevey D & Longphuirt EN (2026), "Mentalization-Based Therapy for Children and
  Families: A Systematic Review and Meta-Analysis of the Recent Literature," *Clinical Child
  Psychology and Psychiatry* 31(3):861–898**, PMID 42029892. 19 studies. On parental reflective
  functioning (PRFQ): **"small, non-significant effects, with high heterogeneity across studies,"**
  and **"the evidence remains inconclusive regarding PRF as a primary mechanism of change."**

## DBT's evidence is on outcomes, not on mentalizing capacity
- **Kweon K (2026)**, *J. Korean Academy of Child and Adolescent Psychiatry* 37(1):33–43,
  PMID 41523205, open access: **"dialectical behavior therapy (DBT) had the strongest empirical
  support (high-certainty evidence) for reducing adolescent NSSI,"** while MBT "offered promising
  mechanism-specific approaches" but its NSSI evidence was "preliminary or uncertain."
- **Tan J & Zhang L (2026)**, *Alpha Psychiatry* 27(2), PMID 42110902: DBT "showed the most consistent
  efficacy in reducing NSSI frequency and improving emotion regulation."
- **Cai M, Song X & Tong J (2026), *Frontiers in Psychiatry* 17:1833555**, PMID 42368806.
  **Meta-analysis, 12 RCTs, N=844 adolescents with BPD**, covering DBT-A, MBT-A, CAT, ERT, UP-A.
  BPD symptom severity **SMD = −0.27 [−0.47, −0.06]** (k=8, n=636); emotion regulation difficulties
  **SMD = −0.26 [−0.48, −0.04]** (k=5, n=304). **Mentalizing was not an outcome.**

**So: DBT is the better-evidenced treatment, and its evidence is on self-injury and emotion
regulation — not on mentalizing capacity. Do not cite DBT as proof that mentalizing is trainable;
that step is not measured.**

## The revised position, which is better than either of mine
1. **Mentalizing is trainable.** MBT is an established treatment and two RCTs show movement on
   mentalizing measures. **My exclusion was wrong.**
2. **Where mentalizing itself is measured, the effect is partial** — one domain of several at 5 years
   (ηp²=0.17), non-significant in the parental-RF meta-analysis. The treatments demonstrably move
   symptoms more reliably than they demonstrably move mentalizing.
3. **Every population here is clinical**: borderline personality disorder, psychotic disorder,
   adolescent self-injury. **MBT exists because mentalizing collapses under attachment stress in
   these groups. That is not the general reader.**

## What this changes for Lesson 2 — a different design instruction, not a different verdict
**The lesson's job is not to build the capacity. It is to prompt its use.**
Darryl's framing is the right one: most readers already mentalize. The evidence base for *training*
mentalizing exists for people whose capacity is impaired, and its results there are modest and
domain-specific. **So Lesson 2 should not promise to make anyone better at mentalizing.** What it can
do is give a reader a reason and an occasion to do it deliberately — which is the same shape as the
Bornemann finding that *actively consulting* the body (Body Listening, d=0.40) moved while *passive
sensitivity* (Noticing, p=.44) did not.

**Consistent pattern across this entire lesson's evidence: deliberate use moves; passive capacity
does not need building.**

**And this rehabilitates asking clarifying questions as the vehicle.** A question is the occasion for
mentalizing, not a substitute for it. **Still no trial located for question-asking specifically — and
per the standing rule, that is an unsearched absence, not a demonstrated one.**

# Emotionally Focused Couple Therapy — searched 14 Aug 2026, two passes

Darryl: *"research Emotion Focused Couples therapy / EFT. lots of evidence there. look for robust
designs with third party video rating as well."*

**Method note worth keeping.** My first query returned "**NO STUDIES IDENTIFIED**" for observer-coded
couple interaction. **That was a search artifact, not an absence** — Europe PMC indexes the
*Journal of Marital and Family Therapy* thinly and my terms didn't match how these papers describe
themselves. A second query naming the actual coding systems (SPAFF, RMICS, Experiencing Scale,
softening) found them immediately. **Two queries, opposite answers. Never report a null from one
search.**

## The RCT evidence for EFCT

- **Sandberg J, Anderson S, Calatrava M, Greenman PS, Lafontaine MF, Andrade-Urbina D,
  Sambuceti-Lewis A, Osorio A, Cueli-Naranjo MA, Steffen P & Rodríguez-González M (2026),
  "A Randomized Controlled Effectiveness Trial of Emotionally Focused Couple Therapy in Five
  Spanish-Speaking Countries."** Argentina, Costa Rica, Guatemala, Mexico, Spain. **70 couples / 140
  individuals**, EFCT vs waitlist, **18–20 sessions, 17 community-based therapists.** Preregistered
  on ClinicalTrials.gov.
  **Dyadic adjustment dGMA = 1.09 · relationship satisfaction dGMA = 0.72 · attachment avoidance
  dGMA = −0.31 · attachment anxiety not significant.**
  **⚠ PsyArXiv PREPRINT (DOI 10.31234/osf.io/sx5j4_v2) — not peer reviewed. Flag this whenever cited.**
- **Mirzazade Z, Molazade J, Hadianfard H & Taghavi M (2025)**, "The effect of emotionally focused
  couple therapy (EFCT) on shame and intimacy in couples: a randomized controlled trial,"
  *BMC Psychology* 13(1):1111, PMID 41057959, **open access.** **Only 26 couples (13/13)**; results
  reported as "p < 0.05" with **no effect sizes.** Weak.
- **White VanBoxel JM, Miller DL, Morgan P, Iqbal N, Edwards C & Wittenborn AK (2024)**, "Exploring
  associations among baseline emotion regulation and change in relationship satisfaction among
  couples in a randomized controlled trial of emotionally focused therapy compared to usual care,"
  *Family Process* 63(3):1637–1654, PMID 38462780, open access via Unpaywall.
  **Directly relevant to this curriculum's logic:** "Baseline emotion regulation difficulties were
  associated with lower initial relationship satisfaction. **However, baseline emotion regulation
  difficulties were not associated with change in relationship satisfaction** over the course of
  treatment and this relationship **did not differ by treatment group.**" Their conclusion: "partners
  with diverse presentations of emotion regulation at baseline may benefit from couple therapy."
- **Aardal et al. (2025)** — CBT vs EFT for depression in routine care, **n=111 (55/56): no
  significant between-group differences**, d = 0.56 overall improvement.
- **Wiebe et al. (2025)** — EFIT (individual) for depression/anxiety, n=88 vs waitlist.

**Cited but not retrievable: "Spengler et al., 2024"**, named in the Sandberg abstract as the
evidence base for EFCT. **Neither Europe PMC query surfaced it and I do not have its title.**
Per the standing rule, an unnamed paper does not go on any list. **Ask Darryl or find the title.**

## Third-party video coding — it exists, and here it is

- **Myung HS, Furrow JL & Lee NA (2022), "Understanding the emotional landscape in the withdrawer
  re-engagement and blamer softening EFCT change events," *Journal of Marital and Family Therapy*
  48(3):758–776**, PMID 35191060, DOI 10.1111/jmft.12583. **Paywalled.**
  **Video-recorded EFCT sessions, coded for in-session emotional states, with sequential pattern
  analysis.** Finding as reported: **adaptive grief/hurt unique to withdrawer re-engagement; rejecting
  anger distinguishing blamer softening.** → **This is the closest thing found to third-party coded
  emotional expression inside a real therapeutic interaction. Retrieve in full.**
  ⚠ The abstract came back **paraphrased, not verbatim** — do not quote until the paper is read.
- **D'Aniello C, Anderson SR & Tambling RR (2021), "Psychotherapeutic processes associated with couple
  therapy discontinuance: An observational analysis using the rapid marital interaction coding
  system," *JMFT* 47(4):891–908**, PMID 33470425. **Paywalled.** Coding system: **RMICS (Rapid Marital
  Interaction Coding System).** Finding: "the absence of positive interactions is linked to therapy
  discontinuation" for female partners specifically.
- **Zamir O, Adar O, Cohen DB, Goldberg C, Regev GM & Shapira M (2025), "Intergenerational
  Transmission: Observed Negative Communication Mediates Dyadic Associations Between Childhood
  Maltreatment and Marital Quality," *Family Process* 64(3):e70059**, PMID 40792455. **OPEN ACCESS.**
  **Video-recorded 10-minute couple conflict discussions, observationally coded for negative
  communication.** Not EFT, but it is a clean example of the design Darryl is asking for, and it is
  freely available. **Retrieve directly.**

**Inter-rater reliability was not reported in any of the returned records.** Must be read from the
papers themselves before any of this is cited as methodologically strong.

## What EFCT does and does not give Lesson 2

**Does not give us a practice.** EFCT is **18–20 sessions of therapist-delivered couple work.** It is
not a self-directed exercise and cannot be recommended as a Lesson 2 practice. Its outcomes are
relationship satisfaction, dyadic adjustment and attachment avoidance — not emotional awareness.

**Three things it does give us:**
1. **The measurement precedent Darryl is asking for.** Couple research routinely video-records
   interaction and codes it with published systems (RMICS, SPAFF). **Nothing in this project's
   awareness evidence does this** — it is all questionnaires, lab tasks and one skin-conductance
   paradigm. **This is the methodological gap in Lesson 2's evidence base, now with a concrete model
   for what would close it.**
2. **Myung 2022's specific emotions at the turning point** — grief and hurt in withdrawer
   re-engagement, rejecting anger in blamer softening. If that survives full reading, it is evidence
   about *which* emotions matter at the moment a relationship shifts, from coded video rather than
   self-report.
3. **White VanBoxel 2024 cuts against a sequencing assumption in this curriculum.** Baseline emotion
   regulation **did not predict who improved**. If awareness/regulation skill is not a prerequisite
   for relational benefit, that weakens any claim that Lesson 2 must come before relational work —
   though it says nothing about whether Lesson 2 *adds* to it.

## Still owed
**The question-asking search.** Offered last turn, not yet run. Not started, not a null — outstanding.

# Spengler et al. 2024 — the EFCT meta-analysis. FULL TEXT READ 14 Aug 2026.

**"A Comprehensive Meta-Analysis on the Efficacy of Emotionally Focused Couple Therapy."**
Spengler PM, Lee NA, Wiebe SA & Wittenborn AK. *Couple and Family Psychology: Research and Practice*
(2024) **13(2):81–99**, DOI 10.1037/cfp0000233. Online first 22 Sep 2022.
**"The authors have no conflict of interest to disclose."** `primary text read in full`
This is the paper cited as "Spengler et al., 2024" in the Sandberg abstract, which I could not name.

**20 studies, 332 couples** (19 studies / 308 couples in the main analysis). Johnson's model only —
deliberately **not** conflated with Greenberg & Goldman's emotion-focused couple therapy, which is a
different model. Includes RCTs, quasi-experimental and one dissertation.

## The three headline effects

| Analysis | k | d | 95% CI | Heterogeneity |
|---|---|---|---|---|
| **Pretest–posttest** | 19 | **0.93** | [.75, 1.12] | I² = 56.8, Q(18)=41.69, p=.001 |
| **EFT vs viable alternative treatment** | 6 | **0.44** | [.03, .85] | homogeneous, I² = 38.5 |
| **Pretest to follow-up** (2–24 months) | 10 | **0.86** | [.56, 1.15] | **I² = 73.2 — considerable** |

Their own caution on the third: "**any interpretation of EFT gains being enduring should be viewed
tentatively** as other factors may account for these results (e.g., attrition bias, time of
follow-up)."

**Their translation into plain terms:** "A d of .93 means that couples who participate in EFT under
experimental conditions… are on average **better off than 81% of couples who do not receive
treatment**," which converts to **70% of couples successfully treated.**

## THE NUMBER TO CARRY ACROSS THIS ENTIRE PROJECT — efficacy to effectiveness shrinkage
**Mitchell & Spengler (2022)**, naturalistic delivery of EFT in routine clinical settings, **7
therapists, 11 couples, 18 months: d = 0.46.**
Against the meta-analytic efficacy estimate of **d = 0.93. Roughly half.**
Spengler's words: "**Such shrinkage in effect size from efficacy to effectiveness studies is common**
and should lead practitioners to be cautious in assuming the findings from this EFT meta-analysis
will generalize to their clinical practice."

**This is the general lesson for every practice in Lesson 2.** Bornemann's d=0.72, Widdershoven's
d=0.43, Thomson's d=0.74 were all produced under trial conditions — supervision, fidelity checks,
payment, monitoring. **Expect roughly half of that in ordinary use.** Cite this whenever a number
from this project is put in front of a reader.

## What the outcome actually was — and it bounds everything above
**"The dependent measure for all studies assessed couple satisfaction"** — DAS or RDAS, only.
**So the therapy most identified with emotion in relationships has no meta-analytic evidence that it
changes emotional awareness, emotional expression, or observed behaviour. Only self-reported
relationship satisfaction.** Same measurement limitation this project keeps hitting.

## Moderators — three that matter to us

**1. Fidelity, and it is checked by videotape.** Percentage of sessions checked for fidelity with
feedback predicted larger effects, **Q(17) = 6.19, p < .05**; the categorical test approached
significance, Q=9.25, **p=.06**. The extremes are striking: **videotape review only, d = 1.63;
supervision only, d = 0.62.** The two highest-fidelity studies were **Lee et al. 2017** (bug-in-ear,
live mirror, videotape; d=1.39) and **McLean et al. 2013** (Sue Johnson supervised 25% of videotaped
sessions; d=1.63). Authors caution k=2 and overlapping CIs.
And on durability: therapists with **study-specific EFT training** produced better follow-up effects
(**d = 1.17**) than therapists with only prior EFT experience (**d = 0.57**), Q(1)=4.80, p=.03.
→ **This is the answer to Darryl's video question, with an important qualification: video coding here
is used to check the therapist's fidelity, not to measure the client's emotional behaviour.**

**2. More sessions produced LESS benefit**, Q(1) = 5.48, p < .05. Mean 13.89 sessions, range 6–31.
The authors inspected the longest-treatment studies and found comorbid sexual abuse, trauma, PTSD and
MDD — **so this is confounded with severity, not evidence that shorter is better.** Session *length*
(60/75/90 min) was unrelated, Q=0.92, p=.39.

**3. A methodological artifact inside the headline number.** Unit of analysis was a significant
moderator, Q(2)=6.32, **p=.04**: studies averaging couple scores gave **d = 1.10**; studies using
couples' individual scores gave **d = 0.68.** Most EFT studies did not use dyadic methods accounting
for interdependence. **The true effect is likely nearer the lower figure.**

## Where EFCT is methodologically stronger than several sources in this ledger
- **Researcher allegiance did not inflate results.** Studies from outside Johnson's lab produced
  **higher** effects (d = 1.01) than those from inside (d = 0.89), ns. "Tentatively dispelling notions
  of researcher allegiance or bias." **Worth contrasting with Thomson owning Arche XR and Lane owning
  the electronic LEAS.**
- **No publication bias.** Fail-safe N = 1,180 studies; Egger's t(17)=0.51, p=.66; symmetric funnel.
- **Design and study quality did not moderate** — RCT d=0.91 vs quasi-experimental d=0.96, p=.80.
- **Two outliers removed** by Tukey rule (Najafi 2015 d=5.72; Solymani ahmadi 2014 d=6.49). Including
  them would have given d=1.30. **This is why Beasley & Ager's 2019 g = 2.09 is inflated — they kept
  them.**

## Limitations the authors state
- 20 studies, **mean 14.3 couples per study.** Low power for moderators; nearly all between-study.
- Participants "predominantly **White, middle-class, and moderately to mildly distressed**, and are, or
  are presumed to be, **cisgender, heterosexual** couples." Only 7 studies reported race at all.
- **Initial distress did not predict response** (Q=0.88, p=.35) — which contradicts Rathgeber 2018 and
  Roddy 2020, both of whom found greater pretest distress predicted greater gains. **Unresolved
  disagreement between meta-analyses; note it rather than picking a side.**

## Verdict for Lesson 2
**Confirms the earlier judgment: EFCT is not a Lesson 2 practice** — 18–20 therapist-delivered
sessions, and the outcome is relationship satisfaction. **But it supplies the effectiveness-shrinkage
figure (0.93 → 0.46), which belongs in the front matter of the claims register and applies to every
practice we recommend.**

# Three corrections to my own Spengler write-up — 14 Aug 2026

Darryl: *"you cannot say expect roughly half as a generalization. you are making far too many leaps
and inferences. are you sure about the video scoring? several studies do this. you keep saying right
or wrong without understanding why one group included or didn't include certain studies."*

## 1. RETRACTED: "expect roughly half" as a project-wide rule
**What I wrote:** that d 0.93 → 0.46 "applies to every number I've given you today," naming
Bornemann, Widdershoven and Thomson.

**Why it was wrong, on four counts:**
- The source is **one naturalistic pilot: Mitchell & Spengler 2022, 7 therapists, 11 couples.**
  No confidence interval is reported in Spengler's text. A single pilot at n=11 couples cannot
  support a numeric deflation rule for anything.
- **Spengler's actual claim is qualitative** — shrinkage "is common." I converted that into a
  quantity.
- **The mechanism does not transfer.** Spengler's own moderator analysis locates EFT's efficacy in
  *therapist fidelity and study-specific training*. Bornemann's body scan, Widdershoven's self-rating
  app and Thomson's self-guided VR have **no therapist whose adherence could drift.** The main engine
  of the shrinkage is largely absent from those designs.
- **It is one treatment in one field.** Nothing licenses exporting it to interoceptive-awareness
  training or emotion-recognition training.

**What can honestly be said:** efficacy-to-effectiveness shrinkage is a recognised phenomenon in
psychotherapy research, and Spengler reports one small pilot consistent with it for EFT.
**The magnitude in any other context is unknown, and no multiplier should be applied to any number in
this register.**

## 2. WRONG: "video coding measures the therapist, not the client"
**I contradicted this ledger's own entry from two turns earlier.** Client-behaviour coding is
routine in this literature and I had already recorded three examples:
- **D'Aniello, Anderson & Tambling 2021** — **RMICS**, coding *couples'* interaction behaviour.
- **Zamir et al. 2025** — video-recorded 10-minute couple conflict discussions, coded for negative
  communication. *Couples*, not therapists.
- **Myung, Furrow & Lee 2022** — coded *clients'* in-session emotional states across EFCT change
  events.
Spengler's reference list adds more process work of this kind, e.g. **Dalgleish, Johnson, Burgess
Moser, Wiebe & Tasca 2015, "Predicting key change events in emotionally focused couple therapy,"
*JMFT* 41(3):260–275**, and **Makinen & Johnson 2006** on attachment-injury resolution.

**Why none of it appears in Spengler, and this is the point I missed:** their exclusion criteria say
a study was excluded if "**it was not an efficacy outcome study (e.g., process research**,
effectiveness study, case application, theoretical or conceptual article)." **Process research is
precisely where client-behaviour coding lives, and Spengler excluded it by design.** The absence in
that meta-analysis is a scope decision, not a feature of the field.

**Corrected statement:** in Spengler's *moderator analysis*, videotape is used to verify therapist
fidelity. **Separately, a substantial body of couple process research codes client emotional
behaviour from video.** Those are two different uses of video and I collapsed them.

## 3. UNJUSTIFIED: calling Beasley & Ager "wrong"
**What I wrote:** "Beasley & Ager's 2019 g = 2.09 is wrong; they kept them."

**That is Spengler's framing repeated as fact.** The disagreements are defensible methodological
choices on both sides:
- **Outlier removal is contested.** Spengler applied the Tukey/Hoaglin–Iglewicz labeling rule — a
  convention, not a truth. Dropping studies *because their effects are large* can bias an estimate
  downward. Beasley & Ager's choice to retain all RCTs meeting their standard is a legitimate
  alternative.
- **The two removed studies are both Iranian** (Najafi et al. 2015; Solymani ahmadi et al. 2014).
  **Spengler does not discuss this.** Systematically excluding non-Western studies on the grounds
  that their effects are large deserves examination, particularly in a meta-analysis that criticises
  the field for a White, middle-class, cisgender-heterosexual participant base.
- **Design breadth cuts both ways.** Spengler included quasi-experimental studies and a dissertation,
  which broadens coverage but relaxes design rigor. **Beasley & Ager's RCT-only rule is the more
  conservative choice on design.** Spengler is more conservative on outliers; Beasley & Ager are more
  conservative on design. Neither dominates.
- **Same for Rathgeber et al. 2018.** Spengler calls conflating Johnson's and Greenberg & Goldman's
  models an "oversight." **Rathgeber may have a stated rationale for treating them as one family.
  I have not read Rathgeber and cannot adjudicate this.**

**Rule reaffirmed (same failure as the Webb / Augustine & Hemenover exchange earlier in this
project): when meta-analyses disagree, record the disagreement and the reasoning on each side.
Do not adopt the most recently read author's framing as the verdict.**

# Rathgeber et al. 2018 — FULL TEXT READ 14 Aug 2026. Adjudicating the Spengler dispute.

**"The Efficacy of Emotionally Focused Couples Therapy and Behavioral Couples Therapy: A
Meta-Analysis."** Rathgeber M, Bürkner P-C, Schiller E-M & Holling H. *Journal of Marital and Family
Therapy* (2018), DOI 10.1111/jmft.12336. University of Muenster. **"There was no funding for this
study."** `primary text read in full`
**33 studies, 2,730 participants, RCTs only**, latest search 16 June 2015. Cochrane risk-of-bias tool,
MARS/PRISMA, robust variance estimation (robumeta), 32 moderators.

## Results

| Time | Therapy | g | k | ks | 95% CI | p | I² |
|---|---|---|---|---|---|---|---|
| Post | Overall | 0.60 | 33 | 56 | [0.45, 0.74] | <.001 | 80% |
| Post | BCT | 0.53 | 21 | 39 | [0.39, 0.67] | <.001 | 70% |
| Post | **EFCT** | **0.73** | 12 | 17 | [0.38, 1.08] | <.001 | 81% |
| 6-mo | **EFCT** | **0.66** | 5 | 5 | [0.15, 1.17] | .024 | 69% |
| 6-mo | BCT | 0.35 | 9 | 19 | [0.17, 0.53] | .002 | 64% |
| **12-mo** | BCT | **0.06** | 8 | 18 | [−0.08, 0.19] | **.35 — no effect** | 6% |
| **12-mo** | **EFCT** | **—** | **0** | 0 | — | — | — |

**No EFCT study provided 12-month data. Zero.** And BCT at 12 months is flat.

## Where Rathgeber and Spengler genuinely contradict each other

**1. Publication bias — a direct empirical conflict.**
- **Rathgeber:** funnel asymmetric; **trim-and-fill estimates 15 missing studies**; **Egger z = 3.68,
  p < .001**; corrected effect drops from **g = 0.60 to g = 0.38** [0.30, 0.49].
- **Spengler:** symmetric funnel, **Egger t(17) = 0.51, p = .66**, fail-safe N = 1,180.
**Not a framing difference — opposite findings.** Plausible reasons: Rathgeber has 33 studies against
Spengler's 19 (more power to detect asymmetry); Rathgeber's funnel includes BCT; and the two plot
different effect-size types (below). **Record both. Do not pick one.**

**2. Fidelity — direct conflict.** Spengler's headline moderator was fidelity (videotape-checked
sessions produced larger effects, p<.05). **Rathgeber lists treatment fidelity, therapists' expertise,
supervision, manualization and implementation among moderators that were NOT significant.**

**3. Initial distress — direct conflict.** **Rathgeber: more baseline distress predicted more
improvement** (g = −0.002 per DAS point, p < .05). **Spengler: no relationship** (Q=0.88, p=.35).
Roddy 2020 sides with Rathgeber.

## THE METHODOLOGICAL DIFFERENCE THAT EXPLAINS THE EFFECT-SIZE GAP — and I had this wrong

**Spengler's headline d = 0.93 is a pretest–posttest change WITHIN the EFT group.**
**Rathgeber's g = 0.73 for EFCT is a CONTROLLED effect — corrected for pretreatment values AND for the
control group.** In their words: "lower effect sizes could also be the result of the **type** of effect
sizes emphasized in the present meta-analysis, since we controlled both for differences between
experimental and control groups and for pretreatment values. **As far as reported, all previous
meta-analyses computed effect sizes not controlling for at least one of these two aspects.**"

**These are different quantities, not competing estimates of one quantity.** The comparable Spengler
figure is its **EFT-vs-alternative-treatment d = 0.44**, not the 0.93. **Anywhere this project quotes
0.93 it must say "pretest–posttest within group."**

## The conflation charge: Spengler mischaracterised what Rathgeber did

Spengler calls combining Johnson's and Greenberg's models an "**oversight**" that "resulted in a
conflation." **It was a stated, pre-specified inclusion decision.** Rathgeber's inclusion criterion (h)
reads: "**Both versions of EFCT and the traditional version of BCT were included.**" Objective 1 says
"The present analysis includes both versions of EFCT (Greenberg's and Johnson's version)." They
describe the distinction explicitly: "the Johnson version focuses on attachment processes, the
Greenberg version focuses on affect regulation."

**Spengler's substantive point — that the models differ theoretically and should be separated — is
reasonable. Calling it an oversight is not accurate.** Two teams made different, declared choices.

**And Rathgeber flags a deeper version of the problem that Spengler does not:** "due to lacking
information in the primary studies, we were **not able to disentangle systematically whether
therapists included certain techniques belonging to another therapy approach** or not… it could be
coded as BCT, even if it were cognitive behavioral couple therapy… or even EFCT. **Thus, a more
rigorous method is needed for determining if studies are BCT or EFCT.**"

## My Iranian-outlier speculation was partly wrong — correcting it
**Rathgeber independently excluded the same study:** "one study was excluded from further analyses,
because of an unrealistically large effect size (**Ahmadi, Zarei, & Fallahchai, 2014; d = 5.58**) that
we believe resulted from a **reporting error**." (Spengler's "Solymani ahmadi et al. 2014"; Beasley &
Ager cite it as "Ahmadi et al. 2014.") **Two independent teams excluded it, and Rathgeber gives a
substantive reason — a suspected reporting error, not size alone.**

**But the underlying question is real, and Rathgeber engaged it:** studies from Iran and India
produced **significantly higher** effects than USA/Canada (g = 0.47, p < .05), driven mainly by one
study at g = 1.74. Their reading: "**this might be an artifact of the low or unknown reliability of
two out of the four outcome measures used** in the studies conducted in Iran and India. Thus, this
result may rather point to **methodological differences** than to differences in the efficacy itself."

## Findings that matter to this project regardless of the dispute

- **Comparator type moves the answer.** Waitlist controls **g = 0.66**; active or individual-therapy
  controls **g = 0.41**; difference g = 0.26, p < .05. **Direct quantitative support for the point
  Darryl made about the dyad trial and Bornemann — an effect against nothing is not an effect against
  something.**
- **BCT and EFCT do not differ significantly** — g = 0.18 post (p=.29), g = 0.31 at 6 months (p=.15),
  both nominally favouring EFCT. Rathgeber: "there is not (yet) enough evidence to favor one treatment
  over the other."
- **Both beat individual therapy** for relationship satisfaction. The firmest clinical conclusion here.
- **Unpublished dissertations produced LOWER effects** (g = −0.51, p < .05) — evidence the published
  record is inflated.
- **Risk of bias was high across the board** for allocation concealment and performance bias.
- **Their DAS critique undercuts both meta-analyses and every EFT number in this ledger:** the DAS
  "focuses more on **consensus** than on satisfaction," addressing "partners' agreement (e.g. agreement
  on child education or agreement on leisure activities) more than on relationship satisfaction."
  Last validated 1994.
- **The point most relevant to this curriculum's values:** "most of the studies did not assess
  **individual** satisfaction supplementary to relationship satisfaction. **Only three studies focused
  also on personal happiness.** All empirically tested couple therapy approaches seem to take a
  relationship-supporting, antiseparation point of view… **This attitude may lead to an
  underrepresentation of individual goals during the therapy, thus possibly preventing deeper
  individual satisfaction for the sake of maintaining the relationship.**"

## Verdict
**Neither meta-analysis is "right."** Rathgeber is stricter on design (RCT-only), uses controlled
effect sizes, has 33 studies, and finds substantial publication bias. Spengler covers 100% of EFT
research including quasi-experimental studies and dissertations, separates Johnson's model cleanly,
and finds none. **They disagree empirically on publication bias, on fidelity and on baseline distress,
and the disagreement is unresolved.** Cite the pair, with the effect-size-type distinction attached.

# Wiebe & Johnson 2016 — read against Lesson 2's aims. Most of it is not Lesson 2.

**"A Review of the Research in Emotionally Focused Therapy for Couples."** Wiebe SA & Johnson SM.
*Family Process* (2016) **55(3):390–407**, DOI 10.1111/famp.12229. `primary text read in full`
**Allegiance note: written by the model's developer.** It reads as advocacy in places — e.g. "EFT is
likely to emerge as an effective treatment for symptoms of post-traumatic stress" is forward-stated
speculation. Weigh accordingly; Spengler tested allegiance in the outcome data and found none, which
is a separate question from how a narrative review is written.

**Skipped as out of scope for Lesson 2:** the depression, PTSD, cancer, chronic-illness, sexual
satisfaction, forgiveness, alliance-rupture and therapist-training literatures. Noted and moved past.

## 1. THE FINDING THAT MATTERS MOST — a direct null on awareness as a precondition

**McRae TR, Dalgleish TL, Johnson SM, Burgess Moser M & Killian KD (2014), "Emotion regulation and key
change events in Emotionally Focused Couple Therapy," *Journal of Couple and Relationship Therapy*
13(1):1–24.**

Verbatim from the review: they "examined whether emotion regulation strategies at baseline, **emotion
self-awareness** and emotion control, would predict whether couples had a softening event or not. They
found that **neither of these emotion regulation strategies were predictive of softening in EFT.**"

**Baseline emotional self-awareness did not predict whether the key emotional change event occurred.**

**This is now the second independent null on the same proposition.** With White VanBoxel et al. 2024
(baseline emotion regulation did not predict change in relationship satisfaction, and did not differ
by treatment group), **two studies say awareness/regulation at baseline is not a prerequisite for
relational emotional work paying off.**

**Consequence for the curriculum, stated plainly:** the sequencing assumption — that Lesson 2 must
come before relational lessons because you need awareness first — **has two nulls against it and no
positive evidence for it in this ledger.** It does not follow that Lesson 2 is useless; it follows that
**we cannot claim it is a prerequisite.** Worth deciding deliberately rather than by default.

## 2. Third-party coding of CLIENT emotional behaviour — the named instrument, and it measures Lesson 2's skills

**Secure Base Scoring System (SBSS; Crowell, Treboux, Gao, Fyffe, Pan & Waters, 2002,
*Developmental Psychology* 38(5):679–693).** Couples are asked to discuss a topic of disagreement;
the interaction is coded by **two independent coders** on two dimensions:
- **Secure base use** — clarity of attachment signaling, signal maintenance, approach, ability to be
  comforted.
- **Secure base support** — **"interest in the partner's distress, recognition of distress, attuned
  interpretation of distress, and responsiveness to the distress."**

**Read that second list against Lesson 2's other-people half: recognising distress and attuned
interpretation of distress are exactly the target skills, and they are measured by blind third-party
coders of real interaction rather than by questionnaire.** This is the measurement model Darryl asked
for, applied to the client rather than the therapist.

**Results:** couples improved significantly in **both** secure base use and secure base support
post-therapy (Burgess Moser et al. 2016, *JMFT* 42(2):231–245), and **both continued improving across
24-month follow-up** (Wiebe et al. 2014). n=32 insecurely attached distressed couples, 14 therapists,
mean 21 sessions (range 8–35). **No effect sizes are given in the review — retrieve Burgess Moser 2016
for them.**

**Also observationally coded, on the self side: "depth of experiencing."** Johnson & Greenberg 1988
found "greater depth of experiencing and more affiliative interpersonal responding by partners in EFT
sessions predicted more improved relationship functioning," and Wiebe et al. 2014 found depth of
experiencing predicted satisfaction gains across follow-up. **A coded measure of being in contact with
one's own felt experience — the self half of Lesson 2, measured from the outside.**

## 3. The only Lesson-2-scale deliverable in this literature

**Kennedy N, Johnson SM, Wiebe SA & Tasca GA (2015), the "Hold Me Tight" group program.**
**95 couples across 16 groups in the US and Canada.** The EFT steps rendered as **structured
conversations "that less distressed couples can grasp and practice at home."** Nine groups ran as 8
weekly sessions; seven ran as **weekend retreats.** Couples were on average **in the nondistressed
range** (M = 106.63, SD = 10.08).

- **Relationship satisfaction d = 0.81** baseline → postgroup.
- **Crucially, no change from baseline to pregroup** (measured 8 weeks earlier), so the gain is not
  simply passage of time. **This is a stronger design feature than most things in this ledger** — it
  uses the participants as their own no-treatment control before starting.
- **Trust d = 0.42.**
- **No significant changes for attachment or intimacy.**
- **Both satisfaction and trust DECREASED from postgroup to follow-up** (3–6 months).

**Why it matters here:** it is the one place EFT has been reduced to structured conversations for
non-distressed people to practise, which is the format Lesson 2 would actually take. **The effect on
satisfaction is large, the effect decays, and the constructs closest to this lesson (intimacy,
attachment) did not move.**
**⚠ Listed as "Manuscript in preparation" in 2016 — find the published version or treat as unpublished.**

## Two smaller notes
- **Johnson & Talitman 1997: "The initial level of relationship distress at intake had no impact on
  the success of EFT."** A third data point in the Spengler-vs-Rathgeber disagreement on baseline
  distress — **siding with Spengler.** Rathgeber and Roddy found the opposite. Still unresolved, now
  2–2.
- **Johnson SM, Moser MB, Beckes L, Smith A, Dalgleish T, Halchuk R et al. (2013), "Soothing the
  threatened brain: Leveraging contact comfort with emotionally focused therapy," *PLoS ONE*
  8(11):1–10. OPEN ACCESS.** fMRI, female partners, threat of ankle shock under three conditions.
  Post-therapy, the neural alarm response was significantly attenuated **only when holding the
  partner's hand** — not alone, not with a stranger — and they reported less pain. Striking, and not
  Lesson 2. Belongs with the co-regulation material.

## Retrieval list from this review
**Burgess Moser et al. 2016**, *JMFT* 42(2):231–245 — for the SBSS effect sizes. **Priority.**
**Crowell et al. 2002**, *Developmental Psychology* 38(5):679–693 — the SBSS instrument itself.
**McRae et al. 2014**, *J. Couple and Relationship Therapy* 13(1):1–24 — the self-awareness null, in
full rather than via this review's one sentence. **Priority.**

# CORRECTION to my reading of the McRae 2014 null — 14 Aug 2026

Darryl: *"the whole point of EFT is to make a couple aware of an emotional loop and to get out of it.
what are you saying?"*

**He is right and my inference was wrong. Correcting it here rather than leaving the earlier entry to
be read as it stands.**

## What I wrote
That McRae et al. 2014 (baseline emotion self-awareness did not predict softening) plus White VanBoxel
et al. 2024 (baseline emotion regulation did not predict change in satisfaction) gave "two independent
nulls on awareness being a precondition," and that the curriculum's sequencing assumption therefore
"has two nulls against it."

## Why that was wrong
**EFT is itself an awareness intervention.** From this same review: Stage 1 is *cycle de-escalation*,
in which "the couple has a **meta-perspective** on their interactions and begins to see their negative
cycle as the problem"; the therapist "**tracks and reflects the patterns of interaction, identifying
the negative cycles.**" Stage 2 helps partners "**identify and to accept previously unconscious primary
emotions**." Awareness of the loop, and awareness of the primary emotion beneath the secondary one, is
the mechanism of the model — not incidental to it.

**So the McRae result answers a moderator question, not a mechanism question.** It asked whether the
awareness someone *walks in with* predicts who achieves a softening event. **If the therapy supplies
the awareness, baseline levels should not predict much — and that is what they found.** A null on
baseline fitness predicting who benefits from a training program is not evidence that fitness is
irrelevant to the outcome. I made that error.

## And the positive finding was sitting in the same review, under-weighted
**Depth of experiencing — being in contact with one's own felt experience during the session — DID
predict outcomes.** Johnson & Greenberg 1988: "greater depth of experiencing and more affiliative
interpersonal responding by partners in EFT sessions predicted more improved relationship
functioning." Wiebe et al. 2014: depth of experiencing predicted increases in relationship
satisfaction across follow-up.

## The correct synthesis, which is more useful than what I wrote
**What predicts change is awareness achieved during the work, not awareness brought to it.**
The two results are consistent, not in tension:
- **Trait-level awareness measured at baseline: does not predict who benefits.**
- **In-the-moment awareness during the work: predicts who benefits.**

**Two consequences for Lesson 2, both practical:**
1. **Do not gate the curriculum on awareness and do not treat a low starting score as a poor prognosis.**
   Baseline scores did not predict response in either study. This also converges with Bornemann's
   baseline dependency — **lowest starters gained most on every MAIA scale.**
2. **The awareness worth teaching is live and in-the-moment, not a trait to be raised.** Which converges
   with the strongest self-side finding in the project: Bornemann's **Body Listening** (actively
   consulting the body, d=0.40) moved while **Noticing** (passive sensitivity, p=.44) did not.

## And a target Lesson 2 does not currently include
**EFT's Stage 1 awareness object is the loop between two people, not the emotion inside one person.**
Seeing "criticise/attack followed by defend/distance" as a pattern is a different act of noticing than
locating fear in your chest. **Lesson 2 as currently scoped has the emotion in me and the emotion in
you, but not the pattern between us.** Worth a deliberate decision about whether that belongs here or
in a later relational lesson.

**What McRae tested was a baseline moderator — whether starting awareness predicted who improved —
not whether awareness work does anything. Those are different questions and the entry above is
scoped to the first.**

# Shayganfar et al. 2026 — read in full, 14 Aug 2026. EXCLUDED, with reasons.

**"Comparing the Effectiveness of Emotion-Focused Therapy (EFT) and Cognitive-Behavioral Couple
Therapy (CBT) in Reducing Anxiety, Depression, and Improving Relationship Quality Among Couples with
Childhood Trauma."** Shayganfar N, Khaneghahi S & Sanagouye Moharer Gh. *Health Psychology and
Behavioral Disorders* (2026) **4(1):1–14**. Islamic Azad University, Zahedan, Iran. Open access
CC BY-NC. No funding. No conflict of interest declared. `primary text read in full`

**Design:** RCT, **45 couples / 90 individuals, 15 couples per arm** — EFT vs CBT vs **no-treatment
control**. Recruited by **convenience sampling** from counselling centres in Tehran and Karaj, then
randomised. Pretest / posttest / **3-month follow-up**. Beck Anxiety Inventory, BDI-II, Spanier DAS.
Repeated-measures ANOVA with Bonferroni, SPSS 27. Protocols 8–12 weekly sessions each.

## Not Lesson 2 material
Therapist-delivered couple therapy, 8–12 sessions; outcomes are anxiety, depression and relationship
quality. **Nothing about noticing bodily signals, naming emotions, or reading others.** It would sit
in the relational lessons at best.

## Why it is excluded on quality grounds

**1. The effect sizes are far outside everything else in this ledger.**
Reported η² for time × group: **anxiety 0.56, depression 0.57, relationship quality 0.58.** Main
effects of time: **0.69, 0.71, 0.67.**
For comparison, from sources read in full this session:
- Smith 2024, matched placebo, N=326: **ηp² = 0.01–0.02.**
- Bornemann 2014, best scale: **d = 0.72.**
- Spengler 2024 meta, EFT pre–post **within group**: **d = 0.93**; EFT vs alternative: **d = 0.44.**
- Rathgeber 2018, controlled: **EFCT g = 0.73.**
**An interaction accounting for ~57% of variance is not in the same universe as the meta-analytic
literature on the same treatment measured with the same instrument (DAS).**

**2. The ANOVA table does not reconcile internally.** In a repeated-measures model, the *time* and
*time × group* F ratios share an error term, so MS ÷ F should give the same value in both rows.
It does not:
- Anxiety: 921.18 / 96.42 = **9.55** vs 397.32 / 52.17 = **7.62**
- Depression: 1005.92 / 102.36 = **9.83** vs 411.02 / 54.68 = **7.52**
- Relationship quality: 1218.26 / 89.73 = **13.58** vs 432.11 / 56.39 = **7.66**
The SS/df/MS arithmetic within each row is correct, so this is not a transcription slip in those
columns. They state sphericity was met (Mauchly W = 0.91, p = .08) and **no Greenhouse–Geisser
correction was applied**, so a correction does not explain it. **Unexplained. I cannot reconstruct
their model from what is reported, and I am not claiming to know the cause — but the implied error
terms are inconsistent and that is enough to withhold the numbers.**

**3. A reporting inconsistency between abstract and table.** Both abstracts say EFT beat CBT on
**relationship quality and depression**. **Table 4 reports EFT–CBT significant on all three**, anxiety
included (−3.57, p = .003). The extended abstract then concedes anxiety differences were "smaller but
still statistically significant." The headline understates the paper's own table.

**4. No effect sizes for any between-group comparison** — mean differences and p-values only.

**5. A no-treatment control**, which by **Rathgeber's own moderator analysis** inflates the estimate:
waitlist comparisons **g = 0.66** vs active/individual-therapy comparisons **g = 0.41**.

**6. Entirely self-report**, which the authors acknowledge: self-report instruments "can be affected
by response bias or a tendency toward social desirability." Also acknowledged: small sample, two
cities only, short follow-up.

## What this paper IS useful for — it makes the Spengler/Rathgeber dispute concrete

This session I recorded that dispute as unresolved and warned myself not to take sides. **This paper is
a live specimen of the phenomenon they were arguing about.**

- **Rathgeber 2018 found** studies from **Iran and India produced significantly higher effects than
  USA/Canada** (g = 0.47, p < .05), and offered a specific explanation: "**this might be an artifact of
  the low or unknown reliability of two out of the four outcome measures used** in the studies conducted
  in Iran and India. Thus, this result may rather point to **methodological differences** than to
  differences in the efficacy itself."
- **Rathgeber excluded Ahmadi, Zarei & Fallahchai 2014 (d = 5.58)** as a suspected **reporting error**.
- **Spengler excluded the same study plus one more** (d = 5.72, 6.49) by the Tukey outlier rule.

**Earlier today I speculated that excluding non-Western studies for having large effects deserved
scrutiny. Having now read a paper of this type in full, Rathgeber's methodological explanation looks
better founded than my speculation did.** The problem here is not geography; it is an internally
inconsistent analysis, a no-treatment comparator, and effect sizes that don't reconcile with the
instrument's own literature. **That is a reason to exclude on stated methodological grounds — which is
what both meta-analyses did.**
**Correction to my own earlier framing: I was too quick to treat outlier exclusion as potentially
biased. It can be, and in this instance the case for exclusion is strong.**

## Two leads from its reference list worth following
- **Timulak L, Dailey J, Lunn J & McKnight J (2025), "Transdiagnostic Emotion-Focused Therapy for
  Couples with Co-Morbid Relational and Mood, Anxiety and Related Difficulties," *Journal of
  Contemporary Psychotherapy* 55(1):1–10**, DOI 10.1007/s10879-024-09645-7. Timulak is a serious
  Greenberg-lineage researcher; **transdiagnostic framing** is closer to how this curriculum thinks.
- **Vedelago L, Balzarini RN, Fitzpatrick S & Muise A (2023), "Tailoring dyadic coping strategies to
  attachment style: Emotion-focused and problem-focused dyadic coping differentially buffer anxiously
  and avoidantly attached partners," *Journal of Social and Personal Relationships* 40(6):1830–1853.**
  → **A moderation finding about which emotional strategy helps whom.** That shape of result is more
  usable in a curriculum than an overall efficacy estimate. **Higher priority than most of the EFT
  outcome literature for our purposes.**

# Reed et al. 2023 — full text retrieved 14 Aug 2026. The general-population bound, fully specified.

**"Assessing the effectiveness of online emotion recognition training in healthy volunteers."**
Reed ZE, Suddell S, Eastwood A, Thomas L, Dwyer I, Penton-Voak IS, Jarrold C, Munafò MR & Attwood AS.
*Royal Society Open Science* (2023) **10(9):230372**, PMID 37771966, PMC10523077. Open access.
**All three studies preregistered on OSF: osf.io/x4kh3, osf.io/drby2, osf.io/bpzcj.**
`full text retrieved`

## THE PRACTICE, FULLY SPECIFIED — this is the most precisely described practice in the project
**A four-alternative forced-choice task.** A face is shown for **1 second**; the participant picks the
emotion; **feedback is given on correctness, and if wrong they must keep responding until they select
the correct emotion.**
- **Study 1:** 4 emotions (angry, happy, sad, scared) × **15 intensity levels = 60 trials.**
- **Studies 2 and 3:** 6 emotions (adding disgusted, surprised) × **8 intensity levels = 48 trials.**
- **~15 minutes per session. One session.**

**The sham is tightly matched:** identical task structure, feedback and duration, but the stimuli are
**coloured blocks instead of faces** — blue/red/green/yellow across 15 greyscale increments in Study 1;
plus orange and purple across 8 increments in Study 2. Participants selected which colour was shown, with the
same forced-correction feedback.
→ **Matched on structure, feedback, duration and effort, differing only in whether the stimulus is a
face. That is a better control than almost anything else in this ledger** — compare Thomson's 5:1 dose
mismatch and Bornemann's no-contact retest control.

## Results

| Study | n (active/sham) | Emotions | Time × group interaction |
|---|---|---|---|
| **1** | 101 (52/49) | 4 | **b = 0.02 [−0.02, 0.07], p = 0.27 — null** |
| **2** | 109 (54/55) | 6 | **b = 0.07 [0.03, 0.12], p = 0.002** |
| **3** | 120 (62 congruent/58 incongruent) | 6 | time × congruency **b = −0.01 [−0.05, 0.03], p = 0.62** |

**Study 1 detail:** main effect of time b = 0.06 [0.04, 0.08], p<.001; main effect of group b = 0.02
[0.002, 0.05], **p = 0.03**. **Anger specifically moved: b = 0.07 [0.01, 0.13], p = 0.03.** Happy false
alarms fell, b = −0.04, p = 0.02.
**Study 2 detail — and the emotion-specific pattern is the useful part:**
**scared b = 0.26 [0.17, 0.36], p < .001** — far larger than the overall effect. Sad b = 0.07
[−0.0002, 0.13], p = 0.05, borderline. Surprised false alarms fell, b = −0.05, p < .001.
**Study 3:** main effect of time **b = 0.10 [0.08, 0.12], p < .001**, with no congruency interaction —
**improvement transferred to face sets the participants had not trained on.**

## Sample — and it corrects an assumption of mine
**Recruited via Prolific.** Mean ages **27–31**. **53–67% MALE across all six arms.** I had been
assuming the usual female-skewed psychology sample; this is one of the few male-majority samples in
this project.
**Screened hard:** excluded anyone "ever being diagnosed with any mental health condition, currently
using psychiatric medication, and having an uncorrected visual impairment." **A genuinely healthy
sample, which is what makes their ceiling explanation credible.**

## THE AUTHORS THEMSELVES GIVE THE CEILING EXPLANATION — direct support for Darryl's argument
Verbatim: "While our studies were well powered to detect effects, we did not find evidence for a
training effect… in study 1—we only observed a trend of improvement. However, as mentioned, **this may
have been owing to ceiling effects leaving little room for improvement. These ceiling effects probably
stemmed from our sample consisting of healthy adults with no known ER difficulties.**"

**This is the null study's own authors attributing the null to ceiling rather than to untrainability.**
Darryl made exactly this argument about mentalizing — "most people can mentalize" — and I initially
read a small effect as evidence of untrainability. **Same error, and here the primary authors are on
his side of it.**

## THE CONFOUND THEY NAME, WHICH BOUNDS THE POSITIVE RESULT TOO
Verbatim: "it is also worth considering the extent to which the effects we observed in these studies
might be owing to **mere exposure to the stimuli, and our choice of control task does not allow us to
eliminate this possibility**… As the same facial stimuli are used in the training and test phases for
the active group, it is plausible that **training effects were owing to participants becoming more
familiar with the facial stimuli (mere exposure) as opposed to the training component of the task
improving underlying emotional processing ability.**"

**So the b = 0.07 might be familiarity with those particular faces rather than improved emotion
recognition.** Note the internal tension: **Study 3 partly answers this** by showing transfer to
untrained faces, yet they still list mere exposure as unresolved. The reconciliation is probably that
Study 3 demonstrates transfer only **within a narrow stimulus class** — their third limitation:
"we have still only tested this for **white male and female composite faces** and thus generalizability
beyond this is unknown."
Fourth limitation: online administration, so "it may be more difficult to be sure that participants
actually pay attention to the study and are honest in their responses."

## A convergence across clinical and non-clinical samples worth carrying into the lesson
**The emotions that move are fear, sadness and anger. Happy is at ceiling everywhere.**
- **Reed (healthy adults):** anger moved in Study 1 (b=0.07); **fear moved most in Study 2 (b=0.26)**;
  happy showed only reduced false alarms.
- **Thomson (conduct disorder adolescents):** sad d=0.75, fear d=0.54, anger d=0.50; **happy ns, at
  ceiling M=7.73/8.**
- **Hubble (juvenile offenders), Hunnikin (children with disruptive behaviour):** fear, sadness and
  anger improved.
**Four independent samples, two clinical and two not, and the same three emotions move.** If Lesson 2
teaches recognition at all, **fear, sadness and anger are where the headroom is, and happy is not
worth training.**

## Honest claim for the practice map
**Practice:** ~48–60 forced-choice trials on faces at varying intensity, one second each, with
corrective feedback that requires you to keep trying until correct. **One session, ~15 minutes.**
**Population:** screened healthy adults, mean age 27–31, majority male, Prolific.
**Result:** **b = 0.07 [0.03, 0.12] on the six-emotion version; null on the four-emotion version
(p = 0.27).** Transfers to untrained white composite faces.
**Cannot show:** that the gain is emotion processing rather than stimulus familiarity; any effect
beyond the trained task; any effect on symptoms, relationships or behaviour; anything past one session;
any generalisation beyond white composite faces.
**Authors' own reading of the null: ceiling in a healthy sample.**

# Hubble et al. 2015 — full text retrieved 14 Aug 2026. TWO CORRECTIONS to what I reported from the abstract.

**"Improving Negative Emotion Recognition in Young Offenders Reduces Subsequent Crime."**
Hubble K, Bowen KL, Moore SC & van Goozen SHM. *PLoS ONE* (2015) **10(6):e0132035**, PMID 26121148,
PMC4486167. Open access. `full text retrieved`

## CORRECTION 1 — the crime result is NOT a between-group finding
**What I told Darryl, from the abstract:** "crime severity reduced at 6 months only in the trained
group… an actual behavioural outcome, stronger than anything in the VR trial."

**What the full text shows:**
- **Reoffending frequency: training 12 of 24, control 10 of 26. Between-group test z = 1.02, p = .31 —
  NOT significant.**
- **Between-group difference in severity: F[1,49] = 0.12, p = .73 — NOT significant.**
- **Offence rates fell significantly in BOTH groups** from the pre- to post-training 6-month periods
  (random-effects negative binomial, z = −3.45, p < .01).
- The significant result is **within the training group only**: "Paired samples t-Tests and general
  linear models adjusting for baseline differences from the mean only showed significant reductions in
  reoffending severity for the Training group (re-offence mean severity: t[23] = 2.17, p = .04;
  re-offence most severe: t[23] = 2.82, p = .01; B = −0.35, z = −2.07, p = .04)."

**So the claim rests on a within-group reduction being significant in one arm and not in the other,
while the direct between-group comparisons are null. That is the "difference in significance is not a
significant difference" fallacy.** The B = −0.35, z = −2.07, p = .04 term in a GLM adjusting for
baseline may be a group term — **ambiguous from the text and I am not going to assume it is.**

**Honest statement: both groups reoffended less over six months; the trained group additionally showed
a within-group drop in offence severity; the between-group comparisons on crime did not reach
significance.** **Do not cite this as a demonstrated behavioural outcome.**

## CORRECTION 2 — how the control group was formed is worse than I described
I said the van Goozen studies allocated "by impairment status." **For Hubble it is by predicted
attendance:**
"Group allocation was strongly influenced by the opportunity and availability of the offenders to
attend the YOS offices." And: "With the help of caseworkers it was decided in advance whether offenders
would be able to attend for the number of sessions required to complete training. **Those who were
unlikely to be able to attend all sessions formed the control group.**"

**The control group is composed of people judged unlikely to show up reliably.** For a *crime* outcome
that is a serious confound — predicted unreliability plausibly tracks the chaos of someone's life and
their reoffending risk. **Worse than allocation by impairment for this particular outcome.**
The authors state it plainly: "The intervention was not randomised… a quasi-experimental design was
used based on the availability of young offenders."

## The practice — and it is NOT pure recognition training. This matters for us.
**2–3 sessions over 2 weeks, ~2 hours total.** Three components:
1. **Identify the emotional expression of a face.**
2. **"Describe an event that has made them feel that emotion."** ← self-referential; the self side of
   Lesson 2.
3. **"Mimic the emotion using a mirror."** ← **an embodied component. Directly on this curriculum's
   premise, and I missed it reporting from the abstract.**
Plus: focus on specified facial features and select the correct description of that feature.
**Difficulty escalates** via lower-intensity expressions and fewer guiding cues.
**Feedback: not specified in the text.**

→ **This is a three-part practice — recognise, recall your own instance, embody it — not a recognition
drill.** If any recognition practice enters Lesson 2, this composition is more interesting than Reed's
pure forced-choice task, because two of its three parts are things Lesson 2 already wants.

## The emotion recognition results, which ARE solid
Time × group interactions:

| Emotion | Interaction | η² | Training group | Control group |
|---|---|---|---|---|
| **Sadness** | F[1,48]=14.30, **p<.001** | **.23** | F=10.93, p=.002 | **DECLINED, F=4.07, p=.049** |
| **Fear** | F[1,48]=13.00, **p=.001** | **.17** | F=25.91, p<.001, η²=.35 | no change, p=.93 |
| **Anger** | F[1,48]=10.13, **p=.003** | **.17** | F=10.16, p=.003 | no change, p=.21 |
| Happiness | no time effect, no interaction | — | group main effect only, p=.030 | — |
| **Disgust** | **no significant effects** | — | — | — |

**Two features worth keeping:**
- **Disgust was not trained and disgust did not move.** A clean internal specificity check — it argues
  against generic practice effects and against the mere-exposure worry Reed could not exclude.
- **Sadness declined in the control group** (p=.049), so part of that interaction is control
  deterioration rather than training gain. Same shape as Smith 2024's six-month DERS result.
- **Fear again shows the largest within-group gain (η²=.35)** — consistent with Reed's b=0.26 for fear
  and Thomson's fear/sad/anger pattern.

## Sample
**50 male young offenders, aged 12–18, mean 16.21.** **All male.** IQ M=80.9 / 83.8 (low). SES mostly
low (79% / 65%). Youth Psychopathy Inventory M=115.2 / 125.8, ns. Lifetime offence rate ~6.4 / 6.9, ns.
Groups did not differ at baseline on age, IQ, SES, psychopathy, CU traits or lifetime offending.
Age at first offence differed at trend level (14.17 vs 13.24, p=.07).

## Limitations, in the authors' words
- "the observed effects, in terms of offences severity, were **relatively small and of moderate effect
  size**… Most of the young offenders were persistent offenders and therefore **by definition those
  whose offending trajectory is resistant to change**."
- Training was short (~2 h); a prior study of the same intervention in severe traumatic brain injury
  used **9 hours**. "it may also be that in order to obtain larger effects, a longer and more advanced
  program could be beneficial."
- Not randomised.
- "there are other possible confounding variables, which we did not control for… such as **substance
  use, self-reported aggression, opportunity, and maltreatment**."
- "our study **does not explain why** the emotion training improved expression recognition and reduced
  reoffending severity."
- "**Future research will need to confirm these results within a randomised control trial framework.**"

## Net for the practice map
**Emotion recognition in male young offenders improved substantially in ~2 hours across three
sessions, with clean specificity (untrained disgust did not move) — η² = .17–.23 on the interactions.**
**The crime outcome does not survive the between-group test and should not be claimed.**
**And the practice contains an embodied mimicry component and an autobiographical recall component that
I had not reported.**

# Wells et al. 2021 — full text retrieved 14 Aug 2026. Same correction as Hubble, plus one finding that holds.

**"Improving emotion recognition is associated with subsequent mental health and well-being in children
with severe behavioural problems."** Wells AE, Hunnikin LM, Ash DP & van Goozen SHM.
*European Child & Adolescent Psychiatry* (2021) **30(11):1769–1777**, PMID 32997168, PMC8558267.
Open access. `full text retrieved`

## CORRECTION — the mental-health comparison was never tested between groups
**What I told Darryl:** "behavioural problems reduced only in the trained group."

**What the text says:** "the present study **lacked sufficient power to detect an interaction** between
group membership and change in SDQ score (power analysis showed that **four times as many participants**
to test this would have been needed)."

**So there is no between-group test of the mental-health outcome at all — not a null, untested, and
underpowered by a factor of four on the authors' own calculation.** And the two arms are closer than
"only the trained group" implies:
- **BP+ (trained), n=40:** SDQ 18.79 (5.16) → 15.38 (6.29), t(39)=2.866, **p=.007, d=0.45**
- **BP− (untrained), n=22:** SDQ 15.05 (6.03) → 12.68 (6.93), t(21)=1.448, **p=.162, d=0.31**
**Both improved. d=0.45 vs d=0.31. The control's failure to reach significance is largely n=22.**
**This is the same "difference in significance is not a significant difference" structure as Hubble, and
I made the same error reporting both from their abstracts.**

High-risk classification did fall in the trained group, **93% → 64%**, χ²(1)=7.692, p=.006 — but the
authors immediately note "**two-thirds of these children were still considered as high risk** at this
stage, showing that further work with these children is needed."

## THE FINDING THAT DOES HOLD — and it is the most useful result in this literature for us
**A hierarchical regression predicting SDQ at 6 months.**
- Step 1 — pre-test SDQ, pre-test FER, IQ: F(3,58)=2.59, **p=.061, not significant.** Only pre-test SDQ
  contributed (β=.270, p=.038).
- Step 2 — **adding post-training emotion recognition**: F(4,57)=3.51, **p=.013.** Variance explained
  rose **11.8% → 19.7%**, F(1,57)=5.63, **p=.021, f²=0.10.**
- **Post-training FER: β = −0.305, p = .021.**
- **Controlled for: baseline SDQ, baseline emotion recognition, and IQ.**
- In the trained subsample alone (n=40): **β = −0.385, p=.031**, variance 5.4% → 17.3%, f²=0.14.
- And across the full sample: **change in recognition correlated with change in SDQ, r(60)=0.366,
  p=.003.**

**Stated precisely: how well a child could read emotions after training predicted their teacher-rated
difficulties six months later, independently of how well they read emotions beforehand, how bad their
difficulties were beforehand, and their IQ.** It adds ~8% of variance.
**That is a prospective prediction with the right controls. It is not evidence that training caused the
improvement** — but it is the only place in this project where an emotion-reading measure predicts a
real-world outcome months later with baseline controlled.

## The practice — 60 minutes, delivered by a non-clinician in a school room
**Cardiff Emotion Recognition Training (CERT): three 20-minute sessions, once a week over three
consecutive weeks. ~60 minutes total.**
Delivered **one-to-one by a family support worker or a police community support officer, in a quiet
room at the child's school.** Not by a psychologist.
Method: "**directing attention to key facial features and providing assistance with the interpretation
of these features.**" Trains happiness, sadness, fear and anger. Also aims to "improve the ability to
understand **when and why** certain emotions are shown" and to "provide guidance on the **appropriate
way to respond**."

**→ Deliverability is the headline: an hour, three short sessions, a non-specialist, an ordinary room.**
Converges with Jin et al. 2025's meta-analytic finding that **teacher-led and school-based delivery beat
researcher-led delivery.**

**⚠ An internal contradiction in this group's own work, worth recording.** CERT is designed around
**directing attention to facial features**. But **Hunnikin et al. 2022 — same lab, same programme, with
eye-tracking — found "eye gaze did not contribute to impairment or improvement in emotion recognition.
The training works by improving children's ability to appraise emotional stimuli rather than by
influencing their visual attention."** **The intervention's design rationale is not how it turned out
to work.** Not a contradiction in findings; a correction to the mechanism. **Another reason not to teach
"look at the eyes" as the mechanism.**

## Recognition results
**BP+ (trained, n=40):** negative emotions t(39)=−6.581, p<.001, **d=1.041**; neutral t(39)=−3.230,
p=.003, d=0.511; fear, sadness and anger individually all p<.05.
**Happy: t(39)=−0.392, p=.697 — no improvement.**
**BP− (untrained, n=22):** no significant improvement in any category.

**Happy fails to move for the fourth time in this project** — Reed, Thomson, Hubble, Wells. The
convergence is now four independent samples across two continents and three age ranges.

## Sample and allocation
**62 children, 52 male (84%), aged 7–10, M=8.61 (SD 1.06)**, all referred to an early-intervention
programme for severe family adversity and behavioural problems.
**Allocation was by impairment, not randomised** — BP+ scored **≤66.67% on at least one of fear,
sadness, anger or neutral (1.5 SD below typical development)** and received CERT; BP− had behavioural
problems with intact recognition and received nothing. Authors: "Our objective was to deliver the
training according to **objectively assessed need**."

**The groups differed at baseline on the outcome: SDQ 18.79 vs 15.04, p=.013.** IQ 82.58 vs 95.36,
p=.07 — **note the BP+ IQ SD of 30.59, which is very large and worth treating cautiously.**

## Limitations, in the authors' words — they name the biggest one themselves
- "once the children had been assessed for emotion recognition problems and assigned to their training
  condition, **the two groups were found to differ in severity of behavioural problems**."
- "participants were **not randomly allocated**."
- "**The fact that the two groups differed in problem behaviour at the outset raises the possibility
  that the significant improvement in the emotion training group at follow-up simply reflects regression
  to the mean.**"
- An RCT "would **rule out the possible role of third variables**."
- "**two-thirds of these children were still considered as high risk**."

**Regression to the mean is the live concern: the trained group started worse (18.79 vs 15.04) and
improved more. That is the classic signature, and the authors say so.**

## Net
**Do not claim training reduced symptoms — the between-group test was never run.**
**Do claim, carefully: post-training emotion recognition predicted teacher-rated difficulties six
months later, controlling for baseline recognition, baseline difficulties and IQ (β = −0.305, p = .021).**
**And note the deliverability: one hour, three sessions, a non-specialist, a school room.**

---

# Lesson 2, Challenge-rewrite citation retrieval — 17 Aug 2026

Thirteen citations arrived in a Challenge draft with no ledger entry behind any of them. All
thirteen were chased through Europe PMC and **every entry below rests on an abstract read
verbatim from the Europe PMC record, or on full text read directly.** Nothing here is written
from a search snippet or a fetch summary.

**Ten are real papers. Three support the sentence they were attached to.**

Where a citation did not fit, it was because the sentence ran one step larger, or one
direction different, than what the paper measured. Each entry below says which.

## The cardiovascular pair — both real, both about anger rather than awareness

**Chida & Steptoe, 2009** ([JACC 54(11):936–946](https://doi.org/10.1016/j.jacc.2008.11.044);
PMID 19281923) — `abstract only`. Meta-analysis of prospective cohorts: **25 studies in
initially healthy populations, 19 in populations with existing CHD.** Anger and hostility →
**CHD events in healthy populations, HR 1.19 [1.05–1.35], p=0.008**; poor prognosis in CHD
populations, **HR 1.24 [1.08–1.42], p=0.002**. Harmful effect in healthy populations greater
in men than women. Authors report **indications of publication bias** in both sets, with
fail-safe numbers of 2,020 and 750.

**Use it for:** anger and hostility carried over time go with more heart disease.
**Cannot support:** anything about emotional *awareness*. The exposure is anger. This is
Lesson 8's construct being borrowed.

**Mostofsky, Penner & Mittleman, 2014** ([Eur Heart J 35(21):1404–1410](https://doi.org/10.1093/eurheartj/ehu033);
PMID 24591550) — `abstract only`. Systematic review and meta-analysis, literature 1966–2013.
**Nine independent case-crossover studies:** MI/ACS (4), ischaemic stroke (2), ruptured
intracranial aneurysm (1), ventricular arrhythmia (2). Verbatim: "There was evidence of
substantial heterogeneity between the studies (I² = 92.5% for MI/ACS and 89.8% for ischaemic
stroke). **Despite the heterogeneity, all studies found that, compared with other times, there
was a higher rate of cardiovascular events in the 2h following outbursts of anger.**"

**The abstract reports no pooled effect sizes at all, and the paper is an author manuscript
outside the PMC open-access subset — full text could not be retrieved.** Per this ledger's own
rule, **do not write any incidence rate ratio, confidence interval, or per-outcome number from
this entry until the PDF is in hand.** A figure circulating from a page-fetch summary was
rejected for exactly this reason.

**Use it for, and only for:** across nine studies, the two hours after an outburst of anger
carried a higher rate of cardiovascular events. **Open question needing the PDF:** whether the
pooled ischaemic-stroke estimate is significant on its two studies. Until that is settled,
either write the claim at the abstract's level of generality or name the heart attack alone.

**Companion, same group, retrieved in the same pass and stronger on its own terms:**
**Mostofsky, Maclure, Tofler, Muller & Mittleman, 2013** ([Am J Cardiol 112(3):343–348](https://doi.org/10.1016/j.amjcard.2013.03.035);
PMID 23642509) — `abstract only`. Case-crossover, **N = 3,886** interviewed during hospitalisation
for acute MI. **Incidence of MI onset elevated 2.43-fold [2.01–2.90] within 2 hours of an anger
outburst**, with a significant dose-response by anger intensity (p trend <0.001). Regular
β-blocker users showed lower susceptibility. **This gives a verified number for the heart-attack
claim without depending on the unretrievable meta-analysis.**

## Smith et al. 2026 — the largest aggression meta-analysis, and it cuts against the sentence

**Smith K, Jones A, Daly N, Widdrington H, Garofalo C & Gillespie SM, 2026**, "Emotion
Regulation and Aggression: A Systematic Review and Meta-Analysis," *Aggressive Behavior*
52:e70055 ([DOI](https://doi.org/10.1002/ab.70055); PMID 41424362, PMC12720225) —
**`full text read`**. Open access; the results section was read directly.

**137 articles, 171 studies, 918 effect sizes, N = 252,605.** Multilevel models.

Headline associations with aggression: maladaptive strategies **r = 0.329** (I²=93%);
difficulties regulating emotions **r = 0.248** (I²=89%); adaptive strategies **r = −0.090, and
the PET bias-corrected estimate was non-significant.**

**The DERS subscale analysis is the part that matters here** — 425 effect sizes from 40
studies, overall r = 0.230 [0.200–0.260], Egger's ns (z=1.84, p=0.065). Significant moderation
by subscale, χ²(5) = 145.80, p<0.001:

| DERS subscale | r [95% CI] | I² |
|---|---|---|
| Impulse control difficulties | **0.343** [0.298–0.386] | 89% |
| Access to ER strategies | 0.295 [0.257–0.331] | 86% |
| Goal-directed behaviour | 0.240 [0.207–0.272] | 81% |
| Non-acceptance | 0.229 [0.189–0.267] | 86% |
| Clarity | 0.210 [0.184–0.236] | 67% |
| **Emotional awareness** | **0.080 [0.057–0.104]** | **30%** |

**Emotional awareness is the smallest of the six, and the paper tests the contrasts directly:
impulse control, access to strategies, non-acceptance and goal-directed were each significantly
stronger than emotional awareness, all p<0.001.** Note the I² of 30%, lowest in the table —
that small effect is unusually *consistent*, not noisy.

**Cannot support: "lack of awareness is one of the main drivers of aggressive behavior."** On
this paper's own numbers, awareness is the weakest of six routes from emotion to aggression,
and the strongest — impulse control — belongs to Lesson 19.

**Use Pond et al. 2012 instead** (already in this ledger): three daily-diary studies, N=628,
16–43% less aggression on high-anger days among high differentiators. It measures
differentiation specifically, and it is correctly sized for the claim.

Authors' own caveat: "The over-reliance on cross-sectional studies poses difficulties for
understanding directional associations."

## The loneliness three — all real, all pointing into alexithymia rather than out of it

Cited for *emotional unawareness produces loneliness*. **All three model loneliness as a
predictor or moderator, with alexithymia as the outcome.** All three are Chinese samples, all
cross-sectional.

**Wu X & Guo Z, 2025**, "The impact of **loneliness on alexithymia** among Chinese adolescents:
the mediating role of problematic smartphone use and the moderating effect of fear of negative
evaluation," *BMC Public Health* 25:2812 ([DOI](https://doi.org/10.1186/s12889-025-23721-0);
PMID 40819026) — `abstract only`. **688 secondary students**, cross-sectional. Loneliness →
problematic smartphone use → alexithymia, moderated by fear of negative evaluation; male
students scored higher on alexithymia. **The title states the direction, and it is the reverse
of the sentence this was cited for.**

**Su S, Wang J, Tang P, Yang P, Yuan Z, Ni W & Liu G, 2025**, "Status and correlates of
alexithymia among Chinese empty nest elders in a cross-sectional study," *Scientific Reports*
15:1010 ([DOI](https://doi.org/10.1038/s41598-025-30706-x); PMID 41350576) — `abstract only`.
**394 empty-nest elderly, convenience sample, Chengdu and Ziyang, surveyed Apr 2022–Jun 2023.**
Alexithymia is the dependent variable: 33.5% alexithymia, 35.3% borderline. **Social loneliness
and emotional loneliness were among the factors positively associated with it** (p<0.01),
alongside introversion and chronic-disease count; social support, education, income and
pre-retirement occupation were negative factors. Model explained 55.3% of variance.
**Not "the elderly" — empty-nest elders in two cities, sampled by convenience.**

**Zhang B, Zhang W, Sun L, Jiang C, Zhou Y & He K, 2023**, "Relationship between alexithymia,
loneliness, resilience and non-suicidal self-injury in adolescents with depression: a
multi-center study," *BMC Psychiatry* 23:445 ([DOI](https://doi.org/10.1186/s12888-023-04938-y);
PMID 37337144) — `abstract only`. **2,343 adolescents with DSM-5 depression across 12 Chinese
hospitals**; NSSI detection rate 76.06% (1782/2343). Alexithymia was a risk factor for NSSI
(OR=1.023), resilience protective (OR=0.949). **The outcome is self-injury, not loneliness.**
Loneliness enters only as a moderator of the first half of the alexithymia → resilience → NSSI
path. **It does not test loneliness as an outcome at all.**

**Use Panahi et al. 2018 instead** (already in this ledger) for loneliness as the thing sitting
between alexithymia and relationship damage — accounting for loneliness left nothing of the
link to explain. **What the three papers above genuinely add is a reverse arrow worth knowing
about: loneliness has its own literature as a cause of alexithymia.** That is a usable fact.
It is not the fact they were cited for.

## The callous-unemotional cluster — two good papers, welded into a claim neither makes

The draft's sentence ran: youth who cannot read fear and pain in a face — *a deficit known as
callous-unemotional traits* — are more likely to be arrested and diagnosed with ASPD.

**Marsh AA & Blair RJ, 2008**, "Deficits in facial affect recognition among antisocial
populations: a meta-analysis," *Neurosci Biobehav Rev* 32(3):454–465
([DOI](https://doi.org/10.1016/j.neubiorev.2007.08.003); PMID 17915324, PMC2255599) —
`abstract only`. **20 studies.** Robust link between antisocial behaviour and a **specific
deficit in recognizing fearful expressions**, not attributable to task difficulty. **Fear only
— not "fear and pain." No effect sizes in the abstract.** The outcome is a recognition task,
not arrest.

**McMahon RJ, Witkiewitz K, Kotler JS & Conduct Problems Prevention Research Group, 2010**,
"Predictive validity of callous-unemotional traits measured in early adolescence with respect
to multiple antisocial outcomes," *J Abnormal Psychology* 119(4):752–763
([DOI](https://doi.org/10.1037/a0020796); PMID 20939651, PMC3760169) — `abstract only`.
**Longitudinal, N = 754.** CU traits at Grade 7 predicted **5 of 6 antisocial outcomes** —
general delinquency, juvenile and adult arrests, early-adult ASPD criterion count and diagnosis
— **over and above prior and concurrent conduct problems and ADHD**, with a very low
false-positive rate. Minimal moderation by sex, race or urban/rural status. **A strong paper
for its own claim.**

**But CU traits here were measured with the Antisocial Process Screening Device — a personality
questionnaire about callousness and lack of remorse. Not a face-reading task.** So Marsh & Blair
link antisociality to fear-recognition deficits; McMahon links CU personality traits to arrest.
**Neither links face-reading to arrest, and the chained sentence is in neither paper.**

**Blair RJ, 2013**, "The neurobiology of psychopathic traits in youths," *Nature Reviews
Neuroscience* 14(11):786–799 ([DOI](https://doi.org/10.1038/nrn3577); PMID 24105343,
PMC4418507) — `abstract only`. Review. **Settles the definitional point in the author's own
words:** psychopathic traits comprise a callous-unemotional component and an impulsive-antisocial
component, whose two core impairments are "**a reduced empathic response to the distress of
other individuals**," reflecting reduced amygdala responsiveness to distress cues, and deficits
in decision making and reinforcement learning. **CU traits are not defined as an inability to
read faces.**

**"Velotti et al., 2024" — NOT FOUND.** The only 2024 Velotti P record is "Exploring Narcissism
in Suicidal Ideation Using the Italian Version of the Guilt and Shame Proneness Scale," *Alpha
Psychiatry* 25(1):75–81, PMID 38799498 — abstract read; 936 Italian adults, narcissism, shame
and suicidal ideation, **nothing on CU traits, face-reading or arrest.** Her wider corpus is
DERS psychometrics, emotion dysregulation, IPV and forensic samples. Wrong year, wrong author,
or a citation that drifted. **Do not re-adopt without a title.**

## Zhang X et al. 2025 — real, and much narrower than the sentence

**Zhang X, Huang L, Wang F & Zhang H, 2025**, "Alexithymia and its influence on perceived social
support, stress, and help-seeking attitudes in men undergoing radical prostatectomy," *Journal
of Affective Disorders* ([DOI](https://doi.org/10.1016/j.jad.2025.119676); PMID 40516627) —
`abstract only`. **N = 430 men after radical prostatectomy for prostate cancer, mean age
69.92 ± 4.71.** Cross-sectional. Higher alexithymia → **lower perceived social support, more
negative attitudes toward seeking professional psychological help**, higher perceived stress;
support and stress both mediated the alexithymia → help-seeking-attitude link.

**Two limits that must travel with it.** The instrument is the **Normative Male Alexithymia
Scale-Brief Form**, not the TAS-20 — a different, gendered construct. And the outcome is an
**attitude questionnaire**: nobody was offered help and nobody refused any.

**Cannot support:** "they regularly reject psychological support when professionals offer it."
**Use it for:** in older men recovering from prostate surgery, difficulty identifying and
expressing emotion went with more negative attitudes about seeking psychological help.

## Beeney 2019 — identified, and it is a BPD study

**Beeney JE, Hallquist MN, Scott LN, Ringwald WR, Stepp SD, Lazarus SA, Mattia AA & Pilkonis PA,
2019**, "The Emotional Bank Account and the Four Horsemen of the Apocalypse in Romantic
Relationships of People with Borderline Personality Disorder: A Dyadic Observational Study,"
*Clinical Psychological Science* 7(5):1063–1077 ([DOI](https://doi.org/10.1177/2167702619830647);
PMID 32670673, PMC7363036) — `abstract only`. **130 couples (260 participants)**, conflict task
plus relationship satisfaction at intake and 12 months, clinician-rated BPD and avoidant PD
criteria. Gottman's measures. **People with more BPD symptoms criticized more; their partners
defended and stonewalled more, and had a worse "emotional bank account," which predicted poorer
satisfaction for both and worsening partner satisfaction by follow-up.**

**This is a genuine match for a paragraph about an escalating couple pattern that damages the
relationship over time — and it has a real 12-month longitudinal arm.** But **the predictor is
BPD symptom count, not emotional awareness**, and the sample was recruited for personality
pathology.

**Cannot support:** a general claim that unnamed feelings drive partner conflict in ordinary
couples. **Use it for:** criticism drawing defensiveness and stonewalling, and the pattern
predicting worsening satisfaction a year later, **in couples where one partner has BPD
symptoms** — stated with that population attached.

*(Also retrieved and abstract-read, same group, sometimes confused with the above:*
**Schreiber, Wright, Beeney, Stepp, Scott, Pilkonis & Hallquist, 2020**, *J Abnormal Psychology*
129(5):433–444, PMID 32437206 — 121 couples, 10-minute conflict discussion, disrupted
physiological coregulation predicted relationship dissatisfaction 1 year later. **2020, not
2019, and Beeney is a middle author.***)

## Dolapoglu 2026 — NOT FOUND

**No paper on alexithymia or somatization under this name exists in Europe PMC.** Records
checked, abstracts read: **Dolapoğlu N** publishes on panic disorder / glutamate (PMID 41195803)
and OCD during COVID (PMID 35900776); **Dolapoglu A** is a vascular surgeon. **Do not re-adopt
without a PDF or DOI.**

For the somatization claim, **De Gucht & Heiser 2003 is already in this ledger and supports it
properly** — medically unexplained physical complaints highest in exactly the people who have
most difficulty telling an emotion from a physical sensation.

## What the ten real papers measured

Recorded as a fact about this batch, not as a rule. Four measure emotional awareness or
alexithymia directly against an outcome: Pond, Norman, Hemming, Honkalampi. Six measure
something adjacent — anger (Chida & Steptoe, Mostofsky), emotion regulation broadly (Smith),
BPD (Beeney), antisocial personality (Marsh & Blair, McMahon, Blair), or loneliness as a cause
rather than an effect (Wu & Guo, Su, Zhang B).

Adjacent is not disqualifying — the committed draft uses Chida & Steptoe and Mostofsky, framed
as what an uncaught emotion does to the body. What each entry above states is what that
particular source can and cannot carry.

---

# Lesson 2, Benefit-section retrieval — 18 Aug 2026

Four sources pulled for The Benefit. Every entry below rests on an abstract read verbatim from
the Europe PMC record, or on full text read directly.

## Kalokerinos and colleagues, 2019 — the mechanism claim, and the register had it backwards

**Kalokerinos EK, Erbas Y, Ceulemans E & Kuppens P (2019)**, "Differentiate to Regulate: Low
Negative Emotion Differentiation Is Associated With Ineffective Use but Not Selection of
Emotion-Regulation Strategies," *Psychological Science* 30(6):863–879
([DOI](https://doi.org/10.1177/0956797619838763); PMID 30990768) — `abstract only`.

Two experience-sampling studies. **N = 200 with 34,660 measurements; N = 101 with 6,282
measurements.**

Verbatim: "we found **few relationships between differentiation and the selection** of putatively
adaptive or maladaptive strategies. Instead, we found interactions between differentiation and
strategies in predicting negative emotion. **Among low differentiators, all strategies (Study 1)
and four of six strategies (Study 2) were more strongly associated with increased negative
emotion than they were among high differentiators.**"

Authors' conclusion: "**effective regulation may underlie differentiation benefits.**"

**Use it for:** telling your feelings apart does not change which strategies you reach for. It
changes how well they work. **Cannot support:** that people low in differentiation use more
strategies, or fewer — the paper reports selection as largely unrelated. The claims register
said "used reappraisal and social sharing more, not less" and called it a scattergun approach;
neither is in the paper, and the title says the opposite.

## Ciarrochi, Heaven & Supavadeeprasit, 2008 — the source I2 needed, and it is longitudinal

**Ciarrochi J, Heaven PCL & Supavadeeprasit S (2008)**, "The link between emotion identification
skills and socio-emotional functioning in early adolescence: a 1-year longitudinal study,"
*Journal of Adolescence* 31(5):565–582 ([DOI](https://doi.org/10.1016/j.adolescence.2007.10.004);
PMID 18083221) — `abstract only`.

**N = 667 high school students**, measured in **Grade 8 and again in Grade 9**. Emotion
identification skill (EIS), social support, positive and negative affect. Structural equation
modelling.

Verbatim: "**low EIS predicted increases in fear, decreases in positive affect, and decreases in
the quality and quantity of social support.** Amongst boys, low EIS also predicted increases in
sadness." Separately, negative affect rose and positive affect fell across the year for the
whole sample.

**Use it for:** difficulty identifying what you feel predicts *later* loss of social support, in
both quality and quantity — the directional version of the claim, not just a correlation.
**Scope:** early adolescents, Australian, self-report EIS, one year. **This is the properly
identified source for the claim the register had been attributing to "Ciarrochi 2003."**

## Rowsell and colleagues, 2014 — the register's citation was wrong in year, journal and finding

**Rowsell HC, Ciarrochi J, Heaven PCL & Deane FP (2014)**, "The role of emotion identification
skill in the formation of male and female friendships: a longitudinal study," *Journal of
Adolescence* 37(2):103–111 ([DOI](https://doi.org/10.1016/j.adolescence.2013.11.005);
PMID 24439616) — `abstract only`.

The register listed this as **"Rowsell, Ciarrochi, Deane & Heaven (2016), *Journal of Research
on Adolescence* 26(1):115–125 — three-year longitudinal, reciprocal model between emotion
identification skill and perceived social support."** **No such paper is findable.** The real
one is 2014, in a different journal, runs five years not three, and reports something narrower.

**N = 795 (406 male, 389 female)** across five Australian high schools, annually **Grade 8 to
Grade 12**; **468 completed Grade 12**. Peer-based objective measure of social functioning
(friendship nominations), subjective EIS.

Verbatim: "EIS in early adolescence was predictive of friendships **for females** in late
adolescence. Specifically, girls starting out with low EIS in Grade 8 tended to have **fewer
female friendships and more male friendships** in Grade 12. **There were no effects for males.**
Lower initial EIS was associated with significant improvements in awareness over time, but
**these improvements had no effect on friendships in Grade 12.**"

**Cannot support:** a reciprocal model with perceived social support; any claim about males; or
a claim that improving emotion identification improves friendships — the paper tested that and
found nothing. **Use it for, if at all:** friendship *composition* in adolescent girls. Thin,
and Ciarrochi 2008 above is the better source for the social-support claim.

## Trentacosta & Fine, 2010 — pooled evidence for emotion knowledge and social outcomes

**Trentacosta CJ & Fine SE (2010)**, "Emotion Knowledge, Social Competence, and Behavior Problems
in Childhood and Adolescence: A Meta-Analytic Review," *Social Development* 19(1):1–29
([DOI](https://doi.org/10.1111/j.1467-9507.2009.00543.x); PMID 21072259, PMC2975582) —
**`full text read`**. Random-effects models.

| Relation | Mean r | Independent samples | Fail-safe N |
|---|---|---|---|
| Emotion knowledge × **social competence** | **.22** | 63 | 76 |
| Emotion knowledge × **internalizing problems** | **−.17** | 19 | 13 |
| Emotion knowledge × **externalizing problems** | **−.17** | 34 | 24 |

**Heterogeneity, and it matters for two of the three.** Social competence: heterogeneous, and
**none of the sample or method moderators explained it**. Internalizing: homogeneous, consistent
across community and clinic subgroups. Externalizing: heterogeneous, and it moves a lot —
community **−.13** vs clinic **−.26**, and by who rated the behaviour, placement status **−.37**,
observer **−.33** and DSM diagnosis **−.33** against parent **−.05**, teacher **−.14** and
combined sources **−.10**.

Authors' own framing: "relatively consistent yet **modest** relations."

**Use it for:** knowing what emotions are goes with being more socially competent, r=.22 across
63 samples. **Scope:** childhood and adolescence, and "emotion knowledge" is recognising and
labelling discrete emotions — a further construct again, not TAS-20 alexithymia and not
differentiation. **Cannot support:** the externalizing figure as a single number. Who does the
rating changes it by a factor of seven.
