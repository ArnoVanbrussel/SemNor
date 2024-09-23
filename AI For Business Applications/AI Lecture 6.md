# 1 Natural Language Processing (NLP)
- NLU (understanding) + NLG (generation)
- **Goal**: to have computers understand the human language
- Ambiguity
	- Interest
		- Bank loan interest
		- Concerns
		- Ownership
	- "He saw her with the telescope"
		- he saw her by using a telescope
		- he saw her while she was using the telescope
## 1.1 NLP Pipeline
- Segmentation
	- Text into sentences
- Tokenizing
- Stop words
	- Remove stopwords
- Stemming
	- Running => run
- Lemmatization
- Feature extraction
- Modeling
## 1.2 NLTK
- Text preprocessing
- Sentiment analysis
- Text classification
## 1.3 Vectorization
- Converting data into numerical vectors or arrays
- Numerical input needed (instead of text data)
### 1.3.1 Bag of Words
- BoW
- Steps
	- Tokenization
		- Break text into words
	- Vocabulary
		- Create list of unique words
	- Vectorization
		- Convert each document into a vector of word counts
### 1.3.2 TF-IDF
- Enhanced BoW model by considering importance of words in the context of the entire corpus
- Term Frequency (TF)
	- how often term in document
- Inverse Document Frequency (IDF)
	- measures how important a term is across all documents
- TF-IDF Score
# 2 Sentiment Analysis
- Opinion mining
- Determine the sentiment or emotional tone
- Positive, negative or neutral
1. Text input
2. Text processing
3. Sentiment classification
	- Positive
	- Negative
	- Neutral
4. Algorithm selection
5. Output
## 2.1 Applications
- Product reviews
- Social media monitoring
- ...
