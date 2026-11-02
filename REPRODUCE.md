# How this repository was made (Barra do Piraí)

This file is written by the build on 2026-11-02, the day the source data was retrieved.

## Sources

| Source | Address | Retrieved | Licence |
| --- | --- | --- | --- |
| Câmara Municipal de Barra do Piraí, SAPL: records of the municipal laws and their PDFs (newest first) | <https://sapl.barradopirai.rj.leg.br/norma/pesquisar> | 2026-11-02 | Texts: Câmara Municipal de Barra do Piraí, SAPL (Sistema de Apoio ao Processo Legislativo), sapl.barradopirai.rj.leg.br; SAPL: "Conteúdo e dados sob licença Creative Commons 4.0 Atribuir Fonte - Compartilhar Igual". Lei 9.610/1998 art. 8 IV: the texts of laws and other official acts are not protected by copyright. Non-official text: only the official gazette is authoritative. |
| Câmara Municipal de Barra do Piraí, SAPL: records of the municipal laws and their PDFs (newest first) | <https://sapl.barradopirai.rj.leg.br/norma/pesquisar> | 2026-11-02 | Texts: Câmara Municipal de Barra do Piraí, SAPL (Sistema de Apoio ao Processo Legislativo), sapl.barradopirai.rj.leg.br; SAPL: "Conteúdo e dados sob licença Creative Commons 4.0 Atribuir Fonte - Compartilhar Igual". Lei 9.610/1998 art. 8 IV: the texts of laws and other official acts are not protected by copyright. Non-official text: only the official gazette is authoritative. |
| Câmara Municipal de Barra do Piraí, SAPL: records of the municipal laws and their PDFs (newest first) | <https://sapl.barradopirai.rj.leg.br/norma/pesquisar> | 2026-11-02 | Texts: Câmara Municipal de Barra do Piraí, SAPL (Sistema de Apoio ao Processo Legislativo), sapl.barradopirai.rj.leg.br; SAPL: "Conteúdo e dados sob licença Creative Commons 4.0 Atribuir Fonte - Compartilhar Igual". Lei 9.610/1998 art. 8 IV: the texts of laws and other official acts are not protected by copyright. Non-official text: only the official gazette is authoritative. |
| Câmara Municipal de Barra do Piraí, SAPL: records of the municipal laws and their PDFs (newest first) | <https://sapl.barradopirai.rj.leg.br/norma/pesquisar> | 2026-11-02 | Texts: Câmara Municipal de Barra do Piraí, SAPL (Sistema de Apoio ao Processo Legislativo), sapl.barradopirai.rj.leg.br; SAPL: "Conteúdo e dados sob licença Creative Commons 4.0 Atribuir Fonte - Compartilhar Igual". Lei 9.610/1998 art. 8 IV: the texts of laws and other official acts are not protected by copyright. Non-official text: only the official gazette is authoritative. |

Every word of law in this repository comes from these sources. Lexifina reads them and records each act's dated versions, and the laws that made each change, in one corpus file. This repository is built from that file.

## What is in it

