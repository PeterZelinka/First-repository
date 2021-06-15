# Message Classifier Using Naive Bayes Algorithm
This repository contains code for a SMS classifier that utlitses multinomial Naive Bayes algorithm to mark messages as spam/non-spam. 

## The Dataset
The dataset contains 5,572 SMS messages that were classfied by humans.
The data itself was collected by Tiago A. Almeida and José María Gómez Hidalgo, 
and it can be downloaded from the The UCI Machine Learning Repository [(here)](https://dq-content.s3.amazonaws.com/433/SMSSpamCollection).
Information on the data collection process can be found on this [page](https://www.dt.fee.unicamp.br/~tiago/smsspamcollection/#composition).

The data contains 2 columns:
* `Label` - Label of the message (either 'spam'- spam message or 'ham'- not a spam message).
* `SMS` - The message itself.


## The multinomial Naive Bayes Formula

![Screenshot 2021-06-15 at 08 40 29](https://user-images.githubusercontent.com/85829899/122005009-6871df80-cdb5-11eb-808c-106c162de9b7.png)
