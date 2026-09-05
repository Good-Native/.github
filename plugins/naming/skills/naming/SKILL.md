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
2. **Native to place.** Names come from the Australian natural world — species
   or plain nature/growth words. Every name anchors to a specific native
   species: built in when the name is the species (sundew, mopoke, currawong,
   paperbark), carried visually in the logo when it isn't (bloom → banksia,
   hover → blue-banded bee). Prefer species local to Castlemaine, Victoria.
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

## Choosing a name — checklist

1. Write what the software does in one verb-led sentence; shortlist natural
   namesakes whose **behaviour** matches. Behaviour first, aesthetics second.
2. Say it out loud — support call, standup, "have you tried \_\_\_?".
3. Check availability: `goodnative.co/x`, the relevant registry (npm, PyPI,
   Shopify App Store), trademark collisions, same-named software nearby.
4. Check the family: at home in the org repo list, no near-duplicates in
   sound or meaning.
5. Write the rationale. If the "The name" paragraph writes itself, ship it;
   if it needs three drafts, return to step 1.

Names are durable — renaming is only for legal conflict or genuine scope
change, never fashion.

## When a name ships

- Add a "The name" section to the project README (chosen name only).
- Add the name story to its overview panel in the org profile
  (`Good-Native/.github` → `profile/README.md`).
- If the name is a plain word, confirm the species anchor appears in the
  logo/brand work.
