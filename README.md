# AWS_Resources_Listing_Automation
Built a shell script dynamivally list AWS resources across services with in an account
# AWS Resource Listing Automation using Shell Scripting

## 📌 Overview
This project automates the process of listing AWS resources within an AWS account using a Bash shell script.  
The script dynamically prompts the user to select an AWS region and the AWS service, then retrieves and displays the available resources using AWS CLI commands.

It helps in quick auditing, monitoring, and understanding resource usage across AWS environments.

---

## 🚀 Features
- Interactive user input for AWS region selection  
- Interactive selection of AWS services  
- Lists resources dynamically based on user input  
- Uses AWS CLI for secure and authenticated access  
- Reusable and extensible shell script  

---

## 🛠️ Tech Stack
- Linux  
- Bash / Shell Scripting  
- AWS CLI  
- AWS Cloud Services  

---

## 📂 Prerequisites
Before running the script, ensure you have:

- Linux-based system  
- AWS CLI installed  
- AWS credentials configured (`aws configure`)  
- Valid IAM permissions to list AWS resources  

---

## ⚙️ How It Works
1. The script prompts the user to enter the AWS region.
2. The user is asked to specify the AWS service (e.g., EC2, S3, IAM).
3. Based on the inputs, the script executes AWS CLI commands.
4. The available resources for the selected service and region are displayed.

---

## ▶️ Usage

```bash
chmod +x aws_resource_list.sh
./aws_resource_list.sh
