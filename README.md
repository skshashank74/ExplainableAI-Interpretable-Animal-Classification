# ExplainableAI Interpretable Animal Classification

Deep Learning models have shown great performance in complex classification tasks, but are inherently uninterpretable. We created a convolutional neural network as our classifier and analysed how it generates features for the different classes. We further delve into attention maps of the last few layers of CNN models and analyse various class discriminative visualization methodologies - Grad-CAM, Guided Backpropagation and Guided Grad-CAM for explaining the model.

The goal of the project is to understand the reasoning process behind the predictions made by a convolutional neural network. We perform two experiments to understand the classification done by the black box model. Then a case based reasoning approach will be used to understand which XAI method worked best. In the XAI method, we focus majorly on layer-wise attention maps, Grad-CAM, Guided Backpropogation and Guided Grad-CAM. The two experiments are:

- Classification of different animals. Example: cats and dogs

- Classifying individual animals of the same breed. Example: identifying individual Asian elephants
