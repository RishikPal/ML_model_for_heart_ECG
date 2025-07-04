# 📈 ECG Signal Processing in Google Colab

This repository contains a Jupyter Notebook for **ECG signal processing** and feature extraction using Python. It covers essential signal processing techniques like filtering, normalization, visualization, and fiducial point detection (P, Q, R, S, T waves).

---

## 📖 Overview

An **Electrocardiogram (ECG)** records the heart's electrical signals and is commonly used to detect heart rhythm irregularities and cardiovascular diseases.  
This notebook provides a step-by-step implementation for:
- Loading ECG signals
- Visualizing raw data
- Removing noise and artifacts
- Detecting QRS complexes and other key features  
Designed for easy use in **Google Colab** and **Google Drive**.

---

## 🖥️ How to Use This Project

### 📦 Option 1: Run on Google Colab (Recommended)
1. Open [Google Colab](https://colab.research.google.com/)
2. Click on `File` → `Upload Notebook` and upload `Ex1 (2).ipynb`  
   **OR**
3. Save this notebook in your **Google Drive**
4. In Google Colab, click `File` → `Open notebook`
5. Switch to the `Google Drive` tab and open the notebook

### 📦 Option 2: Clone and Run Locally
1. Install **Jupyter Notebook** and required Python libraries:
   ```bash
   pip install numpy scipy matplotlib
````

2. Run the notebook locally:

   ```bash
   jupyter notebook Ex1 (2).ipynb
   ```

---

## 📂 Files Included

* `Ex1 (2).ipynb` — Main ECG signal processing notebook
* `README.md` — Project description and usage instructions

---

## 📊 Features Covered

* 📥 Load ECG data (from file or sample dataset)
* 📉 Visualize raw ECG signals
* 🔍 Apply filters to remove baseline wander and noise
* ⚙️ Normalize signals
* 📌 Detect QRS complexes (R-peak detection)
* 📈 Plot clean ECG signals with detected peaks

---

## 🩺 Applications

Useful for:

* ECG signal preprocessing and feature extraction
* Detecting arrhythmias, bundle branch blocks, hypertrophy, etc.
* Educational purposes in biomedical signal processing

---

## 📚 Requirements

* Python 3.x
* Libraries:

  * `numpy`
  * `scipy`
  * `matplotlib`
  * `google.colab` (if running in Colab)

---

## 📜 License

This project is open-source and available under the MIT License.

---

### ✅ Summary:
- Explains what the project does
- Shows how to run it in **Google Colab**
- Describes how to upload it to **Google Drive**
- Lists files, dependencies, and applications  
- Clean, structured, beginner-friendly.

