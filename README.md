**Movie Recommendation System** built using Python. It demonstrates practical application of **content-based filtering** to recommend similar movies based on user preferences. The project covers key steps including data preprocessing, feature extraction using NLP, cosine similarity, and user interaction via terminal input.

---

## 📁 Dataset

The dataset used for this project includes basic metadata of popular movies with the following features:

- `title`: Movie name  
- `genres`: List of movie genres (e.g., Action, Comedy)  
- `overview`: Short description or plot of the movie  
- `keywords`, `cast`, `crew`: Optional features used for enhanced content filtering  

> Dataset format: CSV (e.g., `movies.csv`) with ~5,000 movie entries.

---

## ✅ Prerequisites

- Python 3.8 or higher  
- Required libraries listed in `requirements.txt`:
  - pandas
  - numpy
  - scikit-learn
  - nltk
  - ast
  - (Optional) streamlit or Flask for web deployment

---

## ⚙️ Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Harishkumar177/movie-recommantation.git
   cd movie-recommantation
(Optional) Create a virtual environment

bash
Copy
Edit
python -m venv venv
# Activate:
source venv/bin/activate       # macOS/Linux
venv\Scripts\activate          # Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
🚀 Usage
Run the main script from the terminal:

bash
Copy
Edit
python main.py
The script will:

Load and preprocess movie metadata

Extract key features using TF-IDF or CountVectorizer

Compute similarity matrix using cosine similarity

Take a movie title as input

Output top 5–10 recommended similar movies

📌 Features
📚 Content-Based Filtering using genres, keywords, and overview

🧠 Text Vectorization via TF-IDF or Bag-of-Words

📈 Cosine Similarity for distance-based recommendations

🖼️ Clean, interpretable output showing related titles

🗃️ Efficient for small to medium datasets (~5k movies)

📊 Sample Output
text
Copy
Edit
Enter a movie name: Avatar  
Top 5 recommendations:
1. Guardians of the Galaxy  
2. John Carter  
3. The Avengers  
4. Star Trek  
5. The Fifth Element  
📦 Files
main.py – Core logic for the recommender system

movies.csv – Input dataset (movie metadata)

requirements.txt – Required Python packages

similarity.pkl – (Optional) Saved similarity matrix for faster reloading

🔍 Skills Demonstrated
Natural Language Processing (NLP) for feature extraction

Cosine similarity-based recommendation modeling

Data cleaning and transformation with Pandas

Model deployment readiness (CLI or Web)

🚀 Future Improvements
Add user ratings and implement collaborative filtering

Deploy using Streamlit or Flask as a web app

Integrate TMDB API for real-time movie info and posters

Improve feature engineering with embeddings or neural nets

📜 License
This project is open-source and available under the MIT License.

python
Copy
Edit

Let me know if:
- You're using **collaborative filtering**, **deep learning**, or **Streamlit** (I'll modify accordingly).
- You want to turn this into a **web portfolio project**.
- You want the **Overleaf LaTeX version** of this project description too (for resumes).
