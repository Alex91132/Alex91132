<h1 align="center">Александр Федоров</h1>

<p align="center">
  <b>Аналитик данных и руководитель проектов · 11+ лет в нефтегазе</b><br>
  A/B-тесты · причинный анализ · SQL и Python · инженерия данных
</p>

<p align="center">
  <a href="https://alex91132.github.io/"><b>Портфолио</b></a> ·
  <a href="https://alex91132.github.io/assets/rezume-fedorov.pdf">Резюме (PDF)</a> ·
  <a href="https://t.me/Alex91132">Telegram</a> ·
  <a href="mailto:alexandr91132@gmail.com">alexandr91132@gmail.com</a>
</p>

---

10+ лет был инженером-нефтяником: бурение, ГРП, планирование скважин. Сейчас веду разработку
ИИ-помощников и расчётных продуктов для нефтегазовой отрасли — собираю требования у экспертов,
готовлю данные, валидирую модели, руковожу командой разработки.

В pet-проектах беру задачи, которые решаются на работе, и довожу их до конца: план анализа,
проверка методов на данных с известным ответом, тесты, CI, живая демо и записка с решением.

## Проекты

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://alex91132.github.io/ab-case-email-campaign/"><img src="assets/ab-case.jpg" alt="Записка с решением по email-рассылке"></a>
      <br><b>A/B-кейс на реальных данных: какую рассылку слать и кому</b>
      <br>64 000 клиентов, три группы. План анализа закоммичен до результатов, поправка Холма,
      бутстреп, экономика, таргетинг на отложенной выборке. Итог — <b>+$767&nbsp;на&nbsp;1&nbsp;000&nbsp;писем</b>.
      <br><a href="https://alex91132.github.io/ab-case-email-campaign/">Записка</a> ·
      <a href="https://github.com/Alex91132/ab-case-email-campaign">Код</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://alex91132.github.io/ab-testing-engine/"><img src="assets/ab-engine.jpg" alt="Отчёт движка анализа A/B-экспериментов"></a>
      <br><b>Движок анализа A/B-экспериментов</b>
      <br>Логи → DuckDB → метрики на SQL → SRM, CUPED, дельта-метод, Холм, mSPRT и
      О'Брайен — Флеминг → HTML-отчёт. Каждый метод проверен на 3 000 симулированных экспериментов.
      <br><a href="https://alex91132.github.io/ab-testing-engine/">Отчёты</a> ·
      <a href="https://github.com/Alex91132/ab-testing-engine">Код</a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://alex91132.github.io/gtm-causal-inference/"><img src="assets/gtm-causal.jpg" alt="Оценки эффекта ГРП восемью методами"></a>
      <br><b>Сколько нефти дал ГРП: причинный анализ</b>
      <br>8 методов — от «до/после» до синтетического контроля — против известной истины.
      Монте-Карло: «до/после» занижает эффект на треть, подбор контрольной группы ошибается на 1–2 %.
      <br><a href="https://alex91132.github.io/gtm-causal-inference/">Демо</a> ·
      <a href="https://github.com/Alex91132/gtm-causal-inference">Код</a>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/Alex91132/oil-production-dwh"><img src="assets/oil-dwh.jpg" alt="Дашборд Superset по нефтедобыче"></a>
      <br><b>Платформа данных нефтедобычи</b>
      <br>PostgreSQL → Airflow → ClickHouse → Superset. Целостность на уровне БД, партиционирование,
      идемпотентный ETL со сверкой с источником, дашборд «как код». Поднимается одной командой в Docker.
      <br><a href="https://github.com/Alex91132/oil-production-dwh">Код</a>
    </td>
  </tr>
</table>

**Ещё:**

* [Симулятор A/B-тестов](https://alex91132.github.io/ab-simulator/) — размер выборки, мощность, Монте-Карло на чистом JS
* [Ковёр бурения](https://alex91132.github.io/drilling-carpet/) — график движения буровых установок из Excel
* [REST API на FastAPI](https://github.com/Alex91132/houses_ms) — каталог объектов, в разработке

## Стек

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![ClickHouse](https://img.shields.io/badge/ClickHouse-FFCC01?style=flat-square&logo=clickhouse&logoColor=black)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Greenplum](https://img.shields.io/badge/Greenplum-008B6E?style=flat-square)
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
<br>
![Superset](https://img.shields.io/badge/Superset-20A6C9?style=flat-square&logo=apachesuperset&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Методы:** A/B-тесты (SRM, CUPED, дельта-метод, последовательный анализ, множественные сравнения),
причинный анализ (DiD, сопоставление по пропенсити, синтетический контроль), бутстреп, Монте-Карло,
валидация ML-моделей.

<details>
<summary><b>In English</b></summary>
<br>

Data analyst and project lead with 11+ years in oil & gas — drilling, hydraulic fracturing, well planning.
Today I lead development of AI assistants and engineering calculation products for the industry:
gathering requirements from domain experts, preparing data, validating models, managing the dev team.

Pet projects: an A/B-testing engine in Python (SRM, CUPED, delta method, mSPRT, O'Brien–Fleming, every
method validated by simulation), a real-data A/B case with a pre-registered analysis plan, causal inference
for oil-well treatments (8 estimators benchmarked against known ground truth), and an oil production data
platform (PostgreSQL → Airflow → ClickHouse → Superset). Docs are in Russian; numbers, code and tests are universal.

Open to relocation and remote work.
[Portfolio](https://alex91132.github.io/) · [Telegram](https://t.me/Alex91132) · alexandr91132@gmail.com
</details>
