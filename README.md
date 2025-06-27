# Star Wars Sentiment Analysis

This program does a sentiment analysis for the character Darth Vader in the "Star Wars" movies "A New Hope", "The Empire Strikes Back" and "Return of the Jedi" using Python NLTK (Natural Language Toolkit). 

 First, it identifies the words used by Darth Vader that have emotion values in The NRC (National Research Council Canada) Emotion Lexicon [https://nrc-publications.canada.ca/eng/view/ft/?id=0b6a5b58-a656-49d3-ab3e-252050a7a88c]. Then, it calculates the total value of each of the eight emotions in each of the films, which can later be used for answering sentiment analysis questions such as:

 1. In which of these films was Darth Vader the angriest? (Comparing anger values)
 2. Is Darth Vader more important of a character in "A New Hope" than in "The Empire Strikes Back"? (The movie that has the overall higher score is possibly where Darth Vader is more important.)


### Inputs and outputs

As inputs, we enter the movie scripts and the NRC Emotion Lexicon file. The output is the value of each of the eight 
emotions in each of the films and the total sum of emotions in each of them.

### Files in this repository

There are five text files in this repository and a Jupyter notebook file.
The four input text files are star_wars_4.txt, star_wars_5.txt, star_wars_6.txt (which have the scripts of  "A New Hope", "The Empire Strikes Back" and "Return of the Jedi" respectively) and nrc_emotion_values.txt (the NRC Emotion Lexicon file). 
The Jupyter notebook sta_wars_code.ipynb contains the code for this program. 
The remaining text file is outputs.txt which contains the result produced by the notebook. 


### How to run this program

1. Downloading the text files in Google Drive.
2. Linking Google Drive to Colab.
3. Adjusting the names of the text files on Colab.
4. Running the Notebook on Colab.


### Future updates

Currently working on:
1. sentiment analysis by character 
2. visualizing the outputs for better comparative analysis

