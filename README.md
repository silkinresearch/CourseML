# Course-ML

Курс предполагает 7 занятий. Каждое занятие состоит из 3 частей: 
  - Лекция (30-60 минут). Объяснение теории. 
  - Семинара (30-60 минут). Демонстрация практического применения теории в Jupyter Notebook. 
  - Воркшопа (90 минут). Индивидуальное выполнение заданий. 

Программа:


<p align="center">
  <img src="https://user-images.githubusercontent.com/94602743/206873285-447a8e57-af6b-4bcc-8cd2-4ea5068fcee8.png" width="600" alt="Sublime's custom image"/>
</p>

**Детальное описание программы:**
1. Анализ данных: <br>
    - Базовые элементы статистики: типы переменных, описательные статистики, построение доверительного интервала. 
    - Работа с библиотекой Pandas: операции над датафреймами, чистка датасета, вывод данных по условию, создание новых признаков, группировки. Соединение датафреймов по общему идентификатору: inner join и left join.
    - Визуализация данных с Seaborn: гистограмма, боксплот. Длинное и широкое хранение данных для визуализации разных категорий. 
  
2. Линейная регрессия:
    - Метод обучения модели: градиентный спуск.
    - Функция для минимизации: среднеквадратичная ошибка (Mean Squared Error - MSE).
    - Метрики задачи регрессии: $MAE$ and $R^2$. Вычисление метрик для случайного регрессора.
    - Регуляризация как метод предотвращения переобучения.
    
3. Логистическая регрессия: 
    - Метод обучения модели: градиентный спуск.
    - Функция для минимиции: кросс-энтропия (Cross Entropy - CE).
    - Метрики задачи классификации: ROC AUC, Sensitivity (TPR) and Specifity (TNR), Recall (TPR) and Precision. Выбор оптимального порога. 
    - Регуляризация как метод предотвращения переобучения.
    - Мультикласс-логистическая регрессия.
    
4. Деревья решений:
    - Метод обучения модели: последовательное разделение данных, снижающее неопределённость. 
    - Энтропия как метод подсчёта неопределённости в данных.
    - Использование энтропии для выбора наилушего разделения данных по определённому признаку. 
    - Визуализация дерева решений. 
    - Демонстрация переобочения.

5. Ансамбли деревьев решений: 
    - Случайный лес как метод параллельного построения деревьев. Мажоритарное голосование.  
    - Построение непохожих деревьев внутри случайного леса: бэггинг и случайный выбор признаков для разделения.
    - Демонстрация того, что несколько слабых переобученных моделей могут при помощи мажоритарного голосования создать более сильную модель. 
    - Градиентный бустинг как метод последовательного построения деревьев. Взвешенное голосование. 
    - Подбор гиперпараметров.
    - Кросс-валидация.
    - Feature Importance. 
 
6. Методы понижения размерности и кластеризация.
    - Необходимость понижения размерности: визуализация и снижение мультиколлинеарности.
    - Метод главных компонент как последовательное построение осей, вдоль которых дисперсия данных наибольшая. 
    - TSNE и UMAP для более продвинутого понижения размерности. 
    - Кластеризация KMeans. Поиск оптимального количества кластеров. 
    - Кластеризация с DBSCAN. Подбор параметров. 
    
7. Тексты и Картинки.
    - Тексты
      - Закон Ципфа. Нахождение параметра степенного распределения. 
      - Метод мешка слов $BoW$ для построения векторов текстов. 
      - Метод $TF-IDF$ для построения векторов текстов. 
      - Классификация текстов на полученных признаках. 

    - Картинки:
      - Визуализация картинок. 
      - Разворачивание двумерного изображения в вектор. 
      - Классификация картинок на полученных признаках. 
