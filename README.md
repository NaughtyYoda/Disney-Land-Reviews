# Disney-Land-Reviews
The dataset includes reviews of 3 Disneyland branches (Paris, California and Hong Kong) posted by visitors on Trip Advisor.

## DATASET DESCRIPTION
| Info                 | Description           |
| -------------------- | --------------------- |
| DATASET NAME         | DisneylandReviews.csv |
| DATA SIZE            | 8.39 MB               |
| DATE OF RELEASE      | 10-05-2021            |
| NO. OF FILES         | 1                     |
| NO. OF ATTRIBUTES    | 6                     |
| NO. OF DATA RECORDS  | 42,656                |
| DATA SOURCE PROVIDER | Trip Advisor          |
| DATA PRIVACY         | Open Source           |

## NOTES

| Prepared by       | Arush Chillar                         |
| ----------------- | ------------------------------------- |
| Point of  Contact | Arush Chillar, arushchillar@gmail.com |
| Team Members      | NA                                    |

| Data Type Name Convention | Main Type           | Sub type |
| ------------------------- | ------------------- | -------- |
| MD                        | Metric Discrete     | BIN - Binary |
| MC                        | Metric continous    | DATE - date/time, CURR - Currency |
| CO                        | Categorical Ordinal |  |
| CN                        | Categorical Nominal | DI - Dichotomous, STR - Free string, ID - identification, URL - links, ADDR - address |

## ATTRIBUTE DICTIONARY
| Attribute Name    | Data Type | Data Subtype | Description                                   | Examples            | Additional Notes  |
| ----------------- | --------- | ------------ | --------------------------------------------- | ------------------  | ----------------  |
| Review_ID         | CN        | ID           | unique ID given to each review.               | 670682799           | few duplicates ID |
| Rating            | MD        |              | rating from 1 (unsatisfied) to 5 (satisfied). | 1                   | -                 |
| Year_Month        | MC        | DATE/TIME    | when the reviewer visited the theme park.     | 2019-5              | YYYY-MM           |
| Reviewer_Location | CN        | ADDR         | country of origin of visitor.                 | Philippines         | -                 |
| Review_Text       | CN        | STR          | comments made by visitor.                     | nice park.          | -                 |
| Branch            | CN        | ADDR         | location of disneyland park.                  | Disneyland_HongKong | -                 |
