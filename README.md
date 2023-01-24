# Erdos_2022_05_Audio_Project
Erdos Institute's May Data Science Boot Camp, 2022


### Data source: 

*common-voice2 - Kaggle*
<br>
*https://www.kaggle.com/datasets/danielgraham1997/commonvoice2*




# OVERVIEW - LENA Foundation inspired audio project

## Count spoken words in audio clips

Given an audio clip, we want to count the number of spoken words it contains. 
There are parameters used to split audio clips at "silences" which we optimize.
We use machine learning models to find the features which effect the accuracy of our counter (for example, if our counter more accurate for females than males, we will account for that).

Later, we want to make a model which can associate word counts with people 
(e.g. 100 words by child, 300 words by mother, 500 words by teacher in a specific day). 


>### Most helpful link:

>*Split audio files using silence detection - StackOverflow*
<br>
>*https://stackoverflow.com/questions/45526996/split-audio-files-using-silence-detection*


>>### Other links to consider:

>>*Audio signal split at word level boundary - StackOverflow*
<br>
*https://stackoverflow.com/questions/64153590/audio-signal-split-at-word-level-boundary*

>>*Split speech audio file on words in python - StackOverflow*
<br>
*https://stackoverflow.com/questions/36458214/split-speech-audio-file-on-words-in-python*

>>*Using pyDub to chop up a long audio file - StackOverflow*
<br>
*https://stackoverflow.com/questions/23730796/using-pydub-to-chop-up-a-long-audio-file*
