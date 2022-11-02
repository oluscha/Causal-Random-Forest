# Описание данных
ID – индекс посетителя интернет-магазина, где продаются билеты 1

T – тритмент переменная (0 или 1), показывающая вариант ценообразования А или B

bus_offers_count – количество предложений в выдаче

passenger_count – запрашиваемое пользователем количество билетов

direction_conv – показатель, связанный с конверсией по данному направлению (давайте называть его конверсией)

Характеристики цены в выдаче (руб.): price_mean, price_min, price_max, price_std (це- на средняя, минимальная, максимальная, стандартное отклонение)
Характеристики рейтинга в выдаче (на основе отзывов пользователей): final_rating_mean, final_rating_min, final_rating_max, final_rating_std, final_rating

dist – расстояние, на которое осуществляется перевозка (км)

depth – глубина поиска (т.е. через сколько дней планируется поездка)

global_source_direct = 1, если пользователь пришёл в интернет-магазин через поисковик, 0 иначе

global_source_marketing = 1, если пользователь пришёл в интернет-магазин через рекламное объявление, 0 иначе

bus_entry = 1, если пользователь сразу пришёл на страницу с автобусами (не переходя с других страниц сайта), 0 иначе

search_wen_th – =1, если поиск в магазине осуществлялся пользователем в среду или четверг, 0 иначе

search_fr_sat_sun – =1, если поиск в магазине осуществлялся пользователем в пятницу, субботу или воскресенье, 0 иначе

dep_wen_th – бинарная характеристика поиска: =1, если отъезд пользователя в среду или четверг

dep_fr_sat_sun – бинарная характеристика поиска: =1, если отъезд в пятницу, субботу или воскресенье

arrival_huge_city – бинарная характеристика поиска, =1, если конечная точка город средних размеров

arrival_avg_city – бинарная характеристика поиска, =1, если конечная точка крупный город

departure_huge_city – =1, если отъезд из крупного города departure_avg_city – =1, если отъезд из среднего города arrival_msk – =1, если конечная точка Москва departure_msk – =1, если отъезд из Москвы

arrival_spb – =1, если конечная точка Санкт-Петербург

departure_spb – =1, если отъезд из Санкт-Петербурга

Переменные, связанные с количеством посещений данным пользователем страницы с билетами на разные виды транспорта за некоторый предшествующий период: avia_page – переменная, отражающая количество посещений страницы с рейсами на самолёт за неко- торый предшествующий промежуток времени train, etrain, bus_pages, tours – то же самое для поездов, электричек и автобусов, туров (туристических поездок)

Переменные, связанные с количеством заказов товара из определённого вида транспорта пользователем за некоторый предшествующий период: avia_orders - самолёты, bus_orders - автобусы, zhd - поезда.

buy – факт покупки билетов на автобус (1 или 0)

profit – прибыль компании в условных единицах от этой покупки
