---
title: "Embodied Emotional Intelligence — Lesson Format"
subtitle: "The structure every lesson follows"
date: 2026-07-31
status: internal working document
---

# Lesson Format

Every lesson uses these seven parts, in this order, with these headers. The headers do
not change from lesson to lesson.

These are lessons in a workbook, not essays. They are instructional, structured the same
way every time, cited throughout, and meant to be returned to and re-run. The reader is
working on this themselves, and the aim is that they come away understanding the learning
and holding proven ways to embody it. Each lesson stands alone — readers arrive from a
search and may only ever read this one.

Series-level material — the thesis, the division of labour between overlapping lessons,
the lesson list — lives in `eei-lesson-guide.md`. This file covers shape only.

---

## How a lesson gets built

### Plan first

Before any prose, build section-by-section notes in `notes/NN-<slug>.md`. One heading per
lesson section, and under each:

- the claims that section will make
- the source behind each one
- whether that source has been checked against the primary text, or is still taken on trust
- what is still open

This is the file you work from and write back into. As each section gets drafted, record
what the sources actually said — especially where they disagreed with what you expected
them to say.

**Verification belongs here, not at the end.** A wrong citation changes the paragraph built
on it. On the first lesson there was no planning file, and the cost landed twice: sources
were checked after prose had already been written on top of them, so four claims had to
change late; and The Evidence shipped a draft missing entries for a claim the body was
making in three separate places. Both are planning failures, not writing failures.

The planning file also tells you when a section is ready. A section whose claims have no
sources yet is a section that will get written on assumption.

This sits alongside whatever the notes file already holds — scope, studies, framing, the
honest notes. It does not replace them; the topical material is what feeds it.

```markdown
## Plan — The Challenge
- Claim: [what the section will assert]
  - Source: [author, year, link]
  - Checked: yes / no / partial — [what was confirmed, what wasn't]
- Open: [question that has to be answered before this section can be written]

## Plan — The Benefit
...
```

Two things worth recording as you go, because both cost a round on the first lesson:
**where a source says something narrower than the claim it is being used for**, and
**which claims are yours rather than the literature's** — a claim from teaching experience
is not disqualified, but it has to be known as one before The Evidence gets built.

### Then draft, one section at a time, in this order

**The Challenge → The Benefit → The Practice → What to Expect → The Evidence → The
Overview → The Quotation.**

Not the order they appear in, and each position has a reason:

- **The Evidence** has to answer to whatever the body ended up claiming, so it cannot be
  written until the body has settled.
- **The Overview** summarizes a finished lesson. There is nothing to state flat until
  there is something settled to state.
- **The Quotation** goes last because it has to be tested against the body, and until the
  lesson exists there is no body to test it against. On the first lesson the original
  epigraph led on *allowing* — a capacity that lesson explicitly hands to Observation — and
  that was only visible once everything else was finished.

**Do not draft the whole lesson in one pass.** The first lesson was written that way and
had to be rebuilt section by section. The failure is not visible while it is happening — a
lesson drafted in one pass reads as though it holds together, and only comes apart when
each claim gets checked against its source.

**A section you have not revised yet is a stale artifact, not a draft to edit.** Once the
sections above it have been rewritten, whatever sits below was written against a body that
no longer exists. Rebuild it from what the lesson now claims. Editing it into shape carries
the old lesson's assumptions forward invisibly.

---

## 1. Quotation

One quotation at the top, no header.

**Job:** frame the lesson. Set up the tension it resolves. Not decoration, and not a
restatement of the title.

**Length:** one to three sentences.

**Test it against the body,** the same way an analogy gets tested. Two ways this goes
wrong. A quotation that leads on a capacity the lesson hands to a different lesson points
the reader away before they start. And a quotation that contradicts the body is worse than
none — William James on attention being *"the very root of judgment, character, and will"*
is the most-quoted line in the field and directly contradicts a lesson that says attention
does not teach you judgment. The obvious epigraph is often the wrong one.

**Verification:** traced to a primary source — the actual book, paper, interview, or
translation. Quote sites are not sources. A series that promises *what we know and
don't* cannot open with something the internet invented. Untraceable means cut it; a
lesson may ship without a quotation rather than with a false one.

```markdown
> Quotation text goes here.
>
> — Author Name, *Title of Work* (year)
```

---

## 2. The Overview

Definitions, any context, and a brief overview.

**Job:** say what this capacity is and what the reader is going to learn, up front. The
takeaway goes here, stated flat — someone who reads only this section still gets the
point.

