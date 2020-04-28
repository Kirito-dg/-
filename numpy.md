
# Python科学计算库Numpy

确保第一个事，咱们要用的库已经安装好了


```python
import numpy as np
```


```python
## list结构不能进行“+1”运算
```


```python
array = [1,2,3,4,5]
array + 1
```


    ---------------------------------------------------------------------------

    TypeError                                 Traceback (most recent call last)

    <ipython-input-3-1641d9f25aab> in <module>
          1 array = [1,2,3,4,5]
    ----> 2 array + 1
    

    TypeError: can only concatenate list (not "int") to list


  


```python
## 将变量转换为np.array结构
```


```python
array = np.array([1,2,3,4,5])
print (type(array))
```

    <class 'numpy.ndarray'>
    

    


```python
## 向量加法
```


```python
array2 = array + 1
array2
```




    array([2, 3, 4, 5, 6])




```python
array2 +array
```




    array([ 3,  5,  7,  9, 11])




```python

```


```python
## 向量乘法
```


```python
array2 * array
```




    array([ 2,  6, 12, 20, 30])




```python

```


```python
## 截取元素
```


```python
array[0]
```




    1




```python
array[3]
```




    4




```python
array[1:3]
```




    array([2, 3])




```python

```


```python
## shape值，数据的规模
```


```python
array
```




    array([1, 2, 3, 4, 5])




```python
array.shape
```




    (5,)




```python

```


```python
## list无shape值
```


```python
tang_list = [1,2,3,4,5]
tang_list.shape
```


    ---------------------------------------------------------------------------

    AttributeError                            Traceback (most recent call last)

    <ipython-input-19-c799f36c95f6> in <module>
          1 tang_list = [1,2,3,4,5]
    ----> 2 tang_list.shape
    

    AttributeError: 'list' object has no attribute 'shape'



```python

```


```python
## 二维数组，即矩阵
```


```python
np.array([[1,2,3],[4,5,6]])
```




    array([[1, 2, 3],
           [4, 5, 6]])




```python

```
