# AWS S3 BUCKET POLICY EXPLORATION

## Purpose:

### In this project, I will work with Amazon S3 bucket policies to control access to my S3 buckets. The project is a guideline through creating a simple S3 bucket, defining a policy to manage access permissions, and testing the policy by uploading and retrieving objects.

#### 1. Create an S3 bucket using the AWS Management Console.
   - Login to the AWS console
   - Navigate to S3 service
   - Click the "Create bucket" button

   ![creat bucket](./img/cb-1.png)
   - Follow the prompt to configure the S3 bucket

   ![succefully created bucket](./img/cb-2.png)


#### 2. Add an object
   - Click the "Upload" button

   ![upload object](./img/ao-1.png)
   - Follow the prompt to upload the object file

   ![successfully uploaded object](./img/ao-2.png)


#### 3. Create a folder
   - Click on "Create folder"
   - Follow the prompt to successfully create the folder

   ![Create folder](./img/cf-1.png)


#### 4. Move the uploaded object to the created folder
   - Click on the object that is to be moved

   ![move object](./img/mo-1.png)
   - Go to "Action" and click on "Move"
   - Follow the pompt to successfully move object

   ![successfully moved object](./img/mo-2.png)


#### 5. Access the object URL online
   - Click on the object
   - Go to Properties
   - Copy the object URL and access it online

   ![access URL online](./img/ac-ob-url-01.png)


#### 6. Policy Configuration
1. Block public access (bucket settings)

 - Go to "Permissions"

   ![create a policy](./img/policy-1.png)
   - Scroll down to "Block public access (bucket settings)" and click on "Edit"
   - Uncheck "Block all public access" and save changes
2. Create a new JSON-formatted bucket policy in the AWS Management Console

   - Go to "Permissions"
   - Scroll down to "Bucket policy" and click on "Edit"
   -  Click on "Policy generator" to generate a new JSON-formatted bucket policy
   - Follow the prompt to successfully generate a bucket policy

   ![create a policy](./img/policy-2.png)

2. Apply the policy to the S3 bucket

![create a policy](./img/policy-3.png)


