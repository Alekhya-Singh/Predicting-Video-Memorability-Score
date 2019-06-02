# MediaEval_Prediction
Video Memorability Prediction using Caption feature

This project predict the short-term and long-term video memorability using captions at 2018 Media Predicting Media Memorability Task. In this approach, the captions generated from the video clips are used to predict memorability score reflecting whether videos are memorable or not after 24 or 72 hours by applying Natural Language Processing (NLP) techniques and a Keras Deep Learning model. Prediction can be made on various features extracted from the videos but this approach has low computational cost compared to all other video-based features.

In today’s fast-moving world, data from different platforms of media such as advertisement, information extraction, and social media are growing exponentially. Thus, the ability to recognize the content of the media perform an important role in these systems to help the media industry to optimize their processing. In order to understand the content of media,  concepts like emotion, interestingness, visual saliency and aesthetics, social popularity, and memorability can be used. 
MediaEval 2018 Benchmark Initiative for Multimedia Evaluation performs various task in which Predicting Media Memorability task is one of the most important tasks. 
The main goal of this project is to explain the task that performs the prediction of the memorability score for a video. Prediction of the memorability score represents the probability of a video to be remembered after long term and short term. An extensive set of data containing 8000 short soundless videos along with its various feature accompanied by memorability annotations are provided to perform the task. This dataset is divided into two parts where 6000 data are used for the development of the model and 2000 videos were used to test the model. The dataset comes with both short-term and long-term annotations as a Ground Truth.

### Approach

The work performed here has developed a computational model for predicting video memorability scores by applying the Bag of Words approach to captions: Count Vectorizer and TF-IDF.
The captions are present in the form of text. Captions are preprocessed using Natural Language Processing techniques such as removing Stopwords. Majority of sentence connecting words like ‘and’, ‘the’, ’a’ etc. are present in the captions are called Stopwords.
Tokenization splits sentences into individual word. These individual words are then used as the input for another type of tasks, such as parsing. Captions are then tokenized and every individual word is reduced to lower case for simplicity.
The conversion of NLP text into number format is called vectorization. The two ways used here for text to vector conversions are Count Vectorizer and TF-IDF. The performance of the model is compared after using both the approaches.

