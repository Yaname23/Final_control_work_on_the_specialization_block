# Final_control_work_on-_the-_specialization_block
Задание
1. Используя команду cat в терминале операционной системы Linux, создать
два файла Домашние животные (заполнив файл собаками, кошками,
хомяками) и Вьючные животными заполнив файл Лошадьми, верблюдами и
ослы),

![Задание1 создание 2х файлов](https://github.com/user-attachments/assets/6f72c7ee-a860-4492-8220-66cc6eda18b9)

а затем объединить их. Просмотреть содержимое созданного файла.
Переименовать файл, дав ему новое имя (Друзья_человека).
![Задание 1 Объединение_просмотр содержимого_переименование](https://github.com/user-attachments/assets/d23673d2-b445-4ea0-b270-57b6e69cb5c9)

2. Создать директорию, переместить файл туда.
![Задание2](https://github.com/user-attachments/assets/d0b7e9c7-8bff-49fc-9948-fcfd47cf2837)

3. Подключить дополнительный репозиторий MySQL. 
![задание3_подключение my_sql](https://github.com/user-attachments/assets/aba8f5da-a941-4a4e-b421-838cdac0c9a8)

Установить любой пакет из этого репозитория.
![задание3_2](https://github.com/user-attachments/assets/e029bbbf-cb4d-416d-b12a-326ecc1848d8)

4. Установить и удалить deb-пакет с помощью dpkg.
В задании 3 устанавливала deb-пакет с помощью dpkg. Удаение:
![задание 4 удаление](https://github.com/user-attachments/assets/9739c7ed-0ba1-45d1-b343-106ba3eba2a3)
   
5. Выложить историю команд в терминале ubuntu
![задание5 команда history](https://github.com/user-attachments/assets/b10d582f-b12f-41dd-9b66-f8030ec99958)

6. Нарисовать диаграмму, в которой есть класс родительский класс, домашние
животные и вьючные животные, в составы которых в случае домашних
животных войдут классы: собаки, кошки, хомяки, а в класс вьючные животные
войдут: Лошади, верблюды и ослы).
![задание6_диаграмма](https://github.com/user-attachments/assets/e116b019-ae3e-4e48-b8c6-b448b73ce61c)

7. В подключенном MySQL репозитории создать базу данных “Друзья
человека”
![задание7  Создание БД](https://github.com/user-attachments/assets/0b47d675-afd1-4882-a9cb-9c71f5c408f5)

8. Создать таблицы с иерархией из диаграммы в БД

![задание7 2 Создание таблицы друзья человека](https://github.com/user-attachments/assets/a5062dfb-1468-43b1-8b03-68160b9e4daf)
![задание7 3 Создание таблицы вьючные](https://github.com/user-attachments/assets/da08c880-0e87-4215-9453-c132092096f3)
![задание7 3 Создание таблицы домашние](https://github.com/user-attachments/assets/21b6a64c-023e-43dd-bc5b-2ded339dc032)

9. Заполнить низкоуровневые таблицы именами(животных), командами
которые они выполняют и датами рождения
![задание7 4 осёл_верблюд](https://github.com/user-attachments/assets/38cc21fd-739f-4535-9824-3ec7a21c59f1)
![задание7 4 Создание таблиц_кошка_собака](https://github.com/user-attachments/assets/32d1bb32-a3fc-4685-8914-ee7f06eb9603)
![задание7 4 Создание таблиц_хомяк_лошадь](https://github.com/user-attachments/assets/c440d4d1-5bb9-4412-bd21-34d12d0b0536)
![задание7 5  Проверка](https://github.com/user-attachments/assets/36057961-bd79-403b-98ea-19359f214e2f)

10. Удалив из таблицы верблюдов, т.к. верблюдов решили перевезти в другой
питомник на зимовку. 
![10  удаление верблюдов](https://github.com/user-attachments/assets/9525b2d2-a75b-4ead-8b20-2e13f4c6683a)

Объединить таблицы лошади, и ослы в одну таблицу.

![10 объединение](https://github.com/user-attachments/assets/fc7e98a5-94e7-4738-9d61-698c9574ec2e)

11.Создать новую таблицу “молодые животные” в которую попадут все
животные старше 1 года, но младше 3 лет и в отдельном столбце с точностью
до месяца подсчитать возраст животных в новой таблице
![11 молодые животные](https://github.com/user-attachments/assets/a91b4365-1bde-48f7-8547-06b012092b6f)

12. Объединить все таблицы в одну, при этом сохраняя поля, указывающие на
прошлую принадлежность к старым таблицам.
![12 Все животные](https://github.com/user-attachments/assets/d4d97503-b4e3-4ca7-81a1-9760120e0f60)

13.Создать класс с Инкапсуляцией методов и наследованием по диаграмме.
![Инкапсуляция_1](https://github.com/user-attachments/assets/a61ea89b-f5e8-48b0-8482-227ca410371c)
![Инкапсуляция_3](https://github.com/user-attachments/assets/4c73e020-7bde-424b-90f2-43f8050e87d7)
![Инкапсуляция_2](https://github.com/user-attachments/assets/93fe6c26-6a42-40de-9f29-3e93117f4f8b)

14. Написать программу, имитирующую работу реестра домашних животных.
В программе должен быть реализован следующий функционал:
14.1 Завести новое животное
14.2 определять животное в правильный класс
14.3 увидеть список команд, которое выполняет животное
14.4 обучить животное новым командам
14.5 Реализовать навигацию по меню

код в папке Proggramm в репозитории

15.Создайте класс Счетчик, у которого есть метод add(), увеличивающий̆
значение внутренней̆int переменной̆на 1 при нажатие “Завести новое
животное” Сделайте так, чтобы с объектом такого типа можно было работать в
блоке try-with-resources. Нужно бросить исключение, если работа с объектом
типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение
считать в ресурсе try, если при заведения животного заполнены все поля.





