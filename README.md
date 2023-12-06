# News-Text-Summarisation
The goal of this project is to implement text summarisation with Sequence to Sequence model using LSTM based Encoder Decoder with the help of Attention mechanism. We also performed the same task on a pretrained T5 transformer model to compare the results. The project is implemented in two parts. One is training the T5 transformer and evaluating its performance and in the second part we trained our Seq-to-seq model in a different notebook because the modell architecture is a bit complex to consider doing both experiments in a single colab file as it exceeds the GPU memory allocation for both models combined. 

# Dataset
We are using the CNN-DailyMail News Text Summarization data available at https://www.kaggle.com/datasets/gowrishankarp/newspaper-text-summarization-cnn-dailymail/data.
It contains Training, Validation and Test data in .csv files with each file containing three columns. For each instance, there is a string for the article, a string for the highlights, and a string for the id.
data-fields
id: a string containing the heximal formated SHA1 hash of the url where the story was retrieved from
article: a string containing the body of the news article
highlights: a string containing the highlight of the article as written by the article author.
