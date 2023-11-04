
**Относительные xPath'ы для чек-боксов:**

//*[@formcontrolname="pledgeSber"] - чек-бокс "Залог Сбербанка"  

//*[@formcontrolname="isManualInput"] - чек-бокс "Заполнить вручную"  

//*[@formcontrolname="withoutStreet"] - чек-бокс "Улица отсутствует"  

//*[@formcontrolname="matchesAddress"] - чек-бокс "Адрес имущества совпадает с адресом регистрации"  

//*[@formcontrolname="withoutPropertyStreet"] - чек-бокс "Улица отсутствует", раздел Адрес имущества. Или:  
//span[contains (text(), "Улица отсутствует")]//ancestor::mat-checkbox//input - чек-бокс "Улица отсутствует"  

//*[@formcontrolname="isEmptyMiddleName"] - чек-бокс "Отчество отсутствует"  

//*[@id="mat-checkbox-5"] - чек-бокс "Покрытие по риску терроризм". Или:  
//span[contains(text(), "Покрытие по риску терроризм")]/ancestor::mat-checkbox//input - чек-бокс "Покрытие по риску терроризм"  

//span[contains(text(), "Покрытие по риску диверсия")]/ancestor::mat-checkbox//input - чек-бокс "Покрытие по риску диверсия"  

//span[contains(text(), "Покрытие по риску народные волнения")]/ancestor::mat-checkbox//input - чек-бокс "Покрытие по риску народные волнения"   

//span[contains(text(), "Покрытие по риску бой стекол")]/ancestor::mat-checkbox//input - чек-бокс "Покрытие по риску бой стекол"   

//span[contains(text(), "Покрытие по риску не капитальный ремонт")]/ancestor::mat-checkbox//input - чек-бокс "Покрытие по риску не капитальный ремонт"  

//span[contains(text(), "Внезапные и непредвиденные расходы по расчистке территории от последствий возникновения ущерба")]/ancestor::mat-checkbox//input - чек-бокс "Внезапные и непредвиденные расходы по расчистке территории от последствий возникновения ущерба"  

//span[contains(text(), "Внезапные и непредвиденные расходы по ограждению, укрепленю, обшивке материалами, герметизации или поддержке зданий, сооружений или застрахованного имущества для обеспечения их безопасности")]/ancestor::mat-checkbox//input - чек-бокс "Внезапные и непредвиденные расходы по ограждению, укрепленю, обшивке материалами, герметизации или поддержке зданий, сооружений или застрахованного имущества для обеспечения их безопасности"   

//span[contains(text(), "Расходы на перемещение и защиту")]/ancestor::mat-checkbox//input - чек-бокс "Расходы на перемещение и защиту"  

//span[contains(text(), "Расходы по благоустройству территории")]/ancestor::mat-checkbox//input - чек-бокс "Расходы по благоустройству территории"  

//span[contains(text(), "Расходы по замене ключей, замков, мастер-ключей и т. д. (в случае их хищения)")]/ancestor::mat-checkbox//input - чек-бокс "Расходы по замене ключей, замков, мастер-ключей и т. д. (в случае их хищения)"

**Относительные xPath'ы для кнопок:**

//\*[contains(text(),'Юридическое лицо')]/parent::button - кнопка "Юридическое лицо". Или:   
//button[*[contains(test(), "Юридическое лицо")]] - кнопка "Юридическое лицо"  

//\*[contains(text(),'Индивидуальный предприниматель')]/parent::button - кнопка "Индивидуальный предприниматель". Или:  
//button[*[contains(test(), "Индивидуальный предприниматель")]] - кнопка "Индивидуальный предприниматель"  
 
//button[*[contains(text(), "Гражданин РФ")]] - кнопка "Гражданин РФ"   

//button[*[contains(text(), "Иностранный гражданин")]] - кнопка "Иностранный гражданин"   

//button[@aria-label="Open calendar"] - кнопка "Календарь"   
 
