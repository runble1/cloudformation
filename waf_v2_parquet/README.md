aws cloudformation deploy --stack-name waf-v2-parquet --template-file waf_v2_parquet.yaml --capabilities CAPABILITY_NAMED_IAM
aws cloudformation delete-stack --stack-name waf-v2-parquet

