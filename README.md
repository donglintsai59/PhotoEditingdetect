# PhotoEditingdetect

## Introduction
Program for detecting image modifications.

The detection principle behind it is derived from the implementation of ['Analyzing Benford’s Law’s Powerful Applications in Image Forensics'](https://www.mdpi.com/2076-3417/11/23/11482) paper.


## Example

![image](https://github.com/donglintsai59/PhotoEditingdetect/blob/main/Photo/dec.jpg)

## Analyze

If the detected editing degree value n exceeds 0.7, it can be recognized as edited.
Note: This is based on experiments from the reference paper, where different n values were obtained from the same brightness channel data, and an n value of 0.7 yielded the best accuracy.
## 簡介

這是一個 檢測修圖程度的程式

檢測原理來自於這篇論文 ['Analyzing Benford’s Law’s Powerful Applications in Image Forensics'](https://www.mdpi.com/2076-3417/11/23/11482)


## 範例

![image](https://github.com/donglintsai59/PhotoEditingdetect/blob/main/Photo/dec.jpg)

## 分析

如果檢測到的修圖程度數值n超過 0.7，可以認定為有修圖。

PS.因為參考論文中針對相同亮度通道數據實驗得到不同n值而在n=0.7時有最佳的準確度


