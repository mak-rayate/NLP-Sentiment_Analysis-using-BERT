# NLP-Sentiment_Analysis-using-BERT

### Background

In the field of computer vision, researchers have repeatedly shown the value of transfer learning — pre-training a neural network model on a known task, for instance ImageNet, and then performing fine-tuning — using the trained neural network as the basis of a new purpose-specific model. In recent years, researchers have been showing that a similar technique can be useful in many natural language tasks.

BERT is a multi-layer bidirectional Transformer encoder. There are two models introduced in the paper.

BERT base – 12 layers (transformer blocks), 12 attention heads, and 110 million parameters.
BERT Large – 24 layers, 16 attention heads and, 340 million parameters.

#### BERT ARCHITECTURE ![source](http://jalammar.github.io/illustrated-bert/)

![image](https://user-images.githubusercontent.com/67750027/130549733-6e47ba8b-2d56-499d-aaf4-ed66471fc88a.png)


#### PROJECT : detection of depression and mental illness in Twitter
we have used BERT layer and developed a sentiment analysis model using TensorFlow 2.0. I have reached to model accurecy 77% on test dataset.model working excellent on raw text data. 

Reason : In BERT, the model is made to learn from words in all positions, meaning the entire sentence.BERT incorporates the mighty Transformer in its architecture, which uses attention mechanism over the input sentence. Further, Google also used Transformers, which made the model even more accurate.

#### NLP Data Preprocessing code for below operation available in .ipynb file
1. Expand contraction
2. Cleaning and removing punctuations
3. Cleaning and removing URL’s
4. cleaning_stopwords
5. Cleaning and removing repeating characters
6. Cleaning and removing Numeric numbers
7. Applying Stemming
8. Applying Lemmatizer

#### Final Output:
![image](https://user-images.githubusercontent.com/67750027/130550596-f4d59e97-c989-4283-bdf5-fdef028374d1.png)

