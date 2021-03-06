# Dementia-Classification

This project won the Fidelity Investments Student Challenge. 

Proposal for research
---
The cognitive decline is often gradual and it is hard to perceive the right moment to have the conversation. This neccesitates to look for markers in behavior that are leading indicators of eventual decline. This way perhaps the investor can be gradually introduced to the idea and gently lead into a contingency plan

The problem doesn’t end at the detection phase. The second part of the problem is in convincing customers to take some planning action. As mentioned earlier, this is delicate and means of overcoming psychological hurdles are complicated. 

For solving this problem, 
* Data was requested from the Alzheimers Society of America and received telephonic interviews of people having Alzhiemers and those without Alzheimers.
* Used fastai library to process the speech.
* Performed data augmentation, created deep learning models to classify the data.
* Achieved 47% accuracy for the current framework.


# Dataset
The dataset is taken from the Dementia Bank: https://dementia.talkbank.org/access/. As this data is confidential, one can access data by contacting them.

# Model
The data is classified using Resnet18.

# Libraries.
The whole project is constructed using Fastai v1 libraries.

# Future work.
We are looking for a deployment model. Once the model is deployed successfully, then the audio can be classified on a real-time base.
