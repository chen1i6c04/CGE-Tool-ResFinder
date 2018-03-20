# ResFinder 使用說明

本說明介紹如何在 Linux系統中使用ResFinder分析菌株的抗藥性基因

## 開啟終端機

 1. 進入程式所在的資料夾中
 2. 在資料夾的空白處點擊右鍵，開啟右鍵選單
 3. 選擇 **在此處開啟終端機**

## 使用方式
```
在終端機中輸入：
python3 resfinder_cmd.py [參數]

必要參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
	
可選參數：
	-k 最小相似百分比，預設為95
	-l 最小重疊長度百分比，預設為60
```

### 範例
```
python3 resfinder_cmd.py -i infolder -o outfolder -k 95 -l 60
```
### 注意事項

 - 若要分析的檔案有兩個以上，請將檔案彙整為一個**資料夾**，在 ``-i`` 輸入**資料夾路徑**
 - 若無設定參數 ``-k`` 和 ``-l`` 的值，則使用預設的數字為設定值
 - 複製資料夾並在終端機中貼上，即可獲得**資料夾路徑**
 - 終端機不接受快捷鍵指令，請使用滑鼠貼上

## 分析報告

 1. 所有檔案的分析結果會彙整為文件``total_report.csv``，儲存在輸出的資料夾下
 2. 在輸出資料夾裡，有以各個檔案為名的資料夾，內有詳細的結果報告




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwMzI1NzUxMDgsMjEyNDU1NDE4NCwtMT
AyMjM0OTY1NSwyNDYxOTI5NTAsLTQ4NTM1NDIxLDIwMTcyNzE2
NDgsLTE0NDc5MzAxNzEsLTE1MDE3MjIyNTMsLTIxMDEyMDk5Nz
ksLTExNjIyMDg3OTEsNDQ0MzcyMDU0LC0zMjgxMTMxOCw3NzAz
MzY3ODYsMTQ5NDY3MDU4MCwtNjE4MzE3NDYyLDU2MDQ1MzY1OS
wtMTM3MjAxODUzNywtMTIzNzk2NzEyOSwtODU3NTAxNjczLC0x
NDM0NTMzODY5LC0xNDQ1MTE4MzQ2LDExODgxODQ4MiwxMTgzNz
AyNTE4LDEyOTg2NTc1MjVdfQ==
-->