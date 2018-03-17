# ResFinder 使用手冊

本手冊介紹如何在 **Linux** 系統中使用 **ResFinder** 分析菌株的抗藥性基因

## 開啟終端機

 1. 進入程式所在的資料夾中
 2. 在資料夾的空白處點擊右鍵，開啟右鍵選單
 3. 選擇 **在此處開啟終端機**

## 啟動程式
在終端機中輸入
```
python3 resfinder_cmd.py [設定參數]

設定參數：
	-i 輸入文件的路徑
	-o 分析結果的儲存路徑
	-k 最小相似百分比，預設為95
	-l 最小重疊長度百分比，預設為60
``` 
範例
```
python3 resfinder_cmd.py -i path
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MzU5MDMyMTQsMTg2ODM2MjkwMywtMz
g3NzkzNTQxXX0=
-->