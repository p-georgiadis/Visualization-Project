# Visualization-Project

## Overview
This project is part of the course **"Fundamentals of Data Visualization"** offered by the **University of Colorado Boulder**. The course explores the design, development, and evaluation of information visualizations, combining aspects of design, computer graphics, HCI, and data science. This project involves working with the Titanic dataset to perform exploratory data analysis and create insightful visualizations.

### About the Course
**Course:** Fundamentals of Data Visualization  
**Institution:** University of Colorado Boulder  
**Instructor:** Danielle Szafir, Assistant Professor, ATLAS Institute and Computer Science

**Course Description:**
Data is everywhere. Charts, graphs, and other types of information visualizations help people make sense of this data. This course explores the design, development, and evaluation of such information visualizations. By combining aspects of design, computer graphics, HCI, and data science, students gain hands-on experience with creating visualizations, using exploratory tools, and architecting data narratives. Topics include user-centered design, web-based visualization, data cognition and perception, and design evaluation.

## Project Structure
The project is organized into the following files and directories:

- `Exploratory_Data_Analysis.ipynb`: Jupyter notebook containing the exploratory data analysis of the Titanic dataset.
- `titanic.csv`: The Titanic dataset used for analysis and visualization.
- `requirements.txt`: List of Python packages required to run the Jupyter notebook.
- `visualizations/`: Directory containing saved images of all the visualizations created in the Jupyter notebook.
- `project_documents/`: Directory containing various markdown files documenting different aspects of the project and the Final Report:
    - `Discussion_of_the_dataset.md`
    - `Sketching_your_Data.md`
    - `Preliminary_Evaluation_Plan.md`
    - `Final_Report.md`
    - `index.md`

## Getting Started
To get the notebooks up and running, follow these steps:

### Prerequisites
Make sure you have Python installed. It's recommended to use a virtual environment to manage dependencies.

### Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/Visualization-Project.git
    cd Visualization-Project
    ```

2. Create a virtual environment:
    ```sh
    python -m venv venv
    ```

3. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS and Linux:
        ```sh
        source venv/bin/activate
        ```

4. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

5. Launch Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

6. Open the `Exploratory_Data_Analysis.ipynb` notebook and run the cells to see the exploratory data analysis and visualizations.

## Project Documents
The `project_documents` directory contains detailed documentation about different aspects of the project. You can navigate through the documents by visiting the [Project Documents Index](project_documents/index.md).

- **[Discussion of the dataset](project_documents/Discussion_of_the_dataset.md)**: Discusses the source of the data, key attributes, and goals for working with the data.
- **[Sketching your data](project_documents/Sketching_your_Data.md)**: Contains sketches and preliminary design ideas for visualizing the data.
- **[Preliminary Evaluation Plan](project_documents/Preliminary_Evaluation_Plan.md)**: Outlines a plan for evaluating the effectiveness of the visualizations.
- **[Final Report](Final_Report.md)**: The final project report includes a comprehensive analysis of the data, visualizations, evaluation approach, and a synthesis of findings.

## Dataset
The Titanic dataset used in this project is sourced from Kaggle. You can find the dataset at [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/brendan45774/test-file/data).

## Visualizations
All visualizations created during this project are stored in the `visualizations/` folder. Each image is saved in `.png` format and named according to the type of visualization (e.g., `Survival_by_Class.png`, `Age_Distribution.png`).

## Evaluation Approach
The evaluation of the visualizations was conducted with three participants who reviewed the visualizations for clarity, effectiveness, and insightfulness. The feedback received helped refine the visualizations and improve the overall design approach.

## Authorship
This project is the work of Panagiotis Georgiadis, a current graduate student pursuing a Master's in Computer Science at the University of Colorado Boulder.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements
Special thanks to Danielle Szafir, Assistant Professor at the ATLAS Institute and Computer Science, University of Colorado Boulder, for teaching the course and providing the foundational knowledge for this project.
