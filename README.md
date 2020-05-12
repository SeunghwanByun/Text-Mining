# Text-Mining

Read a paper related to text mining and carry out a project to realize the content in the [paper](https://www.dbpia.co.kr/pdf/pdfView.do?nodeId=NODE06525096&mark=0&useDate=&bookmarkCnt=1&ipRange=N&language=ko_KR)

* Find how many sentences and how many words are in the 58 inaugural offices.
* Analyze how many words have been removed.
* Analyze how the average length of sentences in each period changes.
* Extract objective subject words that represent the characteristics of the document and create a document-word cross table that records the number of occurrences of the subject words in the speech.

##### step 1. Set of original documents
##### step 2. Extract all words
##### step 3. Remove stopwords
##### step 4. Remove symbol
##### step 5. Remove meaningless words
##### step 6. Keyword list

###### Method
```
- Eliminate stopwords using the stopword dictionary of nltk corpus.
- '-', ')', '?' Remove meaningless symbols such as '0', '13', '14th' and '15th'.
- How many words are finally extracted?
- Extract stems to avoid overlapping words with the same meaning.
- The stem extraction method utilizes the Snowball stemmer method to extract the final number of stems.
- TF-IDF is performed to extract key words from the extracted stems.
```
