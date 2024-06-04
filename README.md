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

# 2) Amazon Quicksight Setup
    -> In the AWS console search for QuickSight service, 
    -> Click on signup to create quick sight account and choose enterprise version
    -> Enter your account name
    -> Now select the S3 Bucket, and finally click finish
    -> Now click on Go to Amazon QuickSight
    -> Click on Datasets, click on new dataset and click on S3
    -> Now there you will be prompted to provide manifest.json file link, so  on the S3 AWS Dashboard click on manifest. json object file and click on 
    copy S3 URI and paste in the particular field of S3 window in QuickSight
    -> Finally click on connect and further visualize
    -> Click on interactive sheet
    -> You will be able to see various column name that are imported on the left side
    -> Now we are ready to create some visualization

# 3) Visualisation on QuickSight
    We will visualise, Out of 50,000 brands which brand is most popular in Amazon
    -> Now name the sheet name as most popular brand
    -> Drag the brand column name in the sheet, and further click on sort option and choose sort by option as brand and sort order as Descending and finally press apply
    -> Now quicksight sorts the brand by the popularity from most popular to the least ones
    -> So for this particular dataset we see that Standard Motor is the most popular brand

    This was one of the example for visualisation for most popular brand, further more many other visualisations can be done for example comparing the prices of different best selling products, analysing the title of the best-selling products and many more.
