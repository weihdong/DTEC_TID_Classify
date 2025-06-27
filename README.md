# 典型平面波记录

### 背景
内容旨在从日本NICT提供的全球DTEC（去趋势总电子含量）历史图像中，筛选出具有典型平面波特征的行进式电离层扰动（Traveling Ionospheric Disturbances, TID）事件，以供后续的研究使用
![典型的平面波TID特征示例](https://img.085410.xyz/2025/06/9150862ef7fe9dfb22ebb04e1b05c7d4.jpg)

### 文件结构
```
Classified/
├── JAPAN/
│    ├── classified_2017/
│    ├── classified_2016/
│    └── ...
├── EUROPE/
│    ├── classified_2017/
│    ├── classified_2016/
│    │    ├── 20160216_142000_Hmap.jpg
│    │    └── ...
│    └── ...
└── USA/
     ├── classified_2017/
     ├── classified_2016/
     └── ...
```

### 说明
* 数据来源：Data provided by the National Institute of Information and Communications Technology ([NICT](https://aer-nc-web.nict.go.jp/GPS/DRAWING-TEC/tec_index.html)), Japan.
* 筛选区域：[欧洲](https://aer-nc-web.nict.go.jp/GPS/EUROPE/MAP/)、[美国南部](https://aer-nc-web.nict.go.jp/GPS/N_AMRC/MAP/)、[日本](https://aer-nc-web.nict.go.jp/GPS/GEONET/MAP/)
* 筛选时间：2000-2017
* 筛选标准：图像中呈现出清晰、较规则的平面波TID特征

如需原始数据及模型，请联系[我](weihdong@hotmail.com)。

---
## 更新日志

### v1.0.0 - 2025-06-25
1. 典型平面波初筛
2. 数据源下载速率限制，部分年份的数据集覆盖尚不完整，待补全

### v1.0.3 - 2025-06-27
1. 更新

---
*June 25, 2025 | [weihao dong (董 玮豪)](weihdong@hotmail.com)* 