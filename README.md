# Cybercrime Classifier

## Overview
The Cybercrime Classifier is a machine learning project aimed at classifying cybercrime-related data. It leverages exploratory data analysis (EDA), machine learning models, and real-world datasets to build an effective classification system.

## Features
- **Data Analysis**: Perform exploratory data analysis using Jupyter notebooks.
- **Model Training**: Train a classifier using machine learning algorithms.
- **Prediction**: Predict outcomes based on input data.
- **Customizable Pipelines**: Easily modify and extend for new datasets.

## Project Structure
```
CybercrimeClassifier-main
├── EDA.ipynb               # Exploratory Data Analysis notebook
├── classifier.py           # Script for building or running the classifier
├── main.py                 # Entry point for the application
├── model.ipynb             # Notebook for model experimentation
├── requirements.txt        # Python dependencies
├── train.csv               # Training dataset
├── test.csv                # Testing dataset
├── updated_data_train.csv  # Updated training dataset
```

## Setup Instructions
### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook (optional, for `.ipynb` files)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd CybercrimeClassifier-main
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Run Exploratory Data Analysis:**
   Open `EDA.ipynb` in Jupyter Notebook and execute the cells to explore the data.

2. **Train the Model:**
   Run the `classifier.py` script to train the model:
   ```bash
   python classifier.py
   ```

3. **Execute Main Program:**
   Use the `main.py` file as the application entry point:
   ```bash
   python main.py
   ```

4. **Test the Model:**
   Evaluate the classifier on the test dataset (`test.csv`).

## Datasets
- **train.csv**: The primary dataset used for training the model.
- **test.csv**: Dataset used for evaluating model performance.
- **updated_data_train.csv**: Updated version of the training data for improved accuracy.

## Dependencies
The required Python libraries are listed in `requirements.txt`. Install them using:
```bash
pip install -r requirements.txt
```

## Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

## Contact
For any questions or feedback, please contact the project maintainer at [tejavenkatballa@gmail.com].

