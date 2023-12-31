# Предисловие  
Чтобы легко и качественно изучать git, прежде всего тебе потребуется ручка и тетрадь, потому что команд будет более 10 и, следовательно,  
запомнить их за 1 раз сразу не получится.  
## Азы   
В первую очередь, нужно скачать необхожимое по(следуя инструкции). Затем изучить базовые команды для навигации по файловой системе компьютера  
и использовать при этом командную строку.  
*Базовые команды*    
```
pwd  
cd  
ls  
```  
Затем необходимо научиться работаь с файлами  
```  
touch  
mkdir  
mv  
cat  
rm  
```  
Пройдя подготовительный этап важно понимать. Что git прежде всего изучают для работы в команде.  
Поэтому, научись обозначать себя, попадая в систему.  
Для этого используются команды  
```  
git config --global
git config --list
```  
### Работа с Git Hub  
Создаем папку и делаем ее репозиторием, чтобы потом связать с сайтом git hub.  
По сути ты связываешь домашний компьютер с удаленным сайтом, доступ к которому есть у всех.  
Это значително упрощает процесс обмена данными.  
```  
git init  
rm -rf .git  
git status  
```  
Когда папка создана и зарепозитирована, можем создавать файлы и смотреть как их правки отобразятся на сайте.  
Для этого используют следующие команды  
```
git add  
git commit -m  
git log  
git remote add  
git push -u origin master  
```  
Самое важное в изменениях это коммиты. В них ты описываешь то, что поменялось в коде.  
Удобно в своих папках-проектах хранить файл README.md  
В нем находится информация - описание твоего проекта. Это делает твой продукт  
более доступным для пользователей.  
*Успехов в изучении git!*