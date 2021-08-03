# CommonLit Readability Prize

Competition URL: https://www.kaggle.com/c/commonlitreadabilityprize/overview

**code credits** \
model training: https://www.kaggle.com/maunish/clrp-pytorch-roberta-finetune \
pooling method: https://www.kaggle.com/rhtsingh/utilizing-transformer-representations-efficiently \
feature build: https://www.kaggle.com/maximkazantsev/commonlit-readability-univ-sent-encoder-xgb \
model saving for future use: https://www.kaggle.com/questions-and-answers/92749 \
other: https://www.kaggle.com/vineethakkinapalli/clrp-roberta-base-representation-techniques

In this notebook I try to combine features extracted from excerpt into the model training process. There are 3 basic model I used, RoBertA with last 4 layers representations, RoBertA with a attention head, and Attention Pooling method on RoBertA.
The submission answer is the average value of all 15 models (each model has five submodels).
