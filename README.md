![](https://img.shields.io/github/followers/pravinknr?label=Follow%40pravinknr&style=social)
![](https://img.shields.io/github/forks/pravinknr/
Natural-Language-Processing-NLP-Python?label=Fork&style=social)
![](https://img.shields.io/github/stars/pravinknr/
Natural-Language-Processing-NLP-Python?style=social)
![](https://img.shields.io/github/watchers/pravinknr/
Natural-Language-Processing-NLP-Python?style=social)
![](https://img.shields.io/github/issues/pravinknr/DataScience_R_Codes)
![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://pravinknr.github.io/
Natural-Language-Processing-NLP-Python/)]
![](https://img.shields.io/github/repo-size/pravinknr/
Natural-Language-Processing-NLP-Python)
![](https://img.shields.io/github/languages/code-size/pravinknr/
Natural-Language-Processing-NLP-Python)


# Natural-Language-Processing-NLP-Python
Basics of NLP in Python Using spaCy Library

## What is NLP?

* Capability of a Computer to Understand Human Language Or SPeech thereby Interpeting it and doing the required Task.

* NLP is a Subset of AI - Works on Enabling Computer Systems to Effectively Understand and Process Natural Human Language by developing Computer Programs to Analyze and Process Massive amounts of Natural Language Data.

* Mainly concerned with Gaining Useful Knowledge and Insights from the Raw Textual Data.

### Components of NLP :

1. NLU : Natural Language Understanding

2. NLG : Natural Language Generation

### What is NLU?

* Focuses on Understanding anf Observing the Meaning of given User Input. Also Involves in Classifying it into Proper **_Intents_** and **_Entity_**.

+ **_Intents_** : Refers to the Verbs of the User Activities. Mainly used when we want to capture a user Request, or Perform any Action.

+ **_Entity_** : Refers to Noun or the Content for which that Action(or **_Intent_**) is Performed.

* Example : Play(**_Intent_**) Kishore Kumar Songs(**_Entity_**).

#### 3 Tasks or NLU:

1. Reading Aspect of NLP.
2. Mapping the given Input into Variable and Usable Representation.
3. Analysis of Different Language aspects based on Grammar.

#### Areas of Application of NLU:

1. Sentiment Analysis : Describing Positive and Negative Indexes.
2. Topic Classification : Tweet, Message or an E-Mail Type Detection.
3. Entity Detection : Detecting Nouns in a Text such as Locations, Games or Names, Etc.

#### Examples of Real World Devices using NLU:

1. Alexa

2. Siri

3. Google Assistant


### What is NLG?

* Described as Translator that Converts the Structured Computer Data into the Corresponding Natural language Representation.

* Involves the Task of Content or Text Planning, Lexicalization, Sentence Planning, Aggregation, Text Realization.

* Involves in Establishing Natural Language Outputs from Non-Linguistic Inputs. Deals with Process of Generating Language or Writing Aspect of NLP.


#### Areas where NLG Comes to Play:

1. Generating Analytical Reports in Natural Language like English, Spanish, Etc.

2. Enabling Chatbots to interact in a more Efficient way.

3. Automated Contents Writing such as Aticles, Stories, Etc.

### Applications of NLP:

* Automated Question - Answering
* ChatBots
* Sentiment Analysis
* Spam Message Detection
* Machine Translation (e.g Google Translator)
* Spelling and Grammar Correction
* Speech-To-Text Conversion & Speech Recognition
* Information Retrieval & Web Searching

### Some Libraries for NLP

- **_spaCy_**

- **_scikit-learn_**

- **_Natural language Toolkit(NLTK)_**

- **_Textblob_**

- **_Quepy_**

### Token Attributes:

#### What is a Token?
* Token is Defined as each and Every Word along with Punctuations and Symbols present in a Sentence.

* Example : *"Hello! Welcome to my Github Profile."* Here Every Word and Punctuation is Defined as Tokens.

**Token Attributes**

| Tag | Description|
| --- | --- |
| .text | The Original Word Text |
| .lemma_ | The Base form of the Word |
| .pos_ | the Simple Part-Of-Speech |
| .shape_ | The Word Shape - Capitalizations, Punctuation, Digits. |
| .dep_ | The Syntactic Dependency - i.e The Relation Between the Tokens. |
| .is_alpha | Is the Token an Alpha Character? |
| .is_stop | Is the Token a Part of Stop list? Is it the Most Common Words of the Language? |
| .tag_ | Detailed Part-Of-Speech |



***

## To Perform NLP We require the Following :

1. **_Anaconda Navigator_** - Download **Anaconda Navigator** Individual Edition. [Click Here](https://www.anaconda.com/products/individual) to Download. Choose **_Python 3.7_**

2. Install **_spaCy_** : Follow the Below Steps:

* Run **_Anaconda Command Prompt_** as **Administrator**

* Type `conda install -c conda-forge spacy`

or

`pip install -U spacy`

* A list of Packages will be Displayed and Asks our Approval to Proceed Further. Just type `y` and press `Enter`

* Now Download the Specific Model you want, Based on English language

Type the Command `python -m spacy download en`  for Default English Model(`50MB`).

For Large Library Use:

Type the Command `python -m download en_core_web_lg`

Then

Type the Command `python -m spacy link en_core_web_lg en1` to link the Language model with "en1"

* You are Good to Go once you see the `You can now load the model via spacy.load('en1')` in the Anaconda Command Prompt.

Now we can Load the Large Library Model using "en1". 

*** 

### Basics of NLP using Python

* Library Used : **spaCy**

| Name | File |
| --- | --- |
| NLP Basic | [NLP_spaCy_Basics.ipynb](https://github.com/pravinknr/Natural-Language-Processing-NLP-Python/blob/master/NLP_spaCy_Basics.ipynb) |

** Will be Updating it Further. Keep Checking! **