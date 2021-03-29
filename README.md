# DataCamp_ProjectCodeAlongs
## DataCamp Project Code Session
**On 9/29/2020 I participated in a live code along session via DataCamp
guided by Hadrien Lacroix.** 


This project used the request, nltk, and BeautifulSoup libraries to 
process some of the text from the novel Moby Dick.

1. Data for the Moby Dick text was requested from gutenbert.org via 
the requests library

2. Text data from the website was parsed via BeautifulSoup to put
it in the proper/readable format

3. The nltk (Natural Language Toolkit) libray was used to tokenize
the text which mean removie spaces and punctiuations and keeping 
only words and making a list of those words

4. This the list of words called word were all made into lowercases
with a for loop

5. nltk is used again create a list of stop words, which are words 
in english that are considered irrelevant to NLP for understanding 
and analysis

6. A for loop  and if-statement are used to removed stop works 
from words list

7. Finally matplotlib.pyplot and seaborn are used to create a
plot which shows which words are uses most frequently throughout
the text
