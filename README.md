### Amazon_Vine_Analysis

## Purpose of the analysis

The purpose is to pick one of the Amazon product datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 

## Results

The chosen dataset, digital video game downloads held a suprising data count for Vine reviews and Non-Vine reviews. 

- How many Vine reviews and non-Vine reviews were there?

In total, the amount of Vine reviews amounted to 0 in the data set. The total amount of non-Vine revies amounted to 1563


![total non vine](https://user-images.githubusercontent.com/76926631/153773724-da7a019f-32e0-4983-af22-62737377cfdb.PNG)


![Total Vine Count](https://user-images.githubusercontent.com/76926631/153773740-b16846ae-ab50-4b47-ab49-adcc034e5fa4.PNG)


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

Similarly, the amount of Vine reviews that were 5 stars were 0, and the amount of non-vine reviews that were 5 stars amounted to 582.

![Vine counts](https://user-images.githubusercontent.com/76926631/153773620-123a03f4-388b-49ec-8893-2da86157ded6.PNG)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

As such, the overall percentage of Vine reviews that were 5 stars is approximately 37.24% (582/1563).

## Conclusion

As there are no paid Vine reviews in the data set, there is no positivity bias within the dataset. This can be confirmed by the fact that there are 0 reported Vine reviews/paid reviews. This is particularly suprising in the area of digital downloads, because it appears only actual users would review digital downloads.  
