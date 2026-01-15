# COVID-19 Lung Segmentation (U-Net / U-Net++)

This project contains a Colab-ready notebook for training U-Net and U-Net++ to segment lungs on normal chest X-rays from the COVID-19 Radiography Database.

## Contents
- `covid19_unet.ipynb`: end-to-end pipeline (download, training, visualization)
- `kaggle.json`: Kaggle API credentials (place in `/root/.kaggle/` in Colab)

## How to run (Colab)
1. [Open](https://colab.research.google.com/drive/133JI9UcopIuOdiBOMawSOsv2WZoi7uxk?usp=sharing) `covid19_unet.ipynb` in Google Colab.
2. [Upload](https://www.kaggle.com) `kaggle.json` to `/root/.kaggle/` (Colab file browser).
3. Run all cells top to bottom.

## Notes
- The notebook trains on the `Normal` class and uses the corresponding lung masks.
- Results are visualized as triplets: image, ground-truth mask, prediction.
