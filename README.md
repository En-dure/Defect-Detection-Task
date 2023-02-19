一、过程

1. 下载文件

2. ```python
   pip install -r requirements.txt
   ```

3. cd 文件目录

4. 终端输入：

- 训练：python train.py
- 测试：python val.py
- 检测：python detect.py



二、训练阶段文件

1. 路径：runs---train----epoch100_dice

2. 训练过程：tensorboard --logdir=runs （注：其中mdice_c为要求的dice coefficient指标）

   ./yolov5/runs/train/epoch100_dice/result.csv 里存有训练过程dice coefficient（mdice_c）

3. 最佳权重位置：./yolov5/runs/train/epoch100_dice/weights



三、test结果

![image-20230219155525047](https://user-images.githubusercontent.com/48682148/219937613-d3380fbd-5682-4a69-b279-4a22ea09a64c.png)

​		测试集的dice_coefficient为0.92

