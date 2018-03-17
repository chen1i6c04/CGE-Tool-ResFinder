# FastQC 使用說明

本說明介紹如何在 **Linux** 系統中使用 **FastQC** 分析菌株的抗藥性基因

## 開啟終端機

 1. 進入程式所在的資料夾中
 2. 在資料夾的空白處點擊右鍵，開啟右鍵選單
 3. 選擇 **在此處開啟終端機**

## 啟動程式
在終端機中輸入
```
python3 fastqc.py [設定參數]

設定參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
``` 
### 範例
```
python3 fastqc.py -i folder_of_file -o outfolder
```
### 注意事項

請將 fastq 檔案彙整為一個**資料夾**，輸入**資料夾路徑**

<!--stackedit_data:
eyJoaXN0b3J5IjpbNjU4ODg5OTU4XX0=
-->