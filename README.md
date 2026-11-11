# Basit Hub

A custom browser start page for daily research in computational biology: genomics, protein structure, molecular docking, simulation and machine learning, all in one place.

**Live page:** [abdulbasitbehlim.github.io/basit-hub](https://abdulbasitbehlim.github.io/basit-hub/)

<!-- To add a preview: upload a screenshot named preview.png to this repository, then remove the arrows around the next line. -->
<!-- ![Basit Hub preview](preview.png) -->

## Features

- **Time-based greeting** with a live clock, date and a progress bar showing how much of the day has passed.
- **3D protein of the day** rendered with 3Dmol.js. Switch between cartoon, surface and stick views, toggle spinning, or load any structure by its PDB ID.
- **Animated DNA double helix** coloured by nucleotide (A, T, G, C).
- **One search bar for research databases:** Google, Google Scholar, PubMed, UniProt, RCSB PDB, AlphaFold DB, NCBI, PubChem, arXiv, Hugging Face and GitHub. Typing a 4-character PDB ID opens the structure page directly.
- **Quick links** grouped into Genomics, Proteins, Docking and Machine learning.
- **AI assistants:** ChatGPT, Claude, Gemini, Copilot, Perplexity, DeepSeek, Grok, Meta AI and Le Chat, plus research tools such as AlphaFold Server, NotebookLM, Elicit, Consensus and SciSpace.
- **Google apps:** Gmail, Drive, Docs, Sheets, Slides, Calendar, Meet, Colab, Scholar and more.
- **Lab notes** that save automatically in your browser.
- **A daily tip** on docking, molecular dynamics or machine learning practice.
- **Glass design with light and dark themes**, in the same colour gradient as my GitHub profile, and a layout that adapts to phones.

## Use it as your start page

### Desktop

- **Chrome:** Settings → On startup → Open a specific page → Add a new page → paste the live link.
- **Edge:** Settings → Start, home, and new tabs → Open these pages → Add a new page → paste the live link.
- **Firefox:** Settings → Home → Homepage and new windows → Custom URLs → paste the live link.

To show it on every new tab, use an extension such as *Custom New Tab URL* (Chrome, Edge) or *New Tab Override* (Firefox).

### Mobile

- **Chrome on Android:** ⋮ → Settings → Homepage → paste the live link.
- **Samsung Internet:** ☰ → Settings → Homepage → Custom.
- **iPhone (Safari):** open the live link → Share → Add to Home Screen.

## Customise

Everything lives in a single file, `index.html`.

- **Links:** edit the `<a href="...">` lines inside the link group sections.
- **Daily tips:** add or change lines in the `tips` list in the script.
- **Structures of the day:** edit the `structures` list, using any PDB ID and a short title.
- **Colours:** change the colour variables at the top of the `<style>` block.

## Built with

- Plain HTML, CSS and JavaScript, with no build step
- [3Dmol.js](https://3dmol.csb.pitt.edu/) for molecular visualisation
- Structure files from the [RCSB Protein Data Bank](https://www.rcsb.org/)
- [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) from Google Fonts
- Hosted on GitHub Pages

The 3D viewer and fonts need an internet connection. Everything else works offline.

## Author

**Abdul Basit Behlim**
Computational Biologist & Bioinformatician

## License

The code is released under the [MIT License](LICENSE). The profile photo in `index.html` is personal and is not covered by this license; please do not reuse it.
