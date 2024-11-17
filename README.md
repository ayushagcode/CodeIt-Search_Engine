# CodeIt - DSA Problem Search Engine 🔍

CodeIt is a search engine that indexes over 3,000 coding problems from platforms like LeetCode, InterviewBit, and TechDelight. It uses advanced information retrieval algorithms (BM25 and TF-IDF) to provide highly relevant search results for Data Structures and Algorithms problems.

## 🌟 Features

- **Advanced Search Algorithm**: Implements BM25 ranking function with TF-IDF for accurate results
- **Smart Query Processing**:
  - Automatic spell correction
  - Stopword removal
  - Lemmatization for better word matching
  - Number-word conversion (supports both numeric and word forms)
  - Camelcase splitting
- **Rich Problem Sources**:
  - LeetCode problems
  - InterviewBit problems
  - TechDelight problems
- **Real-time Search**: Fast and responsive search interface
- **Title Similarity Matching**: Enhanced relevance using string similarity algorithms
- **Problem Preview**: Quick preview of problem descriptions in search results

## 🚀 Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS, GSAP for animations
- **Search Algorithms**: BM25, TF-IDF
- **Natural Language Processing**:
  - `natural` for spell checking
  - `wink-lemmatizer` for word lemmatization
  - `stopword` for stopword removal
- **UI**: Custom CSS with responsive design
- **Animations**: Typed.js for typing effects

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/CodeIt-Search_Engine.git
cd CodeIt-Search_Engine
```

2. Install dependencies:
```bash
npm install
```

3. Start the server:
```bash
node app.js
```

4. Visit `http://localhost:3000` in your browser

## 💻 Usage

1. Enter your DSA problem or concept in the search bar
2. Get instant results with problem titles and descriptions
3. Click on any result to view the full problem
4. Access original problem links on their respective platforms

## 🔧 Project Structure

```
.
├── app.js              # Main application file
├── public/             # Static assets
├── views/              # EJS templates
│   ├── index.ejs      # Search interface
│   └── question.ejs   # Problem display page
├── idf.js             # Inverse Document Frequency data
├── TF.js              # Term Frequency data
├── keywords.js        # Processed keywords
└── Problems/          # Problem dataset
```

## ⚙️ How It Works

1. **Query Processing**:
   - Removes stopwords and punctuation
   - Converts numbers to words and vice versa
   - Performs spell checking and lemmatization

2. **Search Algorithm**:
   - Uses BM25 ranking function
   - Incorporates TF-IDF scores
   - Considers title similarity
   - Prioritizes LeetCode and InterviewBit problems

3. **Result Ranking**:
   - Combines multiple relevance signals
   - Returns top 10 most relevant problems
   - Provides problem previews

## 👨‍💻 Developer

Made with ❤️ by Ayush Agarwal
- LinkedIn: [Ayush Agarwal](https://www.linkedin.com/in/ayush-agarwal-8a6a60226/)
- Email: ayushag032@gmail.com
