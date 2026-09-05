---
name: naming
description: Good Native naming principles. Use when naming a new Good Native product, app, tool, repo, or package; when evaluating or shortlisting name candidates; or when writing or reviewing a "The name" rationale in a README or the org profile.
---

# Good Native naming

The canonical document is [NAMING.md](https://github.com/Good-Native/.github/blob/main/NAMING.md)
in the `.github` repo — fetch it if this summary is not enough or may be stale.
The org profile (`profile/README.md` in the same repo) carries each shipped
name's story in its overview panel; new names must be added there too.

## The principles

1. **Name the behaviour, not the features.** The namesake's natural behaviour
   mirrors what the software does. Test: "_X_ does _Y_ in nature; this software
   does _Y_ to _Z_." If that sentence can't be written, it's the wrong name.
2. **Native to place.** Names come from the Australian natural world. Every
   name anchors to a specific native species — built in when the name is the
   species (sundew, mopoke, currawong, paperbark), carried visually in the
   logo when it isn't (bloom → banksia, hover → blue-banded bee). Species
   local to Castlemaine / Box–Ironbark country are strongly preferred; the
   closer to home, the truer the name.
3. **Quiet confidence.** Understated over clever. No startup suffixes (-ly,
   -ify, Hub, AI), no compound mashups, no puns that need a beat to land.
4. **One word, everywhere.** Must survive repo, CLI command, package name,
   subdomain (`goodnative.co/x`), app store listing, and being spoken aloud.
   Lowercase must look natural.
5. **The rationale ships with the name.** A two-to-three sentence "The name"
   note in the README and the org profile panel, written when the name is
   chosen. Rejected candidates are never listed in READMEs or public docs.
6. **Respect.** Use common English species names; words from Aboriginal and
   Torres Strait Islander languages are not claimed as brands.
7. **Family, not formula.** Same temperament as the existing names, different
   character. When listing siblings, list the whole family consistently.

## Scope

- Products and tools (anything with an audience) get names and rationales.
- Plumbing (docs sites, infra, internal repos) gets plain functional labels.
- Features inside a product get descriptions (Notify Me, Releases), never a
  second brand.

## Running a naming session

Do NOT jump to candidates. A naming session has five stages, and the first
is a conversation.

### 1. Qualify — ask first, then wait

Ask the qualifying questions before generating anything (AskUserQuestion or
plain conversation; skip only the ones already answered by the brief):

- **The verb:** what does it actually _do_, in one verb-led sentence? Not the
  category ("bundle builder") — the behaviour worth naming is usually the
  differentiator, not the category.
- **The edge:** why will this one be better than the incumbents? What do the
  bad ones get wrong?
- **Who acts:** merchant, shopper, or machine? Who is the name spoken to?
- **Where it lives:** App Store listing, CLI, embedded in a storefront?
- **Temperament:** quiet background worker or front-of-store presence?
- **Adjacency:** which existing Good Native product will it sit next to most
  in conversation and on the profile?
- **Priors:** names or words already loved, hated, or reserved?

### 2. Research the local field — species first

Ground candidates in real species before wordplay. Search (web) for species
of **Castlemaine, the Box–Ironbark forests, and central Victoria** whose
_behaviour_ matches the verb from stage 1 — birds, native bees and insects,
reptiles, mammals, orchids and wildflowers, fungi, trees. Local field guides,
Connecting Country, Museums Victoria, and iNaturalist searches scoped to the
region are good sources. A plain nature word is allowed only when a specific
local species will carry the anchor in the logo — name that species at
shortlist time, not later.

### 3. Shortlist — distinct, not generic

Produce **6–10 candidates**, each with: species (or word + anchor species),
the one-sentence behaviour match, and its distinctiveness. Reject:

- generic common nouns a competitor could plausibly already use (bundle,
  boxy, combo, kit);
- words that drown in search results or existing software;
- anything whose behaviour sentence needs a stretch.

A good candidate feels ownable: rare enough to search, real enough to draw.

### 4. Verify

- Say it out loud — support call, standup, "have you tried \_\_\_?".
- Availability: `goodnative.co/x`, the relevant registry (Shopify App Store,
  npm, PyPI — check live, not from memory), trademark collisions, same-named
  software nearby.
- Family: at home in the org repo list; no near-duplicates in sound or
  meaning; whole-family sibling lists stay consistent.

### 5. Rationale

Write the "The name" paragraph. If it writes itself, ship it; if it needs
three drafts, return to stage 2. Names are durable — renaming is only for
legal conflict or genuine scope change, never fashion.

## When a name ships

- Add a "The name" section to the project README (chosen name only).
- Add the name story and a status tag (scoping / prototype / alpha /
  pre-release) to its overview panel in the org profile
  (`Good-Native/.github` → `profile/README.md`).
- If the name is a plain word, confirm the species anchor appears in the
  logo/brand work.
