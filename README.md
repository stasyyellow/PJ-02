# PJ-02

# 📊 Анализ вакансий Data Scientist (HH.ru)

## Описание проекта
В рамках проекта проведён комплексный анализ вакансий Data Scientist на основе базы данных HH.ru.

Цель проекта - изучить рынок труда в сфере Data Science, выявить ключевые требования работодателей, уровень заработных плат и факторы, влияющие на доход специалистов.

Проект выполнен в рамках этапа Data Understanding, который включает исследование структуры данных и их соответствия задачам анализа.

---

## 🎯 Задачи проекта
- Знакомство с данными и их структурой
- Предварительный анализ вакансий
- Детальный анализ вакансий Data Scientist
- Анализ работодателей и регионов
- Предметный анализ (навыки, зарплаты, опыт)

---

## Структура данных

В проекте использованы следующие таблицы:

- `vacancies` - информация о вакансиях (зарплата, навыки, опыт)
- `areas` - регионы
- `employers` - работодатели
- `industries` - сферы деятельности
- `employers_industries` - связь работодателей и индустрий

---

## 🛠 Используемые технологии

- Python (pandas)
- SQL (PostgreSQL)
- Plotly (интерактивные графики)
- requests / html5lib (работа с данными)
- Jupyter Notebook

---

## 📈 Визуализация

В проекте построены интерактивные графики:

- Топ индустрий по количеству вакансий
- Частота и зарплата по комбинациям навыков
- Средняя зарплата по ключевым навыкам
- Зависимость зарплаты от количества навыков и опыта
- Сравнение зарплат по регионам и опыту

📁 Все графики сохранены в папке `plots/` в формате HTML и доступны для просмотра через браузер.

---

## 🔍 Основные результаты

- Рынок Data Science характеризуется высоким спросом, особенно в IT и консалтинге
- В среднем в вакансиях указывается около **6 навыков**, что отражает требования к T-shaped специалистам
- Наиболее востребованные навыки:
  - Python
  - SQL
  - Machine Learning
- Комбинации навыков (например, Python + ML) напрямую влияют на уровень зарплаты
- С увеличением количества навыков и опыта значительно растёт доход специалиста
- Наблюдается высокий порог входа: вакансий для начинающих существенно меньше

---

## 📊 Бизнес-инсайты

- Компании ищут универсальных специалистов с широким стеком навыков
- Владение Python и SQL является базовым требованием
- Machine Learning значительно повышает ценность кандидата
- Зарплаты сильно зависят от опыта и глубины экспертизы
- Наиболее высокие зарплаты сосредоточены в крупных регионах (Москва, СПб)

---


# PJ-02

# 📊 Data Scientist Job Market Analysis (HH.ru)

## Overview
This project presents a comprehensive analysis of Data Scientist job vacancies based on the HH.ru database.

The goal of the project is to explore the Data Science job market, identify key employer requirements, analyze salary levels, and determine the factors influencing specialists’ income.

The project is carried out as part of the Data Understanding stage, which includes exploring the data structure and assessing its relevance to analytical tasks.

---

## 🎯 Project Objectives
- Initial data exploration and structure analysis
- Exploratory data analysis (EDA)
- In-depth analysis of Data Scientist vacancies
- Analysis of employers and regions
- Domain-specific analysis (skills, salaries, experience)

---

## 📂 Data Structure

The project uses the following tables:

- `vacancies` - job vacancy data (salary, skills, experience)
- `areas` - regions
- `employers` - employers
- `industries` - industry sectors
- `employers_industries` - mapping between employers and industries

---

## 🛠 Technologies Used

- Python (pandas)
- SQL (PostgreSQL)
- Plotly (interactive visualizations)
- requests / html5lib (data handling)
- Jupyter Notebook

---

## 📈 Visualization

The project includes interactive visualizations such as:

- Top industries by number of vacancies
- Frequency and salary by skill combinations
- Average salary by key skills
- Salary dependence on number of skills and experience
- Salary comparison by region and experience level

📁 All charts are saved in the `plots/` folder in HTML format and can be viewed directly in a browser.

---

## 🔍 Key Findings

- The Data Science job market shows strong demand, especially in IT and consulting sectors
- On average, job postings list around **6 skills**, reflecting the demand for T-shaped specialists
- The most in-demand skills are:
  - Python
  - SQL
  - Machine Learning
- Skill combinations (e.g., Python + ML) have a direct impact on salary levels
- Salaries increase significantly with both experience and the number of skills
- There is a high entry barrier: significantly fewer вакансий for junior specialists

---

## 📊 Business Insights

- Companies are looking for versatile specialists with a broad skill set
- Proficiency in Python and SQL is a baseline requirement
- Machine Learning significantly increases candidate value
- Salaries strongly depend on experience and depth of expertise
- The highest salaries are concentrated in major regions (Moscow, Saint Petersburg)

---