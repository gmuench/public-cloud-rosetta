| AWS	                     | Azure                        | Note                       | 
| ------------------------ | -----------------------------|----------------------------|
| AMI                      | VMI                          | machine images|
| Application Load Balancer| Application Gateway          | L7 web-centric. Azure API GW can route traffic to specifics VMs based on URL.|
| Auto Scaling             | VM Scale Sets                | horizontal scaling|
| Availability Zone        | Availability Zone            | isolated locations|
| aws.amazon.com/console/  | portal.azure.com             | portal|
| CloudHSM                 | Key Vault                    | hardware security module|
| Cloud Watch              | Monitor                      | Application logs,metrics,alarms|
| Cloud Formation          | Resource Manager Templates   | Infrastructure as Code|
| Code Deploy              | DevOps                       | |
| Code Commit              | DevOps                       | |
| Code pipeline            | DevOps                       | |
| Control Tower            | Blueprints                   | landing-zones|
| Direct Connect           | ExpressRoute                 | dedicated on-prem connection to the cloud|
| DynamoDB                 | CosmosDB                     | no-sql db, multi-region possible|
| Elastic Beanstalk        | App Service                  | |
| EMR                      | HDInsight                    | Managed Hadoop/Spark|
| GuardDuty                | Defender for identity (Advanced Threat Protection )   | Detect and investigate threats vs baseline|
| IAM                      | AAD                          | |
| Key Management Service   | Key Vault                    | Manage, create, and control keys |
| Kinesis Analytics        | Data Lake Analytics          | process data in parallel|
| Lambda                   | Functions                    | Serverless Compute|
| Light Sail               | App Service                  | |
| Network Load Balancer    | Load Balancer                | L4 TCP/UDP|
| Region                   | Region                       | Set of datacenters deployed within a latency-defined perimeter and connected through low-latency.|
| Route 53                 | DNS                          | DNS|
| Route 53                 | Traffic Manager              | geo routing|
| Redshift                 | Synapse                      | warehouse |
| Rekognition              | Cognitive Services           | Rekognition does image analysis only. Cognitive does images, speech, language, decision. |
| SageMaker                | Machine Learning             | Train, deploy, automate, and manage machine learning models.|
| Security Group           | Network Security Group       | Instance firewall|
| Secrets Manager          | Key Vault                    | Store secrets|
| Step Functions           | Logic Apps                   | visual workflow |
| Support Basic            | Support Basic                | all customers|
| Support Developer        | Support Developer            | |
| Support Business         | Support Standard             | production|
| Support Enterprise       | Support Professional Direct  | business-critical|
| Trusted Advisor          | Advisor                      | best-practice reccomendations|
| Virtual Private Cloud    | Virtual Network              | logically isolated network |
| Xray                     | Monitor                      | tracing |
| ---                      | Databricks                   | |
| ---                      | GZRS                         | |
| ---                      | Information Protection       | Protects PDFs/Emails/Offics docs|
| ---                      | Locks                        | CanNotDelete/ReadOnly|