| Act | Title | Versions | Span |
| --- | --- | ---: | --- |
| `lei-2026-04423` | Lei nº 4.423, de 31 de agosto de 2026 | 1 | 2026-09-01 to 2026-09-01 |
| `lei-2026-04401` | Lei nº 4.401, de 29 de julho de 2026 | 1 | 2026-07-29 to 2026-07-29 |
| `lei-2026-04374` | Lei nº 4.374, de 29 de junho de 2026 | 1 | 2026-06-29 to 2026-06-29 |
| `lei-2026-04333` | Lei nº 4.333, de 15 de maio de 2026 | 1 | 2026-05-19 to 2026-05-19 |
| `lei-2026-04332` | Lei nº 4.332, de 15 de maio de 2026 | 1 | 2026-05-19 to 2026-05-19 |
| `lei-2026-04291` | Lei nº 4.291, de 26 de março de 2026 | 1 | 2026-03-31 to 2026-03-31 |
| `lei-2026-04289` | Lei nº 4.289, de 25 de março de 2026 | 1 | 2026-03-25 to 2026-03-25 |
| `lei-2026-04288` | Lei nº 4.288, de 24 de março de 2026 | 1 | 2026-03-25 to 2026-03-25 |
| `lei-2026-04287` | Lei nº 4.287, de 24 de março de 2026 | 1 | 2026-03-25 to 2026-03-25 |
| `lei-2026-04286` | Lei nº 4.286, de 24 de março de 2026 | 1 | 2026-03-25 to 2026-03-25 |
| `lei-2026-04274` | Lei nº 4.274, de 5 de março de 2026 | 1 | 2026-03-05 to 2026-03-05 |
| `lei-2026-04273` | Lei nº 4.273, de 5 de março de 2026 | 1 | 2026-03-05 to 2026-03-05 |

The build made 12 commits:

| Commits | Kind |
| ---: | --- |
| 12 | first version of an act |
| 0 | one law on its in-force day |
| 0 | changes no amendment note explains, credited to the publisher |

Other counts:
- 0 commits on the branch `futuro`: laws not yet in force on 2026-11-02.
- 0 commits dated 1 January 1970: in force before 1970, with the real day in their `In-force` trailer.
- 12 laws in the record.
- 24 tags.

## Dates

Each commit is dated at noon (America/Sao_Paulo) on the day the change took effect. The other dates, enacted and published, are trailers.

When a law gives no date of its own, the default rule applies: Decreto-Lei 4.657/1942 (LINDB) art. 1: unless it says otherwise, a law takes effect 45 days after its official publication. This record takes in only municipal laws whose own vigência clause says they take effect on their publication (or signature), and dates each by the publication date the Câmara's SAPL records for it (else by its date). https://www.planalto.gov.br/ccivil_03/decreto-lei/del4657compilado.htm

## How the history is built

`tools/build.py` turns the corpus into this history in one pass: one commit per law, on the day it took effect. The same corpus always gives the same commit hashes. `tools/check_repo.py` reads every version back from git and compares it with the corpus. `tools/on.py` shows the law as it stood on any date. The corpus format is described in `tools/SCHEMA.md`.

- Corpus: sha256 `d0f7fd3b53394532e5ec9e5a9e315f25b88f73d317e6a1ef5dffeb90d4347a29` (65839 bytes).
- Builder blob hashes (`git hash-object`): `build.py` `a4faa25af85facb64b956b372f6b528aafdd7ec1`, `check.py` `3d00541d258745461ab52b1b0cb4e1716a27a95d`, `on.py` `644a6c0857fbcc72562032b58d57aa113fee0641`.
- Python 3.12.10; git version 2.46.0.windows.1.

## Checks

12 versions of 12 acts read back from git on the day each took effect and on the day before: 0 mismatches. Trailers: 0 commits whose trailers git cannot parse. Health: 0 merge commits on main, 0 commit dates that go backwards, 0 commits dated after the build.

No second build of this corpus has been compared yet.

## Decisions made by hand

