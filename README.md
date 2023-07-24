## A Deep Learning Method to Localize Objects using Limited Annotation, with Applications to Thoracic Diseases  
Motivation: The localization of objects in images is a longstanding objective within the field of image processing. Most current techniques are based on machine learning approaches, which typically require careful annotation of training samples in the form of expensive bounding box labels. The need for such large-scale annotation has only been exacerbated by the widespread adoption of deep learning techniques within the image processing community: deep learning is notoriously data-hungry. Method: In this work, we attack this problem directly by providing a new method for learning to localize objects with limited annotation: most training images can simply be annotated with their whole image labels (and no bounding box), with only a small fraction marked with bounding boxes. The training is driven by a novel loss function, which is a continuous relaxation of a well-defined discrete formulation of weakly supervised learning. Care is taken to ensure that the loss is numerically well-posed. Additionally, we propose a neural network architecture which accounts for both patch dependence, through the use of Conditional Random Field layers, and shift-invariance, through the inclusion of anti-aliasing filters. Results: We demonstrate our method on the task of localizing thoracic diseases in chest X-ray images, achieving state-of-the-art performance on the ChestX-ray14 dataset. We further show that with a modicum of additional effort our technique can be extended from object localization to object detection, attaining high quality results on the Kaggle RSNA Pneumonia Detection Challenge. Conclusion: The technique presented in this paper has the potential to enable high accuracy localization in regimes in which annotated data is either scarce or expensive to acquire. Future work will focus on applying the ideas presented in this paper to the realm of semantic segmentation.

#### [IEEE paper](https://ieeexplore.ieee.org/abstract/document/9416490)
```
@article{rozenberg2021learning,
  title={Learning to localize objects using limited annotation, with applications to thoracic diseases},
  author={Rozenberg, Eyal and Freedman, Daniel and Bronstein, Alex A},
  journal={IEEE Access},
  volume={9},
  pages={67620--67633},
  year={2021},
  publisher={IEEE}
}
```

## Localization with Limited Annotation for Chest X-rays
#### [PMLR paper](http://proceedings.mlr.press/v116/rozenberg20a.html)
```
@inproceedings{rozenberg2020localization,
  title={Localization with limited annotation for chest x-rays},
  author={Rozenberg, Eyal and Freedman, Daniel and Bronstein, Alex},
  booktitle={Machine Learning for Health Workshop},
  pages={52--65},
  year={2020},
  organization={PMLR}
}
```

