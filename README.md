🎭 Sentiment Analysis App

A Python-based NLP tool that analyzes text and classifies emotions using a 600+ word emotion dictionary. Outputs an interactive bar chart showing emotional frequency distribution.

Show Image


🔍 How It Works

The analyzer processes text through a 6-step pipeline:


Load & Normalize — Reads input text and converts to lowercase
Clean Punctuation — Strips punctuation to isolate pure words
Tokenize — Splits text into individual words
Filter Stop Words — Removes common words (the, and, is) that carry no emotional weight
Map Emotions — Matches words against the emotion dictionary (emotions.txt)
Visualize — Generates a bar chart showing emotion frequency distribution



🧠 Emotion Categories

EmotionExample WordsHappyjoyful, cheerful, delighted, ecstaticSaddepressed, melancholy, sorrowful, heartbrokenAngryfurious, enraged, bitter, frustratedFearfulterrified, anxious, panicked, alarmed

The emotions.txt dictionary also includes modern slang and emoji mappings for social media text analysis.


🚀 Getting Started

Prerequisites

bashpip install matplotlib

Run the Analyzer

bashpython main_sentiment.py

Input

Add your text to read.txt — the analyzer will process whatever is in this file.

Output

A bar chart (Graph.png) showing which emotions appear most frequently in your text.


📁 Project Structure

sentiment-analysis-app/
│
├── main_sentiment.py   # Core analysis script
├── emotions.txt        # 600+ word-to-emotion mappings dictionary
├── read.txt            # Input text file
└── Graph.png           # Sample output chart


💡 Real-World Applications


Customer Feedback Analysis — Understand emotional tone in product reviews
Social Media Monitoring — Track brand sentiment across platforms
Content Analysis — Measure emotional impact of articles or blog posts
Research — Convert qualitative text data into quantifiable sentiment metrics



🛠️ Tech Stack


Language: Python
Libraries: Matplotlib, Collections (Counter)
Techniques: NLP, Tokenization, Stop Word Filtering, Emotion Mapping



👤 Author

Najam Ul Hasan
BSCS Student — Government College University Faisalabad
GitHub | Email
