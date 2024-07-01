---
permalink: /
title: "Data Engineering Portfolio"
author_profile: true
redirect_from: 
  - /portfolio/
  - /portfolio.html
---

### News Extraction and Recommendation System 
**Technologies:** ETL, Airflow, Snowflake, Kafka, CI/CD, MongoDB, FastAPI, Beautiful Soup, Spacy, OpenAI, GPT  
**GitHub Repository:** [Link to Repository](https://github.com/BigDataIA-Spring2024-Sec2-Team2/Final-Project)   
- Spearheaded the creation of an ETL pipeline to extract over 300 news stories every 10 minutes, embedding news titles into a vector database, summarizing using the GPT model, and loading them into Snowflake
-	Established streaming alerts on Kafka for keyword sets, utilizing a Python service to match alerts with user interests stored in MongoDB, and delivering alerts to users via a FastAPI endpoint


### Knowledge Retrieval System (RAG Application)
**Technologies:** RAG, Generative AI, ETL, Airflow, Snowflake, GCP, OpenAI, LLM, Pinecone Vector DB 
**GitHub Repository:** [Link to Repository](https://github.com/BigDataIA-Spring2024-Sec2-Team2/Assignment-5)  
- Designed and implemented an ETL pipeline using Airflow to extract daily information from web sources, transform and load it into Snowflake, and utilized OpenAI's GPT model for efficient knowledge retrieval
- Integrated vector embeddings in Airflow, stored them in a Pinecone vector database for rapid retrieval of information based on user queries and hosted the entire system on GCP for scalability

### Stock Market Real-Time Data  
**Technologies:** Python, SQL, AWS, EC2, S3, Glue, Athena, Kafka, Docker  
**GitHub Repository:** [Link to Repository](https://github.com/ChaudharyAnshul/Stock-Market-Real-Time-Data)    
-	Designed a data pipeline project using Apache Kafka to stream 1000s of real-time stock market data using Python producer and consumer to load streamed data into different folders inside S3 bucket 
-	Utilized AWS Athena to query data from S3 storage using SQL queries and displaying the results on the Streamlit

### Automated PDF Data Extraction and Querying 
**Technologies:** Snowflake, data pipelining, Airflow, DBT, AWS, PyPDF, Data extraction  
**GitHub Repository:** [Link to Repository](https://github.com/BigDataIA-Spring2024-Sec2-Team2/Assignment-4)    
- Created an application to convert unstructured PDFs to structured data, storing files in S3 and initiating an Airflow pipeline for parsing using PyPDF and loading into Snowflake, supporting 1000+ simultaneous requests
-	Executed data transformation in DBT by loading Snowflake data into the DBT model and reloading it into the Snowflake production schema, while providing a Streamlit UI for querying all extracted data


### Text Classification using BERT (Financial Data) 
**Technologies:** LLM models, HuggingFace BERT, Resampling, PyTorch, Scikit-Learn, Machine Learning  
**GitHub Repository:** [Link to Repository](https://github.com/ChaudharyAnshul/TextClassification)    
- Achieved a 95% accuracy rate by fine-tuning Transformer-based LLM models (BERT, DistilBERT) for text classification of financial data into predefined classes (Noise, Text, Table)
- Enhanced model performance by implementing k-fold cross-validation for robustness and applying resampling techniques to address class imbalance in the dataset