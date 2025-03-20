# Condition-Monitoring-of-Rotating-Machinery
Condition Monitoring of Industrial Rotating Machinery

2022"Mobile Cloud Cup"Computing Power Network Application Innovation Competition(Industry Track)

Industrial Edge Cloud Application-Condition Monitoring of Industrial Rotating Machinery Data Set


• Competition Topic:Condition Monitoring of Industrial Rotating Machinery


• Background:In the process of modern industrial development,rotating machinery equipment accounts for more than 80%of the total amount of mechanical equipment.It mainly includes gearboxes,generators,blowers,and other common mechanical equipment in the wind power and petrochemical industries.These rotating devices rotate at high speeds and possess significant kinetic energy.Rotor component detachment can pose a huge threat to the safe operation of equipment.Once a mechanical device fails,it not only damages the equipment but also leads to a decline in product quality and production line efficiency.In severe cases,it may even cause major accidents,resulting in incalculable economic losses and even casualties.Supervising and analyzing equipment based on industrial big data,improving the self-inspection and self-diagnosis capabilities of rotating equipment,and building an intelligent fault diagnosis system for intelligent operation and maintenance management can effectively reduce equipment maintenance costs and enhance the safety and reliability of equipment.This,in turn,promotes the high-quality development of intelligent manufacturing.

However,in real production processes,the working conditions are highly variable,the equipment environment is complex,and there is a lack of effective case studies.It is extremely challenging to obtain sufficient data with accurate labeling information.These factors pose significant challenges to the construction of models.Therefore,it is of great significance to build effective transfer learning model strategies by fully considering the complex and variable working conditions,based on the limited labeling information currently available.


• Competition Task:

The aim of this competition is to develop an equipment fault analysis algorithm that can analyze and diagnose faults using vibration data collected from vibration sensors on the device side.The goal is to achieve fault diagnosis and analysis across different working conditions and even across different devices,thereby assisting in the arrangement of maintenance strategies in real production processes.

1)Data Set Introduction

A.Training Set:

The training set consists of continuous vibration waveforms from real equipment,covering eight common status types,including normal status,inner race fault,outer race fault,etc.The training folder contains two subfolders:labeled and unlabeled.The labeled folder includes eight types of status clearly labeled with numbers 0 to 7(each subfolder represents a specific status).Each type of fault contains 500 samples(provided in txt format),and each sample includes 4096 data points.Meanwhile,the unlabeled folder contains 2000 continuous vibration waveforms from different working conditions or different devices,with the same sample storage format as above.

Data Link:The file"Rotating_Machinery_Data_version.zip"is shared via a cloud storage link:[Baidu Cloud](https://pan.baidu.com/s/1MWw7hWM9uGpUmOMvMksdcA?pwd=d4zt)



工业旋转机械设备健康状态检测


2022年“移动云杯”算力网络应用创新大赛（行业赛道）
工业边缘云应用-工业旋转机械设备健康状态检测专题数据集

1、赛题名称：工业旋转机械设备健康状态检测
2、赛题背景：在现代工业发展的过程中， 旋转机械设备大约占据机械设备总量的 80%以上，主要包含变速箱、发电机、鼓风机等风电、石化行业中常见机械设备。旋转设备高速旋转、动能巨大，转子部件脱落故障给设备安全运行带来巨大威胁。一旦机械设备出现故障，在使得设备受损的同时，也会导致产品的质量以及生产线的流程效率下降，甚至会引发重大事故，带来不可估量的经济损失甚至是人员伤亡。基于工业大数据对设备进行监督与故障分析，完善旋转设备自检与自诊断能力，构建旋转设备智能故障诊断体系的智能运维管理，推动智能制造高质量发展，能够有效减少设备维护费用，提高设备的安全性和可靠性。

然而在现实生产过程中，工况多变、设备环境复杂、有效案例缺失，获取充足的并且带有准确标签信息的数据十分困难，种种因素给模型的构建带来巨大的挑战。因此，利用当前有限的标签信息，充分考虑复杂多变的工况条件，构建有效的迁移模型策略具有十分重要的意义。

3、赛题任务：

本赛题旨在开发一套设备故障分析算法，借由端侧振动传感器传回的振动数据进行算法分析诊断，实现跨工况甚至跨设备的设备故障诊断分析任务，助力实现现实生产过程中维修策略安排。

1）数据集介绍

A.训练集：

来自真实设备的连续运行的振动波形，数据涵盖了正常状态、内圈故障、外圈故障等八种常见的状态类型。在training文件夹中包含labeled以及unlabeled两个子文件夹。其中，labeled文件包含明确标注的八种状态类型，以数值0至7进行标注（每个子文件夹代表某种状态），每类故障中包含500个样本（样本以txt格式提供），同时每个样本中包括4096个数据点。同时，unlabeled文件包含2000条来自不同工况或不同设备的连续运行的振动波形，样本存储格式同上。


网址：https://ecloud.10086.cn/api/query/developer/user/home.html?ticket=ST-7179-Jhem0Myd4NmqdlwEK4He-cas01.example.org#/api/query/developer/match/matchDetails.html?id=6488d309ce3542f7a32b02e36054a473

datalink:  通过网盘分享的文件：Rotating_Machinery_Data_version.zip
链接: https://pan.baidu.com/s/1MWw7hWM9uGpUmOMvMksdcA?pwd=d4zt 提取码: d4zt
