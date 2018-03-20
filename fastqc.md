# FastQC 使用說明

本說明介紹如何在 **Linux** 系統中使用 **FastQC** 分析菌株的抗藥性基因

## 開啟終端機

 1. 在資料夾的空白處點擊右鍵，開啟右鍵選單
 2. 選擇 **在此處開啟終端機**

## 啟動程式

在終端機中輸入

```
fastqc_cmd.py [設定參數]

設定參數：
	-i 檔案路徑
	-o 分析結果的儲存路徑
``` 

### 範例

```
fastqc_cmd.py -i folder_of_file -o outfolder
```

### 注意事項

請將要分析的檔案放在同一個資料夾下，在參數``-i``輸入**資料夾路徑**
<!--stackedit_data:
eyJoaXN0b3J5IjpbNjEyMjgyMDg4LDY1ODg4OTk1OF19
-->