Plagiarism Detection using Jaccard and Cosine Similarity
This project demonstrates a simple plagiarism detection approach using Jaccard Similarity and Cosine Similarity on sentence pairs from a labeled dataset.

📁 Dataset
We are using the MIT Plagiarism Detection Dataset available on Kaggle.

🔗 Download the dataset directly from this link:
https://www.kaggle.com/datasets/ruvelpereira/mit-plagairism-detection-dataset

🧠 Methods Used
🔹 Jaccard Similarity
Measures how many unique words overlap between two sentences.

Formula:
Jaccard(A, B) = |A ∩ B| / |A ∪ B|

🔹 Cosine Similarity
Measures the angle between TF-IDF vector representations of two sentences.
This method often captures contextual similarity better than Jaccard.

📊 Output
The notebook calculates:

Jaccard and Cosine similarity scores for each sentence pair

Predicted labels based on chosen thresholds

Accuracy for both similarity-based predictions

▶️ How to Run
Open the notebook in Google Colab

Download the dataset from Kaggle

Upload the data.txt file when prompted

Run each cell in the notebook sequentially

