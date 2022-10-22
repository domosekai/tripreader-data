# 绍兴市 Shaoxing

## 数据 Data

### 轨道交通（不含城际）

CU识别方式：18文件，终端号

TU识别方式：1E文件，线路和站点（1E导入前使用18文件，终端号识别）

数据文件：metro-tu.csv, metro-cu.csv, metro-1e-tu.csv

### 城际铁路

TU识别方式：1E文件，线路和站点（不写1E时使用18文件，终端号识别）

数据文件：train-tu.csv, metro-1e-tu.csv

## 备注 Remark

绍兴城际线对本地卡不写1E，异地卡1E的城市和收单代码写宁波。

## Changelog

Date | Change | Author
-----|--------|-------
2022.9 | 1号线1E | wchjia
2022.5 | 1号线主线终端号 | wchjia、大象
2021.9 | 城际终端号 | wchjia
2021.8 | 城际1E | Summer
2021.7 | 城际1E | RisingTank
2021.7 | 1号线 | wchjia
