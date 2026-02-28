## **Синтаксис**
![[Pasted image 20250416200100.png]]
```python
has_seven = False # сигнальная метка
```

```python
while True: 
	print('Python is awesome!')
```

```python
k = 10
while k > 5:
    print(k)
    k -= 1
```
![[Pasted image 20250416200736.png]]
## **continue**

```python
i = 2
while i < 8:
    i += 1
    if i == 5:
        print("пропустим 5")
        continue
    print(i)
```
3
4
пропустим 5
6
7
8

## **break**

```python
i = 2
while i < 8:
    i += 1
    if i == 5:
        print("пропустим 5")
        break
    print(i)
```


