# In this simple project, I deployed a static website with AWS S3 using ClouFront as the CDN

## Here are the steps i took to achieving this

## STEP 1: Configuring the S3 bucket

    I logged into my AWS account as the root user.

    I created an s3 bucket and uploaded my static website files
![s3-bucket](./Ass-1/s3-bucket-files.png)

    I then configured my s3 bucket to enable static website hosting and other necessary configurations like specifying the index document
![s3-static](./Ass-1/s3-bucket-config.png)

    The bucket policy was added.
![s3-policy](./Ass-1/s3-bucket-policy.png)

