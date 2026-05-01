# ML_Assignment3

# Requirements
- Python 3
- PyTorch
- h5py
- numpy
- Google Collab

# Dataset
Download the Soli dataset and rename it as SoliData.zip

# How to Run Training
1. Open assignment3.ipynb in Google Colab
2. Run the first cell and upload SoliData.zip
3. Run all remaining cells from top to bottom
4. The following models will be trained one by one:
   - Baseline CNN
   - DANN (domain adversarial)
   - CNN with conditional GAN augmentation
   - Unified model (DANN + cGAN)

# How to Run Testing
Testing runs automatically after each model finishes training.
Results printed are:
- Overall test accuracy
- Fine gesture accuracy (classes 0-3)

# Models
Trained model files are saved to:
- `/content/baseline_model.pt`
- `/content/dann_model.pt`
- `/content/cgan_cnn_model.pt`
- `/content/unified_model.pt`

## Final Model Download Link
[unified_model.pt](PASTE YOUR GOOGLE DRIVE LINK HERE)
