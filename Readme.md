1. Create a conda environment with the following command:
    > conda env create -n environment_name python=3.7
2. Activate the environment:
    > conda activate environment_name
3. Install the requirements from root folder:
    > pip install -r requirements.txt
4.  > cd Chatbot
5. Run the Rasa server from Chatbot folder:
    > rasa run -m models --enable-api --cors "*"
6. Launch index.html file (present in Chatbot folder) in the browser to interact with the chatbot. 