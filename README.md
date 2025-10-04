# Reddit Comment Graph Clustering

This project applies **Graph Theory** and **Machine Learning** to uncover meaningful relationships between Reddit comments across multiple subreddits. Using text-based clustering and graph visualization, it highlights community structures and thematic groupings within large-scale social media data.

---

## Project Overview

The goal of this project is to analyze Reddit discussions and identify patterns in comment similarity using **unsupervised learning**. Each comment is transformed into a vector representation using **TF-IDF**, clustered using **K-Means**, and connected in a **graph network** where edges represent high semantic similarity.

This combination of **Natural Language Processing (NLP)** and **Graph Analytics** enables deeper insight into how conversations evolve across topics and communities.

---

## Key Features

- Processes over **1 million Reddit comments** across **40 subreddits**  
- Cleans and vectorizes text data using **TF-IDF**  
- Performs **K-Means clustering** to group similar comments  
- Builds **graph representations** using **cosine similarity**  
- Visualizes networks and clusters with **NetworkX** and **Matplotlib**  
- Demonstrates the power of **unsupervised NLP and graph modeling**

---

## Methodology

1. **Data Collection**  
   - Dataset: [1 Million Reddit Comments from 40 Subreddits (Kaggle)](https://www.kaggle.com/datasets/smagnan/1-million-reddit-comments-from-40-subreddits)  
   - Imported using the `kagglehub` API.

2. **Data Preprocessing**  
   - Removed noise, punctuation, and stopwords  
   - Tokenized and normalized text data

3. **Feature Extraction**  
   - Used **TF-IDF Vectorizer** to transform text into numerical vectors  
   - Computed **cosine similarity** between comments

4. **Clustering**  
   - Applied **K-Means** to detect topic clusters  
   - Optimized the number of clusters through experimentation

5. **Graph Construction**  
   - Built a **NetworkX graph** where nodes represent comments and edges indicate strong similarity  
   - Explored connectivity and relationships within and across clusters

6. **Visualization**  
   - Used **Matplotlib** and **NetworkX** layouts to visualize cluster graphs and topic interconnections

---

## Technologies Used

- **Python 3**
- **Pandas**, **NumPy**
- **NLTK** for text preprocessing  
- **Scikit-learn** for TF-IDF and K-Means  
- **NetworkX** for graph creation  
- **Matplotlib** for visualization  

---

## Results

- Successfully grouped Reddit comments into distinct thematic clusters.  
- Visual graphs show tightly connected comment communities based on semantic similarity.  
- Demonstrated the effectiveness of combining **vector-space NLP** with **graph analysis** for large-scale text data exploration.

---

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Emanay-Arshad/Reddit-Comment-Graph-Clustering.git
   cd Reddit-Comment-Graph-Clustering
