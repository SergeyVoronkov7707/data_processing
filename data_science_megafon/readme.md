# Megafon  
## Датасет покупок клиентов мегафон  
  
Первичныя обработка  
Модель для baseline я использовал LogisticRegression  
Обработка данных  
Построение моделей KNeighborsClassifier, LGBMClassifier, CatBoostClassifier, RandomForestClassifier  
Подбор гиперпараметров при помощи Greed Search  

При работе с данными использовал библиотеку dask и pandas для загрузки и обьединения данных,для работы с данными использовал библиотеки sclearn,для взуализации matplotlib.  
Обьеденял по столбцам ‘id ’ и ‘buy_time’ т.к. нужно получить понимание покупки покупателей в определенное время.
