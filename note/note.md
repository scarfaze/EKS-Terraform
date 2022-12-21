src: https://developer.hashicorp.com/terraform/tutorials/kubernetes/eks

Outputs:

cluster_endpoint = "https://ED2908AF22027E8515B6E4F605577673.gr7.us-east-2.eks.amazonaws.com"
cluster_id = "Group4-eks-Qssn2QG3"
cluster_name = "Group4-eks-Qssn2QG3"
cluster_security_group_id = "sg-0e705c16db80f4bed"
region = "us-east-2"
PS C:\Users\oluse\OneDrive\Documents\Infrastructure-as-CodE\JJTech-AWS-ProjectScript\Eagle-batchGrp4-Practice\EKS-Cluster-terra\learn-terraform-provision-eks-cluster>  


Changes made:
    1,  on vpc.tf :  name = "Group4-vpc" , coments private subnet and nat gateway
    2,  on main.tf:  change cluster name
    3, on eks-cluster.tf:  change node group name