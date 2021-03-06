###  Исследование объявлений о продаже квартир  

**Данные**: архив объявлений сервиса `Яндекс.Недвижимость` о продаже квартир в `Санкт-Петербурге` и соседних населённых пунктов за несколько лет. По каждой квартире на продажу доступны два вида данных: 
* Первые вписаны пользователем 
* Вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

**Задача**: Установить ключевые параметры для определения рыночной стоимости объектов недвижимости. Установленные параметры позволят построить автоматизированную систему для отслеживания аномалий и мошеннических действий.

#### Выводы: 
   * Близость к аэропорту практически не влияет на цену кв.метра
   * Чем дальше от центра, тем меньше стоит квадратный метр.  
   * Самые дорогие метры в студиях и однокомнатных квартирах (медиана 100 - 110 тыс. рублей/кв.метр).
   * Самые дешевые квартиры на последнем этаже (~ 80-85 тыс. рублей/кв.метр), немного дороже на последних (~ 90 тыс. рублей/кв.метр), самые дорогие на промежуточных этажах  (~ 100 тыс. рублей/кв.метр) 
   * Цена квадратного метра имеет тенденцию к снижению, с ростом доли жилой площади, однако когда доля жилой площади становится более 70 % кв.метр снова вырастает.  
   * Увеличение доли кухни в общей площади повышает цену кв.метра
   * На цену кв.метра типовых квартир практически не оказывают влияния параметры окружения (парки, пруды), расположение (близость к аэропорту), за исключением близости к центру.  
   * На цену нетиповых квартир (студии, свободная планировка, апартаменты) влияние окружения очень сильное:  
     * Парки в радиусе 3 км - 91.8 % 
     * Высота потолков - 89.6 %  
     * Пруды в радиусе 3 км - 71.5 %
   * Квартира в среднем (и по медиане) продается за 3 месяца.
   
   *  Месяц, и день размещения не влияют на цену кв.метра 
   * Также можно сказать что цены в 2019 году вернулись на уровень цен 2014 года, в период с 2015-2017 наблюдалось снижение цен, в 2018 началось повышение цены. 