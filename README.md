## Dataset Scaling Experiment (10,000 → 18,000 Images)

Initially, the DCGAN model was trained using a subset of approximately 10,000 anime face images.  
At this stage, the generated images were blurry and lacked fine details, which is expected during early training with limited data.

To improve image quality, the dataset size was increased to approximately 18,000 images by utilizing the full available dataset.  
With more training data, the generator was exposed to a greater variety of facial structures, hairstyles, and visual patterns.

### Observations:
- **10,000 images**:  
  - Generated images were blurry  
  - Basic face structure was visible  
  - Limited sharpness and detail  

- **18,000 images**:  
  - Improved clarity and facial symmetry  
  - Better learning of hair and face regions  
  - Overall more realistic anime-style outputs  

This experiment demonstrates that increasing dataset size significantly improves the quality and stability of GAN-generated images.
