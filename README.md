# DisasterTweets

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organizations and news agencies).

But, it’s not always clear whether a person’s words are actually announcing a disaster. Take this example:

<img width="296" alt="Disaster Tweets" src="https://user-images.githubusercontent.com/72161591/236884701-f8ba7d17-fd67-4a4d-8f80-150539e2a5fb.png">

The author explicitly uses the word “ABLAZE” but means it metaphorically. This is clear to a human right away, especially with the visual aid. But it’s less clear to a machine.

In this project, I built a machine learning model that predicts which Tweets are about real disasters and which one’s aren’t. I utilized a dataset of 10,000 tweets that were hand classified.
