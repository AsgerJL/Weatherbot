# Weatherbot

1. Install python 3.6 x64 bit
2. Run pip install -r requirements.txt
3. Open cmd with admin access
4. Run python -m spacy download en
5. Download npm
6. Run npm i -g rasa-nlu-trainer
7. Run python nlu_model.py
8. Done


## Training the Rasa Core model
    1. Start the custom action server by running:

python -m rasa_core_sdk.endpoint --actions actions

    2. Open a new terminal and train the Rasa Core model by running:

python dialogue_management_model.py

    3. Talk to the chatbot once it's loaded.


# Starting the interactive training session:
The process of running the interactive session is very similar to training the Rasa Core model:

    1. Make sure the custom actions server is running:

python -m rasa_core_sdk.endpoint --actions actions

    2. Start the interactive training session by running:

python train_interactive.py

