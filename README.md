<p align="center">
  <a href="https://grothendieck.space/"><img src="assets/banner.png" alt="Grothendieckian Universe — the D6 craft in its glass, its seven cells lit, one cell for each world of The Grothendieckian Programme" width="100%"></a>
</p>

<p align="center">
  <a href="https://grothendieck.space/"><img src="https://img.shields.io/badge/play-grothendieck.space-7FE9DE?style=flat" alt="Play at grothendieck.space"></a>
  <img src="https://img.shields.io/badge/worlds-7-536372?style=flat" alt="Seven worlds">
  <img src="https://img.shields.io/badge/levels-57-536372?style=flat" alt="57 levels">
  <img src="https://img.shields.io/badge/puzzles-221-536372?style=flat" alt="221 puzzles">
  <img src="https://img.shields.io/badge/languages-English%20%C2%B7%20%E4%B8%AD%E6%96%87-536372?style=flat" alt="English and Chinese">
  <img src="https://img.shields.io/badge/license-CC%20BY--NC--ND%204.0-0A131E?style=flat" alt="Licence: CC BY-NC-ND 4.0">
  <img src="https://img.shields.io/badge/privacy-no%20cookies%20%C2%B7%20no%20trackers%20%C2%B7%20no%20third--party%20requests-536372?style=flat" alt="No cookies, no trackers, no third-party requests">
</p>

<p align="center">
  <b><a href="https://grothendieck.space/">Play</a></b> ·
  <a href="#the-seven-worlds">Seven worlds</a> ·
  <a href="#how-the-game-teaches">How the game teaches</a> ·
  <a href="#the-repository">The repository</a> ·
  <a href="#licence-and-rights">Licence</a> ·
  <a href="README.zh-CN.md">中文</a>
</p>

<br>

# Grothendieckian Universe

**A puzzle game constructed from the seven published works of The Grothendieckian Programme.**

