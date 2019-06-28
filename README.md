# BigData_Hadoop_PigLatin_Hive_Weblogs_Tableau
## Using all the tools mentioned above, created a data lake. Also simulated more datasets and upload to HDFS using Hive, then finally visualise with Tableau by connecting through ODBC  
You may find the basic datalake created from 3 datasets from various data sources, look through the folders "scoop","pig latin" and "hive".  
Scoop in specific, takes the data from a SQL server by my lecturer, and then we do our data cleaning before uploading to our HDFS via Hive import.  
Pig and Hive datasets came from FS and also did hive import to HDFS.  

After i did the basic requirements, i went on to make various datasets, inclusive on a weblog i made based on very realistic judgements(however,
I did assume no 2 users are on the same website at one page to better express the idea that time taken between each customer at a page
is relatively shorter than the time it takes for next customer to drop by) to simulate.

My weblog is versatile and can allow users to select how many "customers" in their database, and from what date to what date you want the weblog to produce.  
All datasets are simulated and random. See my codes and youtube video for more information on my datasets! At the bottom, you will see how i made use of my datalake to
visualise on Tableau desktop.  

The codes are here: [codes](https://github.com/cjy93/BigData_Hadoop_PigLatin_Hive_Weblogs_Tableau/tree/master/Create%20Weblogs%20and%20Datasets)

Youtube video links:

1) BonusData1 :   
[simulate weather vs sales based on real monthly data on temp and rainfall from data.gov.sg](https://www.youtube.com/watch?v=ICQbOFMSxfI)  
2) BonusData2 :   
[part 1 on how to create a exe file and how the script works](https://www.youtube.com/watch?v=1qGH6aF-tBI) and
                [how to script a weblog](https://www.youtube.com/watch?v=qCmfPTnzrYs)
3) BonusData3 :  
[Simulate count of complaint/feedbacks based on HTTP Status code from Bonus 2](https://www.youtube.com/watch?v=LhU-8s_qQYM)  

Finally, here are the tableau dashboards made using a driver ODBC to connect Tableau desktop to HDFS  
![Dashboard 1](https://github.com/cjy93/BigData_Hadoop_PigLatin_Hive_Weblogs_Tableau/blob/master/Create%20Weblogs%20and%20Datasets/Tableau%20Dashboard%201.PNG)  
![Dashboard 2](https://github.com/cjy93/BigData_Hadoop_PigLatin_Hive_Weblogs_Tableau/blob/master/Create%20Weblogs%20and%20Datasets/Tableau%20Dashboard%202.PNG)  
Youtube links for Tableau dashboards
[Dashboard 1](https://www.youtube.com/watch?v=vR1LQ6HF0oE)
[Dashboard 2](https://www.youtube.com/watch?v=dVPIJFJvxqU)

