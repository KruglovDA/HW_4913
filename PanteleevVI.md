# Краткое руководство по работе с Git
## 1. Основные команды
* git init - инициализация локального репозитория
* git commit - создание коммита
## 2. Ветки
* git branch - выводит список веток
* git branch branch_name - содает ветку с именем branch_name
* git checkout branch_name - переход в другую ветку
* git merge branch_name - позволяет слить ветки
* git branch -d branch_name - удалить уже слитую ветку
* git branch -D branch_name - удалить ветку (даже не слитую)
## 3. Работа с удаленными репозиториями
* git clone - копировать внешний репозиторий на свой ПК
* git pull - эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией
* git push - эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ  на внешнем репозитории.
* pull request - команда для предложения изменений (GitHub)

### Как сделать pull request
1. Делаем fork (ответвление) репозитория
2. Делаем git clone СВОЕЙ версии репозитория 
3. Создаем новую ветку и в НЕЕ вносим свои изменения 
4. Фиксируем изменения (делаем коммиты) 
5. Отправляем свою версию в свой GitHub
6. На сайте GitHub нажимаем кнопку pull request