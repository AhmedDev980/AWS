CFT is a cloud formation template which is used to create the infra in AWS. We can use CFT in only AWS. It is a Iac tool.
Diff between AWS CLI  and AWS CFT is CLI is not a Iac tool and moreover it will be helpful for writing short scripts and code and for quick actions where as CFT is used for large stacks.

           USER----YAML/json--------->CFT----API calls-------->AWS

Drift detection is the key feature. If someone disables the versioning then we can use the drift detection option to see the previous changes and current changes.
Things needed while writing CFT ( version, description, metadata, parameters, rules, mappimgs, conditions, resources ) 

Type: AWS::EC2::Instance
Properties:
  AdditionalInfo: String
  Affinity: String
  AvailabilityZone: String
  BlockDeviceMappings: 
    - BlockDeviceMapping
