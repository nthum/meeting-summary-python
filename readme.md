The below are are deployed using terraform code used for IaC.
The code in checked in the git repo which later then uses CI/CD to run the pipeline confired using gitlab yml.

1. Install required libraries

2. Log in to AWS Management Console

3. Launch EC2 instance:
   - Choose Amazon Linux 2 AMI
   - Select instance type (e.g., t2.micro)
   - Configure security group to allow HTTP (port 80) and SSH (port 22)
   - Create and download new key pair

5. Install dependencies on EC2

6. Transfer files to EC2

7. Run the Streamlit app:

8. Configure EC2 security group to allow inbound traffic on port 80

9. Run Streamlit in background

10. Set up monitoring with AWS CloudWatch

11. Configure Auto Scaling for handling increased traffic