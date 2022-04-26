## Interview
You are required to read the csv file as shown below through java API, and summarize (sum of sales) for a given quarter id (QTR_ID) and year id(YEAR_ID). Write this summarized data into a different file in json format.
* Give your best design and naming conventions while you are implementing.
* Explain on your design before you start programming.

### Read CSV file
Read sales data csv located in "C:\Interviews\JavaFS\issam-interview\src\main\resources\sales_data_sample.csv".
* Use best optimised File Readers.
* Give a solution that can be scalable.
* If file is huge your program shouldn't run into any issues. If it is working for small files it should also work in the same way for big files.

### Write JSON file
Once you aggregated total sales you should write them into a different file in json format.
Output format:

```json
{
[
  {
    "totalSales": "xxxxx",
    "qtr_id": "1",
    "year_id": "2005",
    "total_sales": "x"
  },
  {
    "totalSales": "xxxxx",
    "qtr_id": "2",
    "year_id": "2005",
    "total_sales": "x"
  }

```