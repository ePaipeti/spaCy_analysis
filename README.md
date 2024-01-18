# spaCy_analysis

## Corpus Analysis with spaCy: Nick Cave's lyrics from the albums Let love in & Murder Ballads
 The corpus contains 20 songs of Nick Cave & The Bad Seeds in txt format.
  In accordance with copyright regulations, I deleted the corpus of the GitHub repository. 

 ## Description of corpus:
 20 files in .txt format

 ## Target Audience & Intended Use

  The target audience for the corpus would likely include researchers, linguists, musicologists 
  interested in the analysis of song lyrics. Scholars exploring the intersection of literature, 
  music or cultural studies may find value in studing thematic, poetic or linguistic elements from the lyrics 
  of the album. The intended use could be many forms of text analysis, thematic analysis and
  linguistic examination of the lyrics. The structure of this analysis is in the form of tutorial for people intrested
  in learning Text Annotation and analysis with soaCy.

  ## Data Collection 
  The data collection process was simply copy pasting every lyrics in textfiles.
  I also created a metadata csv with the following information:

  |Header   |Description     | Datatype|
  | ------- | -------------- | ------- |
  | ID      | filename       | string  |
  | Title   | song title     | string  |
  | Album   | album title    | string  |
  | Year    | year published | integer |
  | Artist  | name of artist | string  |

  ## Annotations and Tools

  I used and documented how to tokenize, lemmatize and annotate Parts-of-speech and taggs about Name Entities.
  For this purpose I used spacy, and pandas library in Python.
  
  The newly created, annoteted csv file contains the following information:
  
  1. Filename: the name of the file without the txt extension
  2. Title: name of the title
  3. Text: the original text
  4. Tokens: tokenized text
  5. Lemmas: lematized text
  6. POS: part of speech in text
  7. Named_Entities: named entities in text
  8. NER_Words: specific named entities
      
  
  

  
