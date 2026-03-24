# 👋 Hi, I'm Palina Krasiuk

## 👩‍💻 About Me

Aspiring **Cloud Data Engineer** with 15+ years of experience as a **Chief Accountant**, now transitioning into data engineering.  

Specializing in **ETL pipelines**, **data analysis**, and **visualization**, I transform raw data into actionable insights. Currently completing the IBM Data Engineer Professional Certificate on Coursera, focusing on modern data engineering tools and practices.

I value **accuracy**, **clarity**, and **structured workflows**, and I genuinely **love working with data and numbers**. My strong accounting background ensures data integrity, precision, and reliability, while my meticulous approach guarantees high-quality, actionable results.  

💡 **Open to**: collaboration, internships, and job opportunities  
📍 **Location**: Poland

---

## 🛠 Tech Stack  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-000000?style=for-the-badge&logo=apachekafka&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![IBM Db2](https://img.shields.io/badge/IBM%20Db2-054ADA?style=for-the-badge&logo=ibm&logoColor=white)

![MongoDB](https://img.shields.io/badge/MongoDB-NoSQL-green?style=for-the-badge&logo=mongodb&logoColor=white)
![Apache Cassandra](https://img.shields.io/badge/Apache%20Cassandra-1287B1?style=for-the-badge&logo=apachecassandra&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

![IBM Cognos](https://img.shields.io/badge/IBM%20Cognos-054ADA?style=for-the-badge&logo=ibm&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Google%20Looker%20Studio-4285F4?style=for-the-badge&logo=google&logoColor=white)

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)


---

## 🧠 Skills
- **Programming:** Python (Pandas, NumPy), OOP  
- **Databases:** PostgreSQL, MySQL, Oracle, IBM Db2, MongoDB (NoSQL), Apache Cassandra  
- **Data Engineering:** ETL pipelines (batch & streaming), Apache Airflow (DAGs), Apache Kafka, data modeling, CSV/COPY exports  
- **BI & Visualization:** IBM Cognos Analytics, Google Looker Studio, Jupyter, Matplotlib  
- **Bash & Linux:** Bash scripting, cron automation, CLI tools (curl, grep, awk, cut)  
- **Cloud & Tooling:** GitHub Codespaces (hands-on)  
- **Learning:** AWS, GCP  
- **Foundations:** Data Engineering & Data Science fundamentals  

---

🌍 **Languages**: Russian (native), Polish (B1), English (B1 → actively improving)  

---

## 🚀 My Projects

### 🏗️ [DBA Capstone Project – End-to-End Relational Data Platform](https://github.com/CloudDataPalina/dba-capstone-project)

A comprehensive **enterprise-level database administration project** simulating a real-world **e-commerce data platform**.
- Designed and implemented a production-style **OLTP system (MySQL)** with transactional schema, indexing, and data validation
- Built a **PostgreSQL Data Warehouse** (fact & dimension tables, analytical queries, materialized views)
- Developed automated **ETL pipelines using Apache Airflow (DAGs)** for data extraction and loading
- Implemented **backup & restore automation** with Bash and CRON (disaster recovery scenarios included)
- Applied **query optimization, execution plan analysis, RBAC access control, and data encryption**
- Structured into **5 modular components**: OLTP, DWH, ETL, Backup, Security & Performance

This project demonstrates full lifecycle **database design, administration, automation, and optimization** in a hybrid OLTP + Data Warehouse architecture.

**Tools:** `MySQL`, `PostgreSQL`, `Apache Airflow`, `Python`, `Bash`, `Linux`, `pgAdmin`, `phpMyAdmin`, `GitHub Codespaces`

---

### 🎬 [Movies Data Engineering Pipeline (MongoDB → Cassandra)](https://github.com/CloudDataPalina/movies-data-engineering-pipeline)

An end-to-end **NoSQL data pipeline** for data ingestion, transformation, and cross-system transfer.

- Imported JSON data into **MongoDB**
- Performed analytical queries using **aggregation pipelines**
- Exported processed data to **CSV**
- Loaded data into **Apache Cassandra**
- Created schema, index, and executed **CQL** queries

Demonstrates **ETL workflow, JSON → CSV transformation, and NoSQL system integration**.

**Tools:** `MongoDB`, `Mongo Shell`, `mongoimport/mongoexport`, `Apache Cassandra`, `CQL`, `JSON`, `CSV`, `Linux CLI`

---

### 📊 [Automotive Sales & Service BI Analytics](https://github.com/CloudDataPalina/automotive-sales-bi)

Executive **Business Intelligence project** focused on sales performance and product quality monitoring.

- Built **KPI-driven dashboards** (Total Profit, Units Sold, Dealer Efficiency)
- Analyzed profit concentration and dealer performance gaps
- Evaluated model-level sales distribution and seasonality trends
- Designed recall risk heatmap and defect **clustering analysis**
- Integrated customer sentiment segmentation
- Replicated analytical logic in **IBM Cognos** and **Google Looker Studio**

Demonstrates executive dashboard design and cross-platform BI implementation..

**Tools:** `IBM Cognos Analytics`, `Google Looker Studio`, `Data Visualization`, `Business Intelligence`

---

### 🚦 [Toll Data Pipelines (Airflow & Kafka)](https://github.com/CloudDataPalina/toll-data-pipelines-airflow-kafka)

An end-to-end **batch + streaming data engineering project** for processing traffic toll data using **Apache Airflow** and **Apache Kafka**.
- Batch ETL pipelines orchestrated with **Apache Airflow** (BashOperator & PythonOperator)
- Real-time streaming ingestion with **Apache Kafka → MySQL**
- Vehicle passage events consumed from Kafka topic `toll`
- Streaming data persisted in **MySQL** (`livetolldata table`)
- Tested in **GitHub Codespaces** with local Kafka & MySQL services
- Includes a clear **README** with architecture, data flow diagram, and sample output

**Tools:** `Apache Airflow`, `Apache Kafka`, `Python`, `Bash`, `MySQL`, `Linux CLI`, `GitHub Codespaces`

---

### 🌦️ [Bash Weather Forecast Pipeline](https://github.com/CloudDataPalina/bash-weather-pipeline)

A fully automated **Bash-based data pipeline** that collects weather data and evaluates forecast accuracy.
- Daily data collection from **wttr.in** using curl
- Parsing observed vs forecasted temperatures
- Forecast accuracy calculations and weekly summaries
- Automated backups with timestamped `.tar.gz` archives
- Reproducible runs and execution logs in **GitHub Codespaces**
- Detailed **README** with pipeline diagram and sample output

**Tools:** `Bash`, `curl`, `cron`, `grep/awk/cut`, `tar/gzip`, `Linux CLI`, `GitHub Codespaces`

---
 
### 🏙️ [Chicago SQL Data Analysis](https://github.com/CloudDataPalina/Chicago-SQL-Data-Analysis)

A hands-on SQL + Python project analyzing socioeconomic indicators, crime data and public school metrics for Chicago community areas.  

- Built SQL queries and joins across multiple datasets (socioeconomic, crime, schools).  
- Created a **VIEW** in IBM Db2 and developed a stored procedure `UPDATE_LEADERS_SCORE` with transaction control (COMMIT/ROLLBACK).  
- Produced visual insights: scatter plots of **Income vs. Hardship Index** and **Poverty vs. School Safety Score** (saved to `/images`).  
- Included screenshots of all SQL queries and Db2 objects for reproducibility.  
- Organized the project into clear folders: `/data`, `/images`, `/screens`, `/notebooks`.  

**Tools:** `Python`, `pandas`, `sqlite3`, `ipython-sql`, `matplotlib`, `seaborn`, `IBM Db2 on Cloud`, `GitHub Codespaces`

---

### ☕ [Coffee Shop Database](https://github.com/CloudDataPalina/Coffee-Shop-Database)

A mini end-to-end RDBMS project that designs a relational model for a coffee shop and makes the data portable across systems.

- Designed ERD → generated DDL → loaded demo data in **PostgreSQL**
- Built **views** + a **materialized view** for analytics
- Exported views to **CSV** and imported into **MySQL** and **IBM Db2** (with screenshots)
- One-command reproducible run in **GitHub Codespaces** via `run_all.sh` (Docker)
- Included sample analytical queries and quick sanity checks

**Tools:** `PostgreSQL`, `SQL (DDL/DML, PL/pgSQL)`, `GitHub Codespaces`, `MySQL`, `IBM Db2`, `pgAdmin`

---

### 🏦 [Largest Banks ETL Project](https://github.com/CloudDataPalina/Largest-Banks-ETL)

A **web scraping + ETL** pipeline that extracts the *largest banks* by market capitalization from Wikipedia,  
transforms the data into multiple currencies (USD, GBP, EUR), and stores it in CSV and SQLite for further analysis.

- Extracted and parsed HTML table from Wikipedia using **BeautifulSoup**
- Transformed market capitalization from USD into GBP and EUR using exchange rates CSV
- Saved processed datasets into `.csv` and `.db`
- Logged all processing steps with timestamps (`code_log.txt`)
- Created visual insights using **Matplotlib** (Top-5 banks by market cap)

**Tools:** `Python`, `pandas`, `numpy`, `BeautifulSoup`, `requests`, `matplotlib`, `sqlite3`, `Jupyter Notebook`

---

### 🚗 [Car Price ETL Project](https://github.com/CloudDataPalina/ETL_Project/)

A mini **ETL pipeline** that extracts, transforms, and loads used car price data **from multiple formats**:

- Parsed data from `.csv`, `.json`, and `.xml` sources  
- Transformed and merged into a cleaned DataFrame  
- Logged all steps with timestamps (`log_file.txt`)  
- Exported final dataset to `.csv` and charts to `.png`  
- Created visual insights with `matplotlib`

**Tools:** `Python`, `pandas`, `matplotlib`, `glob`, `csv`, `json`, `xml.etree.ElementTree`, `Jupyter Notebook`

---

### 🌍 [Quality of Life Analysis – 2025](https://github.com/CloudDataPalina/Quality-of-Life-2025)

A web scraping and data visualization project exploring the quality of life across global cities in 2025:

- Parsed local HTML from Numbeo using `BeautifulSoup`
- Focused on three core indexes: **Quality of Life**, **Safety**, and **Health Care**
- Visualized Top-20 cities using horizontal bar charts
- Exported results in `.csv`, `.png`, and `.svg` formats

**Tools used:** `Python`, `pandas`, `BeautifulSoup`, `matplotlib`, `Jupyter Notebook`

---

### [📉 Financial Crisis Analysis](https://github.com/CloudDataPalina/Financial-Crisis-Analysis)

An in-depth analysis of the fictional company **Technoprom Ltd.** and its 5-year financial collapse:

- Key metrics analyzed: revenue, gross/net profit, debt, margins  
- Year-by-year visualizations showing financial decline  
- Ratio analysis: Gross, Operating, and Net Profit Margins  
- Business diagnosis and strategic recommendations (in English)

**Tools used:** `pandas`, `numpy`, `matplotlib`, `Jupyter Notebook`, `Python`

---

## 🌐 Connect with Me
- [LinkedIn Profile](https://www.linkedin.com/in/palina-krasiuk-954404372/)

---

### 📅 Learning Path

**🎯 Current Focus**  
[IBM Data Engineer Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-engineer) — mastering **Python**, **SQL**, **ETL**, and **cloud platforms** through hands-on, real-world projects.

**🛠 Next Steps**  
1. Work with **Big Data** using **Apache Spark**  
2. Gain multi-cloud expertise (**GCP**, **AWS**)  
3. Complete a **Data Engineering Capstone Project** and prepare for technical interviews  

---

## 🎓 Certifications

### 🏆 Professional Certificates
- [IBM Data Warehouse Engineer - Professional Certificate](https://coursera.org/share/bdfd9f8f2df72ebcbd4cdae08bff30da) - 28.02.2026  
- [IBM Relational Database Administrator with GenAI - Professional Certificate](https://coursera.org/share/5c1200721baee7158920a452b490fd5b) - 30.01.2026  

---

### 📊 Specializations
- [BI Foundations with SQL, ETL and Data Warehousing (IBM)](https://coursera.org/share/6a1715f9f434b73e72ac5770d33ea38f) - 20.02.2026  

---

### 🧪 Capstone Projects
- [Data Warehousing Capstone Project](https://coursera.org/share/288ed179784ec9190e8e5515024d4c03) - 23.02.2026  
- [Relational Database Administration Capstone Project](https://coursera.org/share/9fb16ad83eeba7b47a53b6b7bf3bb510) - 20.01.2026  

---

### ⚙️ Core Data Engineering
- [Introduction to NoSQL Databases](https://coursera.org/share/403e25c70e8d10f171c48e7c5fba1340) - 23.03.2026  
- [SQL: A Practical Introduction for Querying Databases](https://coursera.org/share/1e886f64981ec905ca305f8a3d2e61e2) - 28.02.2026  
- [Data Warehouse Fundamentals](https://coursera.org/share/3f4bb18e08194ee10ac9b20419b883cb) - 13.01.2026  
- [ETL and Data Pipelines with Shell, Airflow and Kafka](https://www.coursera.org/account/accomplishments/certificate/FKATB04P6S30) - 22.12.2025  
- [Databases and SQL for Data Science with Python](https://coursera.org/share/12f6ea584d1a20f93de532badc8e8c66) - 15.09.2025  

---

### 📊 BI & Visualization
- [BI Dashboards with IBM Cognos Analytics and Google Looker](https://coursera.org/share/d43eac47e8d05e587dde7e9dfa648606) - 20.02.2026  

---

### 🧠 Databases & SQL (Additional)
- [Databases and SQL Course (MySQL based)](https://stepik.org/cert/2888336?lang=en) - 12.06.2025  
- [Oracle SQL Course](https://www.udemy.com/certificate/UC-0980df6f-7645-4129-a572-7a045118e41e/) - 14.04.2025  
- [Relational Database Administration (DBA)](https://coursera.org/share/39f57a0da245b8851dae3e38bf51633a) - 29.11.2025  
- [Introduction to Relational Databases (RDBMS)](https://coursera.org/share/b1b9e2b978131fb51f61eb0502695e25) - 24.08.2025  

---

### 🐍 Python & Programming
- [Python Project for Data Engineering](https://coursera.org/share/7db0e33b2da935334bc601a87de1f2fc) - 01.08.2025  
- [Python for Data Science, AI & Development](https://www.coursera.org/account/accomplishments/verify/RE1QJ5J27Q9M) - 06.07.2025  
- [Object-Oriented Programming](https://stepik.org/cert/2530129?lang=en) - 28.07.2024  
- [Python Professional Course](https://stepik.org/cert/2432220?lang=en) - 17.04.2024  
- [Python Intermediate Course](https://stepik.org/cert/2341634?lang=en) - 25.01.2024  
- [Python Beginner Course](https://stepik.org/cert/2056820?lang=en) - 08.05.2023  

---

### ⚙️ Tools & Foundations
- [Generative AI: Elevate your Data Engineering Career](https://coursera.org/share/727f3d7d9baeb5883e984426348d6147) - 30.01.2026  
- [Hands-on Introduction to Linux Commands and Shell Scripting](https://coursera.org/share/ef2ffe73099bd1eb450b4bfa911b60d3) - 15.11.2025  
- [Introduction to Data Engineering](https://www.coursera.org/account/accomplishments/verify/Q1QM933TRCOI) - 16.05.2025  
- [Tools for Data Science](https://www.coursera.org/account/accomplishments/verify/7MXBOZMD8SHE) - 08.02.2025  
- [What is Data Science?](https://www.coursera.org/account/accomplishments/verify/6XFV92CM88JB) - 29.01.2025  
---

### 📊 GitHub Stats

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=CloudDataPalina&layout=compact)
![GitHub stats](https://github-readme-stats.vercel.app/api?username=CloudDataPalina&show_icons=true)

---
  
