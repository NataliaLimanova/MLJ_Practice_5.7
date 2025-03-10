# MLJ_Practice_5.7
Регуляризация линейной регрессии. Практическая работа
Цель практической работы
Научиться строить модель линейной регрессии с регуляризацией на реальных данных.

Что входит в практическую работу
Загрузить данные и ознакомиться с ними.
Изучить данные и провести анализ, сконструировать новые признаки.
Разделить данные на обучающую и тестовую выборки.
Реализовать построение модели с помощью библиотеки Scikit-learn.
Подобрать коэффициенты регуляризации.
Получить качество модели с помощью MSE, MAE,  𝑅2
 .
Ответить на вопросы в конце блокнота.
Что оценивается
Выполнены все этапы работы.
Подобраны коэффициенты регуляризации.
Сделан вывод по результатам.
Модель не переобучена.
Получена модель хорошего качества.
Сделаны выводы в конце блокнота.
Как отправить работу на проверку
Скачайте файл с заданиями в материалах, откройте его через Jupyter Notebook и выполните задания.

Задача
С набором данных вы уже знакомы из прошлого модуля — это данные по продажам домов. В этот раз признаков будет чуть больше, чтобы вам было интереснее. Краткое описание признаков:

LotArea — размер участка в квадратных футах.
LotArea_M — размер участка в квадратных метрах.
Street — тип доступа к дороге.
BldgType — тип жилья.
OverallQual — общее качество материала и отделки.
OverallCond — общая оценка состояния.
YearBuilt — первоначальная дата постройки.
YearRemodAdd — дата реконструкции.
RoofStyle — тип крыши.
ExterQual — качество материалов снаружи.
ExterCond — текущее состояние материалов снаружи.
Foundation — тип фундамента.
TotalBsmtSF — общая площадь подвала в квадратных футах.
TotalBsmtSF_M — общая площадь подвала в квадратных метрах.
Heating — тип отопления.
HeatingQC — качество и состояние отопления.
CentralAir — кондиционирование.
GrLivArea — жилая площадь в квадратных футах.
GrLivArea_M — жилая площадь в квадратных метрах.
Bath — количество ванных комнат.
KitchenQual — качество кухни.
GarageArea — площадь гаража в квадратных футах.
GarageArea_M — площадь гаража в квадратных метрах.
DateSold — месяц и год продажи.
SaleCondition — условия сделки.
SalePrice — стоимость продажи в долларах. Это целевая переменная, которую нам нужно предсказать.
Постройте модель линейной регрессии на этих данных. Проверьте качество модели на обучающей и тестовой выборках с помощью MAE, MSE,  𝑅2
 . Определите, что модель не переобучилась.
