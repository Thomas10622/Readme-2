# -2-in-GameDev-# АНАЛИЗ ДАННЫХ В РАЗРАБОТКЕ ИГР ЛАБОРАТОРНАЯ РАБОТА 2 [in GameDev]
Отчет по лабораторной работе #2 выполнил:
- Бархатдинов Михаил Евгеньевич
- НМТ-230803
Отметка о выполнении заданий :

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | |
| Задание 2 | * |  |
| Задание 3 | * |  |
| Задание 4 | * |  |
| Задание 5 | # |  |



##Структура отчета

- #Данные о работе: Работа #2. 
- #Научиться передавать в Unity данные из Google Sheets с помощью Python.

  
- # Задание 1. Настроить доступ к google-таблице по api
 Ход работы:
- Перейти в Google Cloud Console .
- Создать новый проект, выбрав Выберите проект - Новый проект .
- Дать имя проекта и нажмите кнопку «Создать» .
- Перейти Панель управления созданного проекта.
- Перейти в Google Drive API , используя текстовый поиск.
- Нажать кнопку Включить API .
- Перейти в раздел «Учетные данные» и создайте учетные данные для ключа API.
- Сохранить файл с ключом в формате JSON на своем компьютере.
- Скопировать адрес сервисного аккаунта.
- создать Google-таблицу и доступ к ней для редактирования с созданного сервисного аккаунта.
  
![image](https://github.com/user-attachments/assets/5a178b42-aad3-411d-9482-f77fad26bfbd)






- # Задание 2.Генерация данных с помощью Python и их передача в google таблицу
 Ход работы:
- Запустить Jupyter Notebook и создать новый .ipynbфайл. 
- В .ipynb файле реализовать передачу данных в созданную ранее Google-таблицу.

![image](https://github.com/user-attachments/assets/9133e86a-5c93-42ac-ac07-7e66a98bf834)


![image](https://github.com/user-attachments/assets/9fee5404-c296-4a63-81e4-cd153536e779)


![image](https://github.com/user-attachments/assets/4d32bbf7-0b80-401f-a31a-c259f6385382)



- # Задание 3.Создание ключа API для передачи данных из google-таблицы в Unity
- Создать ключ API для получения данных из таблиц и их обработки в Unity.

  ![image](https://github.com/user-attachments/assets/680d530b-65e6-4541-98f7-bec75e42ddcd)



- # Задание 4. 4 Новый проект на Unity
- Создать новый 3D-проект на Unity.
- Добавить в файлы проекта jsonPackage и soundPackage.
- Создать на сцене Unity пустой GameObjectи подключите к ней .csскрипт, в котором подключение к Google-таблице по API и подать сигнал в игру в соответствии со считываемыми значениями:
  
![image](https://github.com/user-attachments/assets/2aab30f3-6d8b-41fe-9c33-0f8834a4e78a)

![image](https://github.com/user-attachments/assets/3f94e28c-0639-486b-aaad-15256df2a1e9)



## Выводы

В ходе лабораторной работы был изучен способ передачи данных из Google Sheets в Unity с использованием Python и настроенного API. Реализованы генерация данных на Python, их передача в Google Sheets, а также использование этих данных на игровом движке Unity для передачи звука в соответствии с экономической моделью динамики.
