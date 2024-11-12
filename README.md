Developed a free health-care monitoring system, that takes a Chest X-Ray image & Electronic Stethoscope audio input and predicts the probability of the patient suffering from respiratory illnesses.
Contributed by implementing a novel idea of introducing audio-modal data along with image to improve accuracy and out-perform existing algorithms

Implemented a VGG-16 model along with transfer learning, pre-trained on the ImageNet dataset. 
The multi-modal model made use of Decision Fusion (soft voting), ANN and Image & Audio individual model accuracy scores to perform its diagnosis.

The test set data (both image and audio) was evaluated by multiple practicing doctors who also compared the classification and results of our model and **98%** of the cases were rightly diagnosed by the model. This value is much higher confirming our alternate hypothesis that a multi-modal approach out-performs existing singular modal approaches.
