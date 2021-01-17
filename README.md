# HowYaDoing
*Multi* *emotion* sentiment classifier.  
Classify the emotion in a sentence into the following:  
1. sadness
2. joy 
3. love 
4. anger 
5. fear 
6. surprise

## Method
Currently Using pretrained Roberta model from HuggingFaces transformers library,
with classifier replaced with a single nn.Linear layer with 6 output features.

## Training Dataset
Model is fine-tuned using the Emotion Dataset from the 
CARER: Contextualized Affect Representations for Emotion Recognition
paper


### Paper Citation
E. Saravia, H.-C. T. Liu, Y.-H. Huang, J. Wu, and Y.-S. Chen, 
“CARER: Contextualized Affect Representations for Emotion Recognition,” 
Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing, 2018.
