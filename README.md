# Проект: Определение стоимости автомобилей

Сервис по продаже автомобилей с пробегом «Не бит, не крашен» разрабатывает приложение для привлечения новых клиентов. В приложении пользователи смогут узнать рыночную стоимость своего автомобиля. 

Необходимо построить модель, которая будет предсказывать стоимость автомобиля на основе данных о его технических характеристиках, комплектации и ценах других автомобилей.

Критерии, которые важны заказчику:
- качество предсказания;
- время обучения модели;
- время предсказания модели.

**Признаки:**
- **DateCrawled** — дата скачивания анкеты из базы
- **VehicleType** — тип автомобильного кузова
- **RegistrationYear** — год регистрации автомобиля
- **Gearbox** — тип коробки передач
- **Power** — мощность (л. с.)
- **Model** — модель автомобиля
- **Kilometer** — пробег (км)
- **RegistrationMonth** — месяц регистрации автомобиля
- **FuelType** — тип топлива
- **Brand** — марка автомобиля
- **Repaired** — была машина в ремонте или нет
- **DateCreated** — дата создания анкеты
- **NumberOfPictures** — количество фотографий автомобиля
- **PostalCode** — почтовый индекс владельца анкеты (пользователя)
- **LastSeen** — дата последней активности пользователя
- **Price** — цена (евро) - **целевой**

# Что было изучено:
## Анализ алгоритмов  
- Вычислительная сложность  
- Время обучения линейной регрессии  
- Итеративные методы  
- Сравнение методов  

## Градиентный спуск  
- Методы оптимизации  
- Функция потерь  
- Градиент функции  
- Градиентный спуск  
- Градиентный спуск для линейной регрессии  
- Стохастический градиентный спуск  

## Градиентный бустинг  
- Ансамблевые методы  
- Градиентный бустинг  
- Регуляризация градиентного бустинга  
