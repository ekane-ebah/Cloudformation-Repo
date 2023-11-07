aws cloudformation create-stack --stack-name dev-network-infra-pf --template-body file://network.infra.yaml --parameters file://sg.yaml 

# to delete stack
aws cloudformation delete-stack \
    --stack-name dev-network-infra-pf