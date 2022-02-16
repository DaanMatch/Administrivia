# Database Project

## Project objective

Using DaanMatch's Data Model, create a Schema and load DaanMatch data to database.

:::{admonition} What is a Data model?
:class: tip, dropdown
A data model is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.
:::

## Data Model

```{figure} ../images/drawsql.png
---
height: 300px
name: DaanMatch-DataModel
---
DaanMatch's Data Model visualized using DrawSQL.
```

## Resources ℹ️

- [Codebook Documentation](https://github.com/DaanMatch/Codebook)
- [Geocoded Data](https://github.com/DaanMatch/ngodata/tree/main/geocoded_data)
- [Data Model](https://github.com/DaanMatch/ngodata/tree/main/Data%20Model)
- [Webscrapers](https://github.com/DaanMatch/webscrape)
- Data Files on AWS S3.


**TRANSFORMATION** Shekar --> People + Member Tables (ONE PERSON)

- Python: Data processing, cleaning, manipulation, transformation

**TRANSFORMATION** Fall2021Webscrape --> Data Model (ONE PERSON)

- Python: Data processing, cleaning, manipulation, transformation

**DELIVERABLE** Load data to database - Allow for SQL queries (1 + 2 Together)

- Python, SQL: DBMS
