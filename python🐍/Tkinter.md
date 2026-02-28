```python
# основные команды
from tkinter import *
root = Tk()                 # создание окна
root.title('Start Window')  # надпись на панели окна
root.geometry('500x500')    # размер окна
root['bg'] = 'purple'       # фон
root.mainloop()             # запуск окна (обязательная команда)
```

```python
# кнопка
btn = Button(root, bg = 'green', text = 'button', \
             fg = 'yellow',font = ('Arial', 15), activebackground='white')
btn.pack()
```

```python
# текстовое поле
lbl = Label(root, bg = 'black', fg='white', text = 'button', font = ('Arial', 15))
lbl.pack()
```


