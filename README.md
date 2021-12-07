# Discussion
validation_data(30k rows)  vs comments_to_score vs test data (LB)
pl is 10k


cannot beat my first baseline run's LB score
* more data
* targeted pretraining
8 folds and no leaks
Baseline run with roberta-large: CV: 0.74 | LB: 0.815
Pretrain with previous competition data: CV: 0.77 | LB: 0.7

* heavier regularization
* different loss functions
* different learning rate schedules.

# Past Solutions
* 4 years ago
1st: https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52557
2nd : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52612
3rd (single model): https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52644
3rd : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52762
5th : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52630
12th : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52702
15th : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52563
25th : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52647
27th : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52719
33rd : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52666
34th : https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/discussion/52645

* 2 years ago
1st: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/103280
3rd: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97471
4th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/101927
5th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100718
7th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100611
8th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100961
9th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100530
10th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/101630
11th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100799
14th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100821
15th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97443
16th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/100708
18th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97425
23rd: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97400
26th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97422
27th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97389
33rd: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97464
56th: https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/97484

* More
https://www.kaggle.com/c/jigsaw-toxic-severity-rating/discussion/286333



# Paper List
[Ruddit: Norms of Offensiveness for English Reddit Comments](https://aclanthology.org/2021.acl-long.210/):
dataset that involved tuples of four sentences that were marked with best-worst scoring

Detecting and Classifying Toxic comments
https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1184/reports/6837517.pdf

Exploring Deep Learning in Combating Internet Toxicity
https://web.stanford.edu/class/archive/cs/cs224n/cs224n.1184/reports/6909170.pdf

Toxic Comment Classification Using Neural Networks and Machine Learning
https://iarjset.com/wp-content/uploads/2018/10/IARJSET.2018.597.pdf

Convolutional Neural Networks for Toxic Comment Classification
https://arxiv.org/pdf/1802.09957.pdf

A Machine Learning Approach to Comment Toxicity Classification
https://arxiv.org/ftp/arxiv/papers/1903/1903.06765.pdf

Adversarial Text Generation for Google’s Perspective
https://www.nyit.edu/files/engineering/SOECS_REU2018_PosterPresentation_AdversarialTextGenerationForGooglePerspective.pdf

Content Moderation Across Multiple Platforms with Capsule Networks and Co-Training
http://precog.iiitd.edu.in/Publications_files/Vani_Agarwal_Masters_Thesis.pdf

* 2021
https://www.kaggle.com/c/jigsaw-toxic-severity-rating/discussion/286362
