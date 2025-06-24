

# Pectoral Muscle Groundtruth Segmentation

**Official repository for the pectoral muscle annotations from the following papers:**

- _"Towards Robust Supervised Pectoral Muscle Segmentation in Mammography Images"_
- _"Supervised Pectoral Muscle Removal in Mammography Images"_

---

## Overview

Mammography images are the most commonly used tool for breast cancer screening. The presence of pectoral muscle in images for the mediolateral oblique view makes designing a robust automated breast cancer detection system more challenging. Most of the current methods for removing the pectoral muscle are based on traditional machine learning approaches. This is partly due to the lack of segmentation masks of pectoral muscle in available datasets. In this paper, we provide the segmentation masks of the pectoral muscle for the INbreast, MIAS, and CBIS-DDSM datasets, which will enable the development of supervised methods and the utilization of deep learning. Training deep learning-based models using segmentation masks will also be a powerful tool for removing pectoral muscle for unseen data. To test the validity of this idea, we trained AU-Net separately on the INbreast and CBIS-DDSM for the segmentation of the pectoral muscle. We used cross-dataset testing to evaluate the performance of the models on an unseen dataset. In addition, the models were tested on all of the images in the MIAS dataset. The experimental results show that cross-dataset testing achieves a comparable performance to the same-dataset experiments.

### ✅ We release the **pectoral muscle segmentation masks** for the following datasets: **INbreast**, **MIAS**, **CBIS-DDSM**. The **Preprocessed** file is the images that are preprocessed according to the papers. The **Raw** file is for the original data downloaded from the sources.






## 📦 Downloads

### 🔹 Ground Truth Masks with images (for Preprocessed Images)

[ Google Drive Link](https://drive.google.com/file/d/1Ek25FOImqBHEIfpV6O5Vix5gueGFEeGx/view?usp=sharing)

---

### 🔹 Ground Truth Masks (for Raw Images )

[ Google Drive Link](https://drive.google.com/file/d/1yEKepjP4OKhiiP82cO5T4R-xLS7ZDpNn/view?usp=sharing)

---

## 🗂 Dataset Sources

- ** 🔹CBIS-DDSM**  
  [ The Cancer Imaging Archive](https://www.cancerimagingarchive.net/collection/cbis-ddsm/)

- ** 🔹INbreast**  
  [ Kaggle Dataset](https://www.kaggle.com/datasets/ramanathansp20/inbreast-dataset)


- ** 🔹MIAS**  
  [ Cambridge Repository](https://www.repository.cam.ac.uk/items/b6a97f0c-3b9b-40ad-8f18-3d121eef1459)

---


## 📚 Citation

If you use this repository or the segmentation masks in your work, please cite the following papers accordingly:

```bibtex
@article{aliniya2024towards,
  title={Towards Robust Supervised Pectoral Muscle Segmentation in Mammography Images},
  author={Aliniya, Parvaneh and Nicolescu, Mircea and Nicolescu, Monica and Bebis, George},
  journal={Journal of Imaging},
  volume={10},
  number={12},
  pages={331},
  year={2024},
  publisher={MDPI}
}

@inproceedings{aliniya2024supervised,
  title={Supervised Pectoral Muscle Removal in Mammography Images},
  author={Aliniya, Parvaneh and Nicolescu, Mircea and Nicolescu, Monica and Bebis, George},
  booktitle={International Conference on Artificial Intelligence in Medicine},
  pages={126--130},
  year={2024},
  organization={Springer}
}
