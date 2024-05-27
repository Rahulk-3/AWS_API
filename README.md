# AWS_API

# AWS EC2 Instance Starter

This Python script allows you to login to AWS programmatically using Boto3 and start an EC2 instance.

## Prerequisites

Before running this script, ensure you have:

- Python installed on your system
- Boto3 library installed (`pip install boto3`)
- AWS credentials (Access Key ID and Secret Access Key) configured either in a credentials file or environment variables

## Usage

1. Clone this repository or download the Python script.
2. Configure your AWS credentials:
   - Set the `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables.
3. Replace `'YOUR_INSTANCE_ID'` in the script with the actual ID of the EC2 instance you want to start.
4. Run the script using Python:
   ```bash
   python start_ec2_instance.py
