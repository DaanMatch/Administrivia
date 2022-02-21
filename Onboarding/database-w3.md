# Database - w3

## [Team Meeting - 24 Feb 2022 6:45pm PST](https://us02web.zoom.us/j/4833516577?pwd=emgvY2xnSEF5Zlh4Si9kVkx3S0dzZz09)

**Agenda:**

1. Short EDA presentation
2. AWS RDS Setup
3. Connection to MySQL WorkBench
4. TODOs
5. Questions

## This Week's Objective

Get familiar with AWS RDS and MySQL.

:::{admonition} What is AWS RDS?
:class: tip, dropdown
Amazon Relational Database Service (Amazon RDS) makes it easy to set up, operate, and scale a relational database in the cloud. It provides cost-efficient and resizable capacity while automating time-consuming administration tasks, such as hardware provisioning, database setup, patching, and backups.
:::

:::{admonition} What is MySQL?
:class: tip, dropdown
MySQL is a relational database management system (RDBMS) developed by Oracle that is based on structured query language (SQL). A database is a structured collection of data. It may be anything from a simple shopping list to a picture gallery or a place to hold the vast amounts of information in a corporate network.
:::

**TODO:** [Connect to DaanMatch's DB instance running the MySQL database engine](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToInstance.html)

```{note}
End point and Port can be found in #team-shpg on Slack.
```

## DaanMatch's Data Model

:::{figure-md} Data-Model
:class: myclass

<img src="images/drawsql.png" alt="DaanMatch Data Model" class="bg-primary mb-1" width="600px">

DaanMatch's Data Model visualized using DrawSQL.
:::

**TODO:** [Create a Model](https://dev.mysql.com/doc/workbench/en/wb-getting-started-tutorial-creating-a-model.html)

### Model Assignment

- **Arthi:** registration_number, registration_office
- **Emily:** finance, partnership
- **Apoorv:** people, member

**TODO:** Save SQL Script onto data-model repository.

## Resources ℹ️

- [DS Discovery Scheduling](https://docs.google.com/spreadsheets/d/1uwpQJ0VeinKC-fPI7-ZN-RinID5Y0VamjWiwza7-otY/edit#gid=1395204760)
- [Codebook Documentation](https://github.com/DaanMatch/Codebook)
- [Data Model](https://github.com/DaanMatch/ngodata/tree/main/Data%20Model)
- [Webscrapers](https://github.com/DaanMatch/webscrape)