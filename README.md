# TweetGrab - WordCloud

### This quick project is about data wrangling and not necessarily about visualization.
I was interested in the process of capturing some snapshot data from a site, cleaning/extracting it from the dross and gettng it into a useful form.

Of the things I learned, there are several major takeaways:

1. While data availability is ubiquitous, the majority of it is not in an ingestible format.
2. For data cleaning/wrangling/preperation to be efficient and successful, an end vision of the output has to be envisioned but also flexible because not every visualization communicates what the data is saying.
3. Data wrangling, i.e., finding, capturing, cleaning and preperation for use is the lions share in Data Science. Adaptable skills, efficiency and the ability to find relevant data are going to be strengths.
4. It's very possilbe that Data Wrangling could be a career in and of itself without ever really becoming a full "Data Scientist"...but that could get a little old.

### Grab a users twitter feed via user url.
Run the script, enter the twitter name without the '@' symbol and the script will scrape a few tweets from the user's feed and convert them to a wordcloud.
<br/><br/>
Thanks to [Andreas Mueller](http://amueller.github.io/) for word cloud generator in Python.
https://github.com/amueller/word_cloud


![WordCloud](https://github.com/Hamberfim/TweetGrab_WordCloud/blob/master/DalaiLamaJupt.png)
-DalaiLama's Twitter Posts - Used my TweetGrab in Jupyter-Notebook with WordCloud- 10/19/18


### Comparison
![WordCloud](https://github.com/Hamberfim/TweetGrab_WordCloud/blob/master/DalaiLama.png)
-Used my TweetGrab in python script with WordCloud 10/19/18

![Plot](https://github.com/Hamberfim/TweetGrab_WordCloud/blob/master/DalaiLamaBar.png)
-Used my TweetGrab with MatPlotlib 10/19/18
<br/>
## Licensing
The wordcloud library is MIT licenced by [Andreas Mueller](http://amueller.github.io/), but contains DroidSansMono.ttf, a true type font by Google, that is apache licensed. Ownership/Licensing reside with the respective owners and by extention my included "TweetGrab" code is MIT licenced.
<br/><br/><br/>
WARNING: 
Use TweetGrab at your own risk! I assume NO responsibility if you get blacklisted/blocked. Excessive and agressive use of this script is NOT endorced. It is strickly for educational purposes.
