# Лабораторная работа №8 — анализ и прогнозирование временного ряда

Методичка: [LAB_TMO_TIMESERIES](https://github.com/ugapanyuk/courses_current/wiki/LAB_TMO_TIMESERIES).

## Файлы

| Файл | Назначение |
|------|------------|
| `lab8_timeseries.ipynb` | Анализ ряда, train/test split, ARIMA, символьная регрессия, (опционально) GMDH через `gmdh`, метрики и графики |

## Запуск

```bash
jupyter notebook lab8_timeseries.ipynb
```

# Лабораторная работа №8 — анализ и прогнозирование временного ряда

Лабораторная по методичке: [LAB_TMO_TIMESERIES](https://github.com/ugapanyuk/courses_current/wiki/LAB_TMO_TIMESERIES).

## Файлы

| Файл | Назначение |
|------|------------|
| `lab8_timeseries.ipynb` | Визуализация ряда, train/test split, прогноз ARIMA, символьная регрессия, (опционально) методы МГУА через `gmdh`, сравнение MAE/RMSE и графики прогнозов |

## Запуск

Из корня репозитория (виртуальное окружение один раз — см. [README.md](README.md)):

```bash
jupyter notebook lab8_timeseries.ipynb
```

## Важно про `gmdh`

В методичке требуется использовать библиотеку `gmdh` для COMBI/MULTI и MIA/RIA. На macOS установка `gmdh` может требовать системный Boost (например, через Homebrew). В ноутбуке этот пункт сделан **опциональным**: если `gmdh` не импортируется, ячейка выводит подсказку и продолжает выполнение остальных пунктов.

## Отчёт

Экспортируйте ноутбук в HTML (*File → Save and Export Notebook As…*) или в PDF и добавьте титульный лист по требованиям преподавателя.

