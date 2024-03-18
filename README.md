# shell_script_projects
# Project 1: AWS Resource usage Tracker:
# Project Description:
This project is a simple script designed to report AWS resource usage. It provides a snapshot of various AWS services such as S3 buckets, EC2 instances, Lambda functions, and IAM users.
The script is intended to be run periodically to keep track of changes in resource usage over time.it will execute the script Resource_tracker_script.sh on EC2 instance with OS Amazon Linux 2023
and  fetch information about AWS resources and store it in a file named 'resource_tracker'. The script is sheduled to run automatically after every 1 hours using crontab sheduler.
# Dependencies:
# AWS CLI:
Ensure that you have the AWS Command Line Interface (CLI) installed and configured on your system. The script utilizes AWS CLI commands to fetch information about AWS resources.
# jq: 
The script uses jq command-line JSON processor to parse and format JSON output from AWS CLI commands. Make sure jq is installed on your system.
# Notes:
This script provides a basic overview of AWS resource usage and may need to be customized or extended based on specific requirements.

