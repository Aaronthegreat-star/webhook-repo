**Trigger Lambda via Webhook**
Project Overview

This project demonstrates a GitHub Actions workflow that triggers an API Gateway webhook. The API Gateway then invokes an AWS Lambda function to stop specified EC2 instances by processing instance IDs passed in the webhook payload.

Features:

Automates the triggering of an API Gateway to invoke a Lambda function.

Utilizes a cron schedule to execute daily at 8:00 UTC.

Sends instance IDs dynamically through the POST request payload.

