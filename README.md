# Movie-Recommendation-Project


## Overview
This project is a **Movie Recommendation System** built using **Machine Learning**. It suggests movies based on user preferences, viewing history, and similarity between movies. The system utilizes content-based filtering techniques with **Natural Language Processing (NLP)**.

## Features
- **Content-Based Filtering**: Uses **TF-IDF Vectorization** and **Cosine Similarity** to recommend movies based on text similarity.
- **Collaborative Filtering (Future Scope)**: Can be integrated for better personalization.
- **Interactive Web Interface**: Built using Flask/Streamlit for easy accessibility.
- **Data Preprocessing & Feature Engineering**: Uses CountVectorizer and NLP techniques to process movie metadata.

## Tech Stack
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, nltk, flask, streamlit
- **Dataset**: TMDB 5000 Movies dataset
- **Deployment**: Flask/Streamlit for web app, Docker for containerization



## Usage
- Enter a movie name to get similar movie recommendations.
- Uses **CountVectorizer** and **Cosine Similarity** to generate recommendations.



## Dataset
- **TMDB 5000 Movies Dataset**:
  - Movie details: title, genre, cast, crew, overview, keywords.
  - Used **CountVectorizer** to process textual data.

## Model Training
- **Text-Based Similarity**:
  - Uses **CountVectorizer** to convert text features into numerical vectors.
  - Computes **Cosine Similarity** between movie descriptions to find similar movies.


## Future Improvements
- Improve recommendation accuracy with **deep learning models**.
- Implement **Collaborative Filtering** for user-based recommendations.
- Integrate **real-time feedback and adaptive learning**.
- Deploy on cloud platforms like **AWS/GCP**.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.


## Acknowledgments
- Inspired by **Netflix’s recommendation algorithm**.
- Dataset from **TMDB 5000 Movies Dataset**.

---
**Author**: Niviti Sharma
**GitHub**: Niviti2604(https://github.com/niviti2604)  
**Email**: niviti_s@me.iitr.ac.in

