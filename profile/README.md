# Spacewar! (1962): A Critical Code Studies Reading

A critical code reading of **_Spacewar!_**, the space-combat game written for the DEC PDP-1 at MIT in 1961–62. We read the original MIDAS assembly source as a cultural text, in the tradition of Critical Code Studies: at once literature, mechanism, spatial form, and a repository of the social formation that produced it. The source is small, roughly two thousand words of macro-assembly, yet it condenses much of the history that follows from it: real-time interaction, the hacker ethic, the demo, and the free circulation of code.

This is a companion to **_Inventing ELIZA: How the First Chatbot Shaped the Future of AI_** (MIT Press, 2026). They are two foundational programs of the long 1960s, read side by side: ELIZA teaches the machine to talk, _Spacewar!_ teaches it to play.

### Ways forward for the reading

The reading proceeds in movements, each beginning from a fragment of the code and spiralling outward: the machine that owns itself; the MIDAS macros as a small language for writing the game; the Expensive Planetarium and its real sky; gravity and the central star; hyperspace as designed contingency; and the demo as gift. Alongside close reading, we treat programming as scholarship, using the bundled emulator to run, modify, and port the program, so that interpretation is tested against the artefact rather than asserted about it. Open directions include a variorum across the surviving versions and ports, a fuller account of the paratexts (Graetz, Brand, Levy, the PDP-1 and MIDAS manuals), and the political economy of the gift economy that circulated the source inside a Cold-War research budget.

### Code and image together

_Spacewar!_ is unusual among objects of code study because it is also, immediately, an image: a vector drawing on the Type 30 display, a phosphor starfield with two ships and a burning sun. We therefore propose to read the visual register in conjunction with the code that produces it, moving between the outline compiler and the ship it draws, between the star catalogue held in memory and the sky thrown onto the screen. This binds critical code studies to a visual and media-archaeological analysis of the display itself, its vector aesthetic, its persistence and decay, asking how the code's procedures become images and what those images ask us to read back into the code. Working through both registers at once, code and image, is one of the things the running emulator makes possible: we can watch the output while reading the source that generates it.

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

- **Professor David M. Berry**, University of Sussex (d.m.berry@sussex.ac.uk)
- **Professor Mark C. Marino**, University of Southern California (mcmarino@usc.edu)
