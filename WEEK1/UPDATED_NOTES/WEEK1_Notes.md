# WEEK 1 Notes


With this file, I will start using obsidian to make my "Tools in Data Science" notes

This vault contains the week 1 notes of TDS

## Content:

1. [Sources of Data](#Sources-of-Data)
2. [Types of Datasets](#Types-of-Datasets)
3. [Types of Values](#Types-of-Values)
4. [Examples](#Examples)

***
***
***
***

# Sources of Data

**Sources of data can be classified into 3 categories :**

## <u> PUBLIC DATA </u>
        1. Open and free
        2. A lot of data, but might be hard to find the right data

[Examples#Public datasets](#Public-Datasets)
                
## <u> PRIVATE DATA </u>
        1. Inside an organisation
        2. Can pay for them

[Examples#Private datasets](#Private-Datasets)

## <u> PERSONAL DATA </u>
        1. App based data
        2. Personal logging also comes under this (Ex: my MAD project, quantified self app)

[Examples#Personal datasets](#Personal-Datasets)


***
***
### NEXT: [Types of Datasets](#Types-Of-Datasets)
***
***

# Types Of Datasets

- The data will range from structured to unstructured. 
- This isn't a binary classification, but a continuum.
- Datasets can be broadly classified into 3 types/categories:

## <u>Structured </u>
        - Follows a particular fixed schema

[Examples#Public datasets](#Public-Datasets)
        
## <u>Semi-Structured</u>
        - A schema exists but is not fixed
        - JSON files, XML files
        
[Examples#Semi-Structured Datasets](#Semi-Structured-Datasets)
        
## <u>Unstructured</u>
        - People work to convert this to structured
        - No structure at all
        
[Examples#Unstructured Datasets](#Unstructured-Datasets)


***
***
### NEXT:  [Types of Values](#Types-of-Values)
***
***

# Types of Values

Each dataset will have different types of values that each attribute can take
We can broadly bucket them into 3 categories:

## Categorical
        - Allows fewer computations
        - List, sort but not more than that

[Examples#Categorical Values](#Categorical-Values)

## Numerical
        - Can perform series of operations
        - Add, multiply, take ratios, etc

[Examples#Numerical Values](#Numerical-Values)

## Composite
        - Even more operations can be performed
        - formed by a combination of multiple values

[Examples#Composite Values](#Composite-Values)

***
***
### NEXT: [Examples](#Examples)
***
***

# Examples

## Public Datasets
- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets) 
        - Will also give a list of govt dataset websites
- [GADM: Country related data (ShapeFiles)](https://gadm.org/)
- [Google Dataset Search](https://datasetsearch.research.google.com)
- [Kaggle](https://www.kaggle.com/)
- data.gov.*
- [datameet](https://datameet.org/)
        - Can use the mailing list, to request data

## Private Datasets
        - Corporate dataset
                - Performance details
                - Operations, financial logs
                - MOST INVESTED DATASET
        - Paid datasets
                - Need to pay for them
                - Google "paid datasets" or "buy datasets"
                - More reliable and richer than public datasets

## Personal Datasets
        - Unique to each person
        - Mobile app datasets
        - Messages data, WhatsApp data, etc

***
***

## Structured Datasets
- Database files
        - Tabular
        - Each column has a specific data type as well
- Spreadsheets
        - Again, tabular
    - __*Structured data can be in sheets, data in sheets may not be structured!*__
- ShapeFiles
        - Geographic data
        - DBF file is like an excel file
        - SHP file contains how the shape of the location is
    - Ex: [GADM provides ShapeFIles data](https://GADM.org/)

## Semi-Structured Datasets
        - Documents files: PDF, HTML
                - PDF with tables(not entirely tabular, but tabular)
                - Wikipedia pages (they have tables as well in between)
                - Structured + unstructured together is also semi-structured
        - Messages, Emails
                - Original form of emails are also semi-structured
        - Containers(ZIP, DOCX)
                - ZIP containing a sheet and a .txt file together

## Unstructured Datasets
        - Texts
        - Images
        - Audios
        - Videos


***
***

## Categorical Values
- Boolean
        - True or False
- Unordered
        - Red, green, blue
        - Cities, etc
        - We can order cities by population, but we are not using the categorical variable to order them. We are using another order
        - We can alphabetically sort them but we are not treating them as a series of letters
- Ordered
        - Low, medium, high
        - Cyclic ordered values are also there
                - Monday, Tuesday,..., Sunday, Monday,...
                - Jan, Feb,..., Dec,..., Jan
- Unstructured
        - Text, Binary. etc

***NOTE:*** Can use categorical values to get derived values. Ex: Use cities to get population


## Numerical Values
- Integers
    - -2, -1, 0, 1, 2, ...
- Real numbers
    - 2.7, 3.5, e, $ \pi $ ...

## Composite Values
- Data / Time
        - Date is composite
        - Time is also composite
        - Data is made up of day, month, year combined
        - Time is hours, minutes and seconds combined
- Spatial Structured
        - Lat/Long combination
        - Shapes
                - A line from one point to another
- Structured
        - JSON, XML
        - Internally, a structure exists
- Specialised Structured
        - IP Addresses
        - Currency



***
***
# [NEXT WEEK'S NOTES](../WEEK2/week2.ipynb)
***
***


