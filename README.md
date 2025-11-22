# Assignment 2

## Corpus
This project uses a small corpus of 12 IMDb movie reviews. The reviews cover three films – The Chef (2014), The Devil Wears Prada (2006), Trainspotting (1996) and Wicked (2025) – with three reviews per movie. All reviews are written in English by non-professional users and were copied from the public IMDb website.

## Target audience
The target audience for this corpus includes students, researchers, and instructors interested in practicing natural language processing on real-world, user-generated texts. Because the corpus consists of IMDb movie reviews, it is also useful for those studying film reception, online opinion-sharing, sentiment analysis,or media discourse.

_Note: Possible research questions that could be explored using this corpus are further stated in the Jupyter Notebook._

## Text selection criteria.
For this project, I selected a small set of movie reviews directly from the IMDb website. For each film in the corpus, I chose three user-written reviews, ensuring that the texts were written in English and varied in length and style. The goal was to create a compact but comparable sample across movies while keeping the corpus manageable for annotation and analysis. No additional filtering criteria (such as rating, reviewer profile, or posting date) were applied; the reviews were simply taken from the publicly available IMDb review section for each title.
## Data collection process.
The data was retrieved from the official IMDb website. The reviews were randomly selected for each movie and simply copy and pasted into a ```.txt``` file.
## Cleaning and/or preprocessing steps if you’ve done any.
No cleaning or preprocessing has been performed on the data.
## Annotations that you’ve added and tools that you used for that.
The following annotations have been added to the corpus:
- Tokens
- Lemmas
- POS
- Proper_Nouns
- Named_Entities
- Ne_Words
## Format of the files in the corpus 
-  ``` .txt``` files containing the movie reviews 
-  ```.csv``` files with corpus data and annotations

The table below contains a more detailed description of the ```annotated_data.csv ``` file:

| Column Name  | Description | Data Type |
| ------------- | ------------- | ------------- |
| Filename  | name of the ```.txt``` file | text |
| TITLE  | title of each movie  | text |
| GENRE | genre(s) of each movie  | text |
| DIRECTOR  | name of the director of each movie | text |
| YEAR  | year of release  | number |
| Text  | the text of each movie review | text |
| Doc | contains each review after being processed by spaCy’s NLP pipeline | text |
| Tokens | lists the individual words and punctuation marks spaCy extracted from each review | text |
| Lemmas | the base or dictionary form of each toke | text |
| POS | includes the part-of-speech tag for each token (e.g., noun, verb, adjective) | text |
| Proper_Nouns | lists all tokens in each review that spaCy tagged with the PROPN part-of-speech tag | text |
| Named_Entities | he entities identified by spaCy’s NER | text |
| NE_Words | the actual text strings of the named entities detected by spaCy | text |

The table below contains a more detailed description of the ```metadata.csv ``` file:

| Column Name  | Description | Data Type |
| ------------- | ------------- | ------------- |
| Filename  | name of the ```.txt``` file | text |
| TITLE  | title of each movie  | text |
| GENRE | genre(s) of each movie  | text |
| DIRECTOR  | name of the director of each movie | text |
| YEAR  | year of release  | number |


## Quality checks
No formal quality checks were applied to the corpus. Since the reviews were taken directly from IMDb without modification, the dataset reflects the natural variation, spelling choices, and writing styles of the original users.
