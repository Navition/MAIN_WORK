==in== -  позволяет проверить, что одна строка находится внутри другой

```python
s = 'https://pygen.ru/' 
if 'a' in s: 
	print('Введенная строка содержит символ а') 
else: 
	print('Введенная строка не содержит символ а')
```

```python
s = input()
if '.' not in s:
    print('Введенная строка не содержит символа точки')
```

```python
print('ab' in 'abc') 
print('ac' in 'abc')

выводит:
True 
False
```
