# British Airways — Customer Satisfaction Analysis in Tableau

![Tableau](https://img.shields.io/badge/Tool-Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Excel](https://img.shields.io/badge/Prep-Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

## Business context

British Airways collected passenger reviews covering seat comfort, cabin crew, food, ground service, value for money and in-flight entertainment. The goal is to help a quality manager see **where satisfaction is low**, for which passengers and on which aircraft, through an interactive Tableau dashboard.

## Data

- **1,324 reviews** with an overall rating and 6 service scores (1 to 5)
- Traveller type, seat class, aircraft, route, country, and whether the passenger recommends the airline
- A country reference table (country, code, continent, region) joined to map reviews geographically

## Approach

1. Explored the reviews in Excel and identified the main variables (dates, scores, aircraft, countries).
2. Related the reviews to the country table in Tableau to analyse by continent, and grouped aircraft models.
3. Built four views (summary of scores, map, monthly trend, aircraft comparison) combined in one dashboard, with filters by continent, traveller type, seat class, aircraft and date.

## Key results

| Indicator | Value |
|---|---|
| Reviews analysed | 1,324 |
| Passengers who recommend BA | **43%** |
| Best-rated criterion | Cabin crew service (3.3 / 5) |
| Worst-rated criterion | **In-flight entertainment (1.4 / 5)** |

**Insights**
- **Entertainment (1.4/5) and food & drinks (2.4/5)** are the weakest points: they are the first levers to improve.
- **Business travellers are the least satisfied: only 25% recommend BA**, against 55% for solo leisure travellers. This is a priority segment because it is also the most valuable.
- Cabin crew is the strongest asset (3.3/5) and should be protected in any cost-cutting decision.

## Dashboard

The dashboard shows the average of each score at the top, then the trend over time, a world map by country and a comparison by aircraft (average rating and number of reviews). A parameter lets the user switch the metric (rating, seat comfort, cabin crew, food, ground service, value, entertainment), and filters apply to seat class, traveller type, continent, aircraft and month.

## Skills demonstrated

Tableau · data preparation in Excel · data joins · maps · time series · interactive filters · customer analytics

## Files

| File | Content |
|---|---|
| `Tableau de bord final de british aiways.twb` | Tableau workbook (dashboard) |
| `british_airways_avis.xlsx` | Reviews data and country reference table |
| `Analyse des Avis Clients de British Airways.pdf` | Project brief |

<details>
<summary>🇫🇷 Version française</summary>

Analyse de **1 324 avis clients** de British Airways dans **Tableau**, pour aider un responsable qualité à repérer les points faibles du service.

- Seuls **43 %** des passagers recommandent la compagnie
- Points les plus faibles : **divertissement à bord (1,4/5)** et **restauration (2,4/5)**
- Les **voyageurs d'affaires** sont les moins satisfaits : **25 %** seulement recommandent BA, contre 55 % des voyageurs solo
- Point fort : le **personnel de cabine** (3,3/5)

Outils : préparation dans Excel, jointure avec une table de pays, tableau de bord Tableau avec carte, évolution dans le temps et filtres.
</details>

## Author

**Nanga Alexis Camara** — Junior Data Analyst
[Portfolio](https://portfolio-nanga.vercel.app) · [LinkedIn](https://www.linkedin.com/in/nanga-alexis-camara-292045242)
