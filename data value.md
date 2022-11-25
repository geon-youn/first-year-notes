---
alias: observation, case, variable, characteristics, relational database, relation, data
tags: COMMERCE_1DA3
created: Sunday March 13, 2022; 09:36:10 
---
# Data value
Data values or observations are information collected regarding some subject. Data can be numbers, names, etc., and tell us the "*who* and *what*". 

```ad-warning
Data are useless without their **context**
```

Data are often organized into a data table like below

| Purchase Order Number | Name         | Ship to Province | Price | Area Code | Previous CD Purchase | Gift? | ASIN       |
| --------------------- | ------------ | ---------------- | ----- | --------- | -------------------- | ----- | ---------- |
| 10675489              | Katherine H. | Alberta          | 10.99 | 403       | Nashville            | N     | B0000015Y6 |
| 10783489              | Samuel P.    | Nova Scotia      | 16.99 | 902       | Classical            | Y     | B000002BK9 |
| 12837593              | Chris G.     | Quebec           | 15.98 | 819       | Hip Hop              | N     | B000068ZVQ |
| 15783947              | Monique D.   | Ontario          | 11.99 | 905       | Reggae               | N     | B000001OAA           |

The rows of a data table correspond to individual **cases** about *whom*/*which* we record some characteristics.

The **characteristics** recorded about each individual or case are called **variables** (e.g. in the table, "Purchase Order Number", "Name", "Ship to Province", "Price", etc.). 

Data tables are cumbersome for complex data sets, so often two or more separate data tables are linked together in a **relational database**. 

Each data table included in the database is a **relation** because it is about a specfic set of cases with information about each of these cases for all of the variables. 

