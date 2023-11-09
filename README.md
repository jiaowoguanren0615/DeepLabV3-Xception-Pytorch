# DeepLabV3-Xception-Pytorch
This is a warehouse for DeepLabV3-Xception-pytorch-model, can be used to train your segmentation datasets

## Precautions
### <1> DownLoad Datasets
Download VOC & COCO & CityScapes： 链接：https://pan.baidu.com/s/1fy0R6NJo0YanfD4n6kgCiw?pwd=0grl 提取码：0grl --来自百度网盘超级会员V3的分享

### <2> Train and evaluate model
Before training, you may need to enter the corresponding ___train_XXX.sh___ file to modify the ___batch_size, total number of training times, learning rate and other hyperparameters___. Note: When you start training with a shell script, do not directly modify the contents of the ___train.py___ file. The parameter size in the shell file should be modified directly. The path of the data set is modified in the ___mypath.py___ file.
