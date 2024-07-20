# Hosting a Website on Amazon S3🌐
![Screenshot 2024-07-20 at 22 05 53](https://github.com/user-attachments/assets/cc597502-3839-4ad4-a723-333df8b63621)

## Introduction🚀
Today's project involves using Amazon S3 to host a static website. Let's walk through the process step by step.

## Getting Started🎯

### What is Static Website Hosting?🌍
Static website hosting allows you to deploy a website to the public on the internet.

### Initial Setup on AWS🛠️
I enabled static website hosting on S3 by configuring ACLs (Access Control Lists) for my files.

### Unexpected Challenge ❗
Initially, accessing the hosted website endpoint resulted in a 403 Forbidden error, indicating that my files were still private.

## Step-by-Step Guide📝

### 1. Create an S3 Bucket📦
Creating an S3 Bucket took less than 5 minutes. Remember, S3 bucket names must be globally unique.

![Screenshot 2024-07-20 at 21 24 59](https://github.com/user-attachments/assets/45b1c72e-5aba-4ba5-be49-dce966610740)


### 2. Upload Website Files🖥️
I uploaded index.html and related files. HTML files are crucial as they define the structure of web pages.

![Screenshot 2024-07-20 at 21 39 00](https://github.com/user-attachments/assets/2d51a2eb-a2b0-4022-b59d-76267093edd7)

### 3. Configure Static Website Hosting🌟
In the Properties of my bucket, I configured static website hosting to make my site public.

### 4. Accessing Your Website🔗
Upon visiting the bucket's endpoint URL, ensure your objects are public to avoid access errors.

![Screenshot 2024-07-20 at 21 57 10](https://github.com/user-attachments/assets/baee43e6-ff3d-4cd9-bcac-6b9669157cf3)

### 5. Troubleshooting Errors🔍
If you encounter a 403 Forbidden error, adjust your ACL settings to make your objects public.

![Screenshot 2024-07-20 at 22 02 56](https://github.com/user-attachments/assets/0818252a-3690-4852-9485-d45bd58789d8)

### Conclusion🎉
Successfully resolving the error, I now have my website hosted on Amazon S3.

![Screenshot 2024-07-20 at 22 05 53](https://github.com/user-attachments/assets/de11ef81-24bc-459a-9dbd-7d3b8350200f)
