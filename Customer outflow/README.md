
# Телеком - исследование оттока клиентов
## Описание проекта
Оператор связи «ТелеДом» хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, «ТелеДому» нужна модель, которая будет предсказывать, разорвёт ли абонент договор. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и услугах. Ваша задача — обучить на этих данных модель для прогноза оттока клиентов.

### Содержание проекта 
#### План работы
Шаг 1. Загрузка данных<br>
Загрузим данные и выполним их первичный осмотр.

Шаг 2. Исследовательский анализ и предобработка данных<br>
Выполним исследовательский анализ каждого датафрейма и выполним предобработку. Сделаем выводы об имеющихся признаках: понадобятся ли они для обучения моделей.

Шаг 3. Объединение данных<br>
Объединим выбранные признаки в один датафрейм по ключу.

Шаг 4. Исследовательский анализ и предобработка данных объединённого датафрейма<br>
Выполним исследовательский анализ объединённого датафрейма, визуализируем распределения признаков и выполните предобработку. Проведем корреляционный анализ. Сгенерируем новые признаки.

Шаг 5. Подготовка данных<br>
Выполним подготовку данных для обучения модели. Разделим данные на две выборки, при масштабировании и кодировании учитываем особенности данных и моделей.

Шаг 6. Обучение моделей машинного обучения<br>
Обучим 2 модели. Сделаем перебор гиперпараметров для улучшения качества и создадим pipeline для оптимизации.

Шаг 7. Выбор лучшей модели<br>
Выберите лучшую модель и проверьте её качество на тестовой выборке.

Шаг 8. Общий вывод и рекомендации заказчику<br>
Сделаем общий вывод о проделанной работе: опишем основные этапы работы, полученные результаты и передадим рекомендации для бизнеса.

### Библиотеки, используемые в проекте:
- Pandas
- Numpy 
- Matplotlib
- Seaborn 
- SKlearn
- SciPy 
- Catboost
- LightGBM
- Phik
