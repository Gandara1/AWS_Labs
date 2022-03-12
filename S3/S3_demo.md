# S3 Static Website Demo
---
## Part 1: Create your instance
---
>***Open the AWS console at [aws.amazon.con](https://aws.amazon.com/)***
>
>Select S3 from the search bar after you log in. 
>
![S3search](images/s3_search.png)
>Select **Create Bucket**
>
![create bucket](images/create_bucket.png)
>
>Part 1: Create your Bucket 
>
>>***The bucket name must be a globally unique name***
>>
>>Object Ownership will have disabled ACLs by default.  This will require us to make S3 resource policies to allow public access to our buckets. 
>>
>>Block Public Access is enabled by default.  We will uncheck that box and allow public access
>>
>>We will enable bucket versioning
>>
>>The remaining settings on this page will be default settings. 

![S3 Bucket creation](images/s3_bucket_creation/s3_bucket_creation.gif)
---
## Part 2: Upload your First File
>Before we begin, make sure to click this [***link***](https://drive.google.com/uc?export=download&id=1xSwlSNYvF9GunT_0hvXj-hNiBlqlXAKV) to download the index.html file for this lab. 
>
>**Step 1:** Select the bucket you just created
>
>**Step 2:** Select upload
>
>**Step 3:** select add files
>
>**Step 4:** find the index.html file you just downloaded and upload it to your bucket. 

![upload file](images/upload_file/upload_file.gif)
---
---
## Part 3: Provide public access to your bucket through policy
>Step 1:
