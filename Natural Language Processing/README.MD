**Course Name: Natural Language Processing**
* **Project Title**: Joint Topic and Sentiment Modelling for a Comparative Assessment of Product Lines - Leveraging Consumer-Generated * Data for Disney World’s Theme Parks Across Digital Platforms
* **Deliverable**: Python code for combined topic modelling and sentiment analysis
* **Tools**: Python (SciKit-Learn, NLTK, Top2Vec)

**Exam deliverable**: Apply traditional and state-of-the-art NLP techniques on an interesting text dataset

**Outcome**:
* We scraped reviews of different Disneyland resorts across Google Maps and social media
* We used topic modelling to classify the reviews into different topics
* We then used sentiment analysis on each topic, calculating how satisfied users were with each of the generated topics
* We then grouped topics, so that we had similar topics across parks, which we then could compare based on NPS scores
* We found that users were the most happy with the Epcot and Animal Kingdom resorts, while Magic Kingdom and Hollywood Studios were lacking behind
* We identified that Magic Kingdom lacked in 'unique experiences' while Hollywood Studios just had far fewer 'Positives experiences'

**Methodology overview**:
![Methodology process graph](imgs/nlp_process_graph.png)

**NPS scores calculated based on sentiment analysis across topics for Disney's resorts**:
![Joint topic and sentiment modelling](imgs/nlp_resort_ratings.png)