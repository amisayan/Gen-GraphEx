# Gen-GraphEx
Official Repository  of Gen-GraphEx
# Guide to Running Jupyter Notebooks

This README provides detailed instructions on how to run the provided Jupyter notebooks either through Google Colab for an online, cloud-based approach, or locally on your machine using a `requirements.txt` file for managing dependencies.

## Overview of Notebooks

These notebooks are designed to perform graph explanation generation and analysis using Gen-GraphEx. Each notebook gives the full workflow beginning from generating/importing a dataset, training a classifier, checking the explanantions on target classes and finally also generating instances on the decision boundary.

Google Colab allows you to run notebooks directly in your browser without any setup required, which is ideal for users who prefer not to deal with local environment setups.

### Steps:

1. **Access Google Colab**:
   - Visit [Google Colab](https://colab.research.google.com/) and log in using your Google account.

2. **Upload the Notebook**:
   - Select `File > Upload notebook`.
   - Browse and upload the `.ipynb` file you want to run.

3. **Run the Notebook**:
   - To execute the code, select `Runtime > Run all`.
   - Alternatively, run cells individually by clicking the play button next to each cell.

4. **Save and Download Your Work**:
   - To save a copy of your notebook to Google Drive, choose `File > Save a copy in Drive`.
   - To download the notebook to your local system, select `File > Download .ipynb`.

## Running Notebooks Locally

For those preferring to run notebooks locally, ensure you have Python and Jupyter installed, with all dependencies managed through a `requirements.txt` file.

### Prerequisites:

- **Python 3.x**: Download and install from [python.org](https://www.python.org/downloads/).
- **Jupyter**: Install by running `pip install jupyter` in your command line.

### Steps:

1. **Setup Your Project Directory**:
   - Create a directory for your project.
   - Place the `.ipynb` notebook files and `requirements.txt` file in this directory.

2. **Install Dependencies**:
   - Open a command prompt or terminal.
   - Navigate to your project directory.
   - Execute `pip install -r requirements.txt` to install the required Python packages.

3. **Launch Jupyter Notebook**:
   - In the command prompt or terminal, run:
     ```
     jupyter notebook
     ```
   - This will open Jupyter in your default web browser.

4. **Open and Run Your Notebook**:
   - Navigate to and open your notebook file through the Jupyter interface.
   - Execute the notebook cells as needed by clicking the run button.

## Saving Your Work Locally

- To save changes to your notebook, use the save option available in the Jupyter interface under the `File` menu.

This README aims to facilitate users in setting up and running the provided Jupyter notebooks in their preferred environments effectively.
