# hotel-chatbot

# Pre-processing
## Pre-processing scripts are for reference and do not need to be ran
 - A_Scrape booking.com.ipynb – Scrapes hotel review data from Booking.com.
 - B_Data Preprocessing.ipynb – Cleans and structures the scraped review data for further analysis.
 - B2_EDA.ipynb – Exploratory Data Analysis (EDA) of the processed reviews to identify key patterns.
 - B3_Topic Modelling.ipynb – Performs topic modeling and sentiment analysis using BERTopic and sentence-level sentiment classification.
 - 'B3_Topic Modelling.ipynb - Colab.pdf' - The PDF of the above notebook, given that some figures cannot be displayed when opening notebook in Git.
 - C_Weaviate.ipynb – Uploads processed review data to Weaviate for semantic search and retrieval.

# Main script and Evaluation
## Running either the chat_main_code.py or 'Chatbot Main Code.ipynb' will have the Gradio UI appear
 - chatbot_main_code.py – Backend Python script for a chatbot that interacts with the Weaviate database to provide hotel insights.
   - Take note that the hugging face token has to be replace with your own before running the script
 - Chatbot Main Code.ipynb - Same script as the above, but in notebook format 
 - evaluation_v2.ipynb – Evaluation scripts for analyzing chatbot performance and sentiment accuracy.
