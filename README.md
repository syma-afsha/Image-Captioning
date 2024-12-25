### Image-Captioning

Step 1: Dataset: 

Use the Flickr8k dataset [Link](https://www.kaggle.com/datasets/adityajn105/flickr8k)

Implement a PyTorch Dataset class to manage the data

Incorporate image and caption preprocessing, including tokenization and appropriate padding for batch processing

Split it into training, validation and test sets

Step 2: Model:

Create an Encoder-Attention-Decoder architecture

Encoder: create a custom layer or use a pre-trained backbone (e.g., ResNet) for image features extraction, which must be fine-tuned

Attention: Implement an attention mechanism to focus on specific parts of the image (context) during caption generation (text). Use Linear layers or something of your choice

Decoder: Use a sequence based model, LSTM to generate captions based on the encoder's features and the attention context.

Visualize the loss and metric progress across epochs.

Visualize attention weights to demonstrate the learning process. 

Use the BLEU score to measure the quality of generated captions.

Step 3: Existing Model Comparison:

Evaluate both my model and the pre-trained model on the test set and compare their performance visually.
