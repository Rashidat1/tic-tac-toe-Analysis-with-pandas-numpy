Tic-Tac-Toe Endgame Analysis

This project explores the *Tic-Tac-Toe Endgame dataset* from the UCI Machine Learning Repository.  
The dataset contains all possible final board states of tic-tac-toe and whether player X wins.
source : https://archive.ics.uci.edu/dataset/101/tic+tac+toe+endgame

 Analysis Steps
1. *Data Exploration*
   - Loaded dataset with Pandas
   - Displayed first rows (`.head()`), data types (`.info()`), and summary statistics (`.describe()`)

2. *Basic Statistics*
   - Calculated mean, median, mode, and standard deviation for encoded features
   - Examined class distribution
   - Computed correlation matrix (`.corr()`)

3. *Encoding*
   - Converted categorical values (`x`, `o`, `b`) into numeric form using `LabelEncoder`

4. *Visualization*
   - Heatmap of correlations using Seaborn
   - Frequency counts of board positions

 Results
- Certain board positions (like the center square) show stronger correlation with the outcome
- Dataset is well-suited for classification tasks (e.g., decision trees)

 