Grothendieckian Universe is a browser-based puzzle game built on the mathematical content of
[The Grothendieckian Programme](https://alienmuse.space/) by Vincent Liu: seven works, each addressing one
problem or one architecture of machine reasoning. The game converts that content into interactive form. A level
does not summarise a book; it makes the reader perform the operation the book performs — glue local data where it
agrees, locate the obstruction where it does not, and transport a problem into a setting in which it can be
answered at a stated cost.

Seven worlds, one per work. Fifty-seven levels, each anchored to one idea of its work. Two hundred and twenty-one
puzzles across thirty-two interaction types. Playable in English and in Chinese, free of charge, without an account,
without cookies, and without a request to any third-party origin.

## Design principles

The game is governed by four constraints, each enforced by an automated check rather than by editorial intent.

1. **Every level is one idea of its book.** Levels are not themed decoration around a mechanic; the mechanic is
   the idea. Where a book proves a theorem, the level asks the player to carry out the corresponding construction
   in a finite, complete setting.
2. **Every quotation is the book's own wording.** Each discovery card closes with a passage printed in the work,
   identified by chapter. All 245 quotations are verified verbatim against the printed sources.
3. **Every claim outside the books is verified against an authority.** Named theorems, numerical facts and named
   results are checked against external references and recorded in a claim register.
4. **Every level states its boundary.** Each discovery card carries a line beginning *not established here*,
   naming precisely what the level does not claim. A level may teach an idea without asserting the theorem that
   the idea belongs to.

## The seven worlds

The worlds open in sequence: S01, then S02, then the four works on open problems in any order, then S07.
Progress is saved automatically. Each world below is given by the mathematical object it works with, the operation
the player performs on that object, and the obstruction the world teaches the player to locate.

| | World | Work | Levels | Object · operation · obstruction |
|---|---|---|---|---|
| **S01** | The Grothendieckian Machine | *GAI-MUA*, six volumes | 19 | **Object:** a cover of a site by pieces of a ring or a space. **Operation:** glue a family of local sections across every overlap; restrict, compare, then publish a global section. **Obstruction:** the first of five gates that fails — restriction, common points, compatibility, uniqueness, existence — and, in the boss level, a triple-overlap cocycle that closes only when the core is glued first. |
| **S02** | Topos-Native Intelligence | *GM-Ω∞*, five volumes | 16 | **Object:** a site, its presheaves, and the subobject classifier. **Operation:** assemble a cover from evidence, transport values into shared stalks, glue them to a section, or compute the class that prevents it; then evaluate propositions by forcing over the site's stages. **Obstruction:** a non-zero cohomology class on the nerve, where pairwise and triple agreement still fail to compose. |
| **S03** | Arithmetic Spectral Descent | *ASD* | 4 | **Object:** the spectrum of a Frobenius operator under an indefinite form. **Operation:** count points of a curve over a finite field, watch the roots of the zeta function land on the circle \|α\| = √q, then rotate the form and track where eigenvalues cross the critical line. **Obstruction:** an index bound, min(n₊, n₋), rather than a positivity — and a bridge whose final span is a proved implication from open hypotheses, and is therefore left dashed. |
| **S04** | Fractured Adelic Geometry | *FAG* | 4 | **Object:** an elliptic curve over ℚ together with its local points at every place. **Operation:** test local solubility prime by prime, add points by the chord-and-tangent law, and compare the two sides of the BSD identity for a specified curve. **Obstruction:** a Tate–Shafarevich class that is trivial at every place and non-trivial globally — everywhere local, nowhere global — and the rank-one barrier that stops every Gross–Zagier theorem at the first derivative. |
| **S05** | The Archimedean Prism | *TAP* | 5 | **Object:** the Hodge conjecture as a machine of four steps, each consuming a different hypothesis. **Operation:** locate the single step that requires an ample class, then grade every claim about it on a four-rung ladder — computation, enclosure, exact verification, formal kernel. **Obstruction:** a positivity statement that is open in codimension two and beyond, and a gap that is named exactly without being closed. |
| **S06** | Strained Prismatic Geometry | *SPG* | 4 | **Object:** the abc conjecture, and the derivation that would make it provable. **Operation:** search for triples of high quality, compare degrees over polynomials where the theorem holds, and attempt to construct a non-zero derivation of ℤ. **Obstruction:** every derivation of the integers is zero — the integers have no base over which to differentiate — so every surrogate must change either the law or the object. |
| **S07** | The Arithmetic Topos | *TAT* | 5 | **Object:** an arithmetic curve together with its local charts at every prime and at infinity. **Operation:** count points of an elliptic curve and expand the coefficients of its L-series, verify that the two agree, and count fixed points of a torus endomorphism by one minus trace plus determinant. **Obstruction:** the Main Conjecture, printed in the game's closing ledger as *C* — and a constitution in which no printed status may exceed the strength of its proof. |

The final level, **S07-05 The arithmetic curve**, is the game's closing boss: the player assembles the whole from
its local charts and publishes the ledger as it stands, with the dashed line left where the mathematics leaves it.

## How the game teaches

Each level is a sequence of four puzzles, following the classical progression *introduce, develop, twist,
conclude*. Each world ends in a boss level whose final puzzle requires every operation the world has taught.

**The board.** A puzzle presents one question and a small complete structure: a finite ring, a cover of a space,
a nerve of evidence, a curve over a small field, a lattice of points, a matrix pair. The player acts directly on
that structure — selecting cells, pushing pieces together, drawing a path, rotating arrows, sorting claims into
bins, or choosing among formal statements.

**The proposer.** Two hints are available on request. The first identifies where to look; the second names the
relation that decides the question. Neither computes the answer. Using them is recorded in the ledger and affects
the honesty rating shown on the discovery card.

**The discovery card.** Successful play opens a card with four elements: a one-sentence statement of the idea, the
formula that the idea is, a verbatim quotation from the work with its chapter, and the boundary line naming what
the level does not establish. The card is the unit of pedagogy; the boundary line is what keeps the pedagogy
honest.

**The ledger.** Every move, hint, undo, restart and stamp is recorded. The published state of a level — done,
fewest moves, honest — is derived from the ledger, not assigned.

## Playing

- **In the browser:** [grothendieck.space](https://grothendieck.space/). English is the default language. The
  **ZH** control in the top-right corner switches the entire interface in place, without reloading the page and
  without losing the current puzzle's state.
- **On a phone:** the same URL. The layout is designed for portrait and landscape phones as well as desktop.
- **Accessibility and privacy:** the game is keyboard-operable, respects reduced-motion preferences, sets no
  cookies, performs no tracking, and issues no request outside its own origin. Its fonts are bundled, its images
  are generated at build time, and its sound is synthesised in real time.

## The repository

This repository is the public face of the game. It contains the licence, the policies, the banner, and the built
site that GitHub Pages serves. It does not contain the game's source.

The engine — the kernel that decides whether a configuration glues, the thirty-two puzzle kinds, the level
definitions, the rendering, the audio synthesis, and the automated checks that verify them — is the copyright of
Vincent Liu and is not published here.

| Path | Contents |
|---|---|
| `site/` | the built game, byte-for-byte as deployed to grothendieck.space, including the Chinese page at `site/zh/` |
| `assets/` | the banner and the social preview image |
| `LICENSES/` | third-party licences: three.js (MIT), the TGP faces (GUST), STIX Two Math and Orbitron (SIL OFL 1.1) |
| `NOTICE.md` | the licence of each part of the game, and the uses that require permission |
| `SECURITY.md` | reporting impersonation, modified copies, and security problems |
| `TRADEMARKS.md` | permissible use of the name and the mark |
| `CITATION.cff` | citation metadata in Citation File Format |

## Licence and rights

- **The game** — its code, design, levels, scenes, art and sound: © 2026 Vincent Liu. **All rights reserved.**
- **The game's own text** — level titles, lines, hints and discovery cards: **CC BY-NC-ND 4.0**.
- **The quotations:** each is the wording of its work and carries that work's licence as printed on its
  copyright page (CC BY-NC-ND 4.0 for all seven works).

**Permitted without request:** playing the game; teaching with it in a classroom; streaming, recording, reviewing
and producing commentary on it, including the ordinary revenue such platforms pay.

**Requires prior written permission:** brand or commercial promotion; paid courses and training; commercial
events; inclusion of the game, its levels, art or sound in a commercial product or service; adaptations and ports.

**Not permitted:** copying, mirroring or republishing the game, in whole or in part.

Requests: [vincent.liu@wisemotif.ai](mailto:vincent.liu@wisemotif.ai). See [NOTICE.md](NOTICE.md) and
[TRADEMARKS.md](TRADEMARKS.md).

## Elsewhere in the Programme

- [**AlienMuse.space**](https://alienmuse.space/) — the author's own site: the Programme, the works and the essays.
- [**Grothendieck Lab**](https://grothendiecklab.com/) — the Programme's official site: the seven works with their
  pages and DOIs.
- [**The works this game is built from**](https://grothendiecklab.com/works/) — each work, its licence and its record.

## Authenticity

The authentic build is the one served from https://grothendieck.space/ and the one contained in `site/` of this
repository. Reports of modified copies, impersonating accounts, or files bearing these names with different
contents are handled under [SECURITY.md](SECURITY.md).
