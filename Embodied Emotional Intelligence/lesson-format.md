---
title: "Embodied Emotional Intelligence — Lesson Format"
subtitle: "The structure every lesson follows"
date: 2026-08-06
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
the lesson list — lives in `eei-lesson-guide.md`. This file covers shape and prose.
Checking claims — what to verify and when, plus the publishing checklist — lives in
`verification-checklist.md`. Run that alongside this one; it is not optional reading,
it is a pass you run per claim while drafting.

---

## Working process

Darryl drafts prose by hand in a parallel `.txt` file next to the lesson
(`lessons/NN-<slug>...txt`) — he overwrites it in place, so re-read it before responding
rather than working from a copy read minutes earlier. The assistant's job is research and
verification, not re-voicing him: hand back proposed edits as a numbered list with
reasons, not prose rewrites, and let him decide what to apply.

Revising text already in the `.md` goes one paragraph at a time, confirmed before moving
to the next. Do not batch fixes across a section, and do not fix something adjacent that
wasn't asked about — flag it and wait. When he questions a sentence, that is a question,
not authorization to rewrite the section around it.

Section build order for a lesson in progress: **The Challenge → The Benefit → The
Practice → What to Expect → The Evidence → The Overview → The Quotation** (reasons below,
under *How a lesson gets built*). A section below the one currently being revised is a
stale artifact of the old draft, not a base to edit, until it gets its own pass.

### Order of passes when revising a section that already exists

Learned the expensive way on Lesson 1's Evidence section, where dozens of wording edits
went into entries that a structural pass would have cut or merged outright.

**0. Read this file first.** The rework on Lesson 1 was mostly re-deriving rules already
written here — lead with the claim, define terms as they're used, keep notation out and
link the study. They were never consulted.

**1. Structural pass, whole section, before any wording.** For every entry, three
questions, answered in writing before anything gets reworded:
- Does it earn its place, or is it backing a claim this lesson doesn't make?
- Does it make one claim, or is it several studies stacked under one heading?
- Does it have its own citation? A paragraph without one is usually a footnote to the
  entry above it, and wants merging rather than a new headline.

Cut and merge decisions all get made here. Rewording an entry that's about to be deleted
is the single largest source of wasted passes.

**2. Verification pass on everything that survived.** Open the source. The ledger is a
pointer to a verified reading, not a substitute for one — an entry that doesn't say it was
read in full can't support specifics, and a thin entry reads as authoritative while being
unable to carry prose. Two of Lesson 1's worst errors came from writing off a one-line
ledger note and from copying a verb ("pooled") off the adjacent citation.

**3. Wording pass last.**

**4. After any cut, grep for what referenced it.** Removing Goyal's effect sizes silently
broke two other paragraphs that cited that range by digit. Deleting a number, a study, or
a claim is not a local edit.

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

*Exception — contemplative teachers.* For a teacher quoted from an oral or teaching
tradition, with no journal article or fixed edition to check against, corroboration
across multiple independent teaching pages or the tradition's own materials is enough —
it does not need to block publishing. This does not extend to research citations, which
still need the actual paper.

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

**A study used as illustration does not need its methods aired.** State limits where the
lesson's claims depend on the study. Where it is there to make something visible rather than
to carry a claim, the limits change nothing a reader would do or believe, and airing them
buys the reader nothing. The test is that question, not whether the study has limits —
every study has limits. The first lesson's heat-pad study was its most vivid, appeared in two
body sections, and had a four-entry walkthrough in The Evidence before anyone asked what a
reader was meant to do with fourteen self-selected participants. None of the practice
advice rested on it. The whole walkthrough came out.

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

**An effect size is defined by its control group, so figures from different studies rarely
compare.** Same intervention, same people, same outcome — change the control and the number
changes. Lesson 1's own citations run from d=0.30 (active controls) to g=0.95 (no control)
for roughly "mindfulness helps depression," and almost none of that spread is the practice
behaving differently. Two consequences: print a number and you owe the reader the control it
was measured against, and never rank two studies' effect sizes against each other unless the
paragraph's argument *is* about the control difference.

**Never state a comparison the paper doesn't make.** A study of children cannot support
"works better than in adults" however the numbers look beside an adult study. Setting three
papers' figures side by side is the lesson's claim, not the research's — and it is the
lesson that will be wrong.

**A paragraph with no citation of its own is a footnote — merge it into the entry above.**
Two in Lesson 1 opened by restating the entry they followed, which is why neither carried a
source. Giving them headlines would have dressed up the structural problem instead of
fixing it.

**State the direction of effect.** "Significant gains in depression, anxiety, and stress"
says the training made those worse. One noun cannot cover measures moving in both
directions.

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

**Sourcing caveats, absence claims, unbacked assertions, and numbers all have their own
checks — run `verification-checklist.md` per claim while drafting, not as a final pass.**
The rules that used to sit here moved there; this file keeps shape and prose.

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
than a plain noun, and worst where the reference is a safety instruction. The front
matter's `cross_references` still lists every intended lesson whether it exists or not —
that is the map of what to come back and link once each target ships.

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
mismatch rate, the DBT recovery and dropout numbers, the Volanen dose finding. Anything
still flagged goes in this list, and the lesson does not move to
`content/embodied-emotional-intelligence/eei/` until it's empty. Either verify against a
primary source or write the lesson without the number.

Hugo ignores fields it doesn't recognize, so these are safe to carry into published
content.

---

## Publishing checklist

Moved to `verification-checklist.md` — run it in full before a lesson ships.

---

## Length

There is no target length. It depends on the topic. Sleep and shame have far more
established research behind them than Turning It Up or De-escalation, and some
capacities need more practice detail than others. A lesson runs as long as its
material earns.

Do not pad a thin section to match the shape of a fuller lesson. A short Evidence
section saying the research is thin is correct, and better than three paragraphs about
adjacent studies that don't quite bear on it.
