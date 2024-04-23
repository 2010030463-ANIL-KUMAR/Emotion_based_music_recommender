# Emotion_based_music_recommender

 Facial emotion recognition is a challenging task within computer vision, garnering sig
nificant attention from researchers striving to improve both accuracy and processing
 efficiency. Numerous techniques have been proposed, ranging from standalone ap
proaches to ensemble-based methods, all aimed at refining emotion classification. How
ever, this particular study is dedicated to elevating accuracy and processing efficiency
 through the utilization of a single standalone neural network, adept at correctly cate
gorizing human emotions based on facial expressions. Transfer learning serves as a
 cornerstone, with EfficientNetB3 serving as the chosen base model. Leveraging trans
fer learning enables the model to inherit knowledge gained from pre-training on a large
 dataset, subsequently fine-tuning its parameters to suit the specific task of facial emo
tion recognition. The FER2013 dataset serves as the primary data source, comprising
 28,709 training images and 7,178 testing images. One notable challenge encountered
 during the project stems from the inherent class imbalance within the training data. To
 address this issue, oversampling techniques are employed, aiming to mitigate the dis
parities between different emotion classes. Such imbalances typically lead to subpar
 model performance, underscoring the importance of implementing strategies to rectify
 them.Upon thorough experimentation and refinement, the proposed model achieves no
table results, boasting an accuracy of 93.30
