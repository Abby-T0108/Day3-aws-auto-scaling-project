Day3: AWS Auto Scaling Project
Overview
In this project, I set up an Auto Scaling Group (ASG) to automatically scale the number of EC2 instances based on CPU utilization metrics from CloudWatch. This is a real-world scenario used in many production environments to ensure applications have sufficient compute resources while saving costs by scaling down when demand is low.

Files and Configuration
•	index.html: Simple HTML page to display when website is accessed.
•	error.html: Error page for when something goes wrong.
•	cloudwatch-alarm.json: Configuration for the CloudWatch alarm to trigger scaling.
•	launch-template.json: EC2 Launch Template configuration to define instance settings.

Steps Taken:
•	Created a Launch Template for EC2 instances.
•	Set up Auto Scaling Group to scale instances based on CPU utilization.
•	Configured a CloudWatch Alarm to trigger scaling when CPU usage exceeds 70%.
•	Tested the Auto Scaling by manually causing high CPU usage.
•	Cleaned up resources after testing.

Tools/Services Used:
•	AWS EC2 (Elastic Compute Cloud)
•	AWS Auto Scaling
•	AWS CloudWatch
•	AWS CLI (optional for scripting)

Screenshots

EC2 Instance Running in Auto Scaling Group
https://github.com/Abby-T0108/Day3-aws-auto-scaling-project/blob/main/ec2-instance-scaling.png
CloudWatch Alarm Configuration
https://github.com/Abby-T0108/Day3-aws-auto-scaling-project/blob/main/cloudwatch-alarm-config.png
Auto Scaling Group Metrics
https://github.com/Abby-T0108/Day3-aws-auto-scaling-project/blob/main/auto-scaling-metrics.png

How to Run This Project:
1. Clone this repository:
   ```bash
   https://github.com/Abby-T0108/Day3-aws-auto-scaling-project
