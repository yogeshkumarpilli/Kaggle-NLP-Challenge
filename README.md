# Kaggle-NLP-Challenge

## Task overview
This edition of the Défi IA pertains to NLP. The task is straightforward: assign the correct job category to a job description. This is thus a multi-class classification task with 28 classes to choose from.

The data has been retrieved from CommonCrawl. The latter has been famously used to train OpenAI's GPT-3 model. The data is therefore representative of what can be found on the English speaking part of the Internet, and thus contains a certain amount of bias. One of the goals of this competition is to design a solution that is both accurate as well as fair, as explained in the Evaluation section.

## Evaluation
The original aspect of this competition is that there will be 3 tracks on which solutions will be ranked. First of all, solutions are ranked according to the Macro F1 metric, which will be used to build the Kaggle leaderboard. The Macro F1 score is simply the arithmetic average of the F1 score for each class.




