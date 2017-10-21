#Spam Classifier

first we need to have our traning data that contains messages and their correct classification.

this spam classifier is based on spliting data into a list of words and count how many times every word occure in a message and associate this to the right
classification so the next time it will be giving a message it will use this information to decide whether this message is spam or not.


We use :


countVectorizer to calculate the number of occurance of each word in a message

MultinomialNB to associate the number of occurance of a given word to the classification of the message.