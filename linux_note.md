## 常用一般指令
`$ ls` 
列出所有檔案與資料夾

`$ ls -l`
詳細資訊

`$ ls -a`
顯示隱藏檔案

`$ ls -S`
依照檔案大小排序

`$ ls -d`
只列出目錄

`$ ls -F`
顯示檔案類型
`@`:連結檔
`*`:可執行檔
`/`:目錄

`$ tree`
列出檔案架構樹狀圖

-rw-r--r--
權限標示


## log操作指令
`$ cat filename`
顯示檔案內容

`$ head filename`
顯示檔案內容前幾行

`$ tail filename`
顯示檔案內容最後幾行

`$ wc [option] filename`
列出檔案的行數、單字數、位元組數

**[options]**
-c：--bytes 顯示位元數統計。 
-m：--chars 顯示字母數統計。 
-l：--lines 顯示行數統計。 
-L：--max-line-length 印出最長一行的字數。 
-w：--words 顯示單字數(word)統計。 


### .gz操作
`$ gzip FileName` 
壓縮

`$ gunzip FileName.gz` 
解壓縮

`$ zcat FileName` 
不壓縮直接讀取檔案




