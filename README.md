# **Hello**

This project is very simple with 3 goals consist of (Data Transformation):
- Get data from two sources (txt,xlsvx)
- Data cleaning
- Modify the data structure
- Data integration

Some rows of txt files:

CalendarYear;BillTo Target;Office
2011;N/A 21;
2011;Tailspin Toys 17;head office
2011;Wingtip Toys 17;head office
2012;N/A 13;
2012;Tailspin Toys 12;head office
2012;Wingtip Toys 12;head office

Some rows of xlsvx file:

	2015												2015 Total	2016	
Row Labels	1	2	3	4	5	6	7	8	9	10	11	12		1	2
N/A	1800000	1500000	1800000	2000000	1800000	1700000	2000000	1400000	1800000	1900000	1500000	1600000	20800000	1800000	1500000
Tailspin Toys (Head Office)	1400000	1400000	1400000	1400000	1400000	1400000	1600000	1300000	1500000	1300000	1000000	1400000	16500000	1500000	1200000
Wingtip Toys (Head Office)	1300000	1300000	1300000	1600000	1500000	1300000	1500000	1300000	1300000	1400000	1400000	1400000	16600000	1300000	1100000
Grand Total	4500000	4200000	4500000	5000000	4700000	4400000	5100000	4000000	4600000	4600000	3900000	4400000	53900000	4600000	3800000

As you can see, data structure of two sources are very different from each other. Therefore, it is necessary to make these two structures the same first and then make them visual. This example is very simple, but includes many fine points, including:
- Promote headers
- Sort rows
- Filter rows
- Replace value
- Merge Columns
- Split Columns
- Change type
- Transpose table
- Appeand table
- Group by
- unpivote


Sample of this project
![Screenshot 2023-03-04 at 14 53 21](https://user-images.githubusercontent.com/65550422/222906325-c0f7f91d-0d39-40d1-8606-6e1bbb83ef1a.png)
