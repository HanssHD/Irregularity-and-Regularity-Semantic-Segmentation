## 💻 Objective
The publication of this code aims to:
1. Share the results of this final project’s research and development with the public, particularly in the context of implementing semantic segmentation for building irregularity detection.
2. Facilitate the reproduction of experiments by other researchers working on similar topics.
3. Provide a reference for developers or researchers who wish to utilize or further develop this final project’s research.

## 📟 Technologies / Environment Used
[running with Kaggle Notebook] with using:
1. Python 3.10
2. TensorFlow / PyTorch / Keras
3. Sklearn
4. -U segmentation-models
5. Jaccard Coefficient for accuration metrics

## 🗄️ Masking Image for Dataset
Before making mask dataset, image dataset should be labelled as masking of image dataset. On this final project used Label Studio with 2000 image dataset. For further information regarding its use it can follow the following link: https://labelstud.io/

## ⚙️ Model Performance
In this research, the model training was carried out as many as 50 epochs, but configured with 2 callbacks (EarlyStopping and ReduceLROnPlateau) and the results were obtained as in Figure I - Figure III.
<div align="center">
    <img src="https://github.com/user-attachments/assets/b6a25e65-f66b-4645-a105-102c04228b65" width="500">
    <p><b>Figure I: Training vs Validation Loss</b></p>
</div>

<div align="center">
    <img src="https://github.com/user-attachments/assets/68adc0bd-6869-4947-9ae1-f606a5ff9171" width="500">
    <p><b>Figure II: Training vs Validation IoU</b></p>
</div>

<div align="center">
    <img src="https://github.com/user-attachments/assets/1cae3013-7937-4b00-8c2b-676f83eff6d1" width="500">
    <p><b>Figure III: Metrics Evaluation</b></p>
</div>

## 📡 Visualization with Gradio
The model for predicted image generated in this research was integrated with Gradio and resulted in two classes, namely irregularity and regularity as shown in Figure IV and Figure V.
<div align="center">
    <img src="https://github.com/user-attachments/assets/a047c0bb-0831-41af-9180-d33249c28b41" width="500">
    <p><b>Figure IV: Predict as Irregularity Building</b></p>
</div>

<div align="center">
    <img src="https://github.com/user-attachments/assets/e672d72c-c5d2-4014-8315-be1b8b21e19f" width="500">
    <p><b>Figure V: Predict as Regularity Building</b></p>
</div>

