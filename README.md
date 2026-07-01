# The Effect of CV-Building Activities on Student Stress Levels at Institut Teknologi Sains Bandung

Survey report for the **Sampling Techniques and Survey** course — Bachelor of Data Science Program, Institut Teknologi Sains Bandung (Semester 2).

> Lecturer: Dr. Andi Pujo Rahadi, S.T., M.Sc.
> Group 3 · Sampling Method: Purposive Sampling

## Background

Early-semester students are often already faced with pressure to prepare a competitive CV — through organizations, internships, competitions, and training — while also dealing with high academic demands. This research examines whether increasing pressure to build a CV is associated with higher stress levels among students.

## Research Objectives

1. Identify the demographic profile of respondents
2. Measure students' level of CV-related pressure (5-point Likert scale)
3. Measure students' stress level related to career preparation
4. Calculate the Pearson correlation between CV Score and Stress Score
5. Present the results through clear visualizations
6. Draw conclusions to inform student guidance programs

## Methodology

| Aspect | Description |
|---|---|
| Population | ± 1,000 active ITSB students |
| Sampling Method | Purposive Sampling |
| Sample Size (Slovin's Formula, e=15%) | ≈ 43 respondents |
| Actual Respondents | 36 students |
| Instrument | Google Form questionnaire, 5-point Likert scale |
| Variables | CV Score (7 items) and Stress Score |

## Key Findings

- A strong, statistically significant positive correlation between CV pressure and student stress: **r = 0.71, p < 0.001**
- Average CV Score = **3.56/5**, with the highest pressure coming from concerns about insufficient organizational experience and anticipation of recruitment
- The career-anxiety item scored highest overall (**4.19/5**)
- ~28% of respondents had never built a CV yet still reported high pressure and stress → the pressure appears to be **anticipatory rather than reactive**
- **r² ≈ 0.50** → CV pressure explains about 50% of the variance in stress; the rest is likely driven by other factors (academic load, family pressure, financial condition, personal psychological factors)

## Repository Structure

```
├── analisis_cv_stres.ipynb   # Full analysis notebook (Python)
├── presentation.pptx         # Presentation slides of the findings
└── README.md                 # This document
```

## Tools & Libraries

- Python (Jupyter Notebook)
- Pandas, NumPy — data wrangling
- Matplotlib, Seaborn — visualization
- SciPy — Pearson correlation testing

## Recommendations

| Stakeholder | Recommendation |
|---|---|
| ITSB / Institution | Establish structured career guidance and mental health services starting from Semester 1 |
| Lecturers & Academic Advisors | Frame CV preparation positively, as a gradual process rather than an instant target |
| Students | Limit unhealthy social comparison on social media; focus on personal growth |
| Future Research | Expand the sample across all semesters/programs and add moderating variables (social support, time management) |

## Contributors

| Member | Role |
|---|---|
| Christian Michael Juliano | Survey Coordinator & Design |
| Naisya Hafizh Mufidah | Methodology & Data |
| Nakeisha Aulia Zahra | Analysis & Visualization |
| Rafael Yogi Septiadi Putra | Documentation & Publication |

## References

Sugiyono (2019); Slovin (1960); Pearson (1895); McKinney (2010); Hunter (2007); Waskom (2021); Harris et al. (2020); Virtanen et al. (2020); Lazarus & Folkman (1984); APA (2020).

---
*This repository was created for the Sampling Techniques and Survey course, Bachelor of Data Science Program, Institut Teknologi Sains Bandung.*
