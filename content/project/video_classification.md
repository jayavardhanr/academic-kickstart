+++
title = "Video Classification using NLP"
date = 2017-11-25

summary = "Classify Video’s based on the actions performed in the video using Image Captining"

+++

Utilized existing state of the art Image Captioning models to classify video's into different categories based on the actions performed in them.

  * First, we create split the video into multiple frames and create Frame-description pairs using NeuralTalk model for different frames in the video.
  * We train a machine learning models on this Frame-description pairs to classify video into different categories.
  * Model achived accuries in the range of 36%. 
 
**Error Analysis:** 

  1. Model fails to detect actions like a person sitting down or standing up because the image captioning fails to capture these subtle differences, when it handles one frame at a time. 
  2. Also, the model learns wrong signals like "When it sees a chair, it always always predicts sitting".
