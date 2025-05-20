# class-to-image generation finetuning

基於前面的 cfg 以及 ddim 訓練模型，為資料集新增了顏色標籤。

並基於顏色標籤訓練，約束生成結果的顏色。

新的標籤為 $\[n_0,n_1,\cdots,n_4,c_0,c_1,\cdots,c_6\]$，n 為類別，c 為顏色。

今晚修改之後會再跑一次完整的結果
