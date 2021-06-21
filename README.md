# Amazon_Vine_Analysis
Module 16: Big Data

Overview of the analysis: Explain the purpose of this analysis.
For this analysis I have selected baby products review dataset from The Amazon Vine program. I have used following to technique for the analysis; used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 
Also, I have used PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset.

### Deliverable 1: Perform ETL on Amazon Product
The customers_table DataFrame
![image](https://user-images.githubusercontent.com/79486450/122700597-94f48400-d219-11eb-98c1-f8a17633b492.png)

The products_table DataFrame
![image](https://user-images.githubusercontent.com/79486450/122700664-b35a7f80-d219-11eb-985b-adc2c1de76ec.png)

The review_id_table DataFrame
![image](https://user-images.githubusercontent.com/79486450/122700718-cff6b780-d219-11eb-90c1-b0a44e1d545d.png)

The vine_table DataFrame
![image](https://user-images.githubusercontent.com/79486450/122700770-e866d200-d219-11eb-8f95-d898e65634ad.png)

pgAdmin
![image](https://user-images.githubusercontent.com/79486450/122700957-43002e00-d21a-11eb-971e-7d1b333ad45a.png)
![image](https://user-images.githubusercontent.com/79486450/122700994-527f7700-d21a-11eb-811f-8200680f2cd8.png)
![image](https://user-images.githubusercontent.com/79486450/122701027-5dd2a280-d21a-11eb-8cbf-33b1693ad9e8.png)
![image](https://user-images.githubusercontent.com/79486450/122701053-6a56fb00-d21a-11eb-879e-c8afff4391be.png)




### Deliverable 2: Determine Bias of Vine Reviews 
How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/79486450/122700292-fd8f3100-d218-11eb-978e-b3f347512003.png)

![image](https://user-images.githubusercontent.com/79486450/122700356-20b9e080-d219-11eb-9c91-0a03643df6f9.png)

![image](https://user-images.githubusercontent.com/79486450/122700524-70001100-d219-11eb-92d0-ffe774bb2d33.png)

How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/79486450/122700465-56f76000-d219-11eb-9627-ab8712f878bb.png)


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/79486450/122700492-624a8b80-d219-11eb-9013-8f6efef8bf8d.png)

Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
