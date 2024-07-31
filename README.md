# LEGO Dataset Analysis

This project explores and analyzes a dataset of LEGO sets, colors, and themes. The analysis includes visualizations and insights into the distribution of colors, evolution of parts, popularity of themes, and more.

## Data Sources

The project uses two main datasets:

- **colors.csv**: Contains details about LEGO colors, including `id`, `name`, `rgb`, and `is_trans` (transparency status).
- **sets.csv**: Contains information about LEGO sets, including `set_num`, `name`, `year`, `theme_id`, and `num_parts`.

## Analysis and Visualizations

### 1. Color Analysis
- **Distribution of Colors**: Shows the count of different colors available in the dataset.
- **Proportion of Transparent vs. Opaque Colors**: Visualized using a pie chart.

### 2. Sets Analysis
- **Average Number of Parts per Set by Year**: Analyzed using line plots to show trends over time.
- **Distribution of Number of Parts**: Histogram of the number of parts in different sets.

### 3. Themes Analysis
- **Popularity of Themes Over Time**: Number of sets released per theme each year.
- **Average Number of Parts in Top Themes**: Bar plot of the average number of parts for the most popular themes.
- **Evolution of Number of Parts in Top Themes**: Line plot showing how the average number of parts has evolved in top themes over the years.

## Key Findings
- The dataset shows a significant increase in the diversity of colors over time.
- The average number of parts per set has generally increased, reflecting more complex builds.
- Certain themes have consistently been popular, with significant variations in the number of parts.

## Getting Started

### Prerequisites
- Python 3.x
- Pandas
- Matplotlib
- Seaborn

### Installation
Clone the repository and install the required packages:

```bash
git clone <repository-url>
cd lego-dataset-analysis
pip install -r requirements.txt
