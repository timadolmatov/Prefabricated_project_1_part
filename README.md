1. **В данном проекте нужно выявить определяющие успешность игры закономерности. Таким образом мы сможем узнать потенциально популярный продукт, тем самым грамотно спланировать рекламные компании.**
----------------------------------------
2. **ОПИСАНИЕ ДАННЫХ:** 
- Name — название игры
- Platform — платформа
- Year_of_Release — год выпуска
- Genre — жанр игры
- NA_sales — продажи в Северной Америке (миллионы проданных копий)
- EU_sales — продажи в Европе (миллионы проданных копий)
- JP_sales — продажи в Японии (миллионы проданных копий)
- Other_sales — продажи в других странах (миллионы проданных копий)
- Critic_Score — оценка критиков (максимум 100)
- User_Score — оценка пользователей (максимум 10)
- Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.
----------------------------------------
3. **ОСНОВНЫЕ ПУНКТЫ И ЦЕЛИ ИССЛЕДОВАНИЯ:**
- Подготовка данных:
  - Замените названия столбцов (приведите к нижнему регистру);
  - Преобразуйте данные в нужные типы. Опишите, в каких столбцах заменили тип данных и почему;
  - Обработайте пропуски при необходимости:
    - Объясните, почему заполнили пропуски определённым образом или почему не стали это делать;
    - Опишите причины, которые могли привести к пропускам;
    - Обратите внимание на аббревиатуру 'tbd' в столбцах с рейтингом. Отдельно разберите это значение и опишите, как его обработать;
  - Посчитайте суммарные продажи во всех регионах и запишите их в отдельный столбец.
- Проведите исследовательский анализ данных: 
  - Посмотрите, сколько игр выпускалось в разные годы. Важны ли данные за все периоды?
  - Посмотрите, как менялись продажи по платформам. Выберите платформы с наибольшими суммарными продажами и постройте распределение по годам. За какой характерный срок появляются новые и исчезают старые платформы?
  - Возьмите данные за соответствующий актуальный период. Актуальный период определите самостоятельно в результате исследования предыдущих вопросов. Основной фактор — эти данные помогут построить прогноз на 2017 год.
  - Не учитывайте в работе данные за предыдущие годы.
  - Какие платформы лидируют по продажам, растут или падают? Выберите несколько потенциально прибыльных платформ.
  - Постройте график «ящик с усами» по глобальным продажам игр в разбивке по платформам. Опишите результат.
  - Посмотрите, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Постройте диаграмму рассеяния и посчитайте корреляцию между отзывами и продажами. Сформулируйте выводы.
  - Соотнесите выводы с продажами игр на других платформах.
  - Посмотрите на общее распределение игр по жанрам. Что можно сказать о самых прибыльных жанрах? Выделяются ли жанры с высокими и низкими продажами?
- Составьте портрет пользователя каждого региона:
  - Определите для пользователя каждого региона (NA, EU, JP):
    - Самые популярные платформы (топ-5). Опишите различия в долях продаж.
    - Самые популярные жанры (топ-5). Поясните разницу.
    - Влияет ли рейтинг ESRB на продажи в отдельном регионе?
- Проверьте гипотезы:
  - Средние пользовательские рейтинги платформ Xbox One и PC одинаковые;
  - Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.
  - Поясните:
    - Как вы сформулировали нулевую и альтернативную гипотезы;
    - Какой критерий применили для проверки гипотез и почему.
----------------------------------------
4. **ИСПОЛЬЗУЮЕМЫЕ БИБЛИОТЕКИ:**
- pandas
- IPython.display
- matplotlib.pyplot
- numpy
- seaborn
- stats from scipy

