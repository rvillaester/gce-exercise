GCE lab is taken from ACloudGuru's Google Certified Associate Cloud Engineer course.
While they do it in the console, I do it here via CLI and deployment manager

First exercise is create a GCE instance in a brand new project. Install the stackdriver
agent on the instance then monitor the activities

Second exercise is to add auto-scaling on the first exercise

Third exercise is doing the first exercise via deployment manager

Note:
1. I'm running the CLI in Cloud Shell
2. You can get the billing account id by running the following
    gcloud alpha billing accounts list
3. Make sure that the bucket name is unique
4. Make sure to run the CLI against the right project