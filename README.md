# Korean Sarcasm Dataset

* [Korean Sarcasm Dataset](#korean-sarcasm-dataset)
  * [What is Korean Sarcasm Dataset](#what-is-korean-sarcasm-dataset)
  * [Data Format](#data-format)
  * [Number of Data](#number-of-data)
  * [Label Acronyms](#label-acronyms)
  
---


## What is Korean Sarcasm Dataset

* Mass of documents consists of one or more sentences from sports article comments, Twitter and NaverMovieReview which are likely to have **sarcastic** or **ironic** contents.


## Data Format
* The dataset is organized in units of documents, and one document consists of one or more sentences.
* 'DOC_ID': Unique ID for document identification.
* 'number_of_sentences': The number of sentences that make up a document.
* 'sentences': A list containing information about the sentences that make up a document. Dictionary, which is an element type of the list, has 'text', 'label', and 'morph_result' as key values.
  * 'text': Raw corpus in units of a sentence
  * 'label': Label for the sentence
  * 'morph_result': Morphological analysis for the sentence


## Number of Data

* Number of documents: 2,689
* Number of sentences: 8,734
* Number of sentences per label

|Label|Number of sentences|
| :-----: | :---------: |
|I|140|
|IR|1,355|
|IS|101|
|IRS|167|
|None|6,971|
|**TOTAL**|**8,734**|


## Label Acronyms
    ※ Irony: Used to express a contrast between what is expected and what actually happens. Also often used to convey a sense of humor or to point out the absurdity of a situation.
    ※ Sarcasm: Used to express criticism or disdain. It involves saying something that is the opposite of what is meant, often with the intention of insulting or mocking someone or something.
* I: Irony (반어)
* IR: Irony + Rhetorical Question (반어 + 수사의문문)
* IS: Irony + Sarcasm (반어 + 비꼼)
* IRS: Irony + Rhetorical Question + Sarcasm (반어 + 수사의문문 + 비꼼)
* None: None
