# Visualizing the History of Nobel Prize Winners

The Nobel Prize has been among the most prestigious international awards since 1901. Each year, awards are bestowed in chemistry, literature, physics, physiology or medicine, economics, and peace. In addition to the honor, prestige, and substantial prize money, the recipient also gets a gold medal with an image of Alfred Nobel (1833 - 1896), who established the prize.

The Nobel Foundation has made a dataset available of all prize winners from the outset of the awards from 1901 to 2023. The dataset used in this project is from the Nobel Prize API and is available in the `nobel.csv` file in the data folder.

## Overview
In this project, you'll explore and visualize Nobel Prize data to answer various questions related to prize-winning trends and patterns. You can also explore further questions of your interest.

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `numpy`: For numerical operations.
- `seaborn`: For data visualization.

## Data
The dataset used is `nobel.csv` and includes the following columns:
- `full_name`: Name of the laureate.
- `sex`: Gender of the laureate.
- `birth_country`: Birth country of the laureate.
- `year`: Year of the award.
- `category`: Category of the award (e.g., Chemistry, Literature).

## Analysis Steps
1. **Load and Inspect Data**: Read in the Nobel Prize data and inspect the structure.
2. **Gender and Birth Country Analysis**: Identify the most common gender and birth country of Nobel laureates.
3. **USA-Born Winners Analysis**: Analyze the proportion of US-born winners over different decades.
4. **Female Winners Analysis**: Explore the proportion of female laureates by decade and category.
5. **First Female Nobel Laureate**: Identify the first woman to win a Nobel Prize.
6. **Repeat Winners**: List laureates who have won the Nobel Prize more than once.

## Insights
- **Most Common Gender**: Male.
- **Most Common Birth Country**: United States of America.
- **Decade with Highest Proportion of US-Born Winners**: Identified and visualized.
- **Category with Highest Proportion of Female Winners**: Identified and visualized.
- **First Woman to Win a Nobel Prize**: Marie Curie in Physics.
- **Repeat Winners**: List of laureates who have received 2 or more prizes.

## Conclusion
This analysis provides insights into Nobel Prize winners' trends and patterns, highlighting notable findings such as the first female laureate and the most common birth country of laureates.

## Requirements
To run this project, you need the following Python libraries installed:

- `pandas`
- `numpy`
- `seaborn`

## Usage

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/visualizing-nobel-prize-history.git
    ```
2. **Navigate into the Project Directory**:
    ```bash
    cd visualizing-nobel-prize-history
    ```
3. **Install the Required Libraries**:
    ```bash
    pip install pandas numpy seaborn
    ```
4. **Run the Jupyter Notebook**:
    Launch Jupyter Notebook and open the `nobel_analysis.ipynb` file to start the analysis.
    ```bash
    jupyter notebook nobel_analysis.ipynb
    ```