//\*[@id="mat-button-toggle-59"] - кнопка "Женский"  
//button[*[contains(text(), "Женский")]] - кнопка "Женский"  

//button[*[contains(text(), "Мужской")]] - кнопка "Мужской"  

//button[*[contains(text(), "Добавить объект")]] - кнопка "Добавить обьект"  

//button[*[contains(text(), "Добавить территорию")]] - кнопка "Добавить территорию"   

//button[*[contains(text(), "Добавить договор")]] - кнопка "Добавить договор"  

//h4[text()="Залоговый договор 1"]/following-sibling::div//button[*[contains(text(), "Добавить договор")]] - кнопка "Добавить договор", раздел "Залоговый договор 1"  

//h4[text()="Кредитный договор 1"]/following-sibling::div//button[*[contains(text(), "Добавить договор")]] - кнопка "Добавить договор", раздел "Кредитный договор 1"  

//button[*[contains(text(), "Удалить договор 1")]] - кнопка "Удалить договор 1"  

//button[*[contains(text(), "Рассчитать")]] - кнопка "Рассчитать"    

//button[*[contains(text(), "Назад")]] - кнопка "Назад"  


**Относительные xPath'ы для кнопок Декларации страхователя**:  
по порядку размещения на сайте:  
//\*[@id="stop1"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 1 "Является законсервированным ......?", кнопка "Да". Или:  
//\*[contains (text (), "Является законсервированным, под реконструкцией, незавершенным строительством")]/following-sibling::mat-button-toggle-group//button[*[contains(text(), "Да")]] - Вопрос 1 "Является законсервированным ......?", кнопка "Да"    
//\*[@id="stop1"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 1 "Является законсервированным ......?", кнопка "Нет"  

//\*[@id="stop2"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 2, кнопка "Да"  
//\*[@id="stop2"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 2, кнопка "Нет"  

//\*[@id="stop3"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 3, кнопка "Да"  
//\*[@id="stop3"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 3, кнопка "Нет"  

//\*[@id="stop4"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 4, кнопка "Да"  
//\*[@id="stop4"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 4, кнопка "Нет"  

//\*[@id="stop5"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 5, кнопка "Да"  
//\*[@id="stop5"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 5, кнопка "Нет"  

//\*[@id="stop6"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 6, кнопка "Да"  
//\*[@id="stop6"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 6, кнопка "Нет"  

//\*[@id="stop7"]/descendant::button[\*[contains(text(), "Да")]] - Вопрос 7, кнопка "Да"  
//\*[@id="stop7"]/descendant::button[\*[contains(text(), "Нет")]] - Вопрос 7, кнопка "Нет"  


 
**Относительные xPath'ы для полей ввода**:  

//input[@formcontrolname="autoSearch"] - поле ввода текста "Поиск по наименованию/ИНН/ОГРН"  

//input[@data-placeholder="Поиск по ФИО/ИНН/ОГРНИП"] - поле ввода текста "Поиск по ФИО/ИНН/ОГРНИП"  

//input[@formcontrolname="registrationCountry"] - поле ввода "Страна регистрации*"  

//input[@formcontrolname="InsurerFullName"] - поле ввода "Полное наименование*"  

//input[@formcontrolname="inn"] - поле ввода "ИНН*" Юр.лица   

//input[@formcontrolname="kpp"] - поле ввода "КПП*" Юр.лица  

//input[@formcontrolname="ogrn"] - поле ввода "ОГРН*"  

//input[@data-placeholder="Регион"] - поле ввода "Регион*"  

//input[@data-placeholder="Город или населенный пункт"] - поле ввода "Город или населенный пункт*"   

//input[@data-placeholder="Улица"] - поле ввода "Улица*"  

//input[@data-placeholder="Дом, литер, корпус"] - поле ввода "Дом, литер, корпус*"   
//input[@data-placeholder="Офис, помещение"] -  поле ввода "Офис, помещение*"  

//input[@data-placeholder="Фамилия"] - поле ввода "Фамилия*"  

