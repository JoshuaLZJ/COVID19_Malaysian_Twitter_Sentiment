# COVID19_Malaysian_Twitter_Sentiment
A mini project to track public sentiment changes in Malaysia throughout the duration of the COVID19 pandemic

![alt text]([https://ibb.co/yFSP41y])

Hey guys! I've been doing some web scraping on Malay tweets regarding COVID19. I decided to do some sentiment analysis using a NLP model (model is publicly available at https://github.com/huseinzol05/malaya). What the model does is taking in a chunk of text and outputs a sentiment score between 0 to 1 (1 being the text has 100% positive sentiment and 0 being the text is 100% negative). The model is not 100% accurate but it is considered to be comparable to other state-of-the-art models.

I managed to scrape a maximum of 1000 Malay tweets per day containing the words 'malaysia' and 'covid' posted between 17th March 2020 (our first lockdown) till 17th of September 2021 and conducted sentiment analysis on each tweet. I then averaged the sentiment score for each day and produced the above plot which also has the daily new COVID case numbers for each corresponding day.

I don't really have any specific conclusion to draw from this plot and feel like it might be something interesting for you to look at. One recurrent pattern that I spot is the dips in sentiment scores whenever the COVID case numbers are on the rise, but that pattern is not always consistent.

Some fun things i noticed is that the huge spike in sentiment towards the end of August corresponds to Merdeka (31s August). 30th and 31st Aug also holds the record highest sentiment score of 0.5017 and 0.4710 respectively. Kudos for Malaysians for being more positive and encouraging on our National Day!