This also carries the grounding that makes the lesson standalone. Define the terms
this lesson uses, including ones defined in other lessons. Re-establish the dashboard
framing in a couple of sentences where it's needed. Don't reproduce the curriculum page.

**Failure mode:** teasing. No "we'll come back to what to do about this."

---

## 3. The Challenge

Why does this matter? What problems do we typically see? How does that impact our
lives?

**Job:** the default — what people do automatically, and the misconception underneath
it. Most lessons have one organizing correction and it belongs here: *a boundary is
what you will do, not what someone else must do*; *repair attempts are universal, what
differs is whether they're accepted*; *avoidance hides inside apparent approach*.

**Requirement:** write the variants richly enough that readers recognize their own.
Anger escalates in one person, withdraws in another, comes out as a cutting remark
delivered calmly in a third. A reader who can't tell which is theirs will pick the
wrong method in The Practice. This is where that identification happens — it does not
need a separate prompt, but it does need to be written for.

**Failure mode:** a strawman. The default has to be something the reader recognizes
doing.

---

## 4. The Benefit

The learned adjustment: what it looks like in practice, what it does to help, and where
it stops.

**Job:** show the destination before asking for the work. This is what embodiment of
this particular capacity looks like from the inside — concrete, not aspirational.

**Limitations here are about the capacity, not the research.** What this adjustment
cannot fix, who it helps less, what it does not replace. Research uncertainty belongs
in The Evidence. Keeping these apart stops the same caveat being written twice in
different words.

---

## 5. The Practice

The most supported ways to work on this, **ordered most effective first where the evidence
supports a ranking.**

**Job:** the methods. Plural — this is a practice, not an exercise. What actually works,
in what order, and what to do when the first approach isn't available.

**Where nothing ranks, say so.** Sometimes the honest finding is that the options are
interchangeable and the choice is personal. No anchor for attention works best for
everyone, and the research showing that people mispredict which one will suit them is more
useful to a reader than a ranking would be. Inventing an order the evidence does not
support is worse than presenting a set and saying how to choose.

**Include the dose.** Embodiment is repetition until effort becomes reflex, so a method
without a schedule is incomplete: how often, how long per session, how long before it
starts to take. Where the research specifies conditions that make a practice work or
fail, that's the most useful material in the lesson — slow breathing needs sessions of
at least five minutes and multiple sessions; fast-only paces and interrupted sessions
kill it.

**Safety:** where a practice can make things worse before better, say so *here*, at the
point of instruction, as well as in What to Expect. A reader can act on this section and
never scroll further. What counts as worse-before-better is specific to the practice, so
it comes out of that lesson's own evidence rather than from a rule set in advance.

**Failure mode:** abstraction. "Notice your patterns" is not a practice.

---

## 6. What to Expect

How the practice actually goes — the arc, the stalls, how it varies from person to
person.

**Job:** tell the reader what the road looks like. When something shifts, what it feels
like along the way, where people commonly stop, what a plateau means, and who this
tends to work less well for.

The rough patch goes here in full. So does the honest version of a good result: slow
breathing reliably moves the physiology, and whether it moves how you *feel* depends on
how activated you were to begin with. Say that rather than promising calm.

---

## 7. The Evidence

Why we think this, how the studies were built, and where it's uncertain or contested.

**Job:** depth, not justification. Claims are already attributed where they're made, so
this section isn't carrying the argument — it's for the reader who wants to know how we
know.

**Lead each entry with the claim, not the study.** The unit is a claim the lesson makes,
followed by how we know it — how the study was built, who was in it, what was measured,
what came out, and where it is thin. A study backing three claims gets three entries, and
that repetition is the point: a reader arrives holding one claim and has to be able to find
it. Organizing by study instead buries the answer inside material about something else.

**Follow the order the reader met the claims in.** They came from a specific place in the
body and will look for them in the same sequence.

**Then the uncertainties and the opposing views** — Barrett against Panksepp, the
methodological criticism of Gottman's prediction figures, the fact that
emotion-differentiation research is mostly correlational. This half is not answerable to
the body. It guards against claims the reader will import on their own.

**The section is not limited to what the body claims.** It also serves someone who wants to
go deeper into the literature, so a strong study earns a place even when nothing above
cites it — marked as going further than this lesson claims.

**Subheadings are fine here.** When the section gets long enough to need scanning, group
the entries under `###` headings of your own. The seven top-level headers are what stay
fixed from lesson to lesson; what happens inside one does not.

