# 📊 Image Clustering Lab - KMeans with Brightness Feature

This lab demonstrates how to cluster images using the **KMeans algorithm** based on a simple feature: the **average brightness (intensity)** of each image.

---

## 🚀 Overview

- **Goal**: Group similar images by their average brightness using unsupervised learning.
- **Algorithm**: [`KMeans`](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html) from `scikit-learn`.
- **Feature**: Total intensity (normalized brightness) of RGB images.

---

## 📂 Folder Structure

<pre>
lab4/
│
├── data/
│   └── Busy/
│       └── 1/             # Folder containing input images
│
├── data.pickle            # Cached features (auto-created)
├── Kmean2.py              # Main script (code provided in class)
└── README.md              # You're here
</pre>

---

## 🧰 Required Libraries

Make sure you have the following Python libraries installed:

```bash
pip install numpy matplotlib opencv-python scikit-learn
