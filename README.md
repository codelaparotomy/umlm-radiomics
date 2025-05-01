# umlm-radiomics
This reporsitory contains the pipeline developed for taking CT Scans (And eventually MRIs) of Uveal Melanoma Liver metastases and predicting their uveal melanoma immune scores for adoptive cell transfer selection

- access DICOMS, covert to NiFti
- manual segmentation with ITK SNAP
- Feature extraction via pyradiomcs
- Data preprocessing and exploration
- Regression modeling (linear, random forest, XGB, neural networks)

## Repository structure
- '/data/': processed NifTI image masks and extracted features
- '/scripts/': python code for feature extraction, data pocessing, model training
- '/notebooks/': Jupyter notebooks for modeling and visualization
- '/config/': parameter files
- '/results/': outputs, plots, stats