**Written in standard English, with any technical term defined as it's used.** The model
is a gloss in passing: *"the regions of their brains that register salience—how much
something grabs your attention."* A few words, not a sentence of throat-clearing.

Which means precise notation mostly stays out. Write *a small-to-medium improvement*
rather than an effect size and a confidence interval, and **link the study** so anyone
who wants the figures can go get them. Where an exact number genuinely does work for
the reader, give it plainly and say what it means.

---

## Rules that cut across every section

**Cite throughout.** Attribution in prose at the point of the claim, with a link —
*in a nine-month study, adults were trained in three practices one after another.*
Enough that a reader knows this isn't opinion. The Evidence section then carries the
detail. There is no separate bibliography; The Evidence is the reference section, in
prose.

**Signal confidence inline, when it is relevant.** *Reliably*, *in one small trial*, *this is the
weakest-evidenced part of an otherwise strong method*. Many readers will stop before
The Evidence, and they should not come away believing more than we know.

But this is not a licence to hedge everything, and hedging is not free — a body paragraph
loaded with qualifiers is one the reader stops trusting and stops finishing.

**The test is what it costs the reader to be wrong.** *Attention practice is not a treatment
for ADHD* carries a real cost and gets its caveat at the point of the claim. *You notice
sooner when you have drifted* costs a reader nothing if it turns out to be softer than
stated, so it goes in clean with a citation and the calibration waits. Say it cleanly, cite
it, and let The Evidence carry how strong each leg is.

This is also the test for whether an objection to a draft is worth raising at all. A
limiting claim, a safety instruction, or an illustrative vignette costs a reader nothing if
it turns out softer than stated. Matching a rule against one of those produces a correction
that is technically defensible and wastes the round — *this figure has no source* is not a
finding when the figure is a vignette in a passage explicitly about how something feels from
the inside.

**A caveat needs a source the same way a claim does.** An unsourced hedge is an unbacked
claim wearing modesty, and it is harder to spot because it sounds careful. *Findings about
brain structure changing after brief training have a poor track record* went into the first
lesson with nothing behind it — whose findings, which failures, how poor. Worse, it
displaced what the authors did report: that each module's cortical change tracked that same
person's improvement on the behaviour it trained. The hedge was not just unsupported, it
contradicted the paper.

So before writing a limitation, read what the authors state as theirs. It is usually more
specific and more interesting than the generic doubt — in that study, that this work can
only be done with non-invasive scanning, so they can *"merely speculate about the
neurobiological mechanisms."* That is a real limit. *Poor track record* is a mood.

**An unbacked claim gets cut, not labelled.** If a claim has nothing behind it, marking it
as untested does not rescue it; it puts an unsupported assertion on the page with a
disclaimer attached, and a curriculum full of those is a curriculum nobody should trust. Cut
it or find the source. The one exception is a claim so obvious that nobody has studied it
precisely because nobody doubts it — *planning helps you avoid some pain*, *a crisis that is
eating your attention will keep eating it until it is dealt with*. Those read as unbacked
because there is no trial to run.

**Write for the self-guided reader.** Every lesson assumes one person doing this for
themselves. Someone may have pointed them here, and that is all the pointing needs to
be — hand a motivated person the link. No helper notes and no instructions for running
this with someone else. That is a different project with limited upside, and a reader
who isn't motivated won't be carried through it by one who is.

Lessons whose subject is other people — repair, boundaries, de-escalation — are still
about the reader's own relationships. And telling a reader to involve someone else for
their own safety is not a helper note; it stays.

**Cross-references are inline links** at the point the other lesson becomes relevant.
No closing "related lessons" block; it implies the reader is mid-sequence.

**Only link a lesson that has already shipped.** Until then, name the capacity in prose
and leave it unlinked — *Observation is where allowing gets trained*. A dead link is worse
than a plain noun, and worst where the reference is a safety instruction: the first lesson
went live telling a reader whose habit of leaving their body is old and familiar to start
with Observation instead, and that link 404'd. The front matter's `cross_references` still
lists every intended lesson whether it exists or not — that is the map of what to come back
and link once each target ships.

**Plain English everywhere,** not only in The Evidence — see the two-pass process
below. That section is just where jargon accumulates fastest.

---

## Prose style

Clarity above everything. When a simple explanation will do, use it. These rules are about
sentences, not structure, and they apply to every section.

**Say the thing.** Cut the throat-clearing that introduces a claim instead of making it.
*The framing this series uses is that emotions are dashboard lights* is worse than
*emotions are information, lights on a dashboard.* Same for *here is the whole point,
stated flat, so that a reader who reads nothing else still has it* — just state the point.
*And what happens next is the entire lesson* is filler; write what happens next.

