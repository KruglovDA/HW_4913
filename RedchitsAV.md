# Редчиц А.В.
# Инстуркция по командам Git и markdown
GitHub ­ это сервис для хранения репозиториев.
1) Создание с git init(Добавляем папку Git и создаём репозиторий), 

2) Git add - файл через Tab, то есть добавляем нужный, 

3) Git commit -m "комментарий по коммиту"

4) git log - отслеживаем изменения по каждой ветке отедельно, + отображается мастер ветка

5) Создаём ветку - git branch "название"

6) git checkout - меняем ветку(наименование ветки) или версию(первые 4 цифры)

## Базовые операции
1. Создание локальной копии главного репозитория -  git clone https://github.com/.../...

2. Добавление новых файлов в репозиторий:
- git add name
- git commit ­m "My first commit" 

3. Отправка изменений в главный репозиторий
- git push

4. Получение изменений из главного репозитория
- git pull

## Итоговая сводка команд 
1. Создание локальной копии главного репозитория: 
    git clone https://github.com/.../...
    
2. Добавление новых файлов в репозиторий. 
Избранные файлы: 
    git add file1 file2 file3
Все новые файлы: 
    git add .
3. Сохранение изменений файлов: 
    git commit ­am "commit description" 
4. Получение изменений из главного репозитория: 
    git pull
5. Отправка изменений в главный репозиторий (с авторазрешением конфликтов): 
git pull (проверить на наличие новых изменений в репозитории и, если                  
они есть, выкачать их и объединить с локальными изменениями)
    git push  (отправить изменения в репозиторий)

## Работа с изображениями 
Чтобы вставить изображение в текст, нужно написать: 

![Привет, ветка мастер](images.jfif)


