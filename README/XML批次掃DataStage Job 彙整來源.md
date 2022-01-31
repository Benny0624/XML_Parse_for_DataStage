**XML批次掃DataStage Job 彙整來源/目的檔**

1. 批次Export XML

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.001.png)

2. 上傳XML至Python Server(使用Jupyter notebook “Upload” 功能)

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.002.png)

3. 以Jupyter notebook執行XML\_V3.py，輸入XML檔名(不含.xml)

ENV : ![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.003.png)

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.004.png)

4. 輸入以辦行逗號分隔之Pjob清單，或輸入 \* ，代表全部的Job都要跑

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.005.png)

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.006.png)



5. 結束搜尋並輸出結果csv (XML檔名+Result\_out.csv)

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.007.png)

- TD

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.008.png)

- DB2

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.009.png)

- EDB

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.010.png)

- TXT

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.011.png)

1. 將Export 出來之結果csv檔Import 進測試TD之**DP\_CXL\_SCRDB.DATASTAGE\_JOB\_SOURCE** 

![](Aspose.Words.2a3ca779-164d-4574-bbdf-8cc94578a5cc.012.png)

6. 從本機取出檔案彙整使用
