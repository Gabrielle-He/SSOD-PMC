# SSOD-PMC

Official code for  **"Part-Aware Multi-Dimensional Consistency for Semi-Supervised Detection of Industrial Composite Facilities in Remote Sensing Images"**

🚧 **Code is coming soon...**

---

## 🔍 Overview

This repository provides the official implementation of **SSOD-PMC**, a semi-supervised object detection framework designed for industrial composite facilities in remote sensing imagery.  
The proposed method enhances detection robustness under limited annotations by jointly modeling part-level representations and multi-dimensional consistency constraints.

---

## 📂 Dataset: Indus-CO

We introduce **Indus-CO**, a remote sensing image dataset focusing on large-scale industrial composite facilities, including:

- **Thermal Power Plants (TPPs)**
- **Cement Plants (CPs)**
- **Iron and Steel Plants (ISPs)**

The dataset was curated by integrating **Points of Interest (POI)** data with **level-17 high-resolution Google Earth imagery**, followed by manual verification to ensure label reliability.

### Dataset Statistics

| Category | Number of Images |
|--------|------------------|
| TPPs   | 950 |
| CPs    | 791 |
| ISPs  | 349 |
| **Total** | **2,090** |

Each image corresponds to a ground coverage of approximately **4 km × 4 km**, with the industrial facility centered in the scene to preserve both structural completeness and surrounding context.

---

## 📁 Dataset Access

Due to the large size of the Indus-CO dataset, it is **not directly hosted on GitHub**.

👉 Dataset download links and access instructions are provided in:  
📄 [`data/Indus-CO.md`](data/Indus-CO.md)