**Do not narrate the document.** No *we will come to that*, no *the rest is detail:
what people do instead, what the returning gets you...*, no *see The Evidence*, no
table of contents for a page the reader can see. Each lesson stands alone, so it should
not read as a chapter aware of its own position. Inline cross-reference links to other
lessons stay — those are for the reader, not the narrator.

**The narrator recedes.** First person is fine occasionally, and it earns its place most
in The Evidence, where a judgment is being made — *I would treat this as promising rather
than established.* Elsewhere, prefer the claim over a report of the claim.

**Every analogy must teach, and it should do one job.** A good one reaches something the
prose around it cannot: *the best players in the world miss about half their shots, and
they never stop missing. Nobody watches a professional miss and concludes they cannot
shoot.* That earns its place by going at the reader's self-judgment, which a flat statement
of the mechanism does not touch.

A weak one gestures at meaning it does not deliver: *the lift is the repetition and
standing at the bar is not.* If the reader has to work out what maps to what, cut it.

**Cut the parts the prose already covered.** That basketball analogy originally carried the
mechanism as well — *a fast, quiet feedback loop: that one was long, that one drifted left,
adjust, shoot again* — sitting one paragraph after the mechanism had been stated plainly.
Re-teaching in figurative terms what was just taught in literal ones costs the reader
twenty words and returns nothing.

**Test the mapping against the rest of the lesson.** An analogy implying a claim the
evidence section contradicts is worse than no analogy. Watch too for one that argues a
neighbouring claim rather than the one it sits under: a shooter's feedback loop exists to
make the next shot go in, which maps to drifting *less* — not to the return being the
practice, which is what that paragraph was actually about.

**Never flatten a gradient into a binary.** This is the most common way the writing goes
wrong, because binaries sound crisp. *It never stops* and *you can move this a lot but
never to zero* are different claims, and the second one is both truer and the one that
makes someone practice. Watch for *never*, *always*, *what never happens is*, and for
absolutes smuggled in as emphasis — *their minds still went everywhere* when what happened
is *they still wandered*. Where two things both improve, say both and say how they compound.

Note this is the sentence-level twin of the pass-two rule below about deleting qualifiers.
There, nuance is lost by simplifying vocabulary. Here, it is lost by reaching for a
stronger, cleaner-sounding claim than the evidence supports.

**State the fact, link the source, move on.** Study design does not belong in the body.
*Experienced meditators with more than a thousand hours of practice, asked to watch their
breath for twenty minutes, still lost it about fifteen times* plus a link is the body
version. Participant counts, control conditions, effect sizes, confounds and the authors'
own caveats go in The Evidence, which exists for exactly this. A body paragraph that stops
the instruction to explain a study is in the wrong section.

**Numbers must have a source.** If a figure cannot be traced, cut it rather than softening
it. An invented *about fifteen seconds of noticing* reads exactly like a researched one,
which is the problem.

---

## Writing in two passes

Write for clarity first. Fix vocabulary second. Never both at once — simplifying while
still working out what you think produces prose that is easy to read and says nothing.

### Pass one — clarity

Get the thinking right. Use whatever vocabulary the idea needs. Full nuance, every
qualifier, every distinction, every conditional. Simplify nothing yet.

### Pass two — vocabulary only

Go back and replace words a reader at a 7th-grade reading level is unlikely to know.

**Change words. Never change claims.** The target is 7th-grade vocabulary carrying adult
content — not 7th-grade content.

Sort every hard word into one of three piles:

1. **Jargon with a plain equivalent** — *ameliorate*, *utilize*, *efficacious*,
   *modulate*. Replace it. Nothing is lost.
2. **Terms that are the concept** — *decentering*, *co-regulation*, *granularity*,
   *interoception*, *randomized controlled trial*. Keep the word, define it in passing,
   and expect the reader to leave owning it. The introduction makes this argument
   itself: observation needs a vocabulary, and a vague sense that something is wrong
   cannot be reasoned with. It keeps Panksepp's SEEKING and RAGE and teaches them rather
   than translating them away. Some of these words are what the reader came for.
3. **Qualifiers, hedges, distinctions and conditionals** — pass two does not touch these
   at all.

### What this pass must not do

Nuance is rarely cut on purpose. It goes in four edits that each look like
simplification:

