# Проект: Исследование коллекций Метрополитен-музея

В этом проекте проводится анализ коллекций Метрополитен-музея с использованием их открытого API. Доступ к данным музея позволяет исследовать экспонаты, департаменты и выполнять тематические поисковые запросы для изучения музейных коллекций.

## Цели и задачи

1. **Поиск произведений на определенную тематику**  
   Выполнение запросов по ключевым словам, таким как "sunflowers", чтобы собрать список объектов, связанных с заданной темой.

2. **Изучение характеристик объектов**  
   Сбор и анализ данных для каждого найденного объекта, включая следующие параметры:
   - `objectID` — уникальный идентификатор объекта
   - `title` — название произведения
   - `artistDisplayName` — автор
   - `department` — департамент музея
   - `objectBeginDate` — дата создания (начало)
   - `objectEndDate` — дата создания (конец)
   - `period` — название периода
   - `objectName` — название/категория объекта
   - `culture` — культура происхождения

3. **Анализ объектов по культуре и периоду**  
   Определение количества произведений, относящихся к определённой культуре (например, Японии), а также анализ распределения объектов по историческим периодам.

4. **Расширенный поиск по департаментам**  
   Использование более сложных параметров поиска для анализа объектов в определённом департаменте, таких как произведения из "Asian Art" с тегом "cat", для изучения распределения объектов по периодам.

## Используемые данные

Проект использует данные из следующих разделов API:
- **Objects** — данные об отдельных объектах (например, картинах)
- **Search** — поисковый раздел для получения списков объектов по ключевым словам и фильтрам
- **Departments** — данные о департаментах музея (например, "Современное искусство")

Документация API: [The Met Museum API Documentation](https://metmuseum.github.io)

## Выводы

Проект позволяет ознакомиться с основными возможностями API Метрополитен-музея и провести базовый анализ музейных коллекций. Такой подход помогает понять способы работы с данными культурных учреждений и может быть полезен для будущих аналитических или исследовательских проектов.


# Project: Exploring The Met Museum Collections

This project analyzes The Met Museum collections using their open API. Access to the museum's data allows for exploring exhibits, departments, and performing thematic queries to study the museum's collections.

## Goals and Objectives

1. **Search for works on specific themes**  
   Perform queries using keywords such as "sunflowers" to gather a list of objects related to a given theme.

2. **Study object characteristics**  
   Collect and analyze data for each found object, including the following parameters:
   - `objectID` — unique object identifier
   - `title` — title of the artwork
   - `artistDisplayName` — artist
   - `department` — museum department
   - `objectBeginDate` — creation date (start)
   - `objectEndDate` — creation date (end)
   - `period` — historical period name
   - `objectName` — object name/category
   - `culture` — culture of origin

3. **Analyze objects by culture and period**  
   Determine the number of works associated with specific cultures (e.g., Japan) and analyze the distribution of objects across historical periods.

4. **Advanced search by department**  
   Use more complex search parameters to analyze objects in specific departments, such as works from "Asian Art" with the tag "cat," to study the distribution of objects by period.

## Data Used

The project utilizes data from the following API sections:
- **Objects** — data about individual objects (e.g., paintings)
- **Search** — search section for retrieving object lists by keywords and filters
- **Departments** — information about museum departments (e.g., "Modern Art")

API Documentation: [The Met Museum API Documentation](https://metmuseum.github.io)

## Conclusions

The project provides an introduction to the main capabilities of The Met Museum API and enables a basic analysis of the museum's collections. This approach helps understand how cultural institution data can be used and may be beneficial for future analytical or research projects.