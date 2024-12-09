# Home_Sales
### Big Data Manipulation

This, our final homework assignment, was a great culmination of methods and concepts, organized effectively and concisely. The big data module seems applicable, tangible, and pertinent to modern data analytics as it covers basic, integral principles of importing data from online web services and manipulating data with spark SQL. 

Initially, for the homework assignment, as I imported the notebook into Google Colab, I installed and imported the necessary modules and read in the data from Amazon Web Services (AWS), while simultaneously reading the data using PySpark, much like Pandas. The next step was to create a local temporary view, storing the data frame locally to reduce the time needed to run any subsequent query on the data frame I created in the previous step. The next three questions required basic SQL manipulations as they required knowledge recollection from earlier in the course. The next portion of the assignment involved another intermediate SQL query, while also introducing the main concept as we calculated the allotted time necessary for the computer to output the desired outcome as this concept is revisited later during the assignment. 

Subsequently, the assignment demanded the caching of the same data table. After this initial data processing, I re-ran the exact query from the previous section, once again calculating the time necessary for the output, in hopes of reducing the calculation time as we implemented a method to help work with large volumes of data. 

The final portion of the assignment was parallel to the previous one, but this time we used the parquet method to partition the initial data set on the date-built column in hopes of capitalizing on columnar processing properties to help reduce the output time. We partitioned the data, created a temporary view, and ran the same query to see if there was a reduction in calculation time. 

To review, all of the times that I noted were relatively similar as they were all within twenty-tenths of a second, but I can see how, when working with gigantic data sets, implementing the cache and parquet method can be extremely beneficial, and is definitely something that I am glad to have acquired basic knowledge of. 


