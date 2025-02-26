# Практика 3: Атака Carlini-Wagner (CW) на модели ИИ

В данной практике используетс метод атаки Carlini-Wagner (CW), чтобы продемонстрировать, как можно обмануть обученную модель ИИ, классифицирующую изображения из набора данных MNIST. 

## Шаги выполнения

### Шаг 1: Загрузка обученной модели и данных MNIST
Загружаем предварительно обученную модель и нормализуем данные из набора MNIST для дальнейшей обработки.

![image](https://github.com/user-attachments/assets/ee62aaec-da59-4c99-ab4d-44696c90b1b8)

---

### Шаг 2: Установка Foolbox и запуск CW-атаки
Применяем библиотеку Foolbox для выполнения атаки CW на выбранные изображения из набора данных. Атака искажает изображения минимальным образом, сохраняя их визуальное сходство с оригинальными, но изменяет предсказания модели.

![image](https://github.com/user-attachments/assets/ac245645-6740-4894-a03c-c51cd8290828)

---

### Шаг 3: Оценка модели на противоречивых примерах
На данном этапе оцениваем точность модели на новых, атакованных изображениях. Это позволяет измерить устойчивость модели к целенаправленным атакам.

![image](https://github.com/user-attachments/assets/5e795252-0602-48ec-8411-a204428d93a4)

---

### Шаг 4: Сравнение результатов
Результаты атаки демонстрируют значительное падение точности модели на противоречивых примерах. Это указывает на слабую устойчивость модели к направленным искажениям.

---

## Вывод
Точность модели на атакованных изображениях резко упала почти до нуля, что указывает на её неспособность устойчиво классифицировать изображения в условиях целенаправленных, хоть и небольших, искажений. Это подчеркивает важность исследования устойчивости моделей ИИ к атакам для повышения их надежности.
