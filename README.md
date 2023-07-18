Envestnet Yodlee IT proposal 
# CLOUD-CA01-ASSIGNMENT 

### COMPANY: YODLEE REDI2

![alt text](https://mma.prnewswire.com/media/1746801/Redi2_Logo.jpg?w=200)

### **INTRODUCTION**
________________
Businesses often face challenges when managing significant IT technical problems. Before implementing new technology, it is crucial to examine existing hardware for compatibility, preventing integration issues, security vulnerabilities, and cyber threats to systems and data. It is important to reevaluate the role of technology and explore alternatives to internal IT networks. Fortunately, cloud computing offers a solution. With cloud computing, small and medium-sized enterprises (SMEs) can regain control over their IT infrastructure. By leveraging cloud computing, businesses can effectively address their IT needs while retaining complete control.

## Benefits of cloud 
_____________________
- Scalability : This flexibility allows companies to rapidly scale up during peak periods of high demand or scale down during periods of low activity
- Cost : Eliminates the need for upfront investments in hardware and infrastructure.
- Security : Multiple security remidiations are availble in cloud such as Encryption, Firewall and Network Security, Security Information and Event Management (SIEM), Data Loss Prevention (DLP), Threat Intelligence, Compliance and Governance, Security Auditing and Assessments, Backup and Disaster Recovery

![alt text](https://assets-global.website-files.com/5eb143b314c8f35745e1a7f0/623b1ffb22373b66a1443a18_tr8_3MzdcNxQ2E_Z38i5E7pw8xQiRx8wvuFWYn5nXsMCgnVj-WBKaaO3QXr3Ig_GOJ2iZeVPaldiHgKJIwqnIpyc_R_o_NewdAG4NWx9TaTD5JGTcGkRRt4jWGh-mNQRl7mdgyMV.png)


## **Background Of The Enterprise**

![alt text](https://financialit.net/sites/default/files/picsart_04-13-06.18.28_0.jpg)

Yodlee Redi2 is a provider of financial data aggregation and analytics solutions. Their platform and API suite enable secure access to vast amounts of financial data. With data aggregated from various sources, users gain a comprehensive view of their finances, allowing for informed decision-making. Redi2 prioritizes security and compliance with regulatory standards. Trusted by multiple institutions and fintech companies, they drive financial innovation and empower individuals and businesses in the digital era.
	

### Current IT Set Up
______________________

Redi2 operates on premise and azure cloud environment. Redi2 has multiple application services running in azure cloud. Redi2 works on website and mobile application development to connect with their customers. Redi2 uses the private cloud to manage their development environment. They use Azure cloud to run their production load. Which includes networking and workload application servers. Now they have a new application called “redi2 wallet” which need to be deployed to the production environment in Azure cloud.

## Contrast of Cloud and Non-Cloud Solutions
--------------------------------------------
The choice of cloud services significantly impacts the deployment architecture of a cloud-ready application, especially when strict compliance and data residency requirements are involved. Cloud computing is rapidly becoming the go-to platform for businesses of all sizes, from start-ups to large enterprises [Shaji George, 2023]

### Cloud
_________
- Scalability: Cloud resources can be easily scaled up or down based on demand, allowing businesses to efficiently manage their computing resources.
- Cost & Reliability: Cloud providers provide reliable infrastructure and redundant systems, ensuring high availability and minimizing downtime. Additionally, cloud computing eliminates the necessity for upfront investments in hardware and infrastructure, resulting in reduced operational expenses.
- Flexibility: Users can access cloud services and data from anywhere, using any device with an internet connection.
- Security: Cloud providers implement advanced security measures, including encryption and access controls, to protect data and systems.
- Automatic Updates: Cloud providers handle software updates and maintenance, ensuring that users have access to the latest features and security patches.

### Non-Cloud 
_____________

- Control: Organizations have full control over their hardware, software, security, and data allowing for customized configurations and tailored solutions.
- Compliance: For industries with strict regulatory requirements, an on-premises setup provides greater control over data governance and compliance.
- Customization: Organizations have the flexibility to customize their infrastructure, applications, and services to meet specific business requirements.
- Cost Predictability: Could predict the cost of running the environment. 
- Legacy Systems: On-premises setups can support legacy applications and systems that may not be easily migrated to the cloud.
- Long-Term Investment: Large investment required for upfront and maintenance
  
## Cloud Storage VS On-Premises Storage 
__________________________________________
When deciding where to store their data, businesses face a critical choice between on-premises and cloud storage. Understanding the key distinctions between these options is essential as they consider the advantages and disadvantages associated with each.

## Advantages of On-Premises Storage 
-------------------------------------
- Technological Advancements: On-site storage may struggle to keep pace with rapidly evolving technology. Upgrading infrastructure and staying up to date with the latest storage technologies and features can be challenging and costly.
- Scalability: On-site storage typically has limited scalability compared to cloud storage. As data needs grow, organizations may face challenges in expanding their on-site storage capacity, leading to potential bottlenecks and increased costs.
- Disaster Recovery: On-site storage may be vulnerable to physical threats like fires, floods, or theft. Implementing comprehensive disaster recovery solutions, including redundant backups and off-site storage, can be complex and costly.



## Why using on-site storage might not be the best choice?
___________________________________________________________
- Technological Advancements: On-site storage may struggle to keep pace with rapidly evolving technology. Upgrading infrastructure and staying up to date with the latest storage technologies and features can be challenging and costly.
- Scalability: On-site storage typically has limited scalability compared to cloud storage. As data needs grow, organizations may face challenges in expanding their on-site storage capacity, leading to potential bottlenecks and increased costs.
- Disaster Recovery: On-site storage may be vulnerable to physical threats like fires, floods, or theft. Implementing comprehensive disaster recovery solutions, including redundant backups and off-site storage, can be complex and costly.
- Redundancy and Failover: Achieving high levels of redundancy and failover capabilities in on-site storage can be complex and costly. Cloud storage providers often offer built-in redundancy and data replication across multiple data centers, providing better resilience and availability.

## Microsoft Azure for Small and Medium-sized Enterprises
 ___________________________________________________________

Cloud computing has become an essential tool not only in the business world but also in our daily lives. For small and medium-sized enterprises (SMEs), Microsoft Azure offers a reliable and secure cloud computing solution, particularly for data storage and project access. Azure, a leading cloud computing platform, provides on-demand services, enabling SMEs to easily store and access their data. In serverless computing when the particular application is not in use, resources will not be allocated by cloud service provider, hence it is cost efficient as billing is carried out on the basis [Hari Krishnan, 2021]. 

## Recommended Cloud Architecture
___________________________________

Redi2 developed a basic wallet management app. Their development application is hosted on premise, the production environment needs to be hosted in the azure cloud. The application is used to manage the expenses and credentials for their clients. Currently running on a dev environment on premise. 
To enhance security and cost-effectiveness, our implementation plan involves adopting containerization. This process includes setting up a virtual machine, establishing a database, creating containers, and building applications. To handle data storage, we will utilize the existing Azure blob storage solution. In order to reduce expenses, we have opted for the open-source Ubuntu operating system, which will host Docker for managing containers. For scalability and cost-efficiency, we have chosen MySQL as our database solution due to its robust capabilities and free availability. The Docker containers will play a crucial role in managing and deploying the application builds.


## Justification for Azure Cloud
__________________________________

Azure's strengths lie in its scalability and security. The platform offers robust scalability, allowing applications to easily adapt to changing demands by seamlessly increasing or decreasing resources as needed. 
Additionally, Azure places a strong emphasis on security, providing various layers of protection, encryption, and compliance certifications to ensure the confidentiality and integrity of data. Moreover, Redi2 can adapt the hybrid technology with ease compared to other competitors. 

## References
_________________________________________________

Hari Krishnan Andi, Analysis of Serverless Computing Techniques in Cloud Software Framework. Journal of ISMAC (2021), Vol.03/ No.03, Pages: 221-234, http://irojournals.com/iroismac/, DOI: https://doi.org/10.36548/jismac.2021.3.004
Shaji George , S.Sagayarajan . Securing Cloud Application Infrastructure: Understanding the Penetration Testing Challenges of IaaS, PaaS, and SaaS Environments. Partners Universal International Research Journal (PUIRJ) Volume: 02 Issue: 01 | January-March 2023 | ISSN: 2583-5602 | www.puirj.com © 2023, PUIRJ |DOI:10.5281/zenodo.7723187
Azure documentation https://azure.microsoft.com/en-us/blog/introducing-docker-in-microsoft-azure-marketplace/


