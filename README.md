Lambda function to identify and delete stale EBS snapshots, optimizing AWS storage costs.

Project Description:

This project implements an AWS Lambda function designed to optimize cloud storage costs by identifying and deleting stale EBS snapshots. 
The function retrieves all EBS snapshots owned by the account and lists active EC2 instances, including those in running and stopped states. 
It checks each snapshot to determine if its associated volume is linked to any active instance. 
If a snapshot is found to be unattached to an active volume, it is deleted automatically. 
This automated process helps maintain a cleaner environment, reduces unnecessary storage expenses, and enhances overall resource management in AWS.
