# Лабораторная работа №6

## Цель лабораторной работы:
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 

## Ход выполнения работы:

1. Создать аккаунт на сайте GitHub.
2. Сделать копию в личное хранилище из
https://github.com/Kurtyanik/LR6/ (Fork). При создании форка нужно убрать флажок 'Copy the master branch only'
![Рисунок 1](/LR6_screen/Screenshot_1.png)
<p style="text-align: center;">Рисунок 1 - Создание собственной копии репозитория</p>

![Рисунок 2](/LR6_screen/Screenshot_2.png)
<p style="text-align: center;">Рисунок 2 - Настройки при создании форка</p>

3. Установить Git (https://git-scm.com/).
4. После установки настроить клиент git, введя имя пользователя (Группа
Фамилия И.О.) и email. Этими данными будет подписываться каждый коммит, который мы делаем локально.
![Рисунок 3](/LR6_screen/Screenshot_3.png)
<p style="text-align: center;">Рисунок 3 - Изменение имени и почты через консоль</p>

5. Клонировать свой личный удалённый репозиторий на компьютер.
![Рисунок 4](/LR6_screen/Screenshot_4.png)
<p style="text-align: center;">Рисунок 4 - Перенос репозитория из онлайна на ПК</p>

![Рисунок 5](/LR6_screen/Screenshot_5.png)
<p style="text-align: center;">Рисунок 5 - Репозиторий перенесен</p>

6. Добавить файл через интерфейс GitHub. Подтянуть изменения в
локальный репозиторий.
![Рисунок 6](/LR6_screen/Screenshot_6.png)
<p style="text-align: center;">Рисунок 6 - Добавление нового файла через сайт (Интерфейс GitHub)</p>

![Рисунок 7](/LR6_screen/Screenshot_7.png)
<p style="text-align: center;">Рисунок 7 - Пример файла</p>

![Рисунок 8](/LR6_screen/Screenshot_8.png)
<p style="text-align: center;">Рисунок 8 - Настройки коммита, который будет создан</p>

![Рисунок 9](/LR6_screen/Screenshot_9.png)
<p style="text-align: center;">Рисунок 9 - Готовый файл в онлайн репозитории</p>

![Рисунок 10](/LR6_screen/Screenshot_10.png)
<p style="text-align: center;">Рисунок 10 - Подтягиваются изменения, которые были сделаны онлайн</p>

7. Получить историю операций для каждой из веток.
![Рисунок 11](/LR6_screen/Screenshot_11.png)
<p style="text-align: center;">Рисунок 11 - Изменения по каждой ветке в виде графа</p>

8. Просмотреть последние изменения.
![Рисунок 12](/LR6_screen/Screenshot_12.png)
<p style="text-align: center;">Рисунок 12 - Просмотр последнего коммита</p>

9. Выполнить слияние в ветку master, разрешив конфликт (можно использовать специальные редакторы или графический интерфейс git).
![Рисунок 13](/LR6_screen/Screenshot_13.png)
<p style="text-align: center;">Рисунок 13 - Начало объединения веток</p>

![Рисунок 14](/LR6_screen/Screenshot_14.png)
<p style="text-align: center;">Рисунок 14 - Разрешение конфликта, выбор нужных изменений</p>

![Рисунок 15](/LR6_screen/Screenshot_15.png)
<p style="text-align: center;">Рисунок 15 - Создание слепка изменений</p>

![Рисунок 16](/LR6_screen/Screenshot_16.png)
<p style="text-align: center;">Рисунок 16 - Создание коммита с описанием</p>

10. Удалить побочную ветку после успешного слияния.
![Рисунок 17](/LR6_screen/Screenshot_17.png)
<p style="text-align: center;">Рисунок 17 - Удаление ненужной ветки</p>

11. Сделать изменения и зафиксировать их, оставляя комментарии,
несколько раз.
![Рисунок 18](/LR6_screen/Screenshot_18.png)
<p style="text-align: center;">Рисунок 18 - Добавление изменений (Это второе изменение)</p>

12. Сделать откат коммита.
![Рисунок 19](/LR6_screen/Screenshot_19.png)
<p style="text-align: center;">Рисунок 19 - Возврат изменений к предыдущему коммиту</p>

13. Создать ветку для отчёта.
![Рисунок 20](/LR6_screen/Screenshot_20.png)
<p style="text-align: center;">Рисунок 20 - Создание ветки для отчета</p>

14. Начать оформлять отчёт в файле README.md (разрешены сторонние
редакторы с подсветкой синтаксиса), используя markdown синтаксис
(https://guides.github.com/features/mastering-markdown/):
+ В отчёте должен быть снимки экрана консоли и сторонних программ.
Файлы снимков экрана разместить в отдельной папке.
+ Лог команд (без результатов их выполнения).
При написании отчёта периодически делать коммиты, не забывать
комментировать.
![Рисунок 21](/LR6_screen/Screenshot_21.png)
<p style="text-align: center;">Рисунок 21 - Как создается отчет</p>

15. Получить историю операций в форматированном виде (сокращённый
хэш + дата + имя автора + комментарий). Добавить её в отчёт и сделать
финальную фиксацию изменений.
16. Отправить локальные изменения в сетевое хранилище GitHub (если
делаете работу постепенно, то синхронизацию проводить в конце рабочего
сеанса) 