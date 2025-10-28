# Categorized English Words

**A rigorously curated dataset of 154,132 domain-specific English terms**, categorized across **34 academic and professional fields**, created through a **multi-stage AI-driven linguistic pipeline**.  
This dataset is designed for **NLP research**, **education**, **semantic search**, **lexicography**, and **AI model training**.

---

## Overview

This project provides a comprehensive and meticulously structured lexical resource that surpasses existing public wordlists in both accuracy and domain coverage.

### Key Features

- **High Accuracy and Consistency**  
  Cleaned and validated through a multi-stage AI pipeline and manual inspection.  
  Typos, duplicates, and non-domain words were systematically removed.

- **Strict Multi-Domain Categorization**  
  Categorized via **Gemini (LLM)** using conservative, multi-subject logic  
  (for example: “cell” → Biology + Medicine).

- **Standardized Orthography**  
  All terms are lowercased, diacritic-free, and NFKD-normalized.

- **Simple and Ready-to-Use Format**  
  Plain `.txt` files encoded in UTF-8, with one unique word per line.

- **No General Vocabulary**  
  Excludes conversational or everyday words to ensure pure domain relevance.

- **Unique on GitHub (as of October 2025)**  
  No comparable dataset offers:
  - 34 academic and professional categories  
  - Over 150,000 rigorously validated terms  
  - A documented, AI-assisted data curation pipeline  
---

## Dataset Overview

| Category | Words |
|-----------|--------|
| agriculture.txt | 5,468 |
| anthropology.txt | 3,264 |
| archaeology.txt | 2,261 |
| architecture.txt | 2,500 |
| art.txt | 4,439 |
| astronomy.txt | 1,694 |
| biology.txt | 40,424 |
| business.txt | 5,214 |
| chemistry.txt | 16,460 |
| computer_science.txt | 4,555 |
| culinary_arts.txt | 3,513 |
| economics.txt | 3,756 |
| education.txt | 2,068 |
| engineering.txt | 8,595 |
| environmental_science.txt | 6,111 |
| geography.txt | 4,206 |
| geology.txt | 6,611 |
| health_and_wellness.txt | 6,181 |
| history.txt | 13,453 |
| law.txt | 8,181 |
| linguistics.txt | 5,575 |
| literature.txt | 6,489 |
| mathematics.txt | 4,393 |
| medicine.txt | 32,718 |
| music.txt | 3,297 |
| performing_arts.txt | 2,472 |
| philosophy.txt | 10,793 |
| physics.txt | 7,428 |
| political_science.txt | 6,800 |
| psychology.txt | 7,569 |
| religion.txt | 8,961 |
| sociology.txt | 8,070 |
| sports_science.txt | 2,455 |
| technology.txt | 4,568 |
| **Total (Domain-Specific)** | **154,132** |

> Machine-readable statistics are available in [`dataset-metadata.json`](./dataset-metadata.json)

---

## Methodology

The dataset was created through a multi-stage, AI-validated process:

1. **Input Corpus:** 450,729 raw English terms  
2. **Categorization:** Classified with **Gemini (LLM)** using **Pydantic schema validation**  
3. **Cleaning and Filtering:** Removed 3,604 invalid or overly general words  
4. **Normalization:** Lowercased, deduplicated, and NFKD-normalized  
5. **Output:** 154,132 validated domain-specific words across 34 categories

---

## Use Cases

This dataset can be used for:

- Developing domain-aware NLP models  
- Building academic and professional search systems  
- Creating educational materials, flashcards, or quizzes  
- Training AI for specialized writing and text classification  
- Constructing technical dictionaries or linguistic tools  

---

## File Structure

```
data/
├── agriculture.txt
├── biology.txt
├── medicine.txt
└── ... (31 more)
```

Each file contains one term per line, for example:

```
word1
word2
word3
...
```

---

## Contributing

Contributions are welcome.  
If you find errors, missing words, or want to suggest improvements:

1. Open an **Issue**, or  
2. Submit a **Pull Request**  

Please ensure any contributions maintain the dataset’s academic and linguistic precision.

---

## License

**MIT License** — Free for commercial, academic, and personal use.

---

## Citation

If you use this dataset in research, please cite it as follows:

```bibtex
@dataset{categorized_english_words_2025,
  author       = {rezKhosro},
  title        = {Categorized English Words: 154K Domain-Specific Terms from 450K Processed},
  year         = 2025,
  publisher    = {GitHub},
  version      = {v1.0},
  url          = {https://github.com/rezakhosro/categorized-english-words}
}
```