# analyzing_public_perception_and_engagement_with_climate_change_on_reddit

This repository contains a Python project for performing sentiment analysis on Reddit data. The goal is to analyze public perception and engagement with various topics, classifying sentiments in Reddit comments and posts using machine learning techniques.

## Prerequisites

Before running this project, ensure you have the following installed:
- Python 3.x
- pip (Python package manager)

## Installation

1. **Clone the Repository**
   ```bash
   git clone [Your_Repository_URL]
   ```

2. **Navigate to the Project Directory**
   ```bash
   cd [Your_Project_Directory]
   ```

3. **Install Required Python Libraries**
   - The project requires several Python libraries. You can install them using pip:
     ```bash
     pip install pandas scikit-learn nltk regex matplotlib seaborn jupyter
     ```
   - This will install:
     - `pandas`: For data manipulation and analysis.
     - `scikit-learn`: For machine learning algorithms and model evaluation.
     - `nltk`: For natural language processing tasks.
     - `regex`: For regular expression operations.
     - `matplotlib` and `seaborn`: For data visualization.
     - `jupyter`: For running Jupyter notebooks.

4. **Set Up NLTK**
   - Download the necessary NLTK resources:
     ```python
     import nltk
     nltk.download('stopwords')
     nltk.download('punkt')
     nltk.download('wordnet')
     ```

## Dataset

Place the `final_dataset.csv` file in the project directory. This file contains the Reddit comments and posts data used for sentiment analysis.

## Running the Code

1. **Open the Jupyter Notebook**
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open the `Final_Notebook.ipynb` file in Jupyter Notebook.

2. **Run the Notebook**
   - Execute each cell in the notebook to preprocess data, train the model, and evaluate the results.

## Contributing

To contribute to this project:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature_branch`).
3. Make changes and commit them (`git commit -m 'your_message'`).
4. Push to the branch (`git push origin feature_branch`).
5. Create a new Pull Request.