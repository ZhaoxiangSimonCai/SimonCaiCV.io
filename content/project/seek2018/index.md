---
title: Prioritization Algorithm Enhancement and Simplification in Job Recommendation
tags:
- Machine learning
- Presto
- AWS (Linux)

date: "2018-09-05T00:00:00Z"

---

During the 5 weeks internship at SEEK, together with another three group members and one mentor from SEEK, we developed a model to make prioritizations for the relevant jobs selected by existing algorithms. We started the project from the data collection stage and finished the project with a functional model which could lead to a potential 12.8% uplift on the click-through ratio with our estimation. The final dataset we focused contained over 400K observations with 1800+ features. We used both Presto and MS SQL server to extract the data needed. The final model was based on LightGBM, which works especially well on data with a large number of features. With a programming background, I did most of the technical work in the team, including AWS setup/troubleshooting, model tuning etc.