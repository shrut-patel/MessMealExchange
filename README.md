# IIITH Students Mess Meal Exchange: Market Research Dashboard

An interactive **Power BI** dashboard built from a survey of **350 IIITH students** to study meal-missing behaviour and to validate demand for **MealSwap**, a proposed platform for exchanging unused mess meals.

---

## Table of Contents

- [Background](#background)
- [Objective](#objective)
- [Data](#data)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Proposed Solution: MealSwap](#proposed-solution-mealswap)
- [Tech Stack](#tech-stack)
- [Repository Structure](#repository-structure)
- [How to Use](#how-to-use)
- [Survey Form](#survey-form)
- [Author](#author)
- [Copyright and License](#copyright-and-license)

---

## Background

Students at IIITH depend on the campus messes for their daily meals. Because of classes, labs, deadlines, hackathons and other commitments, they often miss meals they have already paid for. There is no way to pass an unused meal to another student, which leads to:

- Money lost by students
- Food wastage
- Frustration

## Objective

To design and develop a dynamic, interactive Market Research Dashboard in Power BI that visualizes the survey data and helps decide whether launching a meal exchange platform is worthwhile.

The full problem statement is in [`Problem_Statement.docx`](./Problem_Statement.docx).

## Data

| Item | Details |
|---|---|
| Collection method | Tally survey form (15 questions) |
| Respondents | 350 students |
| UG students | 274 |
| PG students | 76 |

## Dashboard Features

### KPI Cards
- Students Surveyed
- Average Meals Missed
- Average Money Lost
- Average Frustration
- Market Adoption Intent
- Market Penetration

### Charts
| Chart | Purpose |
|---|---|
| Volume Shares of Mess (donut) | Share of students across each mess |
| Missed Meal Distribution | How often students miss meals |
| Adapting New Platform (branch × Yes/Maybe/No matrix) | Branch-wise willingness to adopt the platform |
| Amount To Pay | How much students would pay for an exchanged meal |
| Frustration Score | How frustrated students are by missed meals |
| Feature Priority | Features students want most |

### Extras
- UG vs PG split card
- CAC (Customer Acquisition Cost) text box
- 50-word Analysis
- 50-word Proposed Solution

## Key Insights

- **Market Adoption Intent: 91.43%**, so the large majority of respondents are open to using a meal exchange platform.
- The survey covers both UG (274) and PG (76) students across branches.


## Proposed Solution: MealSwap

**MealSwap** is a platform that lets students sell or exchange their unused mess meals with other students. It reduces money lost, cuts food wastage and gives students a simple way to recover the value of missed meals.

## Tech Stack

- **Power BI Desktop**: data modelling, DAX measures and visuals
- **Tally**: survey collection
- **Microsoft Word**: problem statement document

## Repository Structure

```
.
├── README.md
├── Problem_Statement.docx
├── MessMealExchange_Dashboard.pbix     # Power BI dashboard file
├── data/
│   └── survey_responses.csv            # survey data (anonymised)
└── screenshots/
    └── dashboard.png                   # dashboard preview
```


## How to Use

1. Clone the repository:
   ```bash
   (https://github.com/shrut-patel/MessMealExchange/)
   ```
2. Open the `.pbix` file in **Power BI Desktop**.
3. If prompted, point the data source to `data/survey_responses.csv` (Home → Transform data → Data source settings).
4. Use the slicers and visuals to explore the results.

## Survey Form

The survey used for data collection: [https://tally.so/r/eqb9Re](https://tally.so/r/eqb9Re)

## Author

Shrut Viroja
IIIT Hyderabad

- GitHub:https: //github.com/shrut-patel/
- LinkedIn: https://www.linkedin.com/
- Email: shrut3337@gmail.com

## Copyright and License

Copyright © 2026 Shrut. All rights reserved.

*Made for the IIITH student community.*
