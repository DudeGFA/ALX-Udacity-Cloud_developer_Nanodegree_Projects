# Deploy a static website through Amazon web services

### Steps taken:

* First, I created an S3 bucket
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/1-Create%20S3%20bucket.jpg>

* I uploaded the website files to the bucket
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/2-Upload%20files%20to%20S3%20bucket.jpg>

* I secured it using IAM policies
 <img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/3-Secure%20Bucket%20via%20IAM.jpg>
 
* The bucket was then configured for website hosting
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/4-configure%20S3%20bucket.jpg>

* I sped up content delivery using AWS’s content distribution network service, CloudFront.
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/5-distribute%20website%20via%20cloudfront.jpg>

### The website can be accessed using a web browser through 3 methods:
1. **Through it's CloudFront domain name**
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/Website%20access%20methods/Website%20access%20through%20cloudfront%20domain%20name.jpg style="height: 512px">

2. **Access the website via website-endpoint**
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/Website%20access%20methods/Acess%20through%20website%20endpoint.jpg style="height: 512px">

3. **Access the bucket object via its S3 object URL**
<img src=https://github.com/DudeGFA/ALX-Udacity-Cloud_developer_Nanodegree-program/blob/main/Project-1%20Deploy%20static%20website%20to%20AWS/Website%20access%20methods/Website%20access%20through%20S3%20object%20URL.jpg style="height: 512px">

>Due to the cost of using AWS services and the limited budget allocated to the AWS account provided by Udacity, the website is currently unavaliable.
