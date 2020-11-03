# UCDOEND-Project-2

This is the Udacity Cloud Dev Ops Engineer Nanodegree project 2.

Running this project will deploy AWS infrastructure via a CloudFormation script.

In order to run:

1. Put all Files in a folder
2. With a configured AWS account and AWS CLI installed, Run the following command in a windows terminal:

  cmd.exe /c create.bat "Udacity-Project-2" Udacity_Project_2.yaml Project_2_Parameters.json

Udacity_Project_2.yaml is a nested stack. It is not necessary to run network-layer-stack.yaml or servers-stack.yaml to deploy the project. They are included for evaluation.

Thanks!

