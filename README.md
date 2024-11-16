# **Harnessing Event-Driven Architecture with AWS Lambda for Seamless Data Processing**

In my latest project, I've implemented an event-driven architecture using AWS Lambda to streamline data processing workflows. Here's a brief overview of how it works:

# **Data Upload to S3 Bucket:**
  When a file is uploaded to an S3 bucket under the 'input' folder, it triggers an event.
# **Lambda Function Execution:** 
  The event invokes an AWS Lambda function. This function is equipped with the necessary IAM role to access and process the uploaded data.
# **Processing and Storage:** 
  The Lambda function processes the data and saves the resulting file back to an S3 bucket, specifically in the 'output' folder.
  
This setup ensures efficient, automated data handling, leveraging the power of AWS services to achieve seamless data processing.
# Architecture
![arch](https://github.com/user-attachments/assets/c4765a9c-d2f3-4b21-bc31-818033747107)
