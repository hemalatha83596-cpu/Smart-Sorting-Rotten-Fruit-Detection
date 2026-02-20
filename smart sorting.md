# Smart Sorting: Rotten Fruit Detection

This project uses Transfer Learning (MobileNetV2) to classify fruits and vegetables as **Fresh** or **Rotten**.

## Project Structure
- `data/`: Contains the training and testing images.
- `models/`: Stores saved models.
- `src/`: Source code for training and processing.
- `app.py`: Streamlit application.

## Setup
1.  Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2.  (Optional) Download dataset:
    Run the dataset download script:
    ```bash
    python src/1_download_data.py
    ```
3.  Train the model:
    ```bash
    python src/2_train_model.py
    ```
4.  Run the app:
    ```bash
    streamlit run 3_run_app.py
    ```