Это тестовое задание в Гриднайн системс
описание:
даны перелеты самолетов (это коллекция)
перелеты созданы из сегментов , сегменты.объекты в свою очередь из двух значений ДатаВылета|ДатаПрилета
задача: создать 3 фильтра(функции) , которые будут обрабатывать коллекцию 
1.фильтр : исключить из коллекции перелеты где(вылет до настоящей даты времени)
2.Фильтр : исключить из коллекции перелеты где(имеются сегменты где дата прилета раньше даты вылета)
3.Фильтр : исключить из коллекции перелеты где(общее время пребывания на земле(это разница между прилетом и вылетом в след сегменте) будет больше 2 часов)

В классе Testclasses лежит тестовая коллекция с сегментами дат прилетов и вылетов, List<List<Flight>> , метод createFlights() ее возвращает 
