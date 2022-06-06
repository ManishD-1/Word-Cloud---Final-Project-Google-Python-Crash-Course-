# Word-Cloud---Final-Project-Google-Python-Crash-Course-
## Project goal 
Create a dictionary with words and word frequencies that can be passed to the generate_from_frequencies function of the WordCloud class.

## What is "word cloud"
A word cloud is an image that's made up of different sized words. Usually the sizes of the words are determined by how many times each word appears in a specific text. To create the image itself, we're going to use an external Python module called creatively Word cloud.
we're going to prepare a dictionary and use that as a parameter for the word cloud module

## How I did it
For this project, I created a "word cloud" from a text by writing a script. This script needs to process the text, remove punctuation, ignore case and words that do not contain all alphabets, count the frequencies, and ignore uninteresting or irrelevant words. A dictionary is the output of the calculate_frequencies function. The wordcloud module will then generate the image from your dictionary.

## Prerequisite
we have to install some pachages for our word cloud script and uploader widget.
!pip install wordcloud
!pip install fileupload
!pip install ipywidgets
!jupyter nbextension install --py --user fileupload
!jupyter nbextension enable --py fileupload
