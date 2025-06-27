# Star Wars Sentiment Analysis

This program implements Python NLTK (Natural Language Toolkit) to conduct sentiment analysis for the character "Darth Vader" in the following three "Star Wars" movies: "A New Hope", "The Empire Strikes Back" and "Return of the Jedi" using Python NLTK (Natural Language Toolkit). 

The goal of the project is to compare how the character's emotions evolve over the three movies. By quantifying the levels of eight core emotions across these movies to facilitate comparison, the project concludes that "The Empire Strikes Back" portrays the most emotionally complex version of Darth Vader among the three movies.

### Workflow

1. First, the program extracts Darth Vader's lines from the scripts.
2. Then, identifies the words in those that have emotion values in The NRC (National Research Council Canada) Emotion Lexicon [https://nrc-publications.canada.ca/eng/view/ft/?id=0b6a5b58-a656-49d3-ab3e-252050a7a88c].
3. Creates eight different dictionaries for the eight emotions in the NRC lexicon: anger, anticipation, disgust, fear, joy, sadness, surprise and trust.
4. Calculates the scores of each of the eight emotions in each of the films, and an overall sum of all emotions for each of them as well representing total emotional intensity.


### Files in this repository

There are five text files in this repository and a Jupyter notebook file.

1. The four input text files are sw4.txt, sw5.txt, sw6.txt (which have the scripts of  "A New Hope", "The Empire Strikes Back" and "Return of the Jedi" respectively) and nrc_emotions.txt (the NRC Emotion Lexicon file). 
2. The Jupyter notebook sta_wars_code.ipynb contains the code for this program. 
3. The output text file outputs.txt contains the result produced by the notebook. 


### How to run this program

1. Downloading the text files in Google Drive.
2. Linking Google Drive to Colab.
3. Adjusting the names of the text files on Colab.
4. Running the Notebook on Colab.


### Future updates

Currently working on:
1. sentiment analysis by character 
2. visualizing the outputs for better comparative analysis

