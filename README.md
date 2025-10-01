
# 📚 Book Recommender System  

A simple Book Recommendation System built with **Python, Pandas, and Scikit-learn**, deployed via **Flask**.  
It suggests books to users based on popularity and collaborative filtering.  

---

## 🚀 Features
- **Popular Books**: Recommend books with highest average ratings.  
- **Collaborative Filtering**: Suggest books similar to the one a user likes.  
- **Preprocessed Data**: Uses `.pkl` files (`popular.pkl`, `pt.pkl`, `similarity_scores.pkl`) for faster predictions.  
- **Flask Web App**: Interactive UI for recommendations.  

---

## 🗂️ Project Structure

├── templates/ # HTML templates for Flask

├── app.py # Flask app entry point

├── book_recommender_system.ipynb # Jupyter notebook for building the system

├── book_recommender_system-checkpoint.ipynb # Checkpoint file

├── Ratings[1].csv # Ratings dataset

├── Users[1].csv # Users dataset

├── popular.pkl # Precomputed popular books DataFrame

├── pt.pkl # Pivot table DataFrame

├── similarity_scores.pkl # Precomputed similarity scores

├── README.md # Project documentation


---

## 📊 How It Works

## Data Preprocessing
- Load ratings and user datasets.
- Clean and filter data.
- Build pivot table (pt.pkl).
## Popular Books
- Group by title and compute average ratings.
- Store in popular.pkl.
## Collaborative Filtering
- Compute similarity matrix (similarity_scores.pkl).
- Recommend top-N similar books
## Deployment
- Flask serves recommendations on a web page.

## 🛠️ Tech Stack

Python
Pandas, NumPy, Scikit-learn (Data processing & ML)
Flask (Web framework)
Jupyter Notebook (Model building & testing)
