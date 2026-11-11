# Substance Harm Across New Zealand

Group project analysing how drug-related police activity differs across New Zealand police districts, written for a New Zealand Government audience.

**Team:** Crime Busters ([add teammates' names]) · **Course:** [add course code], University of Auckland, 2026
**My contribution:** [describe what you did, e.g. data cleaning, regression modelling, Auckland analysis, slides]

## Question
Do police districts differ in their rates of drug-related police action, and do the types of drugs involved differ too?

## Data
- NZ Police drug-related police actions, January 2016 – June 2023
- NZ Police proceedings data, to extend the Auckland analysis to 2026
- Stats NZ population estimates
- New Zealand Health Survey

## Methods
- Converted police actions to **rates per 10,000 people** so districts of different sizes could be compared fairly
- **Quasi-Poisson regression** on monthly counts, with month effects and a population offset
- Compared drug types (all drugs, cannabis, methamphetamine) and three time periods around the 2019 Misuse of Drugs Amendment Act
- Split Auckland into its three police districts to check where its decline came from

## Key findings
- Rates varied more than twofold between districts: **Bay of Plenty 45.8** vs **Auckland 20.8** actions per 10,000 people.
- Districts differ in drug mix as well as volume. Tasman had the highest cannabis (101.5) and methamphetamine (28.0) rates among the districts compared.
- Possession/use proceeding rates fell about 49–58% across all three Auckland districts between 2020 and 2022.
- Police actions measure policing activity, not drug use, so the results describe enforcement patterns, not where people use more drugs.

## Recommendation
Plan substance-harm responses at the district level, and use police data alongside health and wastewater evidence.

## Files
- `report.pdf` – full written report with technical supplement
- `presentation.pdf` – slide deck
