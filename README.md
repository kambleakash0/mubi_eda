# Mubi Movie Dataset Analysis

This repository contains a Jupyter Notebook (`eas503-mini-project-1.ipynb`) that performs an analysis of a Mubi movie dataset. The analysis explores rating trends, director popularity, user behavior patterns, and list engagement.

## Data Source

The analysis utilizes several CSV files derived from Mubi's movie platform:

*   `mubi_ratings_data.csv`
*   `mubi_movie_data.csv`
*   `mubi_ratings_user_data.csv`
*   `mubi_lists_data.csv`

To run the notebook, these files are expected to be located in a `data/` directory within the repository's root.

## Visualizations

The notebook generates and saves the following plots:

*   **MUBI Rating Activity:** A time series plot illustrating the number of monthly ratings on the platform from 2007 to 2021. (Saved as `Rating Activity.png`)
*   **Directors: Cult Followings vs Broad Appeal:** A scatter plot analyzing directors based on their average movie ratings versus the total number of ratings their movies have received (for directors with >100 ratings). (Saved as `Directors.png`)
*   **List Followers Distribution: Subscribers vs Trialists:** A histogram comparing how many followers curated movie lists attract, segmented by Mubi subscribers and trialists. (Saved as `Lists.png`)
*   **24-Hour Viewing Intensity:** A circular bar plot displaying the distribution of rating activity by the hour of the day (UTC). (Saved as `Circular.png`)

## Setup and Usage

To run the analysis:

1.  **Prerequisites:**
    *   Python 3

2.  **Installation:**
    *   Clone this repository.
    *   Install the necessary Python dependencies:
        ```bash
        pip install -r requirements.txt
        ```

3.  **Running the Notebook:**
    *   Ensure the data CSV files are placed in a `data/` directory in the root of the repository.
    *   Open and run the `eas503-mini-project-1.ipynb` notebook using a Jupyter environment (e.g., Jupyter Notebook, JupyterLab, VS Code).
    *   The generated plots will be saved as PNG files in the root directory of the repository.

## Files in the Repository

*   `.gitignore`: Specifies intentionally untracked files that Git should ignore.
*   `LICENSE`: Contains the license for this project.
*   `README.md`: This file, providing an overview of the project.
*   `eas503-mini-project-1.ipynb`: The main Jupyter Notebook containing the data loading, preprocessing, analysis, and visualization code.
*   `requirements.txt`: A list of Python packages required to run the notebook.

## License

Please refer to the `LICENSE` file for details on the licensing of this project.
