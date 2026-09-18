🛠️ AWS Cloud Practitioner — Hands-On Training Portfolio

Welcome to my AWS Cloud Practitioner practical training repository. This project documents my completion of comprehensive, scenario-based labs designed to simulate and solve real-world infrastructure challenges using Amazon Web Services (AWS). 

Through these modules, I moved past theoretical cloud concepts and directly practiced architectural design, network configuration, high-availability deployments, security tuning, database administration, and cloud cost optimization.

**📋 Project Structure & Business Scenarios**

The repository is modeled after 12 distinct business case studies:
Scenario 1: Setting up reliable static web hosting using decoupled storage endpoints.
Scenario 2 & 3: Migrating on-premises physical hardware to virtualized infrastructure and managing vertical compute scale.
Scenario 4: Troubleshooting foundational network architecture, routing paths, and port access.
Scenario 5: Resolving cross-department network isolation blocks through private routing components.
Scenario 6: Modernizing relational database operations to reduce administrative overhead and implement high availability.
Scenario 7: Enforcing strict compliance frameworks and user access control criteria.
Scenario 8: Architecting serverless, shared file infrastructure for distributed regional offices.
Scenario 9 & 12: Developing elastic, auto-healing application tiers to survive physical availability zone outages and traffic surges.
Scenario 10: Engineering end-to-end cloud architecture cost estimates for corporate financial tracking.
Scenario 11: Implementing schema-less, low-latency key-value stores for massive user analytical data collection.


**🧠 Core Skills & Technologies Practiced**

🌐 Networking & Secure Connectivity (VPC Infrastructure)
- Isolated Environment Design: Deployed multi-tier Virtual Private Clouds (VPCs) complete with custom public and private subnets to segregate public-facing web servers from backend databases.
- Routing & Internet Access: Configured Route Tables, Internet Gateways (IGWs), and Network Address Translation (NAT) gateways to provide or restrict external connectivity per system design requirements.
- Network Isolation & Security Tuning: Implemented and modified AWS Security Groups and Network Access Control Lists (NACLs) to manage granular traffic permissions, opening specific ports (e.g., HTTP Port 80, MySQL Port 3306) to enforce tight server-to-database communication loops.
- Inter-Network Communications: Successfully architected and established secure VPC Peering Connections across isolated departments (Finance, Marketing, Development) within single and multi-account environments, modifying respective route tables to allow cross-VPC data flows without routing public internet traffic.

💻 Compute & Scaling Architecture (EC2 & Auto Scaling)
- Instance Management: Provisioned high-availability Amazon EC2 virtual machines (such as t3.micro instances) to replace legacy, failing on-premises physical hardware.
- Vertical Scaling: Analyzed resource constraints and manually resized compute resource families to gracefully handle spikes in compute demand.
- Elasticity & High Availability: Designed and deployed Auto Scaling groups across multiple Availability Zones (AZs) backed by launch templates to establish automated "auto-healing" mechanics for crashing instances.Traffic Distribution: Integrated Elastic Load Balancers (ELB) to evenly distribute incoming customer application traffic and structured automated load balancer health checks to ensure continuous system reliability.
- Scheduled Operations: Configured scheduled scaling policies to automatically provision servers ahead of known peak-demand calendar events and automatically scale down resources to curb unnecessary expenditure.

🗄️ Storage & Database Systems (S3, EFS, RDS, DynamoDB)
- Static Web Hosting: Configured object storage via Amazon S3 to host reliable, publicly accessible static website endpoints, establishing secure bucket policies to safeguard underlying assets.
- Shared Network File Systems: Deployed Amazon EFS (Elastic File System) and configured multi-AZ mount targets to share active photo/file repositories across distinct distributed branch offices.
- Linux Storage Engineering: Used Linux shell environments (sudo, yum) to install amazon-efs-utils and successfully mounted cloud-managed network shares over TLS (mount -t efs -o tls).
- Relational Database Lifecycle: Provisioned Amazon RDS instances to hand off operational patching, automated backups, and database infrastructure maintenance.
- Database High Availability & Performance: Deployed Multi-AZ standby replicas for robust failover defense and established RDS Read Replicas to decouple read-heavy analytical query traffic from primary write databases.
- NoSQL Database Architecture: Constructed schema-less Amazon DynamoDB tables to support scalable, single-digit millisecond latency features (such as user metadata bookmark features) capable of handling petabyte-scale datasets.

🔐 Security & Identity Management (IAM)
- Principle of Least Privilege: Crafted specific role-based system access barriers by organizing engineers into restricted AWS IAM Groups.
- Policy Management: Evaluated and attached specialized AWS Managed Policies (such as AmazonEC2ReadOnlyAccess) to restrict identities from modifying production cloud environments.

📊 Cloud Economics & Optimization
- Architecture Cost Estimations: Modeled comprehensive future infrastructure overhead using the official AWS Pricing Calculator.
- Cost Allocation Modeling: Analyzed total cost ownership breakdown variables for groups of EC2 web servers to generate shareable cost optimization projections for business leadership stakeholders.

🏆 Badge & Lab Milestone Verification
- Completed 10+ live cloud infrastructure production simulation scenarios.
- Resolved live network debugging tickets, applied explicit IAM authorization schemes, and mapped dynamic distributed Linux storage systems via the AWS Management Console and command-line interfaces.
