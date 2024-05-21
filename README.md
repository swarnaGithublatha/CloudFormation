# CloudFormation anatomy -search

# yaml or json
# key-value pairs
# Data types - strings, boolean, list, integer, pipe, floating point numbers

YAMl
AWSTemplateFormatVersion:
Descriprtion:
Metadata:
Parameters:
Rules:
Mappings:
Conditions:
Transform:
Resources:
Outputs:

#Resources:
 ApptierBucket:  Logical ID --any name
  Type: AWS::S3::Bucket -- as per documentation
  Properties: --as required
  Tags: 
    -key: 
    value:

AWS CF YAMl (Step-Step)
1. Open VS code, create file> save in any folder
2. open and copy the Template anatomy to VS COde - VERSION, DESCRIPTION, RESOURCES
