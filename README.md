# 铸造浇注机器人数据集 README  

## 一、数据集简介  
本数据集为铸造浇注机器人相关的目标检测数据集，包含浇注场景下的机器人浇注孔目标的图像及标注信息。数据集可用于训练和评估机器人视觉系统中的目标检测算法，尤其适用于模型在铸造浇注工业场景中的应用研究。  


## 二、数据集结构  
```
casting_pouring_robot_dataset/
│  
├── data/          # 图像文件夹  
│  
├── ann/           # 标注文件夹（voc格式xml文件）  
│  
├── txt/           # 标注文件夹（YOLO格式 txt 文件）  
└── README.md      # 数据集说明文档  
```  


## 三、类别说明  
| 类别编号 | 类别名称               | 说明                          |  
|----------|------------------------|-------------------------------|  
| 0        | pouring_hole           | 浇注孔                  |  



## 四、数据规模  
- **总图像数量**：2000+ 张  
- **训练集**：自行划分  
- **验证集**：自行划分  
- **测试集**：自行划分  



## 五、引用要求  
若使用本数据集进行研究或开发，请在你的论文、报告或项目中引用以下文献：  


### 文献 1  
```
@article{zhao2023lpo,  
  title={LPO-YOLOv5s: A Lightweight Pouring Robots Object Detection Algorithm},  
  author={Zhao, K. and Xie, B. and Miao, X. and Xia, J.},  
  journal={Sensors},  
  volume={23},  
  number={14},  
  pages={6399},  
  year={2023},  
  doi={10.3390/s23146399}  
}  
```  


### 文献 2  
```
@article{zhao2024cp,  
  title={CP-RDM: A new object detection algorithm for casting and pouring robots},  
  author={Zhao, K. and Miao, X. and Xia, J. and Li, J.},  
  journal={Measurement Science and Technology},  
  volume={35},  
  number={12},  
  pages={126009},  
  year={2024},  
  doi={10.1088/1361-6501/ad76c6}  
}  
```  





## 六、版权声明  
本数据集仅供科研和学术用途，商业使用需获得版权方授权。未经允许，请勿擅自传播或用于商业目的。  

---  