- **Deleting a qualifier.** *Slow breathing reliably moves the physiology, and whether
  it moves how you feel depends on how activated you were to begin with* becomes
  *breathing helps you calm down.* Simpler words, finding gone.
- **Collapsing a distinction.** Shame and guilt become "feeling bad." Care and
  compassion become "caring." Those distinctions are usually the whole lesson.
- **Dropping a hedge.** *In one small trial* disappears, and tentative becomes certain.
- **Chopping a sentence that was carrying a conditional.** *X, unless Y, in which case
  Z* becomes three short sentences that sound true and lost the "unless."

### Expect the lesson to get longer

*Interoception* becomes *your sense of what's happening inside your body* — one word to
nine. Growth during pass two is the pass working. If a lesson shrinks, check what went
missing.

### 7th grade is a heuristic, not a score

The test is *would a 7th grader know this word.* Do not run a readability formula and
write toward the number. Flesch-Kincaid and its relatives measure syllables per word and
words per sentence; they cannot see nuance, so the fastest way to improve a score is to
delete conditionals. Writing toward the number causes the exact damage this pass exists
to prevent. Long sentences in plain words are fine.

Both passes cover the whole lesson, not only The Evidence.

---

## Front matter

```yaml
---
title: "Lesson Title"
lesson: 12                    # 1–42
part: "Part Two — The Drives"
date: YYYY-MM-DD
description: "One sentence. Required — drives search and LLM retrieval."
weight: 120                  # lesson number × 10
cross_references: [13, 19]   # every lesson this one links to, plus any the notes plan
unverified: []               # must be empty before publishing
aliases: []
---
```

`unverified` is the publishing gate. The notes carry flagged figures — Tronick's 70%
mismatch rate, the DBT recovery and dropout numbers, Slagter on the attentional blink,
the Volanen dose finding. Anything still flagged goes in this list, and the lesson does
not move to `content/embodied-emotional-intelligence/eei/` until it's empty. Either
verify against a primary source or write the lesson without the number.

Hugo ignores fields it doesn't recognize, so these are safe to carry into published
content.

---

## Publishing checklist

1. `unverified:` is empty.
2. Quotation traced to a primary source, and tested against the body.
3. All seven parts present, in order, with the standard headers.
4. Reads cold — terms defined, no dependence on having read anything else.
5. The Challenge is written so a reader can identify their own variant.
6. The Practice includes a dose, and flags worse-before-better where it applies.
7. Pass two done across the whole lesson — no unglossed jargon left, and every
   qualifier, hedge and conditional from pass one still standing.
8. The Evidence links out to the studies rather than printing effect sizes, and every
   claim the body makes has an entry. A claim asserted in three sections and answered in
   none is the easiest thing to miss when the section gets rebuilt.
9. `description` set, and `cross_references` matches the links actually in the lesson.
10. Moved to `content/embodied-emotional-intelligence/eei/`, filename **without** the
    lesson number — the URL is `/eei/<slug>/` and the numbering stays internal. Check for
    a byte-order mark before the front matter; shell redirects on Windows add one silently
    and it breaks front-matter parsing.
11. **Linked from the curriculum page.** The spiral lists in
    `content/embodied-emotional-intelligence/eei/_index.md` are the navigation hub — turn
    this lesson's entry into a link when it publishes. Hand-maintained, so it drifts
    silently if skipped.
12. Added to `static/llms.txt` — also hand-maintained, same failure mode.
13. **Inbound links added from lessons already published.** Any live lesson that names
    this capacity in prose can now link to it. Check each published lesson's
    `cross_references` for this lesson's number — that is the list of pages waiting on it.
    Skipped, and the curriculum quietly stays a set of disconnected pages.
14. **No lesson count anywhere a reader or crawler sees.** Publicly this is a yearlong
    curriculum designed to be repeated. Internally there are 42 lessons and the numbering
    is used freely; the number stays out of page descriptions, the homepage, `llms.txt`,
    and link text.
15. **Anything this lesson now covers properly comes off the curriculum page.** That page
    previewed lessons before they existed. When a lesson ships, its share of that preview
    moves into the lesson or into the notes, so the two do not say the same thing at
    different levels of rigour.

---

## Length

There is no target length. It depends on the topic. Sleep and shame have far more
established research behind them than Turning It Up or De-escalation, and some
capacities need more practice detail than others. A lesson runs as long as its
material earns.

Do not pad a thin section to match the shape of a fuller lesson. A short Evidence
section saying the research is thin is correct, and better than three paragraphs about
adjacent studies that don't quite bear on it.
