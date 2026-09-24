### Co-Prescription Pattern Mining with Association Rules
**Tools: Python, pandas, mlxtend (Apriori), TransactionEncoder** | M.S. Data Analytics Project (D212 - Data Mining II)

Applying market basket analysis to hospital prescription data to uncover medications frequently prescribed together and what they might suggest about patient comorbidities.
 
- Caught an import artifact where every other row was blank and removed those rows before analysis
- Restructured patient prescription columns into transaction lists and one-hot encoded them for the Apriori algorithm
- Tested support thresholds from 0.01 to 0.2 and chose 0.05 to balance meaningful patterns against noise, with a minimum lift of 1.1
- Surfaced cardiovascular and psychiatric co-prescription pairings (lift up to about 1.44) and recommended joining results with diagnostic data to validate the patterns clinically

[Documentation](https://github.com/hrbergman/prescription-market-basket-analysis/blob/main/prescription-market-basket-analysis/market-basket-analysis-documentation.pdf)
| 
[Video Presentation](https://youtu.be/tVKcg7JKQv8)
