# Depression-detection-in-reddit-users

# Depression Detection App

This is a Streamlit app that uses machine learning to predict whether a Reddit post suggests depression or not.

## Requirements
To run this app, you need Python 3.8+ and the required packages listed in `requirements.txt`.

## Setup

1. Clone the repository:

   ```
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
   ```

2. Create a virtual environment and activate it:
   - For Windows:
     ```
     python -m venv venv
     .\venv\Scripts\activate
     ```
   - For macOS/Linux:
     ```
     python3 -m venv venv
     source venv/bin/activate
     ```

3. Install the dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the Streamlit app:
   ```
   streamlit run d2.py
   ```

5. The app should now be live in your browser.

## Model
The model is pre-trained, so you don't need to train it again. Simply run the app, and the model will be loaded from the `stacked_model.pkl` file.

## Help
If you're feeling depressed or anxious, please refer to the links in the sidebar for helplines and mental health resources.
