# HuBMAP-kaggle

# Model Weight dataset Link
- https://www.kaggle.com/datasets/soumya9977/hubmap-coat-512-weights [coatnet-small-aux5-512-fold3]


## TODO [today: 11-08-22]
- **EXHAUSTE ONE MODEL**
  - try pretrained
  - try not pretrained
  - use LR schedule
  - bigger image
  - try multiclass training
  - try effnet-b4
  - change loss
  - add lable smoothing
  - we can change backbone and stuff, but what can we do technique wise.

## Ideas:
1. Try [`Monai`](https://github.com/Project-MONAI/MONAI)
2. Try tiling image segmentation
3. Integrate [`SMP`](https://segmentation-modelspytorch.readthedocs.io/en/latest/)
4. Train SegFormer with MMseg
5. Try Cellpose
6. Try Unet++ w/ different backbones.
7. Look into stain transforms
8. create a nb to plot all images at the same place
9. create NB to inference one or many images with all the model weights.
10. Apply `TTA`


## TODOs:
- [X] Fix Training loop [deadline: 22/07/22] [done: 23/07]
- [x] Train on image patches [deadline: 24/07]
- [x] Check Dice score implimentation from [here](https://www.kaggle.com/code/p4rallax/hubmap-hpa-pytorch-baseline-w-tiles-stratifiedkf)
- [x] Train MMseg on HuBMAP


## Random:
- virtual env at `/home/lakshita/somusan/hubmap_kaggle` of python 3.7.0

