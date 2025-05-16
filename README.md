# RusDroneMakers

### *Russian language description*

Начиная с 2023 года [1] в России было зарегистрировано рекордное в истории количество компаний, специализирующихся на производстве авиатехники — 407. Многие из них связаны с производством дронов, установил The Insider, и многие производят именно те дроны, которые применяются на фронте. The Insider установил как минимум 140 компаний, производящих дроны — как новых, «кустарных» производств, так и старых, еще советских конструкторских бюро, и еще более 60 компаний и организаций, которые либо поставляют запчасти для них, либо перепродают их дроны, либо обучают операторов. В данном репозитории приводится полный список предприятий с указанием их продукции или роли в производстве применяемых в войне против Украины БПЛА.

**`companies.csv`**

Названия и идентификаторы компаний, что они производят или импортируют, а также связанные с ними компании и компании, обучающие пилотов дронов. 

| Поле      | Описание                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `company_short_name`        | Короткое название компании, по ЕГРЮЛ                            |
| `company_full_name`        | Полное название компании, по ЕГРЮЛ               |
| `ogrn`        |  Основной государственный регистрационный номер юридического лица (ОГРН)      |
| `inn`             | Идентификационный номер налогоплательщика (ИНН)    |
| `product`             | Дроны, которые компания производит    |
| `role`             | Роль компании в производственном процессе    |
| `urls`             | Ссылки на сайты и/или телеграм-каналы компании   |

**`company_data.csv`**

Основная информация об этих компаниях, включая: руководителей и совладельцев, если известны, дату регистрации, адрес регистрации, уставный капитал, численность сотрудников и другую информацию.

| Поле      | Описание                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `company_short_name`        | Короткое название компании, по ЕГРЮЛ                            |
| `company_full_name`        | Полное название компании, по ЕГРЮЛ               |
| `ogrn`        |  Основной государственный регистрационный номер юридического лица (ОГРН)      |
| `inn`             | Идентификационный номер налогоплательщика (ИНН)    |
| `reg_address`             | Адрес регистрации, по ЕГРЮЛ             |
| `current_director`             | Руководитель на апрель 2025 года (либо на момент ликвидации, если компания в процессе ликвидации)    |
| `phone_numbers`             | Номера телефонов   |
| `email`             | Адреса электронной почты   |
| `reg_date`             | Дата регистрации   |
| `reg_year`             | Год регистрации   |
| `clos_date`             | Дата ликвидации   |
| `current_owners`             | Совладельцы компании на апрель 2025 года (либо на момент ликвидации, если компания в процессе ликвидации), если известны |
| `reg_region`             | Регион регистрации   |
| `okved`             | Основной вид деятельности, согласно Общероссийскому классификатору видов экономической деятельности (ОКВЭД) |
| `prev_inn`             | Ранее использованные ИНН   |
| `prev_ogrn`             | Ранее использованные ОГРН   |
| `has_intellectual_property`             | Обладает ли компания интеллектуальной собственностью (патенты, изобретения, торговые знаки и т. д.)  |
| `has_certified_products`             | Обладает ли компания сертификатами на продукцию (как свою, так и других производителей)  |
| `company_size`             | Размер компании (в соответствии с [категориями](https://www.consultant.ru/document/cons_doc_LAW_52144/08b3ecbcdc9a360ad1dc314150a6328886703356/))   |
| `staff_2024`             | Средняя численность работников в штатном расписании за 2024 год  |
| `authorized_capital`             | Уставный капитал   |

### *English language description*

Since 2023 [1], at least 407 companies specializing in aircraft production have been newly registered in Russia, with many directly involved in the manufacture of military drones. *The Insider* has identified at least 140 drone manufacturers — ranging from newly formed *cottage* industries to legacy Soviet-era design bureaus — along with more than 60 other entities that supply parts, resell drones, or train UAV operators.

This repository provides a comprehensive list of these companies, detailing their roles in the production and deployment of drones used in the war against Ukraine.

**`companies.csv`**

Lists company names and identifiers, the types of drones or components they produce or import, and any links to drone pilot training operations.

| Column      | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `company_short_name`        | Company short name, according to the Russian state company register (EGRUL)     |
| `company_full_name`        | Company full name, according to the Russian state company register (EGRUL)   |
| `ogrn`        |  Primary state registration number of the legal entity (OGRN)      |
| `inn`             | Taxpayer ID number (INN)    |
| `product`             | UAVs produced by the company    |
| `role`             | Company’s role in the production process   |
| `urls`             | Links to the company’s websites and/or Telegram channels  |

**`companies.csv`**

Contains basic information such as company leadership, co-owners (if known), incorporation dates and addresses, authorized capital, employee count, and more.

| Column      | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| `company_short_name`        | Company short name, according to the Russian state company register (EGRUL)                   |
| `company_full_name`        | Company full name, according to the Russian state company register (EGRUL)            |
| `ogrn`        |  Primary state registration number of the legal entity (OGRN)    |
| `inn`             | Taxpayer ID number (INN)  |
| `reg_address`             | Registered address, according to the Russian state company register (EGRUL)       |
| `current_director`             | Director as of April 2025 (or at the time of liquidation, if the company is in the process of being dissolved)   |
| `phone_numbers`             | Phone numbers   
| `email`             | Emails |
| `reg_date`             | Registration date |
| `reg_year`             | Registration year  |
| `clos_date`             | Liquidation date   |
| `current_owners`             | Co-owners as of April 2025 (or at the time of liquidation, if the company is in the process of being dissolved), if known |
| `reg_region`             | Region of registration |
| `okved`             | Primary business activity according to the Russian National Classifier of Economic Activities (OKVED) |
| `prev_inn`             | Previously used Taxpayer ID Numbers (INN)  |
| `prev_ogrn`             | Previously used Primary State Registration Numbers (OGRN)   |
| `has_intellectual_property`             | Whether the company owns intellectual property (patents, inventions, trademarks, etc.)  |
| `has_certified_products`             | Whether the company holds certifications for its products (including third-party products)  |
| `company_size`             | Company size category (according to Russian [legislation](https://www.consultant.ru/document/cons_doc_LAW_52144/08b3ecbcdc9a360ad1dc314150a6328886703356/))   |
| `staff_2024`             | Average number of full-time employees in 2024  |
| `authorized_capital`             | Authorized capital  |

[1] From 2023-01-01 to 2025-04-30
