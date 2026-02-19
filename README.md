# Book-Recommendation-Engine-using-KNN
basic ML practice using jupyter
📚 Book Recommendation Engine using KNN
My Machine Learning Project - Building a Book Recommender System!
I built this as part of the freeCodeCamp Machine Learning curriculum. This project uses the K-Nearest Neighbors (KNN) algorithm to recommend similar books based on real user ratings from the Book-Crossings dataset!

🎯 What This Project Does
Have you ever finished a great book and wondered, "What should I read next?" This AI solves that problem! Give it any book title, and it instantly recommends 5 similar books that you might enjoy.

Example:

text
Input: "The Hunger Games"
Output: 
→ Catching Fire (95% similar)
→ Mockingjay (92% similar)
→ Divergent (85% similar)
→ The Maze Runner (82% similar)
→ Twilight (75% similar)
🧠 How K-Nearest Neighbors Works (Simple Explanation)
Imagine you're in a library with thousands of readers:

Step 1: We track how every reader rated every book

Step 2: Books that got similar ratings from the same people are probably similar!

Step 3: KNN measures the "distance" between books - closer distance = more similar

Step 4: The algorithm finds the 5 "nearest neighbors" (most similar books)

It's like finding your taste twins - people who like the same books as you will lead you to other books you'll enjoy!

📊 Real-World Dataset Used
Book-Crossings Dataset (1.1 million real ratings!)

90,000+ real users

270,000+ books

Ratings from 1-10

Real-world messy data (just like in industry!)

🛠️ Technologies & Tools
https://img.shields.io/badge/Python-3.8-blue
https://img.shields.io/badge/scikit--learn-KNN-orange
https://img.shields.io/badge/Pandas-Data%2520Analysis-brightgreen
https://img.shields.io/badge/NumPy-Math%2520Operations-red
https://img.shields.io/badge/Jupyter-Notebook-yellow

Python - Core programming language

scikit-learn - K-Nearest Neighbors algorithm implementation

Pandas - Data cleaning and manipulation

NumPy - Mathematical computations

Jupyter/Colab - Interactive development environment

📁 Project Structure
text
book-recommendation-knn/
│
├── book_recommendation.ipynb    # Main notebook with complete code
├── README.md                     # Project documentation
└── requirements.txt              # Python dependencies
🚀 How to Run This Project
Option 1: Google Colab (Easiest - No Setup!)
https://colab.research.google.com/assets/colab-badge.svg

Option 2: Run Locally
bash
# Clone the repository
git clone https://github.com/yourusername/book-recommendation-knn.git
cd book-recommendation-knn

# Install required libraries
pip install pandas numpy scikit-learn matplotlib

# Launch Jupyter Notebook
jupyter notebook book_recommendation.ipynb
💡 Key Machine Learning Concepts I Learned
K-Nearest Neighbors (KNN) : Finding similar items by measuring distance

Data Preprocessing : Cleaning real-world messy data

Feature Engineering : Creating user-item matrices

Distance Metrics : Euclidean vs Cosine distance

Sparse Matrices : Handling data with many zeros efficiently

Model Evaluation : Testing recommendation quality

🎓 My Learning Journey
This project represents 20+ hours of dedicated learning outside my college curriculum:

✅ Understanding unsupervised learning algorithms

✅ Working with real-world, messy datasets

✅ Building practical recommendation systems

✅ freeCodeCamp Machine Learning certification progress

✅ Industry-relevant skills (recommendation systems are used by Netflix, Amazon, Spotify!)

📈 Sample Output
python
get_recommends("The Queen of the Damned")

# Returns:
[
  'The Queen of the Damned (Vampire Chronicles (Paperback))',
  [
    ['Catch 22', 0.79],                    # Most similar
    ['The Witching Hour', 0.74],            # 2nd most similar
    ['Interview with the Vampire', 0.73],    # 3rd most similar
    ['The Tale of the Body Thief', 0.54],    # 4th most similar
    ['The Vampire Lestat', 0.52]             # 5th most similar
  ]
]
🔗 Connect With Me
GitHub: @Anshul39

LinkedIn: Anshul

Portfolio: [your-website.com]

🙏 Acknowledgments
freeCodeCamp - For providing an amazing, free ML curriculum

Book-Crossings Community - For sharing their dataset

scikit-learn Team - For the excellent KNN implementation

My College Professors - For supporting my self-learning journey
