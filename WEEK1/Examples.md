# Public Datasets
- [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets) 
	- Will also give a list of govt dataset websites
- [GADM: Country related data (ShapeFiles)](https://gadm.org/)
- [Google Dataset Search](https://datasetsearch.research.google.com)
- [Kaggle](https://www.kaggle.com/)
- data.gov.*
- [datameet](https://datameet.org/)
	- Can use the mailing list, to request data

# Private Datasets
- Corporate dataset
	- Performance details
	- Operations, financial logs
	- MOST INVESTED DATASET
- Paid datasets
	- Need to pay for them
	- Google "paid datasets" or "buy datasets"
	- More reliable and richer than public datasets

# Personal Datasets
- Unique to each person
- Mobile app datasets
- Messages data, WhatsApp data, etc

***
***
# Structured Datasets
- Database files
	- Tabular
	- Each column has a specific data type as well
- Spreadsheets
	- Again, tabular
	- __*Structured data can be in sheets, data in sheets may not be structured!*__
- ShapeFiles
	- Geographic data
	- Ex: [GADM provides ShapeFIles data](https://GADM.org/)
	- DBF file is like an excel file
	- SHP file contains how the shape of the location is

# Semi-Structured Datasets
- Documents files: PDF, HTML
	- PDF with tables(not entirely tabular, but tabular)
	- Wikipedia pages (they have tables as well in between)
	- Structured + unstructured together is also semi-structured
- Messages, Emails
	- Original form of emails are also semi-structured
- Containers(ZIP, DOCX)
	- ZIP containing a sheet and a .txt file together

# Unstructured Datasets
- Texts
- Images
- Audios
- Videos

***
***
# Categorical Values
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


# Numerical Values
- Integers
	- -2, -1, 0, 1, 2, ...
- Real numbers
	- 2.7, 3.5, e, $\pi$ ...

# Composite Values
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
