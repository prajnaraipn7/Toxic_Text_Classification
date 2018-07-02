# Toxic_Text_Classification

This git is pull from https://www.kaggle.com/jagangupta/stop-the-s-toxic-comments-eda which was done by Jagan for the competition Toxic text classification.

The kernel is great for getting in-depth info about the text data. I have worked on understanding line to line and overall approach of the author. The git contains Hashtags of the meaning of every line of code written by jagan. By working on this I got a grasp on understanding the approach and tuning data for problem solving.

## The Data
Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.

The Conversation AI team, a research initiative founded by Jigsaw and Google (both a part of Alphabet) are working on tools to help improve online conversation. One area of focus is the study of negative online behaviors, like toxic comments (i.e. comments that are rude, disrespectful or otherwise likely to make someone leave a discussion). So far they’ve built a range of publicly available models served through the Perspective API, including toxicity. But the current models still make errors, and they don’t allow users to select which types of toxicity they’re interested in finding (e.g. some platforms may be fine with profanity, but not with other types of toxic content).

In this competition, you’re challenged to build a multi-headed model that’s capable of detecting different types of of toxicity like threats, obscenity, insults, and identity-based hate better than Perspective’s current models. You’ll be using a dataset of comments from Wikipedia’s talk page edits. Improvements to the current model will hopefully help online discussion become more productive and respectful.


The data consists large number of Wikipedia comments which have been labeled by human raters for toxic behavior. The types of toxicity are:

    • toxic    
    • severe_toxic
    • obscene
    • threat
    • insult
    • identity_hate
    
This git approaches by visualizing the data, creating features, applying different models mainly: Logistic regression, Naive Bayes, LDA.

The dataset can be found: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data
