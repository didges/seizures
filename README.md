# seizures

Построение ML моделей для задачи определения спайков на примере датасета [CHB-MIT](https://physionet.org/content/chbmit/1.0.0/).

Для решения задачи решено было разделить решение на 2 шага:
1. Классификация окна размером в 30с для определения всплеска.
2. Нахождение начала всплеска
