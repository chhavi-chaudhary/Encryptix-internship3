# Book Recommendation System
A Book Recommendation System built using Python, Pandas, and Scikit-learn.
This project suggests books to users based on their preferences using Collaborative Filtering techniques.

## Features

- Personalized Recommendations – suggests books similar to user interests.

- User-Based Collaborative Filtering – finds similar readers and recommends books they liked.

- Cosine Similarity – measures closeness between user profiles.

- Efficient User-Item Rating Matrix for recommendation calculations.

- Python Implementation using Pandas & Scikit-learn.

## Tech Stack
- Language: Python 
- Libraries: Pandas, NumPy, Scikit-learn
-Dataset: Book Ratings dataset (User–Book interactions)

## Project Structure
```
📦 Book-Recommendation-System
 ┣ 📜 README.md
 ┣ 📜 requirements.txt
 ┣ 📜 main.py
 ┣ 📜 recommendation.py
 ┣ 📂 dataset
 ┃ ┗ 📜 books.csv
 ┃ ┗ 📜 ratings.csv
 ┗ 📂 notebooks
   ┗ 📜 analysis.ipynb
```

## Installation & Setup

- Clone the repository
- git clone https://github.com/chhavi-chaudhary/Encryptix-internship3.git
cd Book-Recommendation-System

- Install dependencies

- pip install -r requirements.txt


## Run the project

python main.py

## How It Works

- Load dataset (Books + Ratings).

- Create a User-Item Rating Matrix.

- Apply Cosine Similarity to find similar users.

- Recommend top-rated books liked by similar users.

## Example Output
Recommended books for User 101:
1. Harry Potter and the Philosopher’s Stone
2. The Hobbit
3. The Da Vinci Code
4. Pride and Prejudice
5. To Kill a Mockingbird

## Future Improvements

-  Add Content-Based Filtering (recommend by genre/author).

-  Hybrid Recommendation (User + Content based).

-  Web App Integration (Flask/Django).

-  Improved visualization dashboards.

## Contributing

- Contributions are welcome!
- Feel free to fork this repo, create a branch, and submit a Pull Request.

