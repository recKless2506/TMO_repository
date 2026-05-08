# Лабораторная работа №3 — k-NN и подбор гиперпараметров

Методичка: [LAB_TMO__KNN](https://github.com/ugapanyuk/courses_current/wiki/LAB_TMO__KNN).

## Файлы

| Файл | Назначение |
|------|------------|
| `lab3_knn.ipynb` | `train_test_split`, baseline K, `GridSearchCV` и `RandomizedSearchCV` с двумя CV-стратегиями |

## Запуск

```bash
jupyter notebook lab3_knn.ipynb
```

# Лабораторная работа №3 — k-NN, разбиение выборки, подбор гиперпараметров

Лабораторная по методичке: [LAB_TMO__KNN](https://github.com/ugapanyuk/courses_current/wiki/LAB_TMO__KNN) — подготовка train/test, обучение `KNeighborsClassifier`, `GridSearchCV` и `RandomizedSearchCV` с **двумя** стратегиями кросс-валидации (`StratifiedKFold` и `RepeatedStratifiedKFold`), сравнение метрик базовой и настроенных моделей.

## Файлы

| Файл | Назначение |
|------|------------|
| `lab3_knn.ipynb` | Wine dataset, `train_test_split`, baseline K, Grid/Randomized search, таблица сравнения |

## Запуск

Из корня репозитория (виртуальное окружение один раз — см. [README.md](README.md)):

```bash
jupyter notebook lab3_knn.ipynb
```

## Отчёт

Экспортируйте ноутбук в HTML (*File → Save and Export Notebook As…*) или в PDF и добавьте титульный лист по требованиям преподавателя.
