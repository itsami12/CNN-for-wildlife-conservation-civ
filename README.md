# Wildlife Species Classification in Côte d'Ivoire 🐘🦍🦓

This project focuses on the classification of wildlife species from camera trap images in Côte d'Ivoire. It was developed during my internship at **WorldQuant University’s Applied AI Lab**, under the track **Deep Learning for Computer Vision (AI-01)**.

## 🚀 Project Highlights

- **Goal**: Automate the classification of animal species to aid conservation efforts.
- **Dataset**: Camera trap images from [DrivenData’s Wildlife Conservation Challenge](https://www.drivendata.org/competitions/82/competition-wildlife-video-depth-estimation/page/390/).
- **Model**: Custom CNN built using PyTorch.
- **Performance**: Achieved a validation accuracy of **86%** over 20 epochs.

## 📊 Results

### 📈 Training and Validation Accuracy

| Epoch | Training Loss | Validation Loss | Validation Accuracy |
|-------|----------------|------------------|----------------------|
| 1     | 1.53           | 1.14             | 0.60                 |
| 5     | 0.59           | 0.56             | 0.81                 |
| 10    | 0.35           | 0.49             | 0.85                 |
| 15    | 0.25           | 0.52             | 0.86                 |
| 20    | 0.19           | 0.52             | 0.86                 |

### 📉 Confusion Matrix

<img width="747" height="486" alt="image" src="https://github.com/user-attachments/assets/5ade3aed-317d-41a1-b284-ea9d165fa69f" />

## 📁 Directory Structure

animals/
├── test_features/ # Folder with test data (could be images or CSV)
├── train_features/ # Folder with training data
├── test_features.csv # Tabular test features
├── train_features.csv # Tabular training features
├── train_labels.csv # Training labels 


## 🧠 Model Architecture

- Custom CNN
- ReLU activation
- Batch Normalization
- Max Pooling
- Dropout Regularization
- Final softmax classifier

<img width="716" height="356" alt="image" src="https://github.com/user-attachments/assets/4d20b33e-1116-4e09-96f7-8dfe93ec3649" />



---

## 🎓 Internship Info

- **Institution**: WorldQuant University
- **Lab**: Applied AI Lab
- **Track**: Deep Learning for Computer Vision (AI-01)
- **Project Title**: *Wildlife Conservation in Côte d'Ivoire*
- https://learn.wqu.edu/programs
<img width="1114" height="409" alt="image" src="https://github.com/user-attachments/assets/3c1a00b4-1c69-4fed-8800-b1b74f5c634c" />

---



