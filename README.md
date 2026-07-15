# Man United's Midfield Rebuild — Where Are The Gaps?

## Question
Manchester United signed Andrey Santos and Youri Tielemans in the 
same week. But does the new midfield actually cover every dimension 
a top team needs — or are there still gaps? And which of their 
reported transfer targets best fills what's missing?

## Project Structure
This project produces two heatmaps:

1. **Current midfield heatmap** — Santos, Ugarte, Tielemans, Bruno 
   Fernandes, and Mainoo mapped across eight key metrics
2. **Transfer targets heatmap** — five reported targets evaluated 
   against the same metrics to identify who fills the gap

## Data
FBRef 2024/25 Big 5 European Leagues player statistics (via Kaggle).

- **Heatmap 1** filtered to pure midfielders (Pos == 'MF') in 
  Ligue 1 and the Premier League with 900+ minutes — 117 
  midfielders in total
- **Heatmap 2** filtered to pure midfielders across all five leagues 
  with 900+ minutes — broader pool to fairly compare targets playing 
  in Bundesliga and Serie A

## Metrics
All eight metrics calculated as per-90-minute values, then 
expressed as percentile ranks within the relevant comparison pool:

- Tackles per 90
- Interceptions per 90
- Tkl+Int per 90 (combined defensive actions)
- Goals per 90
- Assists per 90
- Progressive Passes per 90
- Progressive Carries per 90
- Key Passes per 90

## Key Findings

**Current midfield:**
- Santos (93rd tackles, 94th goals) and Ugarte (96th tackles, 
  97th Tkl+Int) give United two of the best ball-winners in either 
  league in the same midfield
- Bruno (100th key passes, 97th prog passes) and Tielemans (89th 
  key passes, 92nd prog passes) provide elite creative output
- Kobbie Mainoo — 16th percentile goals, 14th assists, 22nd 
  progressive passes. Average defensively, well below average 
  offensively. The collective gap is a genuine box-to-box profile 
  that contributes on both sides simultaneously

**Transfer targets:**
- Lamine Camara (Monaco) — the most complete profile. Green across 
  both defensive and creative metrics. Only player on the list who 
  genuinely covers both sides
- Felix Nmecha (Dortmund) — 90th percentile goals, strong 
  interceptions. A genuine box-to-box scorer
- Adam Wharton and Carlos Baleba — elite defensively, limited 
  offensively. Another Ugarte-type profile, not the gap filler
- Manu Koné — elite progressive carrier (91st), poor defensive 
  numbers. Specialist only

## Conclusion
United's midfield is elite in attack and elite in defence — but 
the combination of those qualities in one player is what's missing. 
Camara and Nmecha are the only reported targets whose profiles are 
genuinely balanced across both sides. Everyone else on the list 
defends but doesn't create, or creates but doesn't defend.

## Limitation
Comparing players across different leagues using a shared percentile 
pool introduces some imprecision — league quality and playing styles 
differ. These percentiles should be read as indicative profiles 
rather than direct equivalents.

## Tools Used
Python · Pandas · NumPy · SciPy · Seaborn · Matplotlib · 
Jupyter Notebook

## Author
Rafiz Rayhan
linkedin.com/in/rafiz-rayhan
github.com/rafizrayhan
