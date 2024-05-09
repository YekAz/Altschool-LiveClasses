# In this simple project, I deployed a static website with AWS S3 using ClouFront as the CDN

## Here are the steps i took to achieving this

## STEP 1: Configuring the S3 bucket

    I logged into my AWS account as the root user.

    I created an s3 bucket and uploaded my static website files
![s3-bucket](./s3-bucket-files.png)

    I then configured my s3 bucket to enable static website hosting and other necessary configurations like specifying the index document
![s3-static](./s3-bucket-config.png)

    The bucket policy was added.
![s3-policy](./s3-bucket-policy.png)

    After successfuly doing the above, I was able to access my website through the Amazon S3 endpoint on the internet

* ## End-point URL
![s3-endpoint](./s3-bucket-endpoint-url.png)

* ## My Website
![s3-endpoint](./s3-endpoint.png)

