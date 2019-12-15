```python
str = "Hello there dudes"
```


```python
str.split(" ")
```




    ['Hello', 'there', 'dudes']




```python
fib1 = [1,1,2,3,5,8,13]
```


```python
fib1
```




    [1, 1, 2, 3, 5, 8, 13]




```python
fib1[2]
```




    2




```python
fib1[3]
```




    3




```python
fib1[-1]
```




    13




```python
fib1[-3]
```




    5




```python
fib1[0:4]
```




    [1, 1, 2, 3]




```python
fib2 = [21,34,55]
```


```python
fib1+fib2
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]




```python
fib2+fib1
```




    [21, 34, 55, 1, 1, 2, 3, 5, 8, 13]




```python
fib1[0] = 9
```


```python
fib1
```




    [9, 1, 2, 3, 5, 8, 13]




```python
fib1[0] = 1
```


```python
fib1
```




    [1, 1, 2, 3, 5, 8, 13]




```python
fib = fib1 + fib2
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]




```python
fib.append(89)
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]




```python
fib.pop()
```




    89




```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]




```python
fib.append(89)
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]




```python
fib.remove(89)
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]




```python
fib.append(89)
fib.append(89)
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 89]




```python
fib.remove(89)
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89]




```python
del(fib[10])
```


```python
fib
```




    [1, 1, 2, 3, 5, 8, 13, 21, 34, 55]




```python
del(fib[3])
```


```python
fib
```




    [1, 1, 2, 5, 8, 13, 21, 34, 55]




```python
cars = ['mario','luigi','bowser']
```


```python
cars
```




    ['mario', 'luigi', 'bowser']




```python
cars.append(5)
```


```python
cars
```




    ['mario', 'luigi', 'bowser', 5]




```python
nums = [cars,fib1,[1,2,3,4,5]]
```


```python
nums
```




    [['mario', 'luigi', 'bowser', 5], [1, 1, 2, 3, 5, 8, 13], [1, 2, 3, 4, 5]]




```python
nums[0]
```




    ['mario', 'luigi', 'bowser', 5]




```python
nums[1]
```




    [1, 1, 2, 3, 5, 8, 13]




```python
nums[2]
```




    [1, 2, 3, 4, 5]




```python
nums[0][1]
```




    'luigi'




```python

```
