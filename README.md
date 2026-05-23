# IPL Crunch '26 — Data Analytics Challenge

Submission by **Ashmit (IIT Delhi)** for the Wooble IPL Crunch '26 challenge.

## What's inside
Ball-by-ball analysis of 1,218 IPL matches across 19 seasons (2007–2026), answering:

1. **Do teams that win the toss actually win more matches?**
2. **Which phase — Powerplay, Middle Overs, or Death Overs — is most linked to winning?**
3. **Who are the top 5 batters and top 5 bowlers across all seasons?**
4. **What hidden pattern in the data genuinely surprised us?**

## Key findings
- Toss winners won only **50.5%** of matches — essentially a coin flip
- **Middle Overs** show the biggest gap between winners and losers (+7 runs)
- All-time leaders: **V Kohli (9,050 runs)**, **YS Chahal (229 wickets)**
- **2018** was the inflection point — sixes per match jumped 36% in a single season

## How to run
1. Download IPL dataset from [Cricsheet.org](https://cricsheet.org/matches) (CSV format) or the [Wooble challenge resources](https://wooble.org/hackathon/crunch-26)
2. Place `dataset.csv` in the project root
3. Open `ipl_crunch.ipynb` in Jupyter and run all cells

## Tools used
Python, Pandas, Matplotlib, Scikit-learn

## Data source
[Cricsheet.org](https://cricsheet.org/matches) — official IPL ball-by-ball data
