# Spam-Detection

## The Question

For a human, determining whether a message is interesting or just spam appears simple. Even while you read the message, your brain may already be aware that it's junk. How can we build a model that, in some way, mimics the judgments the brain makes when deciding whether a message is spam or something important?

## The Dataset

We are working on the SMS Spam Collection Data Set present in the UCI Machine Learning Repository. The SMS Spam Collection is a collection of messages with the tag "SMS" that have been gathered for SMS Spam study. It includes one collection of 5,574 English SMS messages that have been classified as either spam or ham (legal). The dataset can be found https://archive.ics.uci.edu/dataset/228/sms+spam+collection.

## The Method

Our dataset consists consists of thousands of words and we treat each word as a feature. Since Naive Bayes Algorithm has the ability to handle a large number of features, we use this machine learning algorithm for classificatio
