# LR6
Лабораторная работа №6

Отчёт по Лабораторной работе №6

Тема: Система контроля версий

Цель: Изучение базовых возможностей системы управления версиями, работа с Git API, локальным и удалённым репозиторием.

1. Создан аккаунт на GitHub.
2. Сделана копия (Fork) репозитория с исходного репозитория по адресу: (https://github.com/Kurtyanik/LR6).
3. Установлен Git с официального сайта.
4. Настроен Git, добавлено имя пользователя и email:

```
git config --global user.name "В3441 Фирстова Анастасия Денисовна"
git config --global user.email "firstova03102005@gmail.com"
```

![image](https://github.com/user-attachments/assets/e1ef8bdf-1c99-4abe-99f8-663e487c0418)

5. Личный удалённый репозиторий был клонирован на компьютер:

```
git clone https://github.com/anastasiyafirstov/dLR6
```

![image](https://github.com/user-attachments/assets/a2af5f01-c4a1-4e76-9846-b2a1759e5503)


6. Новый файл был добавлен через интерфейс GitHub, изменения подтянуты в локальный репозиторий:

```
git pull
```

![image](https://github.com/user-attachments/assets/cd8639d2-9416-4b7c-993a-e1541bc634bd)


7. Получена история операций для каждой из веток:

```
git log --oneline
```

![image](https://github.com/user-attachments/assets/17076a60-1956-446a-923b-2a03ba290492)


8. Последние изменения просмотрены с помощью команды (изменений много, в качестве примера предоставила один скриншот):

```
git log -p 
```

![image](https://github.com/user-attachments/assets/aed57671-68c6-4b76-a632-0aa4227067f6)


9. Ветка с изменениями была слита в ветку master:

```
git checkout -b branchone
git add .
git commit -m "Изменение файла 1"
git checkout master
git merge branchone
```

![image](https://github.com/user-attachments/assets/38f3414b-5d0c-42cc-a542-e3958480bc9d)
![image](https://github.com/user-attachments/assets/56e9d11d-f951-4333-9bf8-7e74be636a03)



10. Побочная ветка удалена после успешного слияния:

```
git branch -d new_branch
```

![image](https://github.com/user-attachments/assets/b1e8431c-31ff-49d5-b161-906479c0a941)


11. Сделаны несколько изменений и зафиксированы с комментариями:

```git add .
git commit -m "Изменение файла 2"
```

![image](https://github.com/user-attachments/assets/b161107a-5dd1-4cf9-a141-912a6f26a335)

```git add .
git commit -m "Изменение файла 3"
```

![image](https://github.com/user-attachments/assets/c689235d-a0fd-4700-b915-060e981e1c3d)

12. Выбран нужный коммит, выполнен откат:
13. Создана отдельная ветка для оформления отчёта:
14. Отчёт оформлен в файле README.md с использованием markdown синтаксиса, cкриншоты консоли и сторонних программ добавлены в отдельную папку screen.
15. Получена история операций с сокращённым хэшем, датой, именем автора и комментарием:
16. Локальные изменения отправлены в удалённый репозиторий на GitHub:

Вывод:

В процессе данной лабораторной работы я освоила базовые команды и операции в Git, включая commit, merge, checkout, pull, push, а также управление ветками и разрешение конфликтов. Получила опыт синхронизации локального и удаленного репозиториев на GitHub и создания отчетов при помощи Markdown.
