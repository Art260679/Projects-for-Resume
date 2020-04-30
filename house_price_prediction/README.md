
Итоговый проект по курсу "Библиотеки Python для Data Science: Numpy, Matplotlib, Scikit-learn"

Ссылка на соревнование >>>>>  https://www.kaggle.com/c/realestatepriceprediction

Задача в этом соревновании - предсказать цены на квартиры в датасете test.csv. 
 Есть два датасета: train.csv (содержит признаки и цены на квартиры) и test.csv (только признаки).

Метрика R2

File descriptions

    train.csv - the training set
    test.csv - the test set
    sampleSubmission.csv - a sample submission file in the correct format

Data fields

    Id - идентификационный номер квартиры
    DistrictId - идентификационный номер района
    Rooms - количество комнат
    Square - площадь
    LifeSquare - жилая площадь
    KitchenSquare - площадь кухни
    Floor - этаж
    HouseFloor - количество этажей в доме
    HouseYear - год постройки дома
    Ecology_1, Ecology_2, Ecology_3 - экологические показатели местности
    Social_1, Social_2, Social_3 - социальные показатели местности
    Healthcare_1, Helthcare_2 - показатели местности, связанные с охраной здоровья
    Shops_1, Shops_2 - показатели, связанные с наличием магазинов, торговых центров
    Price - цена квартиры 
    
    
 Использовался алгоритм lightgbm
Score CV / public 0.7489/ private   0.7369
- Итоговое место на private топ-40%
