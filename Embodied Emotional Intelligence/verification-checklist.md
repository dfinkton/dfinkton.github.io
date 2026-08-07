---
title: "Embodied Emotional Intelligence — Verification Checklist"
subtitle: "Run per claim while drafting, and once in full before a lesson ships"
date: 2026-08-06
status: internal working document
---

# Verification Checklist

`lesson-format.md` covers shape and prose. This file covers checking — what to verify,
and when. Verification is a pass you run per claim during drafting, not a read you do
once and remember. Run it early; a wrong citation changes the paragraph built on it, so
text reviewed before verification gets reviewed twice.

---

## Per-claim checks

**0. Check the ledger first.** `source-ledger.md` records every source already verified
in a previous lesson — what it measured, what it supports, what it cannot. Before
verifying a source, check whether it's already there; after verifying a new one, add it.

**1. Primary source only.** Research citations trace to the actual paper — never a
search-result summary, a blog post, a press release, or another paper's citation of it.
On lesson 1, a pasted description of a study claimed experts "catch and truncate thought
sequences faster than novices"; the actual paper never says this — "truncate" and
"faster" appear nowhere in it. The description was fabricated, and it read exactly like
an accurate one until the primary text was opened directly.

*Exception — contemplative teachers.* For a teacher quoted from an oral or teaching
tradition, with no journal article or fixed critical edition to check against,
corroboration across multiple independent teaching pages or the tradition's own
materials is enough. This does not extend to research citations.

**2. Results, not Discussion.** A claim traces to what a study measured and reported —
not to what its authors proposed as an explanation for it ("we speculate," "we
hypothesize," "this suggests"). On lesson 1, four separate papers on meditation and
mind-wandering all speculated that experienced meditators disengage faster; in every
case the measured data was frequency or intensity, never timing. The claim looked
corroborated because each paper's speculation echoed the last one — invisible unless you
check the Results section specifically, not just the abstract or the discussion.

**3. Aggregate ≠ per-instance.** "Less overall" and "faster/shorter each time" are
separate claims and need separate sources. A drop in total time spent in a state can
come entirely from it happening less often, with each instance costing exactly what it
always did. Check which one a source actually measured before writing either.

**4. The right label, not just the right number.** Cohen's d, Hedges' g, and a
standardized mean difference (SMD) read the same in prose but are computed differently,
and a source reports exactly one for a given result. Check which, rather than defaulting
to "d" as the generic term.

**5. A caveat needs a source the same way a claim does.** An unsourced hedge is an
unbacked claim wearing modesty, and it's harder to spot because it sounds careful.
Check it against what the authors actually state as their own limitation — usually
narrower and more specific than the generic doubt that comes to mind first.

**6. No claiming a literature is empty.** "Nobody has measured this" asserts something
about every study ever run and is the easiest sentence to write and the hardest to
defend. On lesson 1, four absence claims went in and three were wrong, each found false
by one search. Before writing one, go and look — and search in the vocabulary the source
tradition uses. A contemplative construct may be well studied under a name Western
clinical science doesn't use (*nonattachment* for impermanence, *appreciative joy* for
sympathetic joy).

**7. An unbacked claim gets cut, not labelled.** Marking something "untested" doesn't
rescue it — it puts an unsupported assertion on the page with a disclaimer attached.
Cut it or find the source. Exception: a claim so obvious nobody has studied it precisely
because nobody doubts it.

**8. Numbers need a source.** An invented figure reads exactly like a researched one.
If it can't be traced, cut it rather than softening it.

---

## Section- and lesson-level checks

**9. Duplication scan.** The same fact, same citation, making the same point, in two
body sections is duplication, not reinforcement — unless the second mention does
something for the reader the first one couldn't yet do (an early section setting up a
fact a later one returns to with more context is fine; restating it in different words
to make the same point isn't). Check every citation used more than once in the body.
**The Overview is exempt:** its job is to summarize the finished lesson for someone who
reads nothing else, so it may restate body facts freely (ruled on lesson 1). The scan
applies between the other body sections, and between body and Evidence only when an
Evidence entry adds nothing beyond what the body already said.

**10. Definitions sit at first mention.** After reordering or rewriting a section,
recheck that jargon and acronyms are still defined where the reader actually meets them
first. Revising a section can move its content earlier in reading order without moving
the definition it depends on along with it.

**11. Cross-references match.** `cross_references` in the front matter matches the
links actually in the lesson.

---

## Publishing checklist

Run once, in full, before a lesson ships.

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
16. **Run the section- and lesson-level checks above** (duplication scan, definitions at
    first mention, cross-references) once more against the finished lesson — they're easy
    to satisfy section-by-section while drafting and break when sections move.
