# FIFA-Analysis

# FIFA 20 Player Dataset Analysis

## Overview
This project analyzes the FIFA 20 player dataset (`players_20.csv`) to explore various attributes of football players, including their nationality, club, shooting, defending, and wages. The analysis is performed using Python with libraries such as Pandas, Matplotlib, and Seaborn. The goal is to gain insights into player demographics, performance metrics, and team-specific statistics, with a focus on Real Madrid players.

## Dataset
The dataset (`players_20.csv`) contains detailed information about football players from the FIFA 20 video game. It includes 18,278 rows and 104 columns, covering attributes such as:
- Player identification (e.g., `sofifa_id`, `short_name`, `long_name`)
- Personal details (e.g., `age`, `height_cm`, `weight_kg`, `nationality`)
- Performance metrics (e.g., `overall`, `potential`, `shooting`, `defending`)
- Club and financial details (e.g., `club`, `wage_eur`, `value_eur`)
- Positional ratings (e.g., `lw`, `st`, `cb`)

## Project Structure
The Jupyter Notebook (`fifa_analsis.ipynb`) contains the following analyses:
1. **Data Loading and Exploration**:
   - Loading the dataset using Pandas.
   - Displaying the first few rows (`fifa.head()`), dataset shape, and summary statistics (`fifa.describe()`).
   - Listing all columns to understand the dataset's structure.
2. **Nationality Analysis**:
   - Counting the number of players per nationality.
   - Identifying the top 5 nationalities (England, Germany, Spain, France, Argentina).
3. **Player Performance Analysis**:
   - Extracting and sorting players by shooting ability (`player_shooting`).
   - Extracting and sorting players by defending ability (`player_defending`).
4. **Club-Specific Analysis (Real Madrid)**:
   - Filtering players from Real Madrid.
   - Sorting Real Madrid players by wages, shooting, and defending.
   - Analyzing the nationality distribution of Real Madrid players.

## Prerequisites
To run the notebook, you need the following Python libraries:
- `pandas`
- `matplotlib`
- `seaborn`

You can install them using pip:
```bash
pip install pandas matplotlib seaborn
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd <project-directory>
   ```
3. **Ensure the Dataset is Available**:
   - Place the `players_20.csv` file in the same directory as the notebook.
   - The dataset can be sourced from [Kaggle](https://www.kaggle.com/stefanoleone992/fifa-20-complete-player-dataset) or similar platforms.
4. **Launch Jupyter Notebook**:
   ```bash
   jupyter notebook fifa_analsis.ipynb
   ```
5. **Execute the Cells**:
   - Run each cell sequentially to perform the analysis.
   - Ensure the required libraries are installed and the dataset is correctly loaded.

## Key Findings
- **Nationality Distribution**: The top 5 nationalities with the most players are:
  - England: 1,667 players
  - Germany: 1,216 players
  - Spain: 1,035 players
  - France: 984 players
  - Argentina: 886 players
- **Top Shooters**: The players with the highest shooting stats are:
  - Cristiano Ronaldo (93.0)
  - Lionel Messi (92.0)
  - Harry Kane (91.0)
  - Sergio Agüero (90.0)
  - Fabio Quagliarella (89.0)
- **Top Defenders**: The players with the highest defending stats are:
  - Giorgio Chiellini (90.0)
  - Virgil van Dijk (90.0)
  - Kalidou Koulibaly (89.0)
  - Diego Godín (89.0)
  - Mats Hummels (89.0)
- **Real Madrid Insights**:
  - Top earners include Eden Hazard, Luka Modrić, and Toni Kroos.
  - Top shooters include Gareth Bale and James Rodríguez.
  - Top defenders include Sergio Ramos and Casemiro.
  - Nationality distribution shows a dominance of Spanish (13) and Brazilian (6) players.
