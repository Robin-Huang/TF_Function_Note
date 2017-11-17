# TF_Function_Note
Note of Tensorflow function

- [tf.cast](https://github.com/Robin-Huang/TF_Function_Note/blob/master/README.md#tfcast)
- [tf.reduce_mean](https://github.com/Robin-Huang/TF_Function_Note/blob/master/README.md#tfreduce_mean)
- [tf.reset_default_graph](https://github.com/Robin-Huang/TF_Function_Note/blob/master/README.md#tfreset_default_graph)

## tf.cast
改變張量元素的資料型態

|參數|功能|預設|
|---|---|---|
|**`x`**|一個 Tensor 或 Sparse Tensor||
|**`dtype`**|目標類型||
|**`name`**|操作的名稱|*None*|

### 回傳
- 與 **`x`** 大小一致的 Tensor 或 Sparse Tensor<br>

## tf.reduce_mean
計算某張量維度上的元素平均值

|參數|功能|預設|
|---|---|---|
|**`input_tensor`**|欲降維的張量(應為數值型態)||
|**`axis`**|欲降的維度。若為 **`None`** ，則對所有維度降維。輸入範圍必須在 **`[-rank(input_tensor), rank(input_tensor)]`**|*None*|
|**`keep_dims`**|若為 **`True`** ，則保留降維尺寸為1|*False*|
|**`name`**|操作的名稱|*None*|
|**`reduction_indices`**||*None*|

### 回傳
- 降維後的 Tensor

## tf.reset_default_graph
清除目前的圖型(Graph)並重設為預設圖型
