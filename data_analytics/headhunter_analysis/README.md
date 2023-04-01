# Headhunter analysis

## Оглавление

[1. Основные цели и задачи проекта](https://github.com/dissf/pet-projects/blob/main/data_analytics/headhunter_analysis/README.md#Основные-цели-и-задачи-проекта)  
[2. Краткая информация о данных](https://github.com/dissf/pet-projects/blob/main/data_analytics/headhunter_analysis/README.md#Краткая-информация-о-данных)  
[3. Полезные библиотеки](https://github.com/dissf/pet-projects/blob/main/data_analytics/headhunter_analysis/README.md#Полезные-библиотеки)

### Основные цели и задачи проекта

Необходимо собрать информацию о всех вакансиях в сфере аналитики, проанализировать, выявить самые востребованные направления, 
определить ключевые навыки и уровень заработной платы для каждого направления. Полученные данные помогут понять, что сейчас происходит на рынке труда, 
в каком направлении стоит двигаться, какие навыки и технологии сейчас актуальны.

### Краткая информация о данных
Данные отсутствуют, их необходимо собрать.  
Из направлений в сфере аналитики рассмотрим вакансии по таким запросам:  
**Data analyst**,  
**System analyst**,  
**BI analyst**,  
**Business analyst**,   
**Product analyst**,  
**Data engineer**,  
**Machine learning engineer**,  
**Data scientist**,  
**Quantitative researcher**  
 
 
Собираем с сайта hh.ru  
Для анализа необходимы такие данные:  
        **id** — уникальный id, по которому можно однозначно определить вакансию   
        **name** — название вакансии  
        **company** — работодатель(компания)  
        **salary** — зарплата  
        **experience** — требуемый опыт работы  
        **schedule** — тип занятости и график работы  
        **published_at** — дата публикации  
        **tags** — ключевые навыки  
        **role** — тег, который показывает по какому запросу получили эту вакансию

### Полезные библиотеки

* pandas  
* re  
* plotly
* requests
* bs4
