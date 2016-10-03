# cs5644Assignment2
Assignment 2 for Big Data and ML

##Section One - Question One
    [Github Repo Link](https://github.com/britztopher/cs5644Assignment2.git)  
    [Github Raw Code Link](https://raw.githubusercontent.com/britztopher/cs5644Assignment2/master/assignment2)
  
##Section One - Question Two


##Section 1 - Question Three
A lot was learned, gathered, created, destroyed, and others while completing this assignment.  However, analyzation is all about the numbers, and there are plenty therein.  

###Top Performers
Coming in first place in terms of performance/accuracy is the decision tree with ternary inputs.  This yeilded the best scores in every aspect of testing.  With a 1.0 accuracy in the training set of 80% of the dataset, and a .94252 accuracy in the 20% test set.  In addition, its precision, recall, and f1-score averages are .94 across the board.   Another good indication of a performant classifier is its confusion matrix, and with `[[49  3] [ 2 33]]` means its estimates were near perfect for true postives, false positives, true negatives, and false negatives.

A close second was the "Naive Bayes Classifier" with skipping rows.  This yeilded the same precision, recall, and f1-score averages, however, there was forty less supporting numbers.  To clarify, this means the dataset was nearly cut in half and then 80% was used for training.  Thus, leaving only 20% of a reduced dataset for testing future events.  Having that small of a dataset can lead to inaccurate predictions.

Before taking on this assignment I was clueless on how to use a dataset and `sklearn` to output anything, let alone, what each metric's meaning was.  However, after a ton of hard work and dudiligence I concoured this assignment, and finished it on time with a foundation to build on.  The only thing I can add about the dataset is that there are a lot of congress men/woman who dont have a concrete position on tough topics.  I say this because on skipping rows that had question marks in them dwindled the total dataset from 435 to 232 which made the confusion matrix shrink and scores to be manipulated based on amount of data represented.
 
 ##Section 2 - Question One
Naive Bayes:
come up with a probability up front(prior probabilities) then as data is inputed this probability(posterior) learns new evidence.
can give you probabilities of an event that hasnt happened before?  If the event hasnt happened before a frequentist cannot provide 
have a broader area of applicability 

Would use on datasets that continue to evolve and grow as the probability accuracy will be better on more input that is given, however, when data becomes to big it could cause speed performance to decrease as it will need to add on another instance to already big size before caclulating again.

text samples are a good example of good datasets to use. ie - probability of email is spam.  

Not ideal if you want less setup and quick results use decision tree. Uses more data preperation
