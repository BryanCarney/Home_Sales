# Home_Sales

## Link to Solved File
[Colab File](https://drive.google.com/file/d/1TcQZxXtywh31WTsR4UGPBchXMIYMrvCx/view?usp=sharing)

### Original Files
[Module 22 Challenge Files](https://static.bc-edx.com/data/dl-1-2/m22/lms/starter/Starter_Code.zip)

### Instructions

1. Rename the **Home_Sales_starter_code.ipynb** file as **Home_Sales.ipynb**.

2. Import the necessary PySpark SQL functions for this assignment.
![image](https://github.com/user-attachments/assets/9f0801e6-f040-481d-a1e5-869232d68d80)
  ![image](https://github.com/user-attachments/assets/dbb69039-753b-473a-bf98-1ba884c304ba)

3. Read the **home_sales_revised.csv** from the provided AWS S3 bucket location into a PySpark DataFrame.

![image](https://github.com/user-attachments/assets/0a3111f7-56e7-494c-8ed5-2db6df0fd4fd)

4. Create a temporary table called **home_sales**.

![image](https://github.com/user-attachments/assets/7a198805-0cce-4ae5-8ee8-11a673c92001)

5. Answer the following questions using SparkSQL:

>• What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

![image](https://github.com/user-attachments/assets/e7ecb4fb-3e5c-4b80-ae09-8a303ceb3513)

>• What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

![image](https://github.com/user-attachments/assets/9b7e7036-1df9-4785-a5ef-1154222923b6)

>• What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

![image](https://github.com/user-attachments/assets/8314e5c7-6a0f-4793-a995-213d3b21e95c)

>• What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

![image](https://github.com/user-attachments/assets/ff504c34-8ec4-4345-91d1-fe46c1ec14fa)

6. Cache your temporary table **home_sales**.

![image](https://github.com/user-attachments/assets/86359469-c817-4449-9911-86fdbc972bc3)

7. Check if your temporary table is cached.

![image](https://github.com/user-attachments/assets/b26a98f7-b6b2-4a4c-8a14-d3b2a18fea20)

8. Using the cached data, run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![image](https://github.com/user-attachments/assets/368c9519-97b8-4c7d-ac03-6a218f4bd1d2)

9. Partition by the "date_built" field on the formatted parquet home sales data.

![image](https://github.com/user-attachments/assets/3cf22e70-5de8-4dd8-b09b-b893838e7002)

![image](https://github.com/user-attachments/assets/4fd6b4bf-26ea-4b52-8996-4aa02ff329b5)

10. Create a temporary table for the parquet data.

![image](https://github.com/user-attachments/assets/8242fe6e-56d9-48bb-a6c9-0cc97ac899f5)

11. Run the last query that calculates the average price of a home per "view" rating having an average home price greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

![image](https://github.com/user-attachments/assets/bd600383-c4ef-4ff4-9aa6-1c5e00813620)

12. Uncache the **home_sales** temporary table.

![image](https://github.com/user-attachments/assets/653a606f-3e28-41bd-bf54-943a4b910e5b)

13. Verify that the **home_sales** temporary table is uncached using PySpark.

![image](https://github.com/user-attachments/assets/dd360006-ed89-4f77-9a52-e9d9733f706e)

14. Download your **Home_Sales.ipynb** file and upload it into your "Home_Sales" GitHub repository.
