**Citrus_Plant_Disease**

**1. Introduction:**
   Agriculture is crucial for food production and income generation. Citrus fruits play a key role in agriculture but are vulnerable to diseases like black spot and canker. Early detection using deep learning       technology can help farmers improve yields. A new method proposes three phases for segmenting and classifying citrus leaf diseases, with promising results in detecting affected areas accurately.
   
**2. Features:**
    Improved Segmentation models to improve accuracy and robustness of the image segmentation, Transfer Learning: Utilizes pre-trained CNN models for feature extraction and classification.
   
**3. Requirements:**
     Python 3.6 or higher
     TensorFlow 2.x
     Keras
     OpenCV
     NumPy
     Pandas
     Scikit-learn
     Matplotlib

**4. Clone the repository:** git clone https://github.com/Dineshp-max/Plant_Disease

**5. pip install** -r requirements.txt

**6. Prepare Dataset:**
   
   Ensure you have a dataset of citrus leaf images categorized by disease type. The dataset should be organized in subdirectories, each images should be seperated to the corresponding disease directories.
   
**7.Dataset:**
   The dataset used for this project should contain two types of dataset,
   a) The segmentation dataset contaion Masked images, Overlayed images, Original images of the dataset in a seperate folders for segmentation.
   b) The classification dataset contains enhanced and augumented images that should be organized in subdirectories, each images should be seperated and present on the corresponding disease directories.

**8. Training:**
   The training process involves: Loading and unziping the dataset for segmentation and classification. Train the model for on the dataset.
   
**9. Evaluation:**
   The model is evaluated using standard metrics such as precision, recall, specificity, f1 score, accuracy, loss, IoU, Mean IoU, Pixel Accuracy, and Dice-coefficient for segmentation model. Confusion matrices       and precision, recall, specificity, f1 score, accuracy are also generated for detailed analysis classification model.
   
**10. Result:**

   **By utilizing the segmentation model** as proposed, **the training model achieved** a success rate with an **IOU of 0.9847, mean IOU of 0.9846**, weighted mean IOU of 0.9874, **pixel accuracy of 0.9993, mean pixel accuracy of 0.9993, dice coefficient of 0.9936**, mean boundary f1 score of 0.9557, precision of 0.9974, recall of 0.9975, f1 score of 0.9974, specificity of 0.9996, loss of 0.0079, and accuracy of 0.9993. **The Validation model achieved** success with the following metrics: **intersection over union (IOU) of 0.9334, mean IOU of 0.9334**, weighted mean IOU of 0.9517, **pixel accuracy of 0.993, mean pixel accuracy of 0.9931, dice coefficient of 0.9744, mean boundary F1 score of 0.9504**, precision of 0.9778, recall of 0.9769, F1 score of 0.9773, specificity of 0.9959, loss of 0.0282, and accuracy of 0.9931.
   
   **the classification model** achieved a maximum success rate for blackspot, citrus canker, citrus greening, and healthy class in the citrus leaves dataset, with a **98% success rate for overall citrus plant diseases**.

   
