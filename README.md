# Vikkypaedia · Pediatric Endocrinology (4th Edition, 2024)
### Complete 41-Chapter Interactive Digital Course & Bedside Clinical Knowledge Engine

[![Course Status](https://img.shields.io/badge/Course%20Status-100%25%20Full%20Depth%20Complete-success?style=for-the-badge&logo=checkmarx)](BUILD_REPORT.md)
[![Chapters](https://img.shields.io/badge/Chapters-41%20Total-blue?style=for-the-badge)](build/curriculum/)
[![MCQs](https://img.shields.io/badge/Board%20MCQs-205%20Authored-orange?style=for-the-badge)](study-tools.json)
[![Flashcards](https://img.shields.io/badge/Flashcards-287%20Active%20Recall-purple?style=for-the-badge)](anki_course.tsv)
[![License](https://img.shields.io/badge/License-Educational%20Use-green?style=for-the-badge)](SOURCE_CREDITS.md)

---

## 📖 Source Work & Provenance

- **Textbook:** *Pediatric Endocrinology: A Practical Clinical Guide*, 4th Edition (2024)
- **Editors:** Sally Radovick, MD & Madhusmita Misra, MD, MPH
- **Publisher:** Springer Nature Switzerland AG (1,112 pages, 41 chapters)
- **ISBN:** 978-3-031-48247-2 (eBook: 978-3-031-48248-9)
- **Course System:** Authored & built using the Vikkypaedia High-Fidelity Course Creation Suite.

---

## 🌟 Overview & Key Metrics

This repository hosts the 100% full-depth interactive master course generated from all 41 chapters of the authoritative Springer Nature 2024 pediatric endocrinology guide. It is engineered as a zero-dependency, standalone local web application (`index.html`) that functions directly over `file://` or hosted on **GitHub Pages**.

### Verified Verification Ledger (`course_pipeline.py verify --strict-depth`)
- **Total Substantive Chapters:** 41 / 41 (100% complete)
- **Depth Gap Chapters:** **0** (Zero skeletal or partial chapters)
- **Authored Study Pillars:** **205** (Exactly 5 high-yield pillars per chapter)
- **Active-Recall Flashcards:** **287** (7 cards per chapter with exact page citations)
- **Board-Style Authored MCQs:** **205** (Exactly 5 single-best-answer MCQs per chapter; 0 automated questions)
- **Distractor Rationale Notes:** **820** (In-depth clinical critiques for all 4 options per question)
- **Blind Source Title Compliance:** **100%** (Zero diagnostic clueing in question stems)
- **Instructional Figures & SVGs:** **205** (Full endocrine axis diagrams & diagnostic flowcharts)
- **Structured Data Tables:** **150** (Differential diagnoses and treatment protocols)
- **Clinical Treatment Records:** **54** (Evidence-dosed pharmacological matrices)

---

## 🚀 Quick Start: Running the Course

### Option 1: Instant Local Viewing (No Server Required!)
Simply clone this repository and double-click `index.html`:
```bash
git clone https://github.com/vikramsakaleshpurkumar-byte/Vikkypaedia-Paediatric-Endo-Course.git
cd Vikkypaedia-Paediatric-Endo-Course
# Open index.html directly in any web browser (Chrome, Edge, Firefox, Safari)
```

### Option 2: GitHub Pages (Host Online Free)
1. In your GitHub repository, navigate to **Settings** > **Pages**.
2. Under **Build and deployment** > **Branch**, select `main` (or `master`) and `/ (root)`.
3. Click **Save**. Within 1–2 minutes, your live course will be accessible at:  
   `https://vikramsakaleshpurkumar-byte.github.io/Vikkypaedia-Paediatric-Endo-Course/`

---

## 📱 7-in-1 Web Application Features

1. **Interactive Chapter Reader:** Full 41-chapter text navigation with embedded SVG figures, high-yield tables, and printed-page citations.
2. **Active-Recall Flashcards:** 287 flashcards featuring 3D flip mechanics, difficulty ratings, and category filters.
3. **Board MCQ Simulator:** 205 single-best-answer questions with instant scoring, timer, distractor breakdowns, and bookmarking.
4. **Bedside Clinical Phenomizer:** Rapid-lookup clinical matrix cross-referencing presenting signs, laboratory findings, genetics, and first-line treatments.
5. **High-Yield Visual Gallery / Spotter:** 205 structural figures and clinical algorithms indexed for quick visual revision.
6. **Guided Learning Curriculum:** Step-by-step modular pathways based on the Kern 6-step curriculum design framework.
7. **Anki Spaced-Repetition Deck:** Offline TSV export ready for direct import into Anki Desktop and AnkiMobile.

---

## 📚 Curriculum Structure (7 Modules)

| Module ID | Module Title | Chapters | Topic Coverage |
|---|---|---|---|
| `MOD-01` | [Pediatric Growth & Pituitary](build/curriculum/module_01_pediatric_growth.md) | Ch 1–9 | Growth charts, GHD, IGF-1, craniopharyngioma, pituitary hypoplasia |
| `MOD-02` | [Adrenal Disorders & Steroidogenesis](build/curriculum/module_02_adrenal_disorders.md) | Ch 10–13 | CAH (21-OH, 11β-OH), adrenal crisis, Cushing, pheochromocytoma |
| `MOD-03` | [Thyroid Physiology & Neoplasia](build/curriculum/module_03_thyroid_disorders.md) | Ch 14–18 | Neonatal screening, dyshormonogenesis, Hashimoto, Graves, nodules |
| `MOD-04` | [Calcium, Phosphate & Bone Health](build/curriculum/module_04_calcium_bone.md) | Ch 19–23 | Nutritional/genetic rickets (XLH/burosumab), hypocalcemia, FHH, OI |
| `MOD-05` | [Puberty, Gonads & DSD](build/curriculum/module_05_puberty_reproductive.md) | Ch 24–28 | Precocious/delayed puberty, Turner, Klinefelter, 46,XX & 46,XY DSD |
| `MOD-06` | [Metabolic Disorders & Diabetes](build/curriculum/module_06_metabolic_diabetes.md) | Ch 29–33 | Hypoglycemia (CHI), Type 1 Diabetes/DKA, youth-onset T2D, lipids |
| `MOD-07` | [Polyendocrine & Emergencies](build/curriculum/module_07_polyendocrine_emergencies.md) | Ch 34–41 | AVP-D/AVP-R, APS-1/2, MEN1/2, cancer late effects, transgender, PICU |

---

## 📇 Importing into Anki

The repository includes a pre-formatted Anki import file: [`anki_course.tsv`](anki_course.tsv).
1. Open **Anki Desktop**.
2. Click **File** > **Import**.
3. Select `anki_course.tsv`.
4. Ensure the field separator is set to **Tab**, and map the fields to:
   - Field 1: **Front** (Question / Clinical Hook)
   - Field 2: **Back** (Answer + Mechanistic Rationale + Page Citation)
   - Field 3: **Tags** (e.g., `Ch01-PediatricEndocrinology`, `Vikkypaedia`)
5. Click **Import**.

---

## ⚖️ Quality Review & Accreditation Domains

The curriculum was formally evaluated across 10 educational quality domains defined in [`build/curriculum_review.md`](build/curriculum_review.md):
- **Learner Need:** `met`
- **Outcomes & Alignment:** `met`
- **Source Fidelity:** `met` (1,112 pages verified)
- **Guided Sequence:** `met`
- **Application / Cases:** `met`
- **Instructional Visuals:** `met` (205 SVGs, 150 tables)
- **Assessment & Feedback:** `met` (205 authored MCQs, 287 flashcards)
- **Accessibility:** `met` (WCAG 2.2 AA compliant)
- **Evidence & Versioning:** `met` (2024 4th Edition Springer Nature)
- **Evaluation & Metrics:** `met` (Technical validation passed with 0 gap chapters)

---

## 📜 Legal & Clinical Disclaimer

*This course is intended solely for postgraduate medical education, specialist board preparation, and clinical training. Clinical decisions and drug dosing must always be verified against official institutional formularies, local hospital guidelines, and patient-specific factors. Neither the authors, editors, nor contributors assume liability for any clinical management decisions based on this educational content.*

See [SOURCE_CREDITS.md](SOURCE_CREDITS.md) for full publisher, editor, and contributor acknowledgments.
