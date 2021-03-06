# ResFinder 使用說明

本說明介紹如何在 Linux系統中使用ResFinder分析菌株的抗藥性基因

## 開啟終端機

 1. 在空白處點擊右鍵，開啟右鍵選單
 2. 選擇 **在此處開啟終端機**

## 使用方式
```
在終端機中輸入：
resfinder_cmd.py [參數]

必要參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
	
可選參數：
	-k 最小相似百分比，預設 95
	-l 最小重疊長度百分比，預設 60
```

### 範例
```
resfinder_cmd.py -i file.fa -o outfolder
```
```
resfinder_cmd.py -i infolder -o outfolder -k 95 -l 60
```
### 注意事項

 - 輸出資料夾需為空資料夾
 - 若要分析的檔案有兩個以上，請將檔案彙整為一個資料夾，在 ``-i`` 輸入資料夾路徑
 - 若無設定參數 ``-k`` 和 ``-l`` 的值，則使用預設的數字為設定值
 - 複製檔案或資料夾並在終端機中貼上，即可獲得檔案或資料夾的路徑
 - 終端機不接受快捷鍵指令，請使用滑鼠貼上

## 分析報告

 1. 所有檔案的分析結果會彙整為文件``total_report.csv``，儲存在輸出的資料夾下
 2. 在輸出資料夾裡，有以各個檔案為名的資料夾，內有詳細的結果報告




<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEzMDYyNzc2NSwyMTI0NTU0MTg0LC0xMD
IyMzQ5NjU1LDI0NjE5Mjk1MCwtNDg1MzU0MjEsMjAxNzI3MTY0
OCwtMTQ0NzkzMDE3MSwtMTUwMTcyMjI1MywtMjEwMTIwOTk3OS
wtMTE2MjIwODc5MSw0NDQzNzIwNTQsLTMyODExMzE4LDc3MDMz
Njc4NiwxNDk0NjcwNTgwLC02MTgzMTc0NjIsNTYwNDUzNjU5LC
0xMzcyMDE4NTM3LC0xMjM3OTY3MTI5LC04NTc1MDE2NzMsLTE0
MzQ1MzM4NjksLTE0NDUxMTgzNDYsMTE4ODE4NDgyLDExODM3MD
I1MTgsMTI5ODY1NzUyNV19
-->