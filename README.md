# END_TO_END_MEDICAL_CHATBOT

# STEPS
# Clone the repository
# https://github.com/prabhav02/END_TO_END_MEDICAL_CHATBOT.git

# STEP 01- Create a conda environment after opening the repository
# conda create -n medibot python=3.12.11 -y
# conda activate medibot

# STEP 02- install the requirements
# pip install -r requirements.txt

# Create a .env file in the root directory and add your Pinecone & Groq credentials as follows:

# PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
# GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
 # run the following command to store embeddings to pinecone
python store_index.py

## Finally run the following command
#python app.py
