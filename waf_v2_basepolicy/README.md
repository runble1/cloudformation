aws cloudformation create-stack --stack-name waf-v2-basepolicy --region ap-northeast-1 --template-body file://waf_v2.yaml --capabilities CAPABILITY_NAMED_IAM
aws cloudformation deploy --stack-name waf-v2-basepolicy --template-file waf_v2.yaml --capabilities CAPABILITY_NAMED_IAM
aws cloudformation delete-stack --stack-name waf-v2-basepolicy

