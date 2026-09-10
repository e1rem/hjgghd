Лабораторная работа №1
Тема: Введение в командную строку Linux. Навигация, управление файловой системой и 
работа с текстовыми редакторами.
Цель работы: Освоить базовые приёмы работы в командной оболочке Linux, изучить 
структуру файловой системы, научиться управлять файлами и каталогами, получить навыки 
работы с текстовыми редакторами nano и vi/vim (с акцентом на vi/vim как обязательный 
инструмент системного администратора), а также приобрести умение использовать 
справочную систему.
Выполнил: студент группы СА-1-25
Кораблев Антон


2.1.1 Запустите терминал. Проанализируйте строку приглашения
![src1](https://github.com/user-attachments/assets/da4c9338-2bbf-4944-ae3f-65757ddf9998)

2.1.2 Выполните history. Выполнил команду History
![src1](https://github.com/user-attachments/assets/ac5c1527-1c6e-496f-b88e-90d071a42a76)

2.1.3 Очистите экран (clear или Ctrl+L). Очистил экран с помощью комбинации клавиш Ctrl+L
![src1](https://github.com/user-attachments/assets/40428579-07db-438d-afad-b7d6efb503c2)

2.1.4 Определите текущий каталог Определил текущик каталог спомощью команды pwd
![src1](https://github.com/user-attachments/assets/07c9515a-e702-4e77-84af-b6282fbee87f)

2.1.5 Получите справку по команде pwd Выполнил команду тем самым получил спавку по команде
![src1](https://github.com/user-attachments/assets/caf7bf69-0e9c-449f-a888-f2750af92d3b)

2.2.1 Просмотрите содержимое корневого каталога Просмотрил содержимое корневого каталога с помощью команды ls
![src1](https://github.com/user-attachments/assets/592c9be3-ec23-4f7f-a346-1ae5ce485100)

2.2.2 Перейдите в /etc, выведите подробный список Перешёл в /etc
![src1](https://github.com/user-attachments/assets/05facba7-0f0c-48d6-9697-a47ab97b0deb)

2.2.3 Вернитесь в домашний каталог двумя способами Вернулся в домашний каталог первым способом
![src1](https://github.com/user-attachments/assets/98be1ccc-7e2d-4797-9ebd-dfc9a5e8a8be)
![src1](https://github.com/user-attachments/assets/dc40a32f-5cf9-480e-bcd5-3b3f15ab7d11)

2.2.4 Перейдите в предыдущий каталог Вернулся в предыдущий каталог с помощью cd -
![src1](https://github.com/user-attachments/assets/bf195597-c257-4dda-ad6e-3a095d443e07)

2.2.5 Используя абсолютные и относительные пути, доберитесь из домашнего каталога до /usr/share, затем до /usr/bin и обратно в домашний каталог. Атносительный путь Относителный путь
![src1](https://github.com/user-attachments/assets/a53620c9-109f-4b45-848a-7e2a391f357e)

2.3.1 Создайте в домашнем каталоге следующую структуру (команды приведены) Создание структуры
![src1](https://github.com/user-attachments/assets/01165288-2a86-409c-9298-f373fa7b3d57)

2.4 Копирование, перемещение и удаление Копирование перемещение и удаление
![src1](https://github.com/user-attachments/assets/4c87dab5-58de-48ca-b7f3-54261a618682)

2.5.1 Просмотр и определение типов файлов, права доступа 2.5.1 Запишите текст в docs/notes.txt Записал текст в docs/notes.txt
![src1](https://github.com/user-attachments/assets/3077e6ef-e929-40a7-9630-10c96462bc66)

2.5.2 Создайте scripts/hello.sh и сделайте его исполняемым Создал scripts/hello.sh и сделал его исполняемым
![src1](https://github.com/user-attachments/assets/0fb21e20-f45a-4956-8e74-d551cf003d0d)

2.5.3 проверьте: ls -l scripts/hello.sh, file scripts/hello.sh Проверил: ls -l scripts/hello.sh, file scripts/hello.sh
![src1](https://github.com/user-attachments/assets/7aa1c13e-fc8b-4797-8883-4bcd86a23859)

2.6 Освоение текстовых редакторов 2.6.1 NANO 2.6.1.1 nano docs/notes.txt – добавьте 2-3 строки, сохраните (Ctrl+O) и выйдите (Ctrl+X).
![src1](https://github.com/user-attachments/assets/985c04a5-4292-47a1-bce1-e447bee9eab3)

2.6.1.2 проверка
![src1](https://github.com/user-attachments/assets/3b28a8bc-8bb2-4ce9-9743-9fccbe8ff3c6)

2.6.1.3 Создайте ~/lab1/info.txt через nano, запишите туда имя хоста и дату (подсмотрите командами hostname, date)
![src1](https://github.com/user-attachments/assets/29b00797-375d-4686-b844-053141d7cae1)

2.6.2.1 Базовое редактирование
![src1](https://github.com/user-attachments/assets/3ce1f4ce-8a12-4143-996a-f9273984270e)

2.6.2.2 Навигация и поиск
![src1](https://github.com/user-attachments/assets/5869a884-6746-46af-a028-f5d5f6d95c33)

2.6.2.3 Поиск, замена, работа с буфером
![src1](https://github.com/user-attachments/assets/b479f2b8-b570-41c7-bb45-710cfdef53aa)

2.6.2.4
![src1](https://github.com/user-attachments/assets/90b1941e-cf67-4680-9132-9b2146ef1c53)
![src1](https://github.com/user-attachments/assets/39e64f5e-175d-4372-9b0d-efdaf4b027af)

2.7 Итоговая самостоятельная работа. 
![src1](https://github.com/user-attachments/assets/50c85003-b7da-40e3-a115-1c1f255caec2)
![src1](https://github.com/user-attachments/assets/0ac4fb7d-af79-4b8b-ab3f-c54288cd86fa)
![src1](https://github.com/user-attachments/assets/a5c03dc0-01fb-48a3-a034-5fad9420b008)

