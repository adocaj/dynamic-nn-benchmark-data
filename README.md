# Dynamic KD and VP Trees — Experimental Results and Improvements

This repository contains two sets of files related to our research on dynamic KD and VP tree structures for efficient nearest neighbor search.

---

## 1. `experiments.zip`
- **Purpose:** Contains the exact implementations and experimental results used in the published paper.
- **Contents:**
  - Original Colab notebooks used for experiments.
  - Precomputed results and plots corresponding to the tables and figures in the paper.
- **Note:** These files represent the baseline results from the accepted publication and have not been altered.

---

## 2. `improved_tree_designs.zip`

- **Purpose:** Contains improvements to the dynamic KD and VP tree designs made after the submission of the paper.

- **Highlights:**
  - Algorithmic refinements that improve both build/insertion and search performance.
  - In some settings — particularly in lower dimensions — the KD variant now **outperforms** the VP variant, differing from trends observed in the published tables.

- **Contents:**
  - Python scripts that can be run locally, implementing the improved structures.

---

## 3. Disclaimer
These improvements were developed **after submission of the paper** and do not affect the validity of the published results. The original experiments (in `experiments.zip`) remain fully reproducible and unchanged.

For any comparisons or references, please clearly distinguish between the **published results** and the **improved post-submission designs**.
