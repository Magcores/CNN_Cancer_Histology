# CNN_Cancer_Histology
Deep learning classification of breast, lung and colon cancer using histological measures


In this project, we developed and trained four Convolutional Neural Network (CNN) models for the classification of breast, lung, and colon cancer using histological measures. Each model was tailored to specific classification tasks:

Body Part Classification Model (body_part_model.h5):

Purpose: To classify the histological images based on the body part (breast, lung, or colon).
Architecture: A CNN with several convolutional and pooling layers to extract spatial features, followed by fully connected layers to make the final classification.
Breast Cancer Classification Model (breast_model.h5):

Purpose: To differentiate between benign and malignant breast cancer cells.
Architecture: A specialized CNN designed to handle the distinct features of breast tissue images, ensuring high accuracy and robustness in classification.
Colon Cancer Classification Model (colon_model.h5):

Purpose: To classify colon cells as either benign or malignant.
Architecture: A CNN optimized for colon histological images, focusing on distinguishing between healthy and cancerous cells.
Lung Cancer Classification Model (lung_model.h5):

Purpose: To classify lung cells, distinguishing between benign, carcinoma, and adenocarcinoma.
Architecture: A CNN configured to handle the complexities of lung tissue, providing detailed classification of cancer subtypes.
Training and Evaluation
Data Preprocessing: Images were preprocessed through resizing, normalization, and augmentation to enhance model performance and robustness.
Training: Models were trained using labeled datasets with a significant number of images for each type of cancer. The training involved fine-tuning hyperparameters to achieve optimal results.
Evaluation Metrics: Models were evaluated using metrics such as accuracy, precision, recall, and F1-score to ensure high performance and reliability.
Results: The models achieved high accuracy, with the body part classification model reaching 100% accuracy. The breast, colon, and lung cancer models also demonstrated high precision and recall, proving effective for practical diagnostic applications.
These models collectively aim to provide a comprehensive tool for the early detection and classification of various cancer types, leveraging deep learning to enhance the accuracy and efficiency of histopathological diagnosis.






