# 🧠 Multi-Criteria Decision Analysis of Top Twitch Streamers

This project presents a comprehensive analysis of the top 200 Twitch streamers using **Multi-Criteria Decision-Making (MCDM)** techniques. The goal is to develop fair, scalable, and data-driven streamer rankings using several DSS methods with both **subjective** (AHP) and **objective** (Entropy) weighting schemes.

📊 The analysis includes classical methods like **WSM, WPM, WASPAS** and more complex ones like **TOPSIS** and **PROMETHEE I & II**, applied on real-world performance data.

---

## 🚀 Project Highlights

- **Dataset**: Top 1000 Twitch streamers dataset, filtered to the top 200 mature streamers.
- **Criteria**:
  - Followers gained
  - Views gained
  - Peak viewers
  - Average viewers
  - Watch time (minutes)
  - Stream time (minutes)
  - Partnership status

- **Weight Derivation Methods**:
  - AHP (Analytic Hierarchy Process)
  - Entropy (Objective variability-based method)

- **MCDM Techniques**:
  - WSM (Weighted Sum Model)
  - WPM (Weighted Product Model)
  - WASPAS (Hybrid of WSM and WPM)
  - TOPSIS
  - PROMETHEE I & II

---

## 🧠 Key Findings

- **Gaules** consistently ranked 1st across all methods.
- **WASPAS + Entropy weights** offered the best trade-off between speed, consistency, and objectivity.
- PROMETHEE II provides greater nuance but at high computational cost (12s vs. 0.003s).
- Entropy weights highlighted volatile metrics (like peak viewers), ideal for real-time trend spotting.

---

## 🛠️ Technologies Used

- **Python 3.10+**
- `NumPy`, `Pandas`, `Matplotlib`
- Custom implementations of MCDM algorithms (no external DSS libraries used)
