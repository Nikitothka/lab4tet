# Лаборатоная работа 4
## Цель работы
Разработать и реализавать игру пинг-понг. Хранение и обработка модели происходит на сервере. Общение сервера и клиентов происходит по websocket. Для отрисовки вида используется canvas. Игра завершается при достижении нужного счёта одним из игроков
## Ход работы
- Разработаем пользовательский интерфейс и опишем пользовательские сценарии работы

![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%9F%D0%B8%D0%BD%D0%B3-%D0%BF%D0%BE%D0%BD%D0%B3.png)

Первоначально пользователь попадает на главную форму. Здесь он может нажать на кнопку "Одиночная игра", чтобы играть одному, или на кнопку "Пригласить в игру", чтобы играть в мультиплеере. Чтобы играть в мультиплеере ему необходимо будет выбрать игроков из списка на главной форме.

- Опишем хореографию

![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%A5%D0%BE%D1%80%D0%B5%D0%BE%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D1%8F%20(%D1%80%D1%80).png)

- Опишем алгоритмы 

1. Добавление пользователя
 
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%94%D0%BE%D0%B1%D0%B0%D0%B2%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5%20%D0%B2%20%D0%BB%D0%BE%D0%B1%D0%B1%D0%B8.png)
  
  2. Синглплеер
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%A1%D0%B8%D0%BD%D0%B3%D0%BB%D0%BF%D0%BB%D0%B5%D0%B5%D1%80.png)
  
  3. Мультиплеер
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%9C%D1%83%D0%BB%D1%8C%D1%82%D0%B8%D0%BF%D0%BB%D0%B5%D0%B5%D1%80.png)
  
  4. Приглашение игрока
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%9F%D1%80%D0%B8%D0%B3%D0%BB%D0%B0%D1%88%D0%B5%D0%BD%D0%B8%D0%B5.png)
  
  5. Описание движения ракетки
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%A0%D0%B0%D0%BA%D0%B5%D1%82%D0%BA%D0%B0.png)
  
  6. Выход
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%92%D1%8B%D1%85%D0%BE%D0%B4%20(%D1%80%D1%80).png)
  
  7. Процесс отмены игры
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%9F%D1%80%D0%BE%D1%86%D0%B5%D1%81%D1%81%20%D0%BE%D1%82%D0%BC%D0%B5%D0%BD%D1%8B.png)
  
  8. Цикл игры
  
  ![](https://github.com/AlDmitrieva/lab_4_PP/blob/main/%D0%A6%D0%B8%D0%BA%D0%BB%20%D0%B8%D0%B3%D1%80%D1%8B.png)
  
## Вывод
Разработали и реализавали игру пинг-понг.
