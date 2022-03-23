# CloudFormation Examples

Repository of CloudFormation examples. There are too many example to write up each. For the more complex CloudFormation examples that deploy multiple services a diagram of the services they deloy is provided below.

---

- [OpenSearch Demo/OpenSearch_demo.yaml](https://github.com/ev2900/CloudFormation_Examples/blob/main/OpenSearch%20Demo/OpenSearch_demo.yaml) 

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=open-search-demo&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/OpenSearch_demo.yaml)

<img width="500" alt="OpenSearch_demo_Architecture" src="https://github.com/ev2900/CloudFormation_Examples/blob/main/Architecture%20Diagrams%20for%20README/OpenSearch_demo_yaml.png">

---

- [OpenSearch Demo/OpenSearch_demo_VPC.yaml](https://github.com/ev2900/CloudFormation_Examples/blob/main/OpenSearch%20Demo/OpenSearch_demo_VPC.yaml)

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=open-search-demo-vpc&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/OpenSearch_demo_VPC.yaml)

<img width="700" alt="OpenSearch_demo_VPC_Architecture" src="https://github.com/ev2900/CloudFormation_Examples/blob/main/Architecture%20Diagrams%20for%20README/OpenSearch_demo_VPC_yaml.png">

---

- [OpenSearch Demo/OpenSearch_cross_cluster_replication_demo.yaml](https://github.com/ev2900/CloudFormation_Examples/blob/main/OpenSearch%20Demo/OpenSearch_cross_cluster_replication_demo.yaml)

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=open-search-cross-cluster-replication&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/OpenSearch_cross_cluster_replication_demo.yaml)

<img width="700" alt="OpenSearch_demo_VPC_Architecture" src="https://github.com/ev2900/CloudFormation_Examples/blob/main/Architecture%20Diagrams%20for%20README/OpenSearch_cross_cluster_replication_demo_yaml.png">

---

- [OpenSearch Demo/OpenSearch_demo_Cloud9_simple.yaml](https://github.com/ev2900/CloudFormation_Examples/blob/main/OpenSearch%20Demo/OpenSearch_demo_Cloud9_simple.yaml)

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=open-search-demo-cloud9-simple&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/OpenSearch_demo_Cloud9_simple.yaml)

<img width="450" alt="KDA_studio_kinesis_demo_yaml" src="https://github.com/ev2900/CloudFormation_Examples/blob/main/Architecture%20Diagrams%20for%20README/OpenSearch_demo_Cloud9_simple_yaml.png">

---

- [KDA Studio Demo/KDA_studio_kinesis_demo.yaml ](https://github.com/ev2900/CloudFormation_Examples/blob/main/KDA%20Studio%20Demo/KDA_studio_kinesis_demo.yaml)

[![Launch CloudFormation Stack](https://sharkech-public.s3.amazonaws.com/misc-public/cloudformation-launch-stack.png)](https://console.aws.amazon.com/cloudformation/home#/stacks/new?stackName=KDA_studio_kinesis_demo&templateURL=https://sharkech-public.s3.amazonaws.com/misc-public/KDA_studio_kinesis_demo.yaml)

<img width="500" alt="KDA_studio_kinesis_demo_yaml" src="https://github.com/ev2900/CloudFormation_Examples/blob/main/Architecture%20Diagrams%20for%20README/KDA_studio_kinesis_demo_yaml.png">

## Future Improvements Planned for this Repository

1. Log ingestion via. Fluentd to S3
2. Log ingestion via. Fluentd to OpenSearch
3. Log ingestion via. Logstash to OpenSearch
4. Kinesis Data Analytics (KDA) Studio sending data to OpenSearch
