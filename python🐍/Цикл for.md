![[Pasted image 20250416194336.png]]
```python
for i in range(5):
    i += 1
    print(f'{i} Hello, world')
```
## **range**
## Примеры использования функции range()
![[Pasted image 20250416194821.png]]

```python
вызов функции `range(1, 10, 2)` создаст последовательность чисел `1, 3, 5, 7, 9`
```

```python
for i in range(100, 1000): # перебираем числа от 100 до 999 
if i % 10 == 7: # используем остаток от деления на 10, для получения последней цифры 
	print(i)	
```

```python
print(range(10))
```

**range(a, b, c)  
a - начало  
b - конец  -1  
c - шаг**

```python
print(list(list(range(3, 16))))
```
[3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15]
```python
print(list(list(range(3, 16, 3))))
```
[3, 6, 9, 12, 15]
```python
for a in range(4, 9, 2):
    print(a)
```

## **Поэлементный перебор**

```python
ingr = ['cheese', 'bread', 'salat', 'tomato', 'meal']
st = 'iovzjfekskndjdflkv'
for c in ingr:
    print(c)
```

```python
ingr = {'cheese' : 2, 'bread' : 2, 'salat' : 3, 'tomato' : 4, 'meal' : 1}
for c in ingr:
    print(c)
```

```python
ingr = {'cheese' : 2, 'bread' : 2, 'salat' : 3, 'tomato' : 4, 'meal' : 1}
for c, l in ingr.items():
    print(c, l)
```

## **Списочные выражения**

```python
lst = [k**2 for k in range(10)]
print(lst)
```

## **Вложенный цикл**

```python
dc = {"hp" : 10, "exp" : 5}
lvls = ["lvl1", "lvl2"]
for x in lvls:
    print(x)
    for j in dc:
        dc[j] += 10
        print(f'{j} : {dc[j]}')
```


