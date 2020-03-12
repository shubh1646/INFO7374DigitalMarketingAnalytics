# **Cross-channel marketing spend optimization using deep learning - ASSIGNMENT 3-Part2**

## **Developed a Data-pipline using  Amazon AWS** 

**CLAAT LINK:**  https://docs.google.com/document/d/1glWtBM69mdFV27w7KXSFEnLpGg7eYs5rYgGPRy-Z2zc/edit?usp=sharing

Format: ![Alt Text](https://github.com/Abhishek-Gargha-Maheshwarappa/INFO7374DigitalMarketingAnalytics/blob/master/Assignment%203%20part2/Data%20Flow.png)

**Data** -  https://s3-eu-west-1.amazonaws.com/attribution-dataset/criteo_attribution_dataset.zip

# **Steps**
1.  Amazon AWS was used by setting up **EC2 instance** with Ubuntu server-16 setup a Jupyter Notebook. 
2   Data was loaded on the **S3 bucket.**
3.  With web **AWS Glue crawler** connected it to **AWS Athena**.
4.  The output of the Model was saved in the S3 bucket.
5.  The data is connected to the **Apache SuperSet** for visulaization.
 
Python notebook will run on **google colab** with changes to data path and saving location.
