# Building a Spam Filter with Naive Bayes Algorithm
![img](spam.png)

<center>Source:https://readus247.com/fix-yahoo-mail-spam-filter-not-working</center>

This repo contains two notebooks (named SMS-Spam-Filter-from-Scratch.ipynb and SMS-Spam-Filter-with-sklearn.ipynb) where we build a spam filter for SMS messages from scratch and also using scikit-learn. A spam message is defined as any kind of unwanted, unsolicited digital communication that gets sent out in bulk. Often spam is sent via email, but it can also be distributed via text (SMS) messages, phone calls, or social media.

# Why we hate Spams -- Types of spam
Spammers use many kinds of communication to send their unwanted messages in bulk. These communications can be marketing strategies which peddle unsolicited goods. Other types of spam messages can spread malware, trick you into divulging personal information, or scare you into thinking you need to pay to get out of trouble. To find out more how malicious spams can be see [here](https://www.malwarebytes.com/spam).

# The Spam Filter

The purpose of this project (though is done without deployment) is to learn how a spam filter is created to help a user stop getting spam messages altogether via a piece of software.

This software (or algorithm) we're talking about has one purpose, which is to learn how classify messages as spam or non-spam. In order to do this the computer:

1. Learns how humans classify messages.
2. Uses that human knowledge to estimate probabilities for new messages — probabilities for spam and non-spam.
3. Classifies a new message based on these probability values — if the probability for spam is greater, then it classifies the message as spam. Otherwise, it classifies it as non-spam (if the two probability values are equal, then we may need a human to classify the message).

So our task on these projects is to "teach" the computer how to classify messages. To do that, we'll use the multinomial Naive Bayes algorithm along with a dataset of 5,572 SMS messages that are already classified by humans.

The dataset was put together by Tiago A. Almeida and José María Gómez Hidalgo, and it can be downloaded from the [The UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection). You can also download the dataset directly from this link. The data collection process is described in more details on [this page](http://www.dt.fee.unicamp.br/~tiago/smsspamcollection/#composition), where you can also find some of the authors' papers.

### Disclaimer
Please note that this is not a full end-to-end machine learning project. Where we test a bunch of other algorithms to pick the best one and then deploy the model. The purpose here is to learn the basics of applied probability in practice and the workflow of a model. In the near future I'll upload a full end-to-end project.


































































