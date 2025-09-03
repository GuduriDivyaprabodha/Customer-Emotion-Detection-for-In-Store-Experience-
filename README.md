# Customer Emotion Detection for In-Store Experience

## Overview

This project explores how **deep learning models** can recognize customer emotions from facial expressions to improve retail in-store experiences. The research compares three approaches:

* **CNN + Transformer + EfficientNet (Hybrid)**
* **CNN + Transformer**
* **FaceNet\_CNN (Baseline)**

Using the **FER-2013 dataset** with over 35,000 labeled facial images across seven emotions, models were trained and evaluated in TensorFlow/Keras. Preprocessing steps included grayscale normalization, face alignment, resizing, and data augmentation.

The **hybrid model** achieved **74.8% accuracy**, outperforming CNN+Transformer (71.2%) and FaceNet\_CNN (69.3%), showing the value of combining **local feature extractors (EfficientNet)** with **global context modeling (Transformer)**.

---

## Key Features

* Comparative study of **three deep learning architectures**
* Preprocessing pipeline for robust emotion recognition
* Performance improvement of **5.5% over baseline**
* Applicable to **real-time retail analytics** and **customer experience optimization**

---

## Repository Structure

* **/thesis/** – Complete thesis chapters and final document (PDF/DOCX)
* **README.md** – Project overview and instructions
* **.gitignore** – Preconfigured for Python projects and large files
* **.gitattributes** – Configured for Git LFS (PDF, DOCX, ZIP)

> **Note:** This repository currently contains thesis documentation only. Training code and datasets can be added later.

---

## Methodology

1. **Dataset** – FER-2013 (grayscale facial images labeled with 7 emotions)
2. **Preprocessing** – Normalization, alignment, resizing, augmentation
3. **Models Evaluated**:

   * CNN + Transformer + EfficientNet (Hybrid)
   * CNN + Transformer
   * FaceNet\_CNN
4. **Implementation** – TensorFlow / Keras
5. **Evaluation Metric** – Classification accuracy

---

## Results

| Model                            | Accuracy  |
| -------------------------------- | --------- |
| CNN + Transformer + EfficientNet | **74.8%** |
| CNN + Transformer                | 71.2%     |
| FaceNet\_CNN (baseline)          | 69.3%     |

The hybrid model demonstrated the best balance of spatial and contextual feature extraction.

---

## How to Use (Future Code Integration)

When code is added to this repository:

1. Clone the repository:

   ```bash
   git clone https://github.com/<username>/customer-emotion-detection-instore.git
   cd customer-emotion-detection-instore
   ```
2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```
3. Install dependencies (to be listed in `requirements.txt`):

   ```bash
   pip install -r requirements.txt
   ```
4. Run training/inference scripts (to be added):

   ```bash
   python train.py
   python infer.py --image sample.jpg
   ```

---

## Documents Included

All thesis materials are included in **PDF** and **DOCX** format inside the `/thesis` directory.

* Final thesis document
* Individual chapter documents
* Result analysis chapter

---

## Citation

If you use this work in your research, please cite:

```
DivyaPrabodha Guduri, "Customer Emotion Detection for In-Store Experience," MSc Thesis,
Dublin Business School, 2025.
```

---

## License

This project is distributed for **academic and research purposes**. Please contact the author for any commercial use.
