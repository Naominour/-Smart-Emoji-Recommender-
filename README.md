# Smart Emoji Recommender - Automatically Add Relevant Emojis to Your text

Welcome to the Emojify project! This project demonstrates how to use word vector representations to build an Emojifier that makes text messages more expressive by automatically adding relevant emojis.

<div align="center">
<img src="\Emoji.jpg" style="width:450px;"> <br>Designed by Freepik
</div>

![Deep Learning](https://img.shields.io/badge/Skill-Deep%20Learning-yellow)
![Sentiment classification](https://img.shields.io/badge/Skill-Sentiment%20classification-brightblue)
![LSTM](https://img.shields.io/badge/Skill-LSTM-blueviolet)
![Natural Language Processing](https://img.shields.io/badge/Skill-Natural%20Language%20Processing-green)
![TensorFlow](https://img.shields.io/badge/Skill-TensorFlow-orange)
![Keras](https://img.shields.io/badge/Skill-Keras-yellow)
![GloVe algorithm](https://img.shields.io/badge/Skill-GloVe%20algorithm-brightblue)
![Python Programming](https://img.shields.io/badge/Skill-Python%20Programming-orange)

## Project Architecture

Emojifier-V1: Baseline model using word embeddings.
Emojifier-V2: Advanced model incorporating LSTM for better performance.

## Frameworks and Libraries
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.16.1-orange.svg?style=flat&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-3.3.3-red.svg?style=flat&logo=keras)
![NumPy](https://img.shields.io/badge/NumPy-1.26.4-blue.svg?style=flat&logo=numpy)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.6.2-green.svg?style=flat&logo=matplotlib)

## Key Features
- Automatically adds relevant emojis to sentences.
- Utilizes word vectors for flexible emoji lookups.
- Capable of generalizing and associating words with emojis even if not explicitly trained on them.

## Implementation Explanation
The project begins with a baseline model (Emojifier-V1) that uses pre-trained word vectors to map sentences to appropriate emojis. The advanced model (Emojifier-V2) incorporates an LSTM to enhance the performance by capturing the sequence of words more effectively.

## Results

The character-level language model successfully generates text that mimics the style of the training data. The generated text is coherent and stylistically consistent with the works of Shakespeare and the list of dinosaur names, demonstrating the effectiveness of the model in learning and replicating character-level patterns.