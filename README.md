# Результаты стажировки в Яндекс.Доставке (RideTech)

Этот репозиторий содержит итоги моей 4-месячной стажировки в Яндекс.Доставке (RideTech), в команде алгоритмов курьерского продукта.

За время стажировки я занимался запуском и анализом A/B-тестов, улучшением ML-моделей, построением мониторингов и дашбордов, а также исследованием метрик, влияющих на эффективность курьеров.

---

## 📌 Описание

Я работал в команде, которая занимается развитием и оптимизацией ключевых метрик курьерского сервиса, таких как:

- SH (Supply Hours)
- DPH (Deliveries per Hour)
- AR (Acceptance Rate)
- CR (Complited Rate)
- Utilization
- Contact Rate  
...и других.

Мои задачи включали полный цикл работы с экспериментами — от гипотезы до аналитики результатов и мониторинга в продакшене + выводы.

---

## 💼 Ключевые достижения

### 🔬 A/B-тестирование

- Запустил и проанализировал **5+ A/B-тестов**
- Провёл отдельный **A/A-тест**, чтобы оценить стабильность выборки и надёжность курьеров
- Углублённо анализировал эффекты и влияющие факторы

> 📌 **Пример**: В одном из тестов я выявил, что использование дополнительного устройства на точке выдачи может заметно сократить время ожидания курьеров  
> *(подробности скрыты в рамках NDA)* <!-- NDA: redacted -->

### 🤖 Работа с ML-моделью

- Провёл большое исследование логики одной из ML-моделей в продакшене
- Предложил и внедрил **улучшенную версию модели**
- Подкрепил изменения теоретическим анализом и практическими результатами

### 📊 Мониторинг и визуализация

- Создал множество **дашбордов и алертов** для трекинга метрик в реальном времени
- Настроил систему мониторинга для A/B и A/A тестов

---

## 🚀 Основные результаты

- 📉 Снизил среднее время ожидания курьеров на точке выдачи на ~X% (X - существенно влияет на прибыль компании)*(подробности скрыты в рамках NDA)* <!-- NDA: redacted -->
- 📈 Провёл A/A тест на надёжность курьеров
- 🔄 Улучшил ML-модель, доказал её эффективность теоретически и на практике
- 📊 Построил полноценную систему мониторинга и визуализации метрик

---

## 🛠 Используемые технологии

- `YQL` (Yandex Query Language) + `SQL`
- `ClickHouse`, `YT`
- `Python`
- Внутренние инструменты Яндекса для A/B-тестов, мониторинга и визуализации (`Datalens`, `Nirvana`, etc)

---

## 📂 Структура репозитория

```text
/YQL_example.txt      — Большой пример кода на YQL
/Nirvana/             — Проекты в Nirvana реализованные блоками кода с автозапуском
/Dashboards/          — Примеры дашбордов и мониторингов (описания, скриншоты)  
README.md             — Этот файл

---
====================================================================================


# Internship Results at Yandex.Dostavka (RideTech)

This repository contains the results of my 4-month internship at **Yandex.Dostavka (RideTech)**, in the courier product algorithms team.

During the internship, I worked on launching and analyzing A/B tests, improving ML models, building monitoring systems and dashboards, as well as researching metrics that affect courier efficiency.

---

## 📌 Overview

I was part of a team responsible for developing and optimizing key courier service metrics such as:

- SH (Supply Hours)
- DPH (Deliveries per Hour)
- AR (Acceptance Rate)
- CR (Completed Rate)
- Utilization
- Contact Rate  
...and others.

My tasks included the **full experiment cycle** — from hypothesis generation to result analysis, production monitoring, and drawing conclusions.

---

## 💼 Key Achievements

### 🔬 A/B Testing

- Launched and analyzed **5+ A/B tests**
- Conducted a dedicated **A/A test** to assess sample stability and courier reliability
- Performed in-depth analysis of effects and influencing factors

> 📌 **Example**: In one test, I discovered that using an additional device at the pick-up point can significantly reduce courier waiting time  
> *(details hidden under NDA)* <!-- NDA: redacted -->

### 🤖 ML Model Work

- Conducted an in-depth study of the logic behind one of the production ML models
- Proposed and implemented an **improved version of the model**
- Supported changes with both theoretical analysis and practical results

### 📊 Monitoring & Visualization

- Created multiple **dashboards and alerts** for real-time metric tracking
- Set up a monitoring system for both A/B and A/A tests

---

## 🚀 Main Outcomes

- 📉 Reduced average courier waiting time at pick-up points by ~X% (X — significantly impacts company profit) *(details hidden under NDA)* <!-- NDA: redacted -->
- 📈 Conducted an A/A test to evaluate courier reliability
- 🔄 Improved an ML model and proved its effectiveness both theoretically and in practice
- 📊 Built a complete monitoring and visualization system for metrics

---

## 🛠 Technologies Used

- `YQL` (Yandex Query Language) + `SQL`
- `ClickHouse`, `YT`
- `Python`
- Yandex internal tools for A/B testing, monitoring, and visualization (`Datalens`, `Nirvana`, etc.)

---

## 📂 Repository Structure

```text
/YQL_example.txt      — Large example of YQL code
/Nirvana/             — Projects in Nirvana implemented with code blocks and auto-execution
/Dashboards/          — Examples of dashboards and monitoring (descriptions, screenshots)  
README.md             — This file