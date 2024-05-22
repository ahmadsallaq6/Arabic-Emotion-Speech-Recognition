**Arabic Speech Emotion Recognition**

This project focuses on classifying emotions in Arabic speech using a parallel Convolutional Neural Network (CNN) with Long Short-Term Memory (LSTM) and attention mechanisms. The model is trained on the Basic Arabic Vocal Emotions Dataset (BAVED) and achieves a high accuracy of 96.91% in distinguishing between low, neutral, and high emotions.

**Key Features**

Parallel Architecture: Combines the strengths of CNNs for feature extraction and LSTMs for sequence modeling to capture both spatial and temporal patterns in speech.
Attention Mechanism: Employs a multi-head self-attention mechanism to focus on relevant parts of the speech signal, improving the model's ability to discern subtle emotional cues.
Data Augmentation: Utilizes Additive White Gaussian Noise (AWGN) to enhance the dataset and improve the model's robustness to noise variations.
Optimized Learning: Employs the Adam optimizer and a ReduceLROnPlateau learning rate scheduler to achieve efficient and stable training.


**Dataset**

The Basic Arabic Vocal Emotions Dataset (BAVED) consists of 1,935 records from 61 speakers, with recordings of seven Arabic words at three emotion levels (low, neutral, high).

**Model Architecture**

**The model architecture comprises:**

-Convolutional Blocks: Four convolutional blocks with increasing filter sizes (16, 32, 64, 64) for feature extraction.

-LSTM Block: A bidirectional LSTM layer with 128 hidden units for sequence modeling.

-Attention Mechanism: A multi-head self-attention mechanism to weigh the importance of different time steps.

-Output Layer: A linear layer with softmax activation for classification into three emotion classes.


**Results**

The model achieves an accuracy of 96.91% on the test set, demonstrating its effectiveness in recognizing emotions in Arabic speech.


**Future Work**

Future work will focus on:

-Exploring advanced architectures like Kolmogorov-Arnold networks.

-Expanding the dataset to include a wider range of emotions.

-Investigating real-time emotion recognition capabilities.

-Adapting the model for gender recognition.


**Acknowledgments**
We would like to thank Dr. Tmam Alsarhan for her invaluable guidance and support throughout this project.

**References**
Please refer to the references section in the research paper for a complete list of citations.
