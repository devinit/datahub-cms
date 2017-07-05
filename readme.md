## Datahub Content Management System repository

The repository is split by datahub pages, and each page folder contains the narratives and refrence files used by that page.
This should make it easier for analysts to change datahub narratives and refrence file data easily on a per page basis.

You will find that refrence data that can be autogenerated from underlaying tables in the data ware house will now reside with in the Data warehouse.

### Files explained

#### concepts.csv

There is a simplified concepts.csv file in each folder that serves a similar purpose to the concepts.csv file in the digital platform repository

It contains indicator related data i.e id, name etc for each indicator used on the page

#### page.csv

This file contains various page narratives, it has an id column for each page section, secton title where applicable, narrative and finally meta. Meta is where you put any other extra text which may not apply in the other sections.
