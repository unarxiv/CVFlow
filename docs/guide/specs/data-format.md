# Data Formats

When you are using CVPM for training, CVPM requires you to specify the file path of the training, validation and test dataset. In this chapter, we will introduct how the dataset should  be organized.

## Overall

You dataset is a zip file (Do not use .rar or other format since it's not free format). You can also use .7z file.

Inside the file, your dataset should looks like:

```
- train
    - img_0001.jpg (the filename )
    - img_0002.png 
- test
    - img_0001.jpg (仅为例子，具体文件名可根据实际情况修改)
    - img_0002.png
- label_map (如需要)
- annotations.json
```