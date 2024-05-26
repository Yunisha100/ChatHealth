# MHM-Nepal_Health_QA
![ChatNepali](https://github.com/Yunisha100/ChatHealth/assets/88446875/1e60182c-72ed-4baf-92bb-a6f69cab85c2)

The "Open-Source Nepali Health-QA Language Model with Finetuned Transformers and External Knowledge Bases" aims to provide accessible and accurate health-related information in the Nepali language. By fine-tuning the mT5 transformer model and leveraging a vector database, this project enhances the capability of answering health-related queries with precision and contextual relevance. The system offers valuable second opinions and supports users in making informed health decisions.
![CH1 (2)](https://github.com/Yunisha100/ChatHealth/assets/88446875/0ecb8e1f-e042-4633-a753-77007661b769)
![CH2](https://github.com/Yunisha100/ChatHealth/assets/88446875/1b0aa11e-b6c9-41f4-96ab-6331bd21dc24)
## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)

  
## Features
1.Vector Database for Efficient Retrieval
The project uses a vector database (Pinecone index) to improve the accuracy of retrieving relevant information. By employing mathematical dot product or cosine similarity, the system efficiently identifies and returns the most pertinent answers to user queries.
This approach ensures quick and scalable access to vast amounts of health data, making it suitable for real-time applications.

2.Multilingual Support
 Specifically tailored to support health-related queries in the Nepali language, addressing the challenges posed by limited linguistic resources.
 Ensures that the information and responses are culturally relevant and understandable for Nepali-speaking users.

3.Second Opinion Functionality
Beyond just answering queries, the model offers a second opinion on health-related questions, providing users with additional insights and perspectives that can aid in their decision-making process.

4.Evaluation and Analysis
The model's performance is evaluated using metrics like BLEU scores and ROUGE scores, ensuring quantitative measurement of its effectiveness.

Output:
![Screenshot 2024-05-25 140551](https://github.com/Yunisha100/ChatHealth/assets/88446875/50193748-ea79-48f0-80bc-2506ddd219ff)

## Installation 
# Installation
To get started, follow the following steps
1. Clone the repo
  ```bash
  git clone https://github.com/Yunisha100/ChatHealth.git
  ```
2. Install all the requirements
 ```bash
 pip install -r requirements.txt
 ```
3. Start the server
```bash
python manage.py runserver
```
4. Start the server for frontend
```bash
npm start
```
