# 🌌 Amorodium

> *A chronological cartography of human thought.*

**Amorodium** is a personal philosophical archive and website built to trace the history of human ideas. 

Unlike traditional philosophy encyclopedias that silo thinkers by culture or geography, Amorodium displays **Western, Chinese, and Indian philosophers on a single, unified chronological timeline**. This approach highlights the simultaneity of human thought—showing, for instance, that Laozi, the Buddha, and the early Greek Pre-Socratics were grappling with fundamental questions at roughly the same time in history.

## 📖 Structure of the Site

The website is built around two main sections:

1. **The Timeline (Philosophers):** A chronological list of selected thinkers. 
2. **Essays:** A collection of my own writings and reflections.

### The Two-Column Layout
Every philosopher page features a distinct, two-column design that separates interpretation from primary text:
*   **Left Column (Introduction):** My synthesis of the philosopher's life, context, and core ideas, drawn from secondary resources.
*   **Right Column (Selected Origins):** Carefully selected primary texts, fragments, or quotes directly from the philosopher, presented in a visually distinct block to let their voice speak for itself.

## 🛠️ Tech Stack

This site is built using:
*   **[Jekyll](https://jekyllrb.com/):** A static site generator that turns plain text into a website.
*   **GitHub Pages:** Hosting.
*   **Markdown & YAML:** For content creation and metadata.
*   **Vanilla CSS:** A custom, minimalist, academic design (no heavy frameworks).

## 📂 Directory Structure

```text
amorodium.github.io/
├── _config.yml           # Jekyll configuration (collections, permalinks)
├── index.html            # The unified timeline homepage
├── _layouts/             # HTML templates
│   ├── default.html      # Global header/footer
│   ├── philosopher.html  # The two-column layout
│   └── essay.html        # Essay layout
├── _philosophers/        # Markdown files for each thinker
│   ├── laozi.md
│   └── socrates.md
├── _essays/              # Markdown files for your essays
│   └── 2026-10-24-axial-age.md
└── assets/
    └── css/
        └── style.css     # Global stylesheet
