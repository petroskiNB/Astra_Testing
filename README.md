# Astra_Testing
Testing task for internship in Astra x МИЭМ

## Автор
Петров Н.В.

## Дата
05.10.2026

## Источники данных
- [Scrape This Site — Hockey Teams](https://www.scrapethissite.com/pages/forms/) —
  источник статистики команд. Данные собраны 05.10.2026:
  24 страницы, 582 строки.
- Условия и определение целевой переменной — из ноутбука тестового задания.

## Документация
- [pandas](https://pandas.pydata.org/docs/) —
  обработка таблиц, объединение данных, группировки и чтение/запись CSV.
- [scikit-learn: LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html) —
  параметры логистической регрессии.
- [scikit-learn: RandomForestClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) —
  параметры случайного леса.

## Использованные инструменты
- Python и Jupyter Notebook в VS Code.
- requests и Beautiful Soup — получение страниц и извлечение ссылок.
- pandas и lxml — извлечение и обработка HTML-таблиц.
- matplotlib — построение графиков.
- scikit-learn — подготовка признаков, обучение моделей и расчёт метрик.
- OpenAI Codex — помощь в понимании задания, подготовке и объяснении
  фрагментов кода, исправлении ошибок и проверке выводов.

## Воспроизводимость
Исходная выгрузка сохранена в `data/hockey_raw.csv`.
Код анализа, параметры моделей и результаты приведены в ноутбуке.