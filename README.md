![terraform-x-aws-1](https://user-images.githubusercontent.com/61271519/84424047-2a812f00-ac28-11ea-9aea-4d744138f44f.png)

# Set AWS Credentials in Windows PowerShell:

$env:AWS_ACCESS_KEY_ID="xxxxxxxxxxxxxxxxx"
$env:AWS_SECRET_ACCESS_KEY="yyyyyyyyyyyyyyyyyyyyyyyyyyyy"
$env:AWS_DEFAULT_REGION="zzzzzzzzz"

# Set AWS Credentials in Linux Shell:

export AWS_ACCESS_KEY_ID="xxxxxxxxxxxxxxxxx"
export AWS_SECRET_ACCESS_KEY="yyyyyyyyyyyyyyyyyyyyyyyyyyyy"
export AWS_DEFAULT_REGION="zzzzzzzzz"

# Terraform Commands

terraform init
terraform plan
terraform apply
terraform destroy

terraform show
terraform output
terraform console
