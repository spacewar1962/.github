# Spacewar! (1962) — A Critical Code Studies Reading

A critical code reading of **_Spacewar!_**, the space-combat game written for the DEC PDP-1 at MIT in 1961–62. We read the original MIDAS assembly source as a cultural text, in the tradition of Critical Code Studies: at once literature, mechanism, spatial form, and a repository of the social formation that produced it.

This is a companion to **_Inventing ELIZA: How the First Chatbot Shaped the Future of AI_** (MIT Press, 2026) — two foundational programs of the long 1960s, read side by side: ELIZA teaches the machine to talk, _Spacewar!_ teaches it to play.

### 🌐 Project site → **https://spacewar1962.github.io/spacewar/**
🕹 [Play the 1962 original](https://spacewar1962.github.io/spacewar/play.html) · 📚 [Bibliography](https://spacewar1962.github.io/spacewar/bibliography.html)

---

## Repositories

| Repo | What it is |
|------|------------|
| [**spacewar**](https://github.com/spacewar1962/spacewar) | The primary working object: the original `spacewar.mac` MIDAS source, the assembler listing (`spacewar.lst`), the provenance snapshot, a runnable PDP-1 emulator, and the project website (`index.html`, `play.html`, `bibliography.html`). The book scaffolding lives under `book/`. |
| [**spacewar-philspil-transcription**](https://github.com/spacewar1962/spacewar-philspil-transcription) | A secondary hand-transcription, kept as a variorum witness for comparison. |

## The reading

The study works across the registers of Critical Code Studies, pairing close technical explication of a code fragment with the cultural constellation that spirals out from it. Six movements: the machine that owns itself; a language for ships; the Expensive Planetarium; hyperspace, or the random jump; the demo and the gift; the founding myth.

## Working locally

The website is a static site. From a clone of `spacewar`:

```sh
python3 -m http.server 8000
# then open http://localhost:8000/
```

The bibliography page is generated from `book/ccs-bibliography.source.md` by `book/build_bib.py` (`python3 book/build_bib.py`).

## Project leads

- **Professor David M. Berry** — University of Sussex — d.m.berry@sussex.ac.uk
- **Professor Mark C. Marino** — University of Southern California — mcmarino@usc.edu
