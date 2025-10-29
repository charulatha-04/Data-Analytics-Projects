👁️ Early Detection of Diabetic Retinopathy Using Deep Learning

Tool: Python (TensorFlow, Keras)  
Dataset: APTOS Retina Images  
Model Type: Hybrid CNN Model (EfficientNetV2 + Swin Transformer + CBAM + MLP)  
Objective: To detect and classify stages of diabetic retinopathy from retina images.

⚙️ Technical Summary
- Preprocessed 3600 retinal images using augmentation and normalization.  
- Extracted image features using **EfficientNetV2** and **Swin Transformer**.  
- Integrated **CBAM Attention** and **MLP** for hybrid classification.  
- Evaluated model with metrics: Accuracy, Precision, Recall, F1-score, and AUC.

📊 Results
- Achieved high classification accuracy across multiple severity levels.  
- Improved model interpretability using Grad-CAM heatmaps.

📈 Architecture
EfficientNetV2 → CBAM → Swin Transformer → Feature Fusion → MLP Classifier

📂 File
- DR_Detection_Summary.pdf — Project summary report   

