<p align="center">
<a href="https://github.com/PhinanceScientist"><img src = "https://i.ibb.co/NLfc0SV/Deveaner.png" width = 100> </a>
</p>
<h1 align=center><font size = 5>México's presidential speech visual analysis with python  </font></h1>


## Introduction
In this project I will be using some web scraping tools for python to have a simple sight of the most common words used on two different speechs from the President of México found on the government official page for transcriptions.

After retrieving our data using <b>BeautifulSoup</b>, we will use the package <b>word_cloud</b> to convert our obteined text into a wordcloud image in order to focus on the words used on it.<br>  Also, I will be representing the top 10 most commont words on each one using <b>Matplotlib</b>.  The idea is to compare the difference between them within a year apart. 

Finally, I will analyse the results in a very superficial way as the main goal for this project is to demostrate the utility from the used libraries for python.

Feel free to comment or <a href="https://www.linkedin.com/in/novelo-luis/">contact me</a> for further improvement.

Please do notice that if you want to render this Jupyter notebook you can use this link https://nbviewer.jupyter.org/

## DATA
The data used for this project was scraped from the official government speechs transcription site https://lopezobrador.org.mx/ and then cleaned due to its sintaxis as the text use interview dialogue structure.<br>
The transcription of the speechs from the dates "4th of april 2020" and "4th of april 2019" were used.<br>
The technologies used here were IBM Watson Studio for the environment of the Jupyter notebooks in python and GitHub for repository.

## What are the Word Clouds ?

A word cloud is a collection, or cluster, of words depicted in different sizes. The bigger and bolder the word appears, the more often it’s mentioned within a given text and the more important it is.
For this task, we will be using the python library called 'word_cloud' developed by <b>Andreas Mueller</b>. <a hreef="https://github.com/amueller/word_cloud/">Here</a> you can find the repository and learn more about it.
***
## Results 

<b>4th april 2020, top 10 words:</b>
<li> programa</li>
<li> construcción</li>
<li> bienestar</li>
<li> México</li>
<li> créditos</li>
<li> pobres</li>
<li> inversión</li>
<li> gobierno</li>
<li> salud</li>
<li> crisis</li>

<b>4th april 2019, top 10 words:</b>
<li> vamos</li>
<li> si</li>
<li> presidente</li>
<li> reforma</li>
<li> conocer</li>
<li> Estados</li>
<li> tener</li>
<li> México</li>
<li> gobierno</li>
<li> ahora</li>

## Conclusion

We can observe that in the 2020's speech there are words used by the government to talk about its support programs and important sectors such as construction. It also mentions investment and issues of special relevance such as the health crisis, credits and jobs for poor people.
'
In the image from 2019's speech we can notice different words. Here the words like 'reform','well'and 'good' stand out. It <b>seems</b> that the words used during 2019 contained a more positive meaning compared to 2020.

In conclusion, we can use these tools to get an idea of what the President's speech represents and how it changed from year to year in a way that it is  easy to visually identify the important points the government wants to highlight.

Although we did not analyze deeply the content of the transcripts in this work, we can identify the points that the President of Mexico wants to emphasize with the words used during his speech and the message he wishes to deliver.
***

## References

https://github.com/amueller/word_cloud/ <br>
https://lopezobrador.org.mx/ <br>
https://lopezobrador.org.mx/2020/04/05/discurso-del-presidente-andres-manuel-lopez-obrador-en-su-informe-al-pueblo-de-mexico/ <br>
https://lopezobrador.org.mx/2019/04/04/version-estenografica-de-la-conferencia-de-prensa-matutina-del-presidente-andres-manuel-lopez-obrador-60/ <br>
https://prowritingaid.com/art/425/What-the-Heck-is-a-Word-Cloud-and-Why-Would-I-Use-One.aspx <br>
https://matplotlib.org/ <br>

This notebook was made by <a href="https://www.linkedin.com/in/novelo-luis/">Luis Novelo</a>
