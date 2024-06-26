# CNN_Cancer_Histology
## Deep learning classification of breast, lung and colon cancer using histological measures


In this project, we developed and trained four Convolutional Neural Network (CNN) models for the classification of breast, lung, and colon cancer using histological measures. Each model was tailored to specific classification tasks:

### Body Part Classification CNN Model (body_part_model.h5):
To classify the histological images based on the body part (breast, lung, or colon).

### Breast Cancer Classification CNN Model (breast_model.h5):
To differentiate between benign and malignant breast cancer cells.

### Colon Cancer Classification CNN Model (colon_model.h5):
To classify colon cells as either benign or malignant.

### Lung Cancer Classification CNN Model (lung_model.h5):
To classify lung cells, distinguishing between benign, carcinoma, and adenocarcinoma.

### Training and Evaluation
Data Preprocessing: Images were preprocessed through resizing, normalization, and augmentation to enhance model performance and robustness. This included balancing classes, resizing images to a uniform 50x50 pixels, and normalizing pixel values.

Training: Models were trained using labeled datasets with a significant number of images for each type of cancer (35000 in total). The training involved fine-tuning hyperparameters such as learning rate, batch size, and number of epochs to achieve optimal results.

Evaluation Metrics: Models were evaluated using metrics such as accuracy, precision, recall, and F1-score to ensure high performance and reliability. Cross-validation was also performed to ensure the robustness and generalizability of the models.

#### Results:
Body Part Classification Model: Achieved an accuracy of 100%, indicating perfect classification of histological images into breast, lung, or colon categories.

Breast Cancer Classification Model: Achieved an accuracy of 97.31%, with a precision of 96.88%, recall of 97.89%, and F1-score of 97.38%. This model demonstrated high effectiveness in distinguishing between benign and malignant breast cancer cells.

Colon Cancer Classification Model: Achieved an accuracy of 95.85%, with a precision of 98.49%, recall of 93.01%, and F1-score of 95.67%. This model proved reliable in classifying colon cells as either benign or malignant.

Lung Cancer Classification Model: Achieved an accuracy of 95.20%, with a precision of 99.58%, recall of 99.07%, and F1-score of 99.32%. This model successfully differentiated between benign, carcinoma, and adenocarcinoma lung cells.


#### These models collectively aim to provide a comprehensive tool for the early detection and classification of various cancer types, leveraging deep learning to enhance the accuracy and efficiency of histopathological diagnosis.

Source of images:

[1] 	Invasive ductal carcinoma (IDC) histology image dataset. Academic Torrents. 
https://academictorrents.com/details/e40bd59ab08861329ce3c418be191651f35e2ffa

[2] 	Larxel, “Lung and Colon Cancer Histopathological Images.” 14-Apr-2020.
https://www.kaggle.com/datasets/andrewmvd/lung-and-colon-cancer-histopathological-images

Authors:
Martín Antúnez, Luis Acero Morata, Carlos Arcas Perez, Javier Harto Vallejo








