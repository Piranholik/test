![logo](Git-Logo-1788C.png)
# Работа c Git и GitHub

## 1. Проверка установленого Git 
### в терменале выполнитьь команду `git version`

Если Git установлен появится версия программы, иначе будет ощибка


## Установка Git 

Загружам с сайта https://git-scm.com/

Установливакм с настройка по умалчвнию 

## 3. Настройка Git 

При вервом использовании Git нужно представться 
```
git config --global user.name «Ваше имя английскими буквами»

git config --global user.email ваша почта@example.com
```


## 4. Инициализация репозитория
иницилизировать репозиторий можно:
1. в итерминале перейсти к папки, в которой хотим созжать репазиторий:  
`Git init`

в исхдеой папку появится скрытая папка *.git* 

2. Клонировать существующий Git из любого места.

`git clon <адрес репазитория>`

## 5. Запись изменения в репозиторий 

### нужно выпонить следуюшие действия 

```1. git add нование файла```

```2. git commit  -m "Коментарий"```

### существует объединенная команда

```git commit -am "Коментарий"```

## 6. Просмотер истории комитов

После того, как вы создали несколько коммитов или же клонировали репозиторий с уже существующей историей коммитов, вероятно вам понадобится возможность посмотреть что было сделано — историю коммитов. Одним из основных мощных инструментов для этого является команда ```git log.```

### **Продивнутая команда** 

 ```git log --oneline```

## 7.Перемещение между  версиями комитами 

для перемещение между комитами 

```git checkout << Указаваем номер комита  >>```

для возврата исмользуем команту  
```git checkout master```

## 8. Игнорирование файлов
Для того, чтобы исключить из отслеживания определённые файлы или папки необходимо создать там файл **.gitignore** и записать в него их названия или шаблоны, соответствующие таким файлам или папкам.

## 9. Создание веток в Git
По умолчанию имя основной ветки в Git - master
Создать ветку можно командой:
``git branch <имя новой ветки>``

Список веток в репозитории можно посмотреть с помощью команды git branch
Текущая ветка будет отмечена звёздочкой:
#**
master**

## 10. Слияние веток и разрешение конфликтов

Для слияния выбранной ветки с текущей нужно выполнить команду::::
```
git merge ‹название выбранной ветки>
```
Если была изменена одна и та же часть файла в обеих ветках, то может возникнуть конфликт, который потребует участия пользователя.
VSCode предлагает варианты разрешения.

## 10.

## 11.

## 12. 

## 13. 