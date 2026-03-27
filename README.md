# 📊 ML Project with W&B

## 📌 Описание проекта
В этом проекте обучается модель машинного обучения для задачи классификации.  
Используется встроенный датасет из sklearn (без скачивания).

Все эксперименты логируются в Weights & Biases (W&B).

---

## 🛠️ Используемые технологии
- Python
- scikit-learn
- pandas
- matplotlib
- wandb

---

## 🚀 Что сделано
- Загрузка датасета
- Разделение на train/test
- Обучение модели (RandomForest)
- Оценка качества модели
- Логирование метрик в W&B

---

## 📈 Метрики
В проекте считаются:
- accuracy
- precision
- recall
- f1-score
- roc-auc

---

## 📊 Пример результатов

Accuracy: ~0.95  
F1-score: ~0.96  
ROC-AUC: ~0.99  

---

## 🔗 W&B Dashboard
Все эксперименты можно посмотреть в W&B:
https://wandb.ai/zmukusheva-/classification-demo

---

## 📂 Структура проекта

## 📌 Итог проекта

Я построила модель бинарной классификации на встроенном датасете sklearn.  
Сравнила Logistic Regression и Random Forest с помощью wandb.  
По метрикам accuracy, f1 и roc_auc лучшей моделью оказалась Logistic Regression.
