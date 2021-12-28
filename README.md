# MaskMTL: Attribute prediction in masked facial images with deep multitask learning
<div align=center>
<img src="https://github.com/dk-github-acc/Attribute-prediction-in-masked-facial-images-with-deep-multitask-learning/blob/main/Images/ML_extensn_paper.png" width="62%" height="50%" />
</div>

## INTRO
**[Technical Report(link)]** **[ARXIV]**
...

## ARCHITECTURE DIAGRAM
OUR MaskMTL architecture

<div align=center>
<img src="Images/mask_mtl_architecture.png" width="50%" height="50%" />
</div>

## REQUIREMENTS
```
python 3.7
tensorflow
opencv-python
matplotlib
pandas
tensorflow.keras
```

## DATASET
The dataset used in the paper can be downloded from links.
[Images]()   [Labels](https://drive.google.com/file/d/10YXRLApAaCFYlaW3qpBNq6UUZ1D2WnqR/view?usp=sharing)

## USAGE/CODE FOR USE
1. code.ipynb provided has model reparation, training, evaluation and prediction by model. Refer that to train model on your dataset.
2. Use pretrained model given in **PRETRAINED MODEL** section below, to get predictions on masked facial images.
 
## PREDICTION PERFORMANCE
<div align=center>
<img src="Images/ml_extension_performance.png" width="65%" height="50%" />
</div>

## PRETRAINED MODEL
The pretrained model can be downloaded [here](https://drive.google.com/file/d/1g9zaYqbcP9ifyeIaOEHWITSowePwkbXv/view?usp=sharing) and used directly for prediction.

## LICENSE
...

## CITE
Please cite our paper if you use or refer this code:

```
@inproceedings{
  title={MaskMTL: Attribute prediction in masked facial images with deep multitask learning},
  author={Prerana Mukherjee, Vinay Kaushik, Ronak Gupta, Ritika Jha, Daneshwari Kankanwadi, and Brejesh Lall},
  booktitle={PREMI2021},
  year={2021}
}
```
