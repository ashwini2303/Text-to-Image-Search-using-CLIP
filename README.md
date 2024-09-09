# Text-to-Image-Search-using-CLIP
## Project Overview

This project presents a text-to-image search system that retrieves relevant images based on textual queries using CLIP (Contrastive Language-Image Pre-Training) and Sentence Transformers. The system leverages these models to encode both text and images into a shared embedding space, allowing for efficient and accurate image retrieval. This can be applied in areas such as e-commerce, digital marketing, and image recommendation systems.

## Installation 
Step 1: Open the Text_to_Image_Search.ipnyb file in Google Colab / Jupyter Notebook.  <br/>
Step 2: Run all the cells in order to install all the required dependencies. 

## Model Architecture
The system uses the CLIP model from OpenAI, which consists of a text encoder (based on a transformer) and an image encoder (based on a convolutional neural network). The two encoders map text and images into the same high-dimensional space, allowing similarity scores between images and text to be calculated. <br/>
Text Encoder: Sentence Transformer (based on BERT/RoBERTa) is used to encode the query text. <br/>
Image Encoder: CLIP's vision transformer encodes images. <br/>
The system maximizes the cosine similarity between relevant text-image pairs and minimizes it for non-matching pairs.


## Dataset
The project utilizes the Unsplash dataset, which consists of high-quality images along with associated textual descriptions. The model is trained and evaluated on this large-scale image dataset. <br/>
Number of images: 25,000 <br/>
Dataset source: Unsplash

## Future Work

While the current approach delivers high accuracy, future improvements could include: <br/>

Using Generative Adversarial Networks (GANs) for better retrieval quality.<br/>
Incorporating additional modalities such as audio or video for more complex search queries.<br/>
Improving scalability for large-scale image datasets and real-time retrieval.<br/>

## Contributing
Contributions are welcome! If you'd like to contribute to this project, feel free to fork the repository and submit a pull request, or open an issue if you find any bugs.<br/>

Fork the repository <br/>
Create a new branch<br/>
Make your changes and submit a pull request<br/>
