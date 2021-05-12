# 第四屆語言分析黑客松 [插電場] - 測試語料與程序說明

## Task
這個題目涉及尼泊爾的千塘方言 (Chintang) ，修改自美國中學生計算語言學奧林匹亞競賽 NACLO ("A cat in a hat", [原始題目](https://www.nacloweb.org/resources/problems/2020/N2020-B.pdf) 與 [解答](https://www.nacloweb.org/resources/problems/2020/N2020-BS.pdf) )。

修改後的題目已存為 `input.csv`，內容是 23 句的千塘語（編號 1～23）和已亂序排列的英文翻譯（編號 a～w）。

**程式作業任務在於：對於千塘語和相應的英語翻譯做自動配對。**

#### notes
- 除了以上資料，本競賽還可以加上兩個提示給電腦: cuwa:'water'; chintaŋbe: 'Chintang'。  
- 除了千塘-英文字典，參賽者可以使用外部各種資源。


## input data：`input.csv`
輸入檔案之格式如下所示：


index_C | Chintang_in_IPA       | index_E  | English_translation 
--------|:---------------------:|---------:|------------------------
1       | cuwa uthurumbeʔ yuŋno | a        | There is a hole in the towel.
2       | appa chintaŋbeʔ yuŋno | b        | The woman has gone away.
3       | sencak sie	          | c        | The rice has been cooked.
4       | wapaŋa topi wadaŋse   | d        | There is a hat on the head.																						
...     | ...                   | ...      | ... 



## output：`output.txt `
請將輸出檔案命名為 output.txt ，檔案內容應如下所示：

```
1:b
2:f
3:p
...
```


## Process

- 即刻起即可開始程式解題，並將有詳細註解的程式碼，放在 https://github.com/Linghacks-NTU 一個自建的 repo。(請遵循名稱格式：teamName2021）
- 在 5/22 16:10 截止更新。
- 在 16:10 之後做 5 分鐘簡介演算法與展示。



## Evaluation
評測方式以正確率 (70%) 與演算創新與解釋力 (30%) 為評估標準。