//input[@data-placeholder="Имя"] - поле ввода "Имя*"  

//input[@data-placeholder="Отчество"] - поле ввода "Отчество*"   

//input[@formcontrolname="insurerInn"] - поле ввода "ИНН*" ИП  

//input[@formcontrolname="ogrnip"] - поле ввода "ОГРНИП*"  

//input[@data-placeholder="Класс опасности"] - поле ввода "Класс опасности"  

 //input[@data-placeholder="Требование к АПС"] - поле ввода "Требование к АПС"  

 //*[@id="mat-select-value-5"] - выбор значения в поле "Наличие АПС"  

 //span[contains (text (), "Обработка металла, изделий из металла")]//ancestor::mat-select - выбор значения "Обработка металла, изделий из металла" в поле "Отрасль"  

 //input[@data-placeholder="Год постройки здания или последний кап.ремонт"] - поле ввода "Год постройки здания или последний кап.ремонт"      

 //mat-label[contains (text (), "Ремонтные/отделочные работы ведутся на объекте/планируются")]//ancestor::span - поле "Ремонтные/отделочные работы ведутся на обьекте"  

 //input[@data-placeholder="Расшифровка названия обьекта"] - поле ввода "Расшифровка названия обьекта"  

//input[@formcontrolname="propertyRegion"] - поле ввода "Регион"  

//input[@formcontrolname="propertyCity"] - поле ввода "Город"  

//input[@formcontrolname="propertyStreet"] - поле ввода "Улица"  

//input[@data-placeholder="Офис\помещение"] - поле ввода "Офис\помещение"  

//input[@data-placeholder="Кадастровый номер"] - поле ввода "Кадастровый номер"  

//input[@data-placeholder="Площадь обьекта"] - поле ввода "Площадь обьекта"  

//input[@data-placeholder="Страховая сумма"] - поле ввода "Страховая сумма"  

//input[@data-placeholder="Страховая стоимость"] - поле ввода "Страховая стоимость"  

//input[@data-placeholder="Номер"] - поле ввода "Номер", раздел "Залоговый договор 1"  

//input[@formcontrolname="loanNumber"] - поле ввода "Номер", раздел "Кредитный договор 1"  

//input[@data-placeholder="Телефон"] - поле ввода "Телефон*"  

//input[@data-placeholder="Электронная почта *"] - поле ввода "Электронная почта"  

//input[@data-placeholder="Дополнительная электронная почта"] - поле ввода "Дополнительная электронная почта"  

//input[@data-placeholder="Франшиза"] - поле ввода "Франшиза"  

//input[@data-placeholder="Введите промокод"] - поле ввода "Введите промокод"

**Относительные xPath'ы для датапикеров**:  
//input[@formcontrolname="insurerBirthday"] - поле ввода "Дата рождения*"  
//input[@formcontrolname="startDate"] - поле ввода даты начала страхования  
//input[@formcontrolname="pledgeDate"] - поле ввода даты заключения, раздел "Залоговый договор 1"  
//input[@formcontrolname="loanDate"] - поле ввода даты заключения, раздел "Кредитный договор 1"

**Относительный xPath для слайдера выбора срока страхования:**   
//*[@formcontrolname="monthCount"]/descendant::input - движение слайдера в зависимости от ввода количества месяцев.  
//div[@class="mat-slider-wrapper"] - слайдер

**Относительный xPath для логотипа "СберСтрахование":**  
  
//*[contains(@class, "header__logo")]

**Относительный xPath для хедера "Данные страхователя"**:  

//*[contains(@class, "contact-form__insurant")]/descendant::h4  

//*[contains(@class, "contact-form__insurant")]//h4  

**Относительные xPath'ы для текстовых блоков**:  

//p[contains(@class, "date-police")] - блок "Укажите дату начала действия полиса и срока страхования"  

//span[contains(@class, "stop1")] - блок "Является законсервированным, под реконструкцией, незавершенным строительством"