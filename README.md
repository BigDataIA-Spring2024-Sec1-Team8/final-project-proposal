# Final Project Proposal

## Project Overview
MarketMind is an innovative analytics platform designed to transform e-commerce through advanced data aggregation and intelligent analysis. This platform aims to enhance business strategies and consumer engagement by providing real-time insights and personalized product recommendations through a user-friendly conversational interface. It employs cutting-edge machine learning to understand user preferences and taps into customer reviews for a deeper sentiment analysis, enabling businesses to better grasp market demands and customer satisfaction. Emphasizing accessibility, MarketMind offers a seamless user experience, making sophisticated big data analytics available to businesses of all sizes. Built on a scalable cloud infrastructure, it promises to not only streamline the e-commerce experience but also make big data analytics more accessible in the bustling e-commerce arena.

## Project Resources
[![Google Codelabs](https://img.shields.io/badge/-Google%20Codelabs-blue?style=for-the-badge)](https://codelabs-preview.appspot.com/?file_id=1pRm59ElUkxoqgvT62tF9CEygV7fJEHx4JsTQossEerM#2)

## Tech Stack
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Amazon AWS](https://img.shields.io/badge/Amazon_AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Python](https://img.shields.io/badge/Python-4B8BBE?style=for-the-badge&logo=python&logoColor=yellow)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-00A7E1?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-6558F5?style=for-the-badge&logo=pinecone&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Amazon S3](https://img.shields.io/badge/Amazon_S3-F7CA18?style=for-the-badge&logo=amazon-s3&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-2D9CDB?style=for-the-badge&logo=pydantic&logoColor=white)

## Architecture Diagram
![image](https://github.com/BigDataIA-Spring2024-Sec1-Team8/final-project-proposal/assets/114782541/8d90aa23-27e9-48d7-86b2-763036d65b23)


The "MarketMind" architecture combines a Streamlit-powered frontend with a FastAPI and Snowflake backend, all hosted on AWS for robust scalability. This smart e-commerce analytics system uses a chatbot interface for user interaction, processes queries for personalized product matching, and employs OpenAI for enriching content and summarizing data. Automated data extraction, cleaning, and embedding enable the platform to transform raw e-commerce data into insightful, user-friendly outputs.

### Customer Query Pipeline:
![image](https://github.com/BigDataIA-Spring2024-Sec1-Team8/final-project-proposal/assets/114782541/dc45d4d2-c635-4cc2-be95-7d5a56181774)
The MarketMind platform orchestrates a fluid interaction cycle starting with user queries via a chatbot and culminating in personalized responses. User inputs are refined by the backend, leveraging machine learning to classify and embed them into relevant categories for precise product matching. These are further enhanced by OpenAI models to enrich the content provided. The final, customized output is then displayed through a Streamlit UI, ensuring an interactive and informative shopping experience.

### Data Processing Pipeline
![image](https://github.com/BigDataIA-Spring2024-Sec1-Team8/final-project-proposal/assets/114782541/350ef92f-a813-4d72-a92b-c49c75034696)

The Data Processing Layer for the MarketMind project ingests raw e-commerce data, meticulously cleansing and condensing product information and reviews from Amazon's vast datasets. Relevant details are summarized and embedded into a vector space, making them amenable for advanced analytics. These processed assets, including both text and images, are then stored in Snowflake, a cloud data warehouse that supports the platform's scalable, data-driven functionalities. This streamlined pipeline ensures the integrity and utility of data that feeds into the MarketMind user experience.

## Contributions
-Sai Durga Mahesh Bandaru - 33.3%

-Sri Poojitha Mandali - 33.3%

-Shivani Gulgani - 33.3%

WE ATTEST THAT WE HAVEN’T USED ANY OTHER STUDENTS’ WORK IN OUR ASSIGNMENT AND ABIDE BY THE POLICIES LISTED IN THE STUDENT HANDBOOK
