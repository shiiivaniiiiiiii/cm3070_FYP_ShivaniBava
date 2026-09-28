# Deep Learning Breast Cancer Detection from Mammograms

CM3070 Final Year Project.

This project investigates benign-malignant mammogram classification using the CBIS-DDSM dataset.

The experiments compare:
- CNN architectures trained from scratch
- Progressive regularisation
- VGG16 transfer learning
- ResNet50 transfer learning

The evaluation uses patient-disjoint training, validation and held-out test sets, validation-based model and threshold selection, patient-level bootstrap confidence intervals, and Grad-CAM interpretability.

## Final Model

The final selected model was a fine-tuned VGG16 selected using validation AUC.

Held-out test performance:
- AUC: 0.741
- Sensitivity: 0.720
- Specificity: 0.622

## Notebook

The complete experimental pipeline is provided in:

`fypfinal.ipynb`

## Dataset

The project uses the CBIS-DDSM dataset. Dataset files are not included in this repository.

## Disclaimer

This project is for research and educational purposes only and is not a clinically validated diagnostic system.
