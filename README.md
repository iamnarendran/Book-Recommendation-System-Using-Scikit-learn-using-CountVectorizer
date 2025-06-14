# 📚 Genre-Based Book Recommendation System

This is a Streamlit web application that provides book recommendations based on genres using machine learning techniques. The app utilizes **CountVectorizer** from Scikit-learn to convert genres into numerical vectors and uses **cosine similarity** to recommend books that are similar to the selected book.

---

## 🚀 Features

- **Book Recommendations**: Select a book and get the top 5 similar books based on genre similarity.
- **Cosine Similarity**: Finds books with the closest genre match using cosine similarity.
- **Integrated Dataset**: Comes with a pre-loaded CSV file (`books.csv`) containing book titles and genres.

---

## 🛠️ How it Works

1. User selects a book title from the dropdown list.
2. The app computes similarity between the selected book and all other books using genre vectors.
3. The top 5 books with the highest similarity scores are recommended.

---

## 📂 Dataset

The application uses a CSV file named `books.csv` with the following columns:

| Title                                | Genre   |
|--------------------------------------|---------|
| Harry Potter and the Sorcerer's Stone | Fantasy |
| The Hobbit                           | Fantasy |
| The Da Vinci Code                    | Mystery |
| A Brief History of Time              | Science |

---

## 🧰 Technologies Used

- **Streamlit**: Web interface framework.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: Used for `CountVectorizer` and cosine similarity.

---

## 💾 Installation

Follow these steps to run the app locally:

```bash
# Clone the repository
git clone https://github.com/iamnarendran/Book-Recommendation-System-Using-Scikit-learn-using-CountVectorizer.git
cd book-recommendation-app

# Install the required packages
pip install -r requirements.txt

# Run the application
streamlit run app.py
