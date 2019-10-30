# manage_aws_with_ansible

- Following playbook creates: 
    1. VPC with 6 subnets in 3 AZs
    2. Public and Private Route-Tables
    3. Associates public subnets to Public-Route-Table
    4. Associates private subnets to Private-Route-Table
    5. Creates IGW and attaches it to Public-Route-Table

- Each AZ contain 1 public and 1 private subnets

    Variables have to be set are:
    - name_of_VPC:
    - region:
    - az1:
    - az2:
    - az3:
