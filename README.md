# AWS-Auto-Scaling-Group-with-Dynamic-Scaling-and-CloudWatch-Alarms

📘 Project Overview
This project demonstrates how to set up an Auto Scaling Group (ASG) in AWS that dynamically scales EC2 instances based on real-time CPU utilization, using Target Tracking Scaling Policies and CloudWatch Alarms. It showcases a fault-tolerant, cost-effective architecture designed to handle varying traffic loads with minimal manual intervention.

✅ Key Features
Auto Scaling Group (ASG): Automatically launches or terminates EC2 instances based on CPU usage thresholds.

CloudWatch Alarms: Monitors instance metrics and triggers scaling actions at defined thresholds (e.g., >40% and <28% CPU).

Application Load Balancer (ALB): Distributes incoming traffic evenly across instances for high availability.

Launch Template: Automates instance configuration with user data scripts (Apache installation, stress tool for testing, etc.).

Stress Testing: Simulates traffic to test the responsiveness and elasticity of the scaling mechanism.

🛠️ Technologies Used
Amazon EC2

Auto Scaling Group (ASG)

Application Load Balancer (ALB)

CloudWatch Metrics and Alarms

Target Tracking Scaling Policies

Bash scripting for bootstrapping

This setup is ideal for learning dynamic infrastructure scaling, preparing for AWS certifications, or building resilient cloud-native applications.

