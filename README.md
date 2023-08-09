# BIRDS-IMAGE-CLASSIFICATION
Implementation of a comprehensive image classification pipeline using a pre-trained neural network to classify different species of birds with accurancy 99%. Here's a brief description of the results along with the achieved accuracy percentage:

Data Loading and Preprocessing:
The code loads and preprocesses a dataset containing bird images, dividing it into training, testing, and validation sets.
A visualization of sample bird images from the test set provides a glimpse into the dataset's diversity.

Model Training:
The pre-trained EfficientNetB3 model is utilized as a feature extractor, and new layers are added for classification.
Initial training is performed with data augmentation, enhancing the model's ability to generalize.
The model's training progress is tracked through accuracy and loss curves.

Model Fine-Tuning: 
Certain layers of the pre-trained model are unfrozen for fine-tuning, aimed at refining the model's learned features.
A lower learning rate is used for fine-tuning, facilitating the adjustment of higher-level representations.
The fine-tuning process is visualized with accuracy and loss curves.

Evaluation and Accuracy:
The trained and fine-tuned model is evaluated on the test set.
The accuracy achieved on the test set reflects the model's proficiency in classifying bird species.

Visualizing Misclassifications:
Instances where the model made confident but incorrect predictions are visually displayed, shedding light on areas where further improvement may be necessary.

Overall Result:
The image classification pipeline demonstrates impressive performance in identifying bird species:
Initial training with data augmentation and feature extraction yields significant accuracy.
Fine-tuning refines the model's performance, enhancing its accuracy even further.

Accuracy Percentage: The accuracy achieved on the test set serves as a quantitative measure of success.![The-EfficientNetB0-network-architecture](https://github.com/kundankr4/BIRD-IMAGE-CLASSIFICATION-USING-VISION-TRANSFORMER/assets/126001733/4fb426fa-c120-468f-9e93-721a25be07e0)

The model's final accuracy after fine-tuning is reported in the accuracy curve.
The achieved accuracy percentage showcases the model's capability to accurately classify bird species, underscoring the effectiveness of transfer learning and fine-tuning techniques in complex image recognition tasks.
