
# This command will be used to create my stack
aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network-infra.yaml --parameters file://dev-parameter-file.json



# This command will be used to delete the stack on the console.
aws cloudformation delete-stack \
    --stack-name dev-network-infra-pf


