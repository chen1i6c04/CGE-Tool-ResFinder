# SeqSero 使用說明

本說明介紹如何在 **Linux** 系統中使用 **SeqSero** 分析沙門氏菌株的血清型

## 開啟終端機

 1. 在空白處點擊右鍵，開啟右鍵選單
 2. 選擇 **在此處開啟終端機**

## 啟動程式

在終端機中輸入

```
seqsero_cmd.py [參數]

參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
	-m 依照要分析檔案的格式輸入 [1, 2, 3, 4]
	   1：pair-end reads, interleaved
	   2：pair-end reads, seperated
	   3：single-end reads
	   4：assembly
```
### 範例

```
seqsero_cmd.py -i infolder -o outfolder -m 4
```

### 注意事項

-   若要分析的檔案有兩個以上，請將檔案彙整為一個資料夾，在 ``-i`` 輸入資料夾路徑
-   複製資料夾並在終端機中貼上，即可獲得**資料夾路徑**
-   終端機不接受鍵盤快捷鍵指令，請使用滑鼠貼上

# 分析結果

1. 所有檔案的分析結果會彙整為文件`total_report.csv`，儲存在輸出的資料夾下
2. 在輸出資料夾裡，有以各個檔案為名的資料夾，內有詳細的結果報告
<!--stackedit_data:
eyJoaXN0b3J5IjpbODk1NjE4MTEyLC0xOTEzMTg0NDM3LDc5NT
Q1OTE2NV19
-->