# 🫁 Lung Cancer Classification with Explainable AI (XAI)
Implementing **Grad-CAM** using **DenseNet121** to interpret and visualize deep learning decisions on Chest CT-Scan images.

## 📌 Project Overview
In medical diagnostics, "Black Box" AI models can be risky. This project focuses on **Interpretability**—not just predicting whether a patient has lung cancer, but also visualizing **where** the model is looking within the CT scan to make its decision.

Using the **Captum** library and a pre-trained **DenseNet121** architecture, this pipeline provides heatmaps that highlight malignant nodules or abnormalities, helping clinicians build trust in AI-assisted 
diagnoses.

## 🧪 Methodology
- **Dataset:** [Chest CT-Scan images Dataset](https://www.kaggle.com/datasets/mohamedhanyyy/chest-ctscan-images)
- **Classes:** 1. Adenocarcinoma
  2. Large cell carcinoma
  3. Squamous cell carcinoma
  4. Normal (Healthy)
- **Model:** DenseNet121 (Pre-trained on ImageNet)
- **Interpretability Technique:** Grad-CAM (Gradient-weighted Class Activation Mapping)

## 📊 Results & Visualization
The model successfully identifies cancerous regions in CT scans. Below is an example of the Grad-CAM output:

![Grad-CAM Result](results/lung_cancer_gradcam_analysis.png)

*Interpretation: The heatmap (right) confirms that the model is correctly focusing on the density variations and nodules in the lung tissue rather than the surrounding bone or background.*

## 🛠️ Installation & Usage
1. Clone the repository:
   ```bash
   git clone [https://github.com/kamrulkafi1/Lung-Cancer-XAI-DenseNet.git](https://github.com/your-username/Lung-Cancer-XAI-DenseNet.git)
