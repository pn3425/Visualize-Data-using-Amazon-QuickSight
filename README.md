# Visualize-Data-using-Amazon-QuickSight
In this mini-AWS project, we'll be visualizing data with Amazon QuickSight, Amazon S3, and Bright Data. The dataset consists of 50,000 Amazon bestseller products sourced from Bright Data.
Dataset Link - https://github.com/techwithlucy/youtube/tree/main/2-s3-quicksight
Amazon Services used - S3, Quick Sight

# 1) Configuring and Setting up S3 Bucket
    -> Download the dataset and manifest. json file from the link specified above.
    -> Now for Storing the dataset in S3 Bucket,
       -> In the AWS Console search for S3
       -> Click on create bucket
       -> Enter the bucket name , keep all the setting to default and finally click create
       -> Now click on the bucket you created, and click on upload button to upload the csv file
       -> In the manifest.json file enter your bucket name, 
          "s3//BUCKET-NAME/Amazon-Bestseller-Dataset.csv"
       -> Now upload the manifest.json file

#2) Amazon Quicksight Setup 
