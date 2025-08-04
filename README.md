# PRODIGY_ML_05

This repository contains the Jupyter Notebook for the fifth machine learning task of the Prodigy InfoTech internship.

This project involves building a model to classify food images and is designed to be run within the Kaggle environment to take advantage of its free GPU resources and easy dataset integration.

## Dataset

The project uses the **Food-101** dataset available on Kaggle.

-   **Dataset Link:** [Food-101 on Kaggle](https://www.kaggle.com/datasets/dansbecker/food-101/data)

## How to Run on Kaggle

To run this project, you will need to manually create a new notebook on Kaggle and use the code from this repository. Follow the steps below:

1.  **Sign in to Kaggle:**
    Go to [https://www.kaggle.com/](https://www.kaggle.com/) and log in.

2.  **Create a New Notebook:**
    On the left sidebar, click **[+ Create]** and select **New Notebook**.

3.  **Add the Dataset:**
    -   Inside your new Kaggle notebook, look for the **"+ Add data"** button in the top-right panel.
    -   A search window will pop up. Search for the following dataset URL: `https://www.kaggle.com/datasets/dansbecker/food-101/data`
    -   Find the "Food-101" dataset by `dansbecker` and click the **Add** button. The data will now be accessible in your notebook's environment under the `/kaggle/input/` directory.

4.  **Copy the Code:**
    -   Open the `prodigy-ml-05.ipynb` file provided in this GitHub repository.
    -   Copy the code from the cells.
    -   Paste the code into the cells of your new Kaggle notebook.

5.  **Enable GPU (Recommended):**
    -   For faster model training, enable a GPU accelerator. In the right-hand panel of your Kaggle notebook, under **Settings > Accelerator**, select **GPU**.

6.  **Run the Cells:**
    Execute the cells in your Kaggle notebook one by one to see the results.
