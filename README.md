# TF_Function_Note
Note of Tensorflow function

- [tf.cast](https://github.com/Robin-Huang/TF_Function_Note/new/master?readme=1#tfcastx-dtype-namenone)
- [tf.reduce_mean](https://github.com/Robin-Huang/TF_Function_Note/new/master?readme=1#tfreduce_mean)

## tf.cast
改變張量元素的資料型態
### 參數
- **`x`**
 : 一個 Tensor 或 Sparse Tensor<br>

- **`dtype`**
 : 目標類型<br>

- **`name`** *(=None)*
: 操作的名稱<br>

### 回傳
- 與 **`x`** 大小一致的 Tensor 或 Sparse Tensor<br>

## tf.reduce_mean
計算某張量維度上的元素平均值
### 參數
- **`input_tensor`**
 : 欲降維的張量。應為數值型態 <br>
 
- **`axis`** *(=None)*
 : 欲降的維度。若為 `None` (default)，則對所有維度降維。輸入範圍必須在 `[-rank(input_tensor), rank(input_tensor)]`<br>
 
- **`keep_dims`** *(=False)*
 : <br>
 
- **`name`** *(=None)* 
 : <br>
 
- **`reduction_indices`** *(=None)*
: <br>