- Each municipal law ("Lei" and "Lei Complementar") is given as enacted, from the PDF the Câmara's SAPL holds for it, credited to the law itself and dated by the publication date SAPL records for it (else by the law's own date). Later amendments by other laws are not worked into earlier laws: each law is its own file set as enacted. Laws are taken newest first, in parts.
- Left out: scans (with or without an OCR layer), PDFs whose heading does not carry the record's number, texts with no article or no closing date line, texts carrying alteration notes, and laws whose vigência clause sets another day than their publication (or that have none, so that the 45 days of the LINDB apply).
- The text runs from the law's heading to its closing date line (signatures after it are left out); lines repeated at the top or bottom of two or more pages (letterheads, footers) and page numbers are left out. Lines are joined into paragraphs: a new paragraph starts at a provision label, a heading line, or after a line ending in ".", ";" or ":". One file per Art.; "000-titulo" holds what comes before the first article.
- Each municipal law ("Lei" and "Lei Complementar") is given as enacted, from the PDF the Câmara's SAPL holds for it, credited to the law itself and dated by the publication date SAPL records for it (else by the law's own date). Later amendments by other laws are not worked into earlier laws: each law is its own file set as enacted. Laws are taken newest first, in parts.
- Left out: scans (with or without an OCR layer), PDFs whose heading does not carry the record's number, texts with no article or no closing date line, texts carrying alteration notes, and laws whose vigência clause sets another day than their publication (or that have none, so that the 45 days of the LINDB apply).
- The text runs from the law's heading to its closing date line (signatures after it are left out); lines repeated at the top or bottom of two or more pages (letterheads, footers) and page numbers are left out. Lines are joined into paragraphs: a new paragraph starts at a provision label, a heading line, or after a line ending in ".", ";" or ":". One file per Art.; "000-titulo" holds what comes before the first article.
- Each municipal law ("Lei" and "Lei Complementar") is given as enacted, from the PDF the Câmara's SAPL holds for it, credited to the law itself and dated by the publication date SAPL records for it (else by the law's own date). Later amendments by other laws are not worked into earlier laws: each law is its own file set as enacted. Laws are taken newest first, in parts.
- Left out: scans (with or without an OCR layer), PDFs whose heading does not carry the record's number, texts with no article or no closing date line, texts carrying alteration notes, and laws whose vigência clause sets another day than their publication (or that have none, so that the 45 days of the LINDB apply).
- The text runs from the law's heading to its closing date line (signatures after it are left out); lines repeated at the top or bottom of two or more pages (letterheads, footers) and page numbers are left out. Lines are joined into paragraphs: a new paragraph starts at a provision label, a heading line, or after a line ending in ".", ";" or ":". One file per Art.; "000-titulo" holds what comes before the first article.
- Each municipal law ("Lei" and "Lei Complementar") is given as enacted, from the PDF the Câmara's SAPL holds for it, credited to the law itself and dated by the publication date SAPL records for it (else by the law's own date). Later amendments by other laws are not worked into earlier laws: each law is its own file set as enacted. Laws are taken newest first, in parts.
- Left out: scans (with or without an OCR layer), PDFs whose heading does not carry the record's number, texts with no article or no closing date line, texts carrying alteration notes, and laws whose vigência clause sets another day than their publication (or that have none, so that the 45 days of the LINDB apply).
- The text runs from the law's heading to its closing date line (signatures after it are left out); lines repeated at the top or bottom of two or more pages (letterheads, footers) and page numbers are left out. Lines are joined into paragraphs: a new paragraph starts at a provision label, a heading line, or after a line ending in ".", ";" or ":". One file per Art.; "000-titulo" holds what comes before the first article.

## What AI did and did not do

The scripts that read the sources and build this repository were written by Claude Code running Claude Opus 5.5 (`claude-opus-5-5`) under Lexifina's direction.

No model wrote, translated or corrected legal text. No model runs at build time. Every word of law in this repository comes from the official sources above.

The commit messages are written by `build.py` from the source data.

Model use at data-build time:
- Claude Code (claude-opus-5-5) wrote Lexifina's code and chose the sources. No model output is used as legal text or dates: every word comes from the Câmara's SAPL.
- Claude Code (claude-opus-5-5) wrote Lexifina's code and chose the sources. No model output is used as legal text or dates: every word comes from the Câmara's SAPL.
- Claude Code (claude-opus-5-5) wrote Lexifina's code and chose the sources. No model output is used as legal text or dates: every word comes from the Câmara's SAPL.
- Claude Code (claude-opus-5-5) wrote Lexifina's code and chose the sources. No model output is used as legal text or dates: every word comes from the Câmara's SAPL.
