# Building the TReMeDa Datasets: A Research Compendium

The TReMeDa research compendium – a reproducible, narrative record of how the Trust Research Methodology Database (TReMeDa) datasets are discovered, assembled, classified and documented. It renders to a Quarto book (HTML + PDF).

## Architecture

This repository holds **the rendered content only**. Two things live outside it on purpose:

| What | Where | Why |
|------------|------------------------|------------------------|
| **Code** | `https://github.com/CGMoreh/tremeda-compendium` | This is currently on a private repo while in development |
| **Data** (`data/`) | local | Large + licensed; final curated and cleansed version will be built into the TReMeDa database backbone |
| **Rendered site** | `https://github.com/CGMoreh/tremeda-compendium-site` (this public repo) | `output-dir` points here; published to GitHub Pages. Source stays private. |