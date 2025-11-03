# Image Feature Extraction using GLCM

This repository contains a Python notebook for **image feature extraction** using the **Gray-Level Co-occurrence Matrix (GLCM)** method.  
The notebook demonstrates how to analyze texture-based features from images, which are useful for image classification, pattern recognition, and computer vision research.

---

## 🧠 Overview

The project demonstrates a workflow for:
1. **Data Input** — Loading a custom image dataset.
2. **Preprocessing** — Converting images to grayscale and resizing them.
3. **Feature Extraction** — Computing texture-based statistical features using GLCM:
   - **Contrast**
   - **Energy**
   - **Homogeneity**
   - **Correlation**
4. **Output** — Exporting the extracted features into a `.csv` file for further analysis or model training.

---

## ⚙️ Requirements

Ensure the following Python libraries are installed:

```bash
pip install numpy pandas scikit-image opencv-python tqdm
```

---

## 🚀 Usage

You can run this notebook either **locally (Jupyter Notebook / VS Code)** or on **Google Colab**.

### ▶️ Run Locally
1. Install the required libraries.
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook image_feature_extraction_fixed.ipynb
   ```
3. Run all cells to:
   - Load the image dataset
   - Perform preprocessing (grayscale & resize)
   - Extract GLCM texture features
   - Export results to `features.csv`

### ☁️ Run on Google Colab
1. Upload your images and the notebook (`image_feature_extraction_fixed.ipynb`) to Google Colab.
2. Adjust the dataset path in the first few code cells.
3. Run all cells — results will be saved to your Colab session or Google Drive.

---

## 📂 File Structure

```
image-feature-extraction-glcm/
│
├── image_feature_extraction_fixed.ipynb   # Main notebook
├── output/
│   └── features.csv                       # Example of extracted features
└── README.md
```

---

## 🧩 Feature Explanation

| Feature        | Description |
|----------------|-------------|
| **Contrast**   | Measures local variations in the gray-level co-occurrence matrix. |
| **Energy**     | Reflects image uniformity (sum of squared GLCM elements). |
| **Homogeneity**| Measures the closeness of element distribution to the GLCM diagonal. |
| **Correlation**| Describes the correlation between pixel pairs. |

---

## 🧾 Credits

Developed by **Abiyyu Rahman (2025)** using **Python**, **Jupyter Notebook**, and **Google Colab** for research and experimentation in texture-based image feature extraction using the **GLCM (Gray Level Co-occurrence Matrix)** method.

---

## 🪪 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.
