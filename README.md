# DecodeLabs AI Recommendation Logic (Project 3)
## Industrial Training Kit | Batch: 2026

An intelligent, text-based machine learning pipeline designed to step into the role of an **Artificial Intelligence Engineer** at DecodeLabs. This project focuses on **Pattern Alignment** and mastering the fundamental art of matching user profiles with item attributes using pure similarity logic before advancing to neural collaborative filtering models.

---

## 📝 Project Overview & Goal
The main objective of this definitive milestone is to design a digital engine that bridges the gap between raw user data and relevant content with absolute precision:
*   **User Preference Capture:** Ingest clean, qualitative technical skill inputs from a user.
*   **Vector Space Scoring:** Translate text attributes into comparative numerical features using TF-IDF feature extraction.
*   **Pure Similarity Alignment:** Evaluate mathematical alignment utilizing angle-invariant Cosine Similarity metrics to map profiles without relying on random suggestions.
*   **Choice Fatigue Filtering:** Return a localized Top-3 ranked list of tech stack paths to resolve user decision overload.

---

## 📁 Key Repository Components
*   `Recommend.py`: The main production script running the user ingestion, vector mapping, scoring, sorting, and recommendation pipeline.
*   `raw_skills.csv`: The underlying relational dataset tracking technical roles (Data Scientist, DevOps Engineer, Backend Developer, Cloud Architect, Sys Admin) along with their required skill arrays.
*   `Screenshot 2026-06-05 014013.png`: Pipeline validation showing successful alignment mapping to a Cloud Architect path.
*   `Screenshot 2026-06-05 014050.png`: System verification handling diverse input thresholds smoothly.
*   `Screenshot 2026-06-05 014126.png`: Validation proving accurate weighting and routing to a Data Scientist tech path.

---

## 🛠️ Key Skills Mastered
*   **Logic Building:** Translating real-world qualitative concepts into programmatic features.
*   **Pattern Matching:** Utilizing shared vocabulary spaces for geometric distance tracking.
*   **Recommendation Concepts:** Handling edge cases like the "Cold Start Problem" using fallback global defaults.

---

## 🚀 How To Run

### 1. Install Dependencies
Ensure you have Python configured along with the necessary scientific data stacks installed:
```bash
pip install pandas scikit-learn
