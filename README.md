# Домашнее задание к занятию "Zabbix Part 1" - Знаменский Андрей

### Содержание файлов домашнего задания

   1. Файл Task1.md содержит выполненное задание №1 
   2. Файл Task2.md содержит выполненное задание №2
   3. Папка img/ содержит скриншоты выполненных заданий 

---

**TASK1** 

1. Создан новый публичный репозиторий `"Zabbix_learning_1"` и `README.md` файл.
2. Репозиторий склонирован на Git, используя https протокол git clone

`git clone https://github.com/AndrewZnamenskiy/Zabbix_learning_1.git`

3. Перейдите в каталог с клоном репозитория

`cd  Zabbix_learning_1/`

4. Произведите первоначальную настройку Git, указав своё настоящее имя и email:

```
andy@ub-net-1:~/github/LearningRepo$ git config --global user.name "AndrewZnamenskiy"
andy@ub-net-1:~/github/LearningRepo$ git config --global user.email andrewgold2006@yandex.ru
```

5. Используя nano README.md добавлено: 

*Домашнее задание к занятию "Zabbix Part 1" - Знаменский Андрей*

Скриншот решения заданий 1:

![Commit Task1](https://github.com/AndrewZnamenskiy/Zabbix_learning_1/blob/main/img/task1p1.png)

6. Переведём файл в состояние staged, командой `git add .`

7. Теперь можно сделать коммит `git commit -m 'Added tasks solution'`

8. Выполняем `git push origin main`


**TASK2**

1. Приложите в файл README.md скриншот раздела Configuration > Hosts, где видно, что агенты подключены к серверу

![Hosts screen](https://github.com/AndrewZnamenskiy/Zabbix_learning_1/blob/main/img/task2p1.png)

2. Приложите в файл README.md скриншот лога zabbix agent, где видно, что он работает с сервером

![Agent host1 log](https://github.com/AndrewZnamenskiy/Zabbix_learning_1/blob/main/img/task2p2.png)

![Agent host2 log](https://github.com/AndrewZnamenskiy/Zabbix_learning_1/blob/main/img/task2p3.png)

3. Приложите в файл README.md скриншот раздела Monitoring > Latest data для обоих хостов, где видны поступающие от агентов данные.

![Monitoring host1](https://github.com/AndrewZnamenskiy/Zabbix_learning_1/blob/main/img/task2p4.png)

![Monitoring host2](https://github.com/AndrewZnamenskiy/Zabbix_learning_1/blob/main/img/task2p5.png)

4. Приложите в файл README.md текст использованных команд в GitHub

```

git add .

git commit -m 'Added tasks solution'

git push origin main

```
