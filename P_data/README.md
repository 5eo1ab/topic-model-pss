### Data Descriptions

#### science.txt
- Initial data from sciencedirect.com(export search)
- Search keyword is "product service" W/5 system
  - it means "product service" and "system" within 5 space in words
- All of documents have been published since 2000.
- And limited to journal documents.
- 3526 documents were searched and there were 799 abstracts in the document.
  - We think that missing information will exist in the parsing process

#### dataset_v1.csv (799 by 7)
- Extract important bibliographic information such as journal, authors, years
  - abstract / doc_info	/ keywords / *year / publication / authors / title*
  - partially extracted manually. 

#### dataset_v2.csv (799 by 7)
- Standardization of notation such as abbreviations
  - abstract\* / doc_info	/ keywords / *year / publication / authors / title*

#### dataset_v3.csv (799 by 8)
- After the text preprocessing process, append lemmatization result
  - abstract / doc_info	/ keywords / *year / publication / authors / title* / **lemma**

#### dataset_v4.csv (799 by 8)
- After lemmatization process, additional remove stopwords
  - abstract / doc_info	/ keywords / *year / publication / authors / title* / __lemma\*__




#### *The description of the other file will be added if it is an opportunity.*



