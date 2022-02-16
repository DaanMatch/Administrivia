# Database - w2

**Objective:** Map DaanMatch's Geocoded information using ArcGIS Online.

```{admonition} Cara Arellano Contact Info
cara.arellano@berkeley.edu
Mobile: 4083935646 <br>
GitHub: carellano67
```

## This Week's Objective

Get familiar with how to get DaaMatch's data and ArcGIS Online.

## Your team

````{panels}
:column: col-4
:card: border-2
Zane Wang
^^^
zelinewang@berkeley.edu
GitHub: zelinewang
---
Nei (Alex) Fang	
^^^
alex20020805@berkeley.edu
GitHub: alex20020805
````

:::{admonition} What is GIS?
:class: tip, dropdown
A [Geographic Information System (GIS)](https://www.usgs.gov/faqs/what-geographic-information-system-gis) is a computer system that analyzes and displays geographically referenced information. It uses data that is attached to a unique location.
:::

## DaanMatch's data

DaanMatch Geocoded data is currently stored on GitHub.

**TODO:** To access GitHub please have the following.

- [ ] [Download Git](https://git-scm.com/downloads)
- [ ] [Join DaanMatch's GitHub organization](https://github.com/DaanMatch)
- [ ] [GitHub Desktop](https://desktop.github.com/) (Optional)

**TODO:** Clone [NGO Data](https://github.com/DaanMatch/ngodata) <br>
Navigate to [geocoded_data directory](https://github.com/DaanMatch/ngodata/blob/main/geocoded_data/GIS%20Data.ipynb).

### Information in each csv

| Column        | Description        |
| ------------- | ------------------ |
| Ngo Name      | NGO Name           |
| Lat           | Latitude           |
| Long          | Longitude          |
| Mobile        | Mobile Number      |
| Address       | Long address       |
| Area of Focus | Development Sector |
| State         | State in India     |

```{note}
You can add other column information by modifying [GIS Data.ipynb](https://github.com/DaanMatch/ngodata/blob/main/geocoded_data/GIS%20Data.ipynb)
To do this you will need access to DaanMatch's AWS S3, please contact Patrick G for more information.
```

**TODO:** Brief EDA for one state file.

- [ ] How many NGOs in this state?
- [ ] What are more NGOs focusing on in this state?
- [ ] How much information is missing?

**TODO:** <2 min presentation about your data

## Resources ℹ️

- [DS Discovery Scheduling](https://docs.google.com/spreadsheets/d/1uwpQJ0VeinKC-fPI7-ZN-RinID5Y0VamjWiwza7-otY/edit#gid=1395204760)