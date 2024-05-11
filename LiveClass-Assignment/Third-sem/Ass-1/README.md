# In this simple project, I deployed a static website with AWS S3 using ClouFront as the CDN

## Here are the steps i took to achieving this

## STEP 1: Configuring the S3 bucket

I logged into my AWS account as the root user.

I created an s3 bucket and uploaded my static website files
![alt text](s3-create-page.png)

## I checked this to keep my S3 bucket private
![alt text](s3-bucket-privacy.png)

![alt text](s3-bucket-create.png)
## After creating my bucket, i started uploading my website files
![alt text](s3-bucket-upload-page.png)

![alt text](s3-bucket-files.png)

## STEP 2: Configuring the CloudFront Distribution

## I created and configured a CloudFront distribution using the static S3 end-point URL
![alt text](cf-page-1.png)

![alt text](cf-page-2.png)

![alt text](cf-OAC.png)

![alt text](cf-page-3.png)

![alt text](cf-page-4.png)

## The distribution was created and a policy was generated

![alt text](cf-distribution-page.png)

## Adding the policy generated to my S3 bucket permissions
![alt text](s3-permission-tab.png)

![alt text](s3-policy-edit.png)

![alt text](s3-policy.png)

## Save Changes

## The distribution is now enabled. So, i can now copy the distribution domain name to access the website throughmy browser 

![alt text](cf-domain-name.png)


## Website successfully rendered
![alt text](cf-rendered-website.png)


> # THANK YOU
> *yekinni azeez, the Cloud-Daemon*