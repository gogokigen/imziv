# 測試儀器自動化程式設計的工作

幾年打雜下來, 對於控一些有的沒的, 有一些心得\
經驗上, python 接受度很高\
所以後來都是提供python 作為自動化的基礎

&#x20;

通訊方面, 打通以下就差不多了\
GPIP   :  PyVISA\
Serial :  Pyserial\
TCP    :  內建

&#x20;

難免要跟其他 programming language 接\
QCT MTK 都提供C DLL, 那就得用 Ctypes 去接\
如果是C# DLL, 就 Python.NET 去接

&#x20;

如果是控IC, 那學個 arduino 是很好的\
arduino 有 GPIO, 設計個 簡單protocol ,\
走serial 控 arduino 的 GPIO ,\
就可以簡單的作開機, 按鈕之類\
進階一點, I2C , SPI , I2S 也都是可以控的

&#x20;

如果要控android , 有python adb

&#x20;

要產出report , 就弄個csv 產出就好

&#x20;

如果不同品牌儀器, 類似功能, 但是GPIB cmd 不一樣\
那就開個 base object interface\
讓其他人可以繼承\
然後填自己要的GPIB cmd

&#x20;

總之,在目前全民學python氣氛下\
且python又不用錢\
是有機會讓 RF / EE / QA 直接寫python test case\
最符合自己需求, 不需要跨領域的溝通半天

&#x20;

寫完隨便找台電腦, 有空就下去跑壓力測試\
機器很累, 人比較輕鬆, 相當不錯



作者easyman (oops)\
看板Soft\_Job\
標題Re: \[請益] 測試儀器自動化程式設計的工作\
時間Mon Jan  4 22:31:09 2021

[https://www.ptt.cc/bbs/Soft\_Job/M.1609770671.A.B20.html](https://www.ptt.cc/bbs/Soft\_Job/M.1609770671.A.B20.html)
