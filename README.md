# TML25_A4_7

This repository contains the implementation and results for two explainability tasks involving visual interpretation of deep learning models.

## 📁 Folder Structure

- `task_2_results/`
  - Implements **GradCAM**, **ScoreCAM**, and **AblationCAM**
  - Visualizations for multiple classes
  - Analysis and report files
- `task_3/`
  - Implements **LIME** (Local Interpretable Model-Agnostic Explanations)
  - Optimized parameters and enhanced visual explanations
  - Includes code and result images

## 📌 Requirements

Install dependencies using:

```bash
pip install torch pillow numpy matplotlib lime scikit-image
```

## ▶️ Running the Tasks

### Task 2 - CAM-Based Techniques
Navigate to the task 2 directory and run the notebook:
```bash
cd task_2_results
jupyter notebook task2.ipynb
```

### Task 3 - LIME
Navigate to the task 3 directory and run the notebook:
```bash
cd task_3
jupyter notebook task3.ipynb
```

## 📈 Output 

- **Task 2**: Individual and comparative CAM heatmaps for different classes
- **Task 3**: Optimized LIME explanations with enhanced clarity and comparative results

## 🧠 Authors

- Saif Ali and Usaid Bhirya
