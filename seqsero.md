# SeqSero 使用說明

本說明介紹如何在 **Linux** 系統中使用 **SeqSero** 分析沙門氏菌株的血清型

## 開啟終端機

 1. 進入程式所在的資料夾中
 2. 在資料夾的空白處點擊右鍵，開啟右鍵選單
 3. 選擇 **在此處開啟終端機**

## 啟動程式
在終端機中輸入
```
python3 resfinder_cmd.py [參數]

參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
	-m 依照分析檔案格式輸入 [1, 2, 3, 4]
	   1 pair-end reads, interleaved
	   2 pair-end reads, seperated
	   3 single-end reads
	   4 assembly
```
### 範例

<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA2Nzg5OTQyNSw3OTU0NTkxNjVdfQ==
-->