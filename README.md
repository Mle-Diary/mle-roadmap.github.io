Трек для развития в сфере MLE. Полный путь: от базовой теории до продвинутых MLOps–практик и построения продакшн-ML систем. Автор https://t.me/aesthetic_mlops. Материалы будут пополняться
<img width="1172" height="752" alt="image" src="https://github.com/user-attachments/assets/19affc3a-83ea-4ead-a52d-c9596c8a948d" />



# Зарплаты (2025) 
### Machine Learning Engineer, источник Habr Карьера
- Junior: **70–140 тыс ₽**. Рассчитано на основании 8 071 анкеты
- Middle: **120–240 тыс ₽**. Рассчитано на основании 22 827 анкет
- Senior: **220-400 тыс ₽** Рассчитано на основании 11 332 анкет

------

# Ориентировочный план обучения (если охватить весь трек)

### Этап 1 (1–2 месяца)
Python, CS, SQL, базовый ML

### Этап 2 (3 месяца)
ML/DL, PyTorch, sklearn, метрики

### Этап 3 (3–4 месяца)
Backend, Docker, Kubernetes, Airflow, MLflow

### Этап 4 (3–6 месяцев)
MLOps, мониторинг, KServe, CI/CD

### Этап 5 (постоянно)
ML System Design, архитектура, масштабирование

# Нужная теория
## 1. База
- Структуры данных: массивы, списки и др
- Алгоритмы: сортировки, поиск, графы
- Оценка сложности: Big-O
- Основы параллелизма

## 2. Python
- Типизация, классы
- Сборка окружений: poetry, pip-tools
- Ассинхронность
- Многопоточность и многопроцессность, GIL
- Для качества кода: flake8, black, mypy
- Git, CI/CD

## 3. Основы машинного обучения (ML)
- Статистика, линейная алгебра, теория вероятностей
- Генерация признаков
- Sklearn: модели, пайплайны
- Метрики: F1, ROC-AUC, MSE, MAE, MAP@K
- Валидация моделей: KFold, StratifiedKFold
- Интерпретируемость: SHAP, Permutation Importance

## 4. Глубокое обучение (Deep Learning)
- Основы PyTorch: Module, Dataset, DataLoader
- Оптимизаторы: Adam, SGD, schedulers
- Архитектуры: CNN, RNN, Transformers
- Transfer learning
- Distributed training: DDP
- Экспорт моделей: TorchScript, ONNX
- Cервинг: TorchServe, ONNX Runtime

## 5. Фундамент Data Engineering
- SQL: join, window functions
- Spark (DataFrame API)
- Kafka (основы)
- Batch/stream processing
- форматы данных: Parquet, ORC
- Облачное хранилище: S3/MinIO

## 6. Backend для ML (упаковка моделей в сервисы)
- FastAPI, gRPC
- Docker
- Kubernetes: deployments, secrets, autoscaling
- REST/gRPC паттерны для ML-сервисов
- Нагрузочное тестирование: locust, k6
- Кэширование: Redis

## 7. MLOps
- MLflow: эксперименты, Model Registry
- Airflow: проектирование DAG
- Feature Stores: Feast, Hopsworks
- Monitoring: data drift, feature drift
- Quality: Great Expectations
- Metadata: OpenMetadata
- Model serving: KServe, Seldon, BentoML

## 8. ML System Design
- Архитектура batch-инференса
- Онлайн-инференс (REST/gRPC)
- Event-driven / Streaming inference
- A/B тестирование моделей
- Канареечные релизы
- Версионирование моделей
- Масштабирование и отказоустойчивость

---

# Смежные профессии и их отличия

## Data Scientist (DS)
### Фокус:
- исследование данных  
- построение моделей  
- аналитика, эксперименты  
- поиск фичей  

### Отличия от MLE:
- больше математики и анализа  
- меньше продакшена и DevOps  
- не работает глубоко с Kubernetes, CI/CD, модельным сервисингом  

### Типовой стек:
- Python, pandas, numpy  
- sklearn, XGBoost, CatBoost  
- PyTorch/TF (исследовательский)  
- SQL  
- matplotlib/seaborn  

---

## Machine Learning Engineer (MLE)
### Фокус:
- продакшн моделей  
- инфраструктура, пайплайны  
- мониторинг  
- оптимизация inference  
- работа с большим трафиком  

### Отличия:
- глубокий продакшен (K8s, Docker, MLflow, KServe)  
- больше инженерии, меньше ресерча  

### Стек:
- PyTorch  
- FastAPI/gRPC  
- Airflow  
- Spark  
- Docker, Kubernetes  
- MLflow, KServe  

---

## Data Engineer (DE)
### Фокус:
- построение data-платформы  
- ETL/ELT  
- высоконагруженные пайплайны  

### Отличия:
- минимально занимается ML  
- специализация на данных и инфраструктуре
- математика не нужна

### Стек:
- Python/Scala  
- Spark  
- Airflow/DBT  
- Kafka  
- SQL  

---

## MLOps Engineer
### Фокус:
- автоматизация ML-инфраструктуры  
- мониторинг, развёртывание моделей  
- CI/CD  

### Отличия:
- почти не пишет модели  
- тесно работает с DevOps  

### Стек:
- Docker, Kubernetes  
- Terraform  
- MLflow  
- KServe, Seldon  
- Prometheus, Grafana  

# Книги
[список электроных книг](books.md)
### Темы:

[Код и алгоритмы](https://mle-diary.github.io/Mle-Roadmap/books.html#%D0%BA%D0%BE%D0%B4-%D0%B8-%D0%B0%D0%BB%D0%B3%D0%BE%D1%80%D0%B8%D1%82%D0%BC%D1%8B)

[MLE](https://mle-diary.github.io/Mle-Roadmap/books.html#mle)

[Классический ML](https://mle-diary.github.io/Mle-Roadmap/books.html#%D0%BA%D0%BB%D0%B0%D1%81%D1%81%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B8%D0%B9-ml)

[Deep Learning](https://mle-diary.github.io/Mle-Roadmap/books.html#dl)

[Рекомендательные системы](https://mle-diary.github.io/Mle-Roadmap/books.html#%D1%80%D0%B5%D0%BA%D0%BE%D0%BC%D0%B5%D0%BD%D0%B4%D0%B0%D1%82%D0%B5%D0%BB%D1%8C%D0%BD%D1%8B%D0%B5-%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B)



# Рекомендованные курсы
### DS:
1. [Открытый курс по машинному обучению, автор Юрий Кашницкий](https://ods.ai/tracks/open-ml-course/about)

