The sg_eks folder:
it contains 3 files, they are terraform files where the eks security group is defined. The variable.tf defines the vpc, the sg.tf defines the aws_security_group, the ingress and egress.
the output.tf describes the output of the security group.


The eks Folder:
It also contains 3 files, the eks.tf, output.tf and variables.tf.
the variable.tf is where the variables of the security group ids, subnet ids and the vpc id.

the Output.tf contains the value of the endpoint.
The eks.tf this is where the roles are defined, policies and the dependencies. also the cluster roles is defined here, the subnets and the roles they are dependent on.
the node group is also defined 


The VPC_with_EC2.tf 
This is where the aws resources were defined the subnets, the route_tables and the variables.tf are where the variable ids of the subnets where created 
