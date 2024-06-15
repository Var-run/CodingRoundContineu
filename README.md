# Image Classification on Brain MRIs

Fine tuning the pre-trained Google/ViT-base-patch16-224-in21k model. This particular model has a patch size of 16x16 pixels, which is a good balance between capturing fine details and maintaining spatial information. The 224 refers to the input image size, which is the standard size for many pre-trained models. Finally, the "in21k" in the model's name indicates that it has been pre-trained on a dataset with 21,000 classes. This will help the model to generalize well to the classification task at hand.

DATASET : https://drive.google.com/file/d/1Fk0davXze4Lc3oQohwYe-4ruJ3wk8a-V/view

References:
The Vision Transformer (ViT), which was introduced in [June 2021](https://arxiv.org/abs/2010.11929) by a team of researchers at Google Brain.

![vit_figure.png](https://raw.githubusercontent.com/google-research/vision_transformer/main/vit_figure.png)

