# ResFinder 使用說明

本說明介紹如何在 Linux系統中使用ResFinder分析菌株的抗藥性基因

## 連結網路磁碟

 1. 進入桌面上的「家目錄」
 2. 在左邊的側邊欄中，選擇「網路位置」
 3. 選擇 DS715，此時會出現要求輸入帳號與密碼的視窗
 4. 在使用者欄位輸入「centrallab」，密碼欄位輸入「24755118」
 5. 連線成功，可將要分析的檔案複製到Linux資料夾下

## 開啟終端機

 1. 進入程式所在的資料夾中
 2. 在資料夾的空白處點擊右鍵，開啟右鍵選單
 3. 選擇 **在此處開啟終端機**

## 啟動程式
### 使用方式
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
python3 resfinder_cmd.py -i test.fa -o outfolder -k 95 -l 60
```
### 注意事項

 1. 若要分析的檔案有兩個以上，請將檔案彙整為一個**資料夾**，在 ``-i`` 輸入**資料夾路徑**
 2. 若無設定參數 k 和 l 的值，則使用預設的數字為設定值

## 分析結果

 1. 所有檔案的分析結果會彙整為文件``Total_Report.csv``，儲存在輸出路徑的資料夾下
 2. 要檢視




<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwNzMzNDk5ODcsMTMwMzA0MzYwLDM0Mj
g2NzUyNywxNDA0MzkwNTU5LC0yMTg5MDc5MDQsMTQ5NDY3MDU4
MCwtNjE4MzE3NDYyLDU2MDQ1MzY1OSwtMTM3MjAxODUzNywtMT
IzNzk2NzEyOSwtODU3NTAxNjczLC0xNDM0NTMzODY5LC0xNDQ1
MTE4MzQ2LDExODgxODQ4MiwxMTgzNzAyNTE4LDEyOTg2NTc1Mj
VdfQ==
-->