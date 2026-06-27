# Selected Notebook Portfolio

This folder contains a curated set of Jupyter/Colab notebooks prepared for GitHub publishing. The notebooks are grouped by topic and copied into this staging folder from the original local Google Drive notebook directory.

> **Note:** Original notebooks were not modified. These are cleaned staging copies intended for review and publication.

## Folder structure

### `01_course_chapters/`

Course demos, solutions, and challenge notebooks covering neural-network modeling, custom Keras components, autoencoders, pruning, transfer learning, distillation, and language-model prompting examples.

### `02_projects_portfolio/`

Project and portfolio notebooks, including preprocessing, exploration, market/RFM analysis, Pyomo job-shift modeling, and renamed portfolio project notebooks.

### `03_ai_data_science/`

AI and data-science notebooks covering RAG, LangChain chains/tools/agents, prompt engineering, text preprocessing, categorization, search analysis, recommender systems, segmentation, classification, CNNs, and spam/fake-news detection.

## Publishing preparation completed

- Notebook outputs and execution counts were cleared in the staged copies.
- Generic or vague project filenames were renamed where possible.
- A sensitive-keyword review was performed for API keys, tokens, passwords, Colab Drive paths, and similar patterns.
- Review artifacts are included:
  - `MANIFEST.md` — curated file list and final manual-review checklist.
  - `NOTEBOOK_REVIEW.tsv` — notebook metadata/review table.
  - `SENSITIVE_REVIEW.txt` — sensitive-keyword scan notes.

## Before publishing to GitHub

Please manually review the staged notebooks once more and confirm:

- Every notebook is yours or otherwise safe to publish.
- Datasets, screenshots, embedded images, and text content do not contain private information.
- API usage relies on environment variables, Colab `userdata`, or prompts rather than hard-coded secrets.
- Any private Google Drive paths or local paths are either removed, generalized, or acceptable for public viewing.
- Large notebooks are acceptable for your repository size limits.

## Suggested repository description

> A curated portfolio of machine-learning, deep-learning, NLP, RAG, LangChain, and data-science notebooks prepared from Google Colab/Jupyter projects.
