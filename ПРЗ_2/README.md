# Перекомпиляция загруженной модели с функцией потерь sparse_categorical_crossentropy

<img width="916" alt="image" src="https://github.com/user-attachments/assets/c7c05919-0dc4-4d39-8ccc-7c537b985f89">

---

# Загрузка обученной модели и данных MNIST, Реализация атаки FGSM и Оценка модели на противоречивых примерах

<img width="753" alt="image" src="https://github.com/user-attachments/assets/aab24d72-a1e1-4623-84fc-1522b65e5616">
<img width="758" alt="image" src="https://github.com/user-attachments/assets/92cf2985-eaee-4020-aaca-dba99255936f">
<img width="564" alt="image" src="https://github.com/user-attachments/assets/47823b0f-91fa-4914-8fd8-5e104755b415">

---

# Сравнение результатов

<img width="754" alt="image" src="https://github.com/user-attachments/assets/1eeedf15-c0b7-4b96-a9f4-a1b14e56e15f">

#Вывод:
разница в точности модели на стандартных и атакующих примерах поразительна. На "чистых изображениях" точность достигает 97,29%, тогда как на атакующих снижается до 8,65%. Это показывает уязвимость модели к целенаправленным искажениям — распространённой проблеме в машинном обучении.

Столь значительное падение точности указывает на неспособность модели эффективно распознавать примеры при наличии небольших, но целенаправленных изменений.
