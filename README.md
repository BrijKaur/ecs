# Elasticsearch Cluster on AWS

Launch 3 EC2 instances (in free tier) and setup a cluster of 3 ElasticSearch nodes on it.
ElasticSearch is configured in such a way that requires credentials and provides encrypted communication the demonstration of the functioning is also shown.

The entire project has been explained in detail in the esc detail file

The cross-cutting concerns addressed are:
security 
(encrypted communication and credentials required for ElasticSearch 
and 
also, on the Ansible EC2 Server IAM role is assigned for EC2 access instead providing AWS Secret and Access Key), 
reusability (in the playbook, roles are designed to offer reusability) 
and 
cost optimization (use of free tier only) 

