# NLP-Assisted Root Cause Analysis for Semiconductor Wafer Fabrication

**Course:** Natural Language Processing (22AD71), MSRIT, Dept. of AI & DS
**Team:** <your name(s) and USN(s)>

## Problem Statement
Fab engineers deal with large volumes of noisy text: SPC alarms, preventive
maintenance (PM) logs and shift notes full of typos and abbreviations. This
makes it slow to link a process excursion to its root cause and corrective
action. This project builds an NLP layer on top of a statistical RCA model
(Lasso + Bayesian Belief Network). It cleans and understands fab text,
retrieves the right corrective procedure and generates a readable RCA report.

## Objectives
1. Preprocess noisy fab logs using tokenization, morphological normalization,
   spelling correction (minimum edit distance + smoothed n-gram LM) and
   POS tagging.
2. Extract component–parameter–symptom information using a domain CFG with
   CYK parsing and reference resolution, and fuse it with the Lasso/BBN model.
3. Retrieve relevant corrective procedures (OCAP) using a TF-IDF vector space
   model and generate a plain-English RCA report using rule-based NLG.

## Syllabus Mapping
| Unit | Concepts used |
|------|---------------|
| 2 | Smoothing, morphological parsing, spelling correction, minimum edit distance, POS tagging (rule-based, HMM, Brill) |
| 3 | N-grams, perplexity/entropy, CFG, CYK parsing |
| 4 | Reference resolution, cohesion, language generation |
| 5 | Information retrieval (vector space, Boolean), WordNet |

## SDG Mapping
- **SDG 9:** Industry, Innovation and Infrastructure
- **SDG 12:** Responsible Consumption and Production (less wafer scrap)

## Dataset
- Numeric process data (from internship, **not included** in this repo, confidential)
- Text data is generated from the numeric data: SPC alarms derived from
  control-limit violations, plus synthetic PM logs and shift notes with
  realistic noise
- 10–15 OCAP (corrective action) documents written for the retrieval corpus

## Repository Structure
(to be updated)

## How to Run
(to be updated)
