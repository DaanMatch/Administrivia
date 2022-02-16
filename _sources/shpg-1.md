# Database Project

## Project objective

Using DaanMatch's Data Model, create a Schema and load DaanMatch data to database.

:::{admonition} What is a Data model?
:class: tip, dropdown
A data model is an abstract model that organizes elements of data and standardizes how they relate to one another and to the properties of real-world entities.
:::

:::{admonition} What is a Database?
:class: tip, dropdown
A database is information that is set up for easy access, management and updating.
:::

## Data Model

:::{figure-md} Data-Model
:class: myclass

<img src="images/drawsql.png" alt="DaanMatch Data Model" class="bg-primary mb-1" width="600px">

DaanMatch's Data Model visualized using DrawSQL.
:::

## Git

DaanMatch is using GitHub for version control. Code submissions will be done through pull requests.

**TODO:** To enable effective collaboration please download/review the following

- [ ] Join [DaanMatch's GitHub organization](https://github.com/DaanMatch)
- [ ] [Download Git](https://git-scm.com/downloads)
- [ ] [GitHub Desktop](https://desktop.github.com/) (Optional)
- [ ] [Basic Git Branching](https://git-scm.com/book/en/v2/Git-Branching-Basic-Branching-and-Merging)
- [ ] [Git Branching Naming conventions](https://codingsight.com/git-branching-naming-convention-best-practices/)
- [ ] [How to write good commit messages](https://www.freecodecamp.org/news/writing-good-commit-messages-a-practical-guide/)

**TODO:** Create a GitBranch and add your name to CONTRIBUTING.md on [Data Model](https://github.com/DaanMatch/ngodata/tree/main/Data%20Model).

## How to get our data

DaanMatch's data files are stored on AWS S3.

:::{admonition} What is S3?
:class: tip, dropdown

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry-leading scalability, data availability, security, and performance. You can use Amazon S3 to store and retrieve any amount of data at any time, from anywhere.
:::

**TODO:**

- [ ] [Follow Connection instructions on Codebook](Codebook Documentation](https://github.com/DaanMatch/Codebook)

```
{
  "User name": "dsdiscovery",
  "Password": "^iBZ73|F^y2ru{N",
  "Access key ID": "AKIAQE77SAWMUAG7CRUP",
  "Secret access key": "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",
  "Console login link": "https://010736502169.signin.aws.amazon.com/console"
}
```

## Database

DaanMatch is using


:::{admonition} What is SQL?
:class: tip, dropdown

Structured Query Language (SQL) is a standardized programming language that is used to manage relational databases and perform various operations on the data in them.
:::




[Connect to AWS RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/USER_ConnectToInstance.html)

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
