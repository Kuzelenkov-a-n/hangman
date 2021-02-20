## Игра "Виселица" (Ruby)

### Чтобы запустить программу:
##### 1. Скачайте все файлы и папки из репозитория в заранее созданную Вами папку на Вашем ПК (например ../hangman)
##### 2. Откройте терминал
##### 3. Укажите путь к папке с файлом main.rb (с помощью команды **cd**):
```cd /путь к папке с main.rb/```
##### 4. Запустите файл программы:
```ruby main.rb```

### Правила игры
##### - При запуске игры, **СЛОВО** загадывается автоматически
##### - Игрок вводит букву в попытке отгадать загаданное слово
##### - В случае если Игрок *не отгадал* букву, игра сообщает ему об этом выводя информацию о количестве допущенных и оставшихся ошибок
##### - Если Игрок *отгадал* букву, игра также информирует его, заменяя символ загаданной буквы "__" на отгаданную букву
##### - Игра продолжается до тех пор пока Игрок не отгадает слово или не проиграет, допустив 7 ошибок.

### Дополнения.
##### Вы можете самостоятельно добавить или удалить загадываемое **СЛОВО**!
##### Для этого Вам необходимо открыть файл: ```../hamgman/data/words.txt``` и добавить новое слово или удалить уже имеющееся

### **Важно!**
#### Новое слово пишется только БОЛЬШИМИ буквами на **НОВОЙ** строке, это необходимо для корректной работы программы!
