aws cloudformation deploy --stack-name waf-v2-basepolicy --template-file waf_v2.yaml --capabilities CAPABILITY_NAMED_IAM
aws cloudformation delete-stack --stack-name waf-v2-basepolicy


aws --profile Terraform-WAF-DEVSTG cloudformation deploy --stack-name glue-for-waf --template-file glue_for_waf.yaml --capabilities CAPABILITY_NAMED_IAM
