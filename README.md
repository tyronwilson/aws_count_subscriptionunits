# Count AWS resources for ServiceNow Subscription Unit licensing.
Bash script to count resources for ServiceNow Subscription Unit licenses

Run this script in an AWS CloudShell terminal.

## Example output
```bash
./aws_resources.sh 
Scanning region eu-west-1 ...
AWS::EC2::Instance count =33
AWS::RDS::DBInstance count =0
Scanning region eu-west-2 ...
.
.
.
Scanning region sa-east-1 ...
AWS::EC2::Instance count =0
AWS::RDS::DBInstance count =0
Total number of resources is 1094
```
