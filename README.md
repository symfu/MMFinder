# MMFinder
一个美女图搜索引擎的demo。

## 环境
python3.7 + mongodb + SPTAG

## 数据准备
### 1. 准备数据
爬取MM图片数据，并筛选出带脸的图片来。
> 如果没有美女图片，可以去Google Drive下载，链接：https://drive.google.com/file/d/1shZ3gx9nHPHUgylsZIrvWliwCh9TucAo/view?usp=sharing。解压密码：nladuo。

### 2. 过滤图片
只选出带一个脸的美女图，然后放到mongo里面


## 特征工程
通过VGG-net对人脸图片特征提取，转换成dense-vector。
### 1. 下载VGG预训练模型
Google Drive：https://drive.google.com/file/d/1CPSeum3HpopfomUEK1gybeuIVoeJT_Eo/view?usp=sharing]
<br>
百度云链接:https://pan.baidu.com/s/1Dk40tW2lx1ezTda9IyIO9g  密码:0vc7
### 2. 使用VGG提取特征并构建数据集
```bash
cd build_model
python create_dataset.py
```


## 建立索引
### 1. 安装SPTAG



### 2. 对图片建立索引


## 运行demo
### 运行演示网站


### 查看结果


## Reference
- https://sefiks.com/2018/08/06/deep-face-recognition-with-keras/

## LICENSE
MIT
