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

## Git

DaanMatch is using GitHub for version control. Please join [DaanMatch's GitHub organization](https://github.com/DaanMatch).

TODO: To enable effective collaboration please review the following pages.

- [Basic Git Branching](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [Git Branching Naming conventions](https://codingsight.com/git-branching-naming-convention-best-practices/)
- [How to write good commit messages](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)

TODO: Create a GitBranch and add your name to CONTRIBUTING.md on [Data Model](https://github.com/DaanMatch/ngodata/tree/main/Data%20Model).

## How to get our data

DaanMatch's data files are stored on AWS S3.

:::{admonition} What is S3?
:class: tip, dropdown

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.
:::




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
