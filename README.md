This project is a simple chatbot built using Python, Keras, and TensorFlow. 

Requirements
keras_nightly==2.5.0.dev2021032900
tensorflow==2.5.0
numpy==1.19.5
nltk==3.6.2
keras==2.4.3 (optional, only if not using tf.keras)

Install the dependencies:  pip install -r requirements.txt
Before running the code, ensure you have the necessary NLTK data files by running:  import nltk
nltk.download('punkt')
nltk.download('wordnet')

To train the chatbot model:
Ensure that intents.json is populated with the necessary intents, patterns, and responses.
Run the train_chatbot.py script to preprocess data and train the model.
The trained model is saved as chatbot_model.h5, and the processed words and classes are saved as words.pkl and classes.pkl.
