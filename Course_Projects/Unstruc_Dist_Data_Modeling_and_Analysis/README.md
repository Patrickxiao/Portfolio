**The dataset used for this project can be found at: https://www.kaggle.com/datasets/dhruvildave/spotify-charts
**

Project Requirements: 

Basic Requirements
* Dataset: You can use any dataset in the project. However, your data should have substantial size. This is a big data course so datasets below 10MB are not allowed. 
* Environment: You can use Docker to develop and test your code. In the end, you are required to use AWS EMR cluster to run your analysis.
* Programming Language: You can use any type of programming languages or business analytics tools, but must include the use of Spark with Python (PySpark), which needs to be deployed on the cluster; that is, if you need to implement a specific feature but it is not available in Spark, you have the flexibility to justify it and use other tools, but meanwhile you still need to make sure you have something implemented by PySpark in that case. 

Functional Requirements
* Data Ingestion: You can read local files when developing your code locally, but when deploying your code on AWS cluster, you need to save your dataset into AWS S3. Then read data from AWS S3 to do analysis on the AWS cluster. Obtain statistics and perform analysis of the ingested dataset (with PySpark or other packages if necessary) and display your insights (use Jupyter notebook or other type of visualization).

Performance Requirements
* You can test your application or analysis on your laptop with Docker; you are suggested to make sure your code work on Docker first and then run it on the cluster. With your application deployed on the cluster, your implementation should show the potential of horizontal scaling (i.e., when adding more nodes the cluster, the processing should be faster) and take advantage of distributed computing.
