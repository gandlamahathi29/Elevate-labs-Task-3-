# Terraform Docker Task

## Description
This project provisions a Docker container using Terraform with Nginx image.

## Steps Followed:
1. Wrote Terraform code in `main.tf`
2. Ran `terraform init`, `plan`, `apply`
3. Verified container running on localhost:8080
4. Destroyed the setup using `terraform destroy`

## Requirements:
- Docker
- Terraform

## Result:
A Docker container named `nginx_web` was created and served the Nginx default page on port 8080.

