## Simple CNN Classifier   

### Directory structure description   
|--README.md   
|--archive                               // YOLO format dataset   
|--Recognized                            // Training dataset   
|--model_pth                             // Save the trained model   
|--cnn_classifier_pytorch.ipynb          // train models.   
|--extract_yolo_images.ipynb             // Convert the dataset in YOLO format to images and save them in the "Recognized" folder.   
|--predict.ipynb                         // Make predictions using the trained model.   
|--model_evalution.xlsx                  // Save the performance of the model under different parameters.   

### Complete project content   
The complete project content, including the trained model, dataset and other files, can be found at the link.
https://drive.google.com/drive/folders/1FnCXH0nPpbnHrMEurusdecCbgWST4ndY?usp=sharing

### Usage Method   
Running `extract_yolo_images.ipynb` can save the marked pest areas in the `Recognized` folder based on the labels of the dataset in YOLO format in the `archive` folder.   
Running `cnn_classifier_pytorch.ipynb` can train the model. In the code, you can change the batch size, models with different layers, and batch processing size. The best-performing model after training will be saved in the `model_pth` folder. Meanwhile, the performance of the model under different parameters is manually recorded in `model_evalution.xlsx`.   
In `predict.ipynb`, you can use the trained model to predict images.  

### Source of the dataset
Rupankar Majumdar, "AgroPest-12: A 12-Class Image Dataset of Crop Insects and Pests," Kaggle, 2025.