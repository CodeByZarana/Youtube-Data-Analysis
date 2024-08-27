# T-Series YouTube Channel Analysis

This project focuses on analyzing the T-Series YouTube channel by extracting and visualizing key metrics such as views, likes, comments, and more. Using Python, the YouTube Data API, and various data analysis libraries, we have gathered and analyzed data from hundreds of videos to uncover trends and insights.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The T-Series YouTube channel is one of the most popular channels in the world. This project aims to explore its content by analyzing various video metrics. The analysis includes the following:

- Number of views, likes, dislikes, and comments on videos
- Distribution of video uploads over time
- Comparison of interaction metrics (likes, dislikes, comments) across videos
- Month-wise and year-wise trends in video performance

## Project Structure

- `YTanalysis.ipynb`: The Jupyter notebook containing all the code and analysis.
- `tseries.csv`: The dataset extracted from the YouTube Data API, which contains detailed metrics for each video.
- `README.md`: Project documentation.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/CodeByZarana/Youtube-Data-Analysis.git
    cd your-repository-name
    ```

2. Install the required Python packages:
    ```bash
    pip install pandas requests matplotlib seaborn
    ```

3. Ensure you have a valid YouTube Data API key to retrieve data.

## Usage

1. Open the `YTanalysis.ipynb` file in Jupyter Notebook or Jupyter Lab.
2. Run the cells in the notebook to fetch data, process it, and generate visualizations.
3. Review the analysis and insights provided in the notebook.

## Results

The analysis provides various insights, including:

- The most viewed and least viewed videos on the T-Series channel.
- Trends in video uploads over time.
- Interaction patterns such as the ratio of likes to dislikes and the percentage of viewers who comment.

## Contributing

Contributions are welcome! If you have any ideas to improve this project, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
