# Soda Taste Experiment: Effects of Pouring and Consumption Method

**Course:** PSTAT 122 — Design and Analysis of Experiments, UC Santa Barbara  
**Author:** Ryan Park

---

## Overview

Does the way you pour or drink soda actually change how it tastes? This project investigates how **pouring method** and **consumption method** affect perceived soda taste ratings using a controlled experiment grounded in sensory science and consumer behavior research.

---

## Experimental Design

A **2×3 full factorial within-subjects design** was used, with each participant serving as a block to control for individual taste preferences.

**Pouring Method (3 levels):**
- Down the side of the glass
- Straight into the center of a glass
- Left in the can/bottle

**Consumption Method (2 levels):**
- Using a straw
- Drinking directly from the container

**Sample size:** 36 participants (ages 18–22), each rating all 6 treatment combinations → 216 total observations  
**Rating scale:** 0–10 (0 = worst taste ever, 10 = best possible taste)

---

## Hypotheses

- Pouring down the side of the glass (reduces foam, preserves carbonation) will result in higher taste ratings.
- Using a straw may enhance the experience by reducing olfactory interference or creating a smoother mouthfeel.

---

## Methods

- Power analysis using Cohen's f (f = 0.25, medium effect) to determine sample size
- Randomized presentation order to minimize bias
- All sodas were the same brand and temperature, poured fresh before each tasting
- Analyzed using ANOVA with blocking

---

## Files

| File | Description |
|------|-------------|
| `Final_Project.pdf` | Full written report with analysis and results |
| `soda_ratings.xlsx` | Raw data collected from 36 participants across 6 conditions |

---

## Tools & Libraries

- **Language:** R
- **Libraries:** `pwr`, `knitr`
- **Design:** 2×3 Full Factorial with Blocking
