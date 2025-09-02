### Generative AI -



#### Definition:

Generative AI is a type of artificial intelligence that can create new content (like text, images, code, or music) that resembles the data it was trained on. Instead of just analyzing or classifying existing data, it learns the patterns and structures within that data and uses that understanding to generate novel and original outputs.



#### Application:

It can be used in diverse fields such as

* Photo
* Video
* Text
* Development and optimisation
* Personalization
* Education and research
* Data augmentation and synthesis



#### Technology:





#### Traditional AI vs Generative AI:

* Traditional AI focuses on analysing existing data, recognising patterns, and making predictions, classifications, or decisions within predefined boundaries.
* Generative AI focuses on creating new, original content or outputs that resemble the data it was trained on. It learns the underlying patterns and structures within data to generate novel examples.



#### Comparison of AI with -

##### Machine Learning:

A broader field that encompasses algorithms that learn from data, which may or may not involve generative tasks



##### Deep Learning:

A subset of ML that uses a neural network with many layers. Generative AI often employs deep learning models to produce high-quality output.



##### Natural Language Processing:

A field focused on the interaction between computers and human language, where Generative AI can create human-like text responses.



#### Real-life use case of Generative AI:

1. Content Creation
2. Gaming
3. Healthcare



#### Gen AI Model:

1. GPT
2. DALL-E
3. Style GAN



#### Challenges with Gen AI:

1. Bias and Fairness
2. Misinformation
3. Intellectual Property



### Auto Encoders:

Autoencoders are neural networks that aim to learn a compressed, lower-dimensional representation of the input data. They consist of an encoder and a decoder. The encoder maps the input data into a latent space, and the decoder reconstructs the input from this latent representation.



#### Variational Autoencoders (VAEs):

VAEs extend autoencoders by encoding the input data into a probability distribution in the latent space.



#### Latent Space:

It is a lower-dimensional representation of the input data learnt by the autoencoder.


Autoencoder

Input Text (TF-IDF)

Encoder Dense Layer-Vector

Decoder Vector Dense Layer

Reconstructed TF-IDF



Variational Autoencoder

Input Text (TF-IDF)

Encoder \[μ=:ε-\[ μ (mean), o(ar)]]

Reparameterization Trick 2ημοσιε(ε→N(0,1))

Decoder (Vector - Dense Layer)

Sample new z from N (0,1) → Generate New Words

Top Terms != Original Text

