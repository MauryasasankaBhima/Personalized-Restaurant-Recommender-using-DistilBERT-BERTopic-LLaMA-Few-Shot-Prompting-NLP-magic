# Personalized-Restaurant-Recommender-using-DistilBERT-BERTopic-LLaMA-Few-Shot-Prompting-NLP-magic
**GastronomeAI** is an intelligent, AI-powered restaurant recommender system that combines modern Natural Language Processing techniques with deep learning, topic modeling, and semantic similarity to generate personalized restaurant suggestions based on user preferences, reviews, and categories.
This project integrates both zero-shot and few-shot learning approaches with traditional recommender strategies to capture user intent in a dynamic, flexible, and human-like manner.

---

##Objective

To build a hybrid recommendation engine capable of:
- Understanding user input (e.g., “I want cozy Italian places with great wine”)
- Extracting context, cuisine, ambiance, and preference clues
- Generating intelligent recommendations using semantic search, sentiment analysis, and topic modeling

---

##  Technologies Used

| Module                     | Tools / Libraries                            |
|---------------------------|----------------------------------------------|
| NLP & Preprocessing       | SpaCy, NLTK, TextBlob                        |
| Vectorization & Similarity| TF-IDF, Cosine Similarity                    |
| Topic Modeling            | BERTopic (based on BERT + clustering)       |
| Semantic Models           | DistilBERT, Sentence Transformers, LLaMA     |
| Classification            | Zero-shot (HuggingFace), Few-shot Prompting |
| Recommender System        | Custom logic + NLP + embeddings              |
| Visualization             | Matplotlib, Plotly                          |

---

##  Project Structure

- `GS_AI_BERTTopicModelling.ipynb`: Topic modeling from user reviews using BERTopic
- `GS_AI_Category_Extraction.ipynb`: Extracting fine-grained user intents and cuisine types using zero-shot classification
- `GS_AI_Recommender_System.ipynb`: Core recommendation logic using user inputs + review similarity + semantic filtering

---

##  Techniques Involved

-  **Topic Modeling** (BERTopic)
- **Semantic Embedding** (DistilBERT, Sentence Transformers)
- **Cosine Similarity Search** between user profile and restaurant metadata
- **Zero-Shot Classification** for category inference
-  **Few-Shot Prompting** (e.g., using LLaMA or instruction-style prompting)
-  **TF-IDF Ranking** for keyword-based baseline comparison
-  **Sentiment Filtering** to exclude poorly reviewed restaurants

---

##  Key Features

- Personalized restaurant recommendations
- Ability to adapt to vague or expressive user queries
- Hybrid recommendation logic: filters + embeddings + topic coherence
- Modular and scalable for integration with apps or APIs

---

##  Example Use Case

> User Query: “I’m in the mood for a romantic sushi place near the beach.”

GastronomeAI breaks this down into:
- Cuisine: Sushi
- Ambiance: Romantic
- Location intent: Beach proximity
- Sentiment/experience preference

Then it:
- Filters out irrelevant options
- Uses semantic embeddings and sentiment scores
- Recommends top-matching restaurants sorted by coherence and positivity
