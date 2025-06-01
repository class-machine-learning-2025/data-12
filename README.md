# data-12
## dataset for the assignment 12

### training dataset

- dimension: `(1000, 12, 12) (1000, 12, 12) (1000, 12, 12)`
- data type: `float32 float32 float32`

```python
data1_train  = np.load('data1_train.npy')
data2_train  = np.load('data2_train.npy')
data3_train  = np.load('data3_train.npy')
label1_train = np.load('label1_train.npy')
label2_train = np.load('label2_train.npy')
label3_train = np.load('label3_train.npy')
```

### testing dataset

- dimension: `(5000, 12, 12) (5000, 12, 12) (5000, 12, 12)`
- data type: `float32 float32 float32`

```python
data1_test  = np.load('data1_test.npy')
data2_test  = np.load('data2_test.npy')
data3_test  = np.load('data3_test.npy')
label1_test = np.load('label1_test.npy')
label2_test = np.load('label2_test.npy')
label3_test = np.load('label3_test.npy')
```
