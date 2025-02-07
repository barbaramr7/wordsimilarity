# wordsimilarity

To go further in my studies about chatbot development, I've started studying more of Natural Language Processing! This project demonstrates various methods to analyze the similarity between strings using Natural Language Processing (NLP) techniques. The project is implemented in a Jupyter Notebook and includes several similarity metrics such as Levenshtein distance, cosine similarity, Jaccard similarity, and Euclidean distance.

Also, a huge shoutout to my two favorite animes - One Piece and Fullmetal Alchemist! It was a joy using info from them to develop this project.

🔍 NLP String Similarity Analysis
📖 Introduction
In this project, we explore different methods to measure the similarity between strings. The goal is to understand how different NLP techniques can be applied to compare texts and determine their similarity. The project includes examples of text segmentation, stopword removal, and various similarity metrics.

⚙️ Installation
To run this project locally, you need to have Python installed along with the necessary libraries. You can install the required libraries using the following command:

bash
Copy
Edit
pip install nltk pandas numpy scikit-learn
Additionally, you need to download the NLTK data:

python
Copy
Edit
import nltk
nltk.download('punkt')
nltk.download('stopwords')

🚀 Usage
1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
2️⃣ Navigate to the project directory:

bash
Copy
Edit
cd your-repo-name
3️⃣ Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook NLP_processes-Copy1.ipynb
4️⃣ Run the cells in the notebook to see the results of the different similarity metrics.

📊 Methods
The following methods are implemented in this project:

🔤 Levenshtein Distance: Measures the minimum number of single-character edits (insertions, deletions, or substitutions) required to change one string into another.
📐 Cosine Similarity: Measures the cosine of the angle between two non-zero vectors in an inner product space.
🖇️ Jaccard Similarity: Measures the similarity between finite sample sets and is defined as the size of the intersection divided by the size of the union of the sample sets.
📏 Euclidean Distance: Measures the "ordinary" straight-line distance between two points in Euclidean space.

📈 Results
The notebook includes examples of how each method is applied to compare texts. The results are displayed in the notebook, showing the similarity scores between different pairs of texts.

🤝 Contributing
Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or submit a pull request.

📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.
