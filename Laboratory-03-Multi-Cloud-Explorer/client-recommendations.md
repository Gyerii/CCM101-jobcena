# Cloud Platform Recommendation Challenge

## Client A – Startup Company

**Recommended Platform: Amazon Web Services (AWS)**

AWS is a suitable choice for the startup because it provides flexible and scalable cloud services that can support a mobile application as the number of users grows. The company can begin with serverless and managed services to reduce the need to maintain physical servers and infrastructure. AWS also provides several options for scaling applications when demand increases. This makes AWS appropriate for a startup that currently has a limited budget but expects rapid growth.

**Recommended Services:**

* AWS Lambda – for running application code without managing servers
* Amazon DynamoDB – for a scalable application database
* Amazon S3 – for storing application files, images, and other objects

---

## Client B – University

**Recommended Platform: Microsoft Azure**

Microsoft Azure is the most appropriate platform because the university already uses Windows Server, Microsoft 365, and Active Directory. Azure integrates well with Microsoft's enterprise ecosystem, making it easier to extend existing systems into the cloud. Microsoft Entra ID can support identity and access management, while Azure Virtual Machines can host Windows-based workloads. This can help the university create a hybrid environment while continuing to use familiar Microsoft technologies.

**Recommended Services:**

* Azure Virtual Machines – for hosting Windows and Linux servers
* Microsoft Entra ID – for identity and access management
* Azure Blob Storage – for cloud-based file and object storage

---

## Client C – AI Research Company

**Recommended Platform: Google Cloud Platform (GCP)**

Google Cloud Platform is a strong choice for a company focused on artificial intelligence and machine learning. Google Cloud provides services for developing AI applications, running large computing workloads, and deploying containerized systems. Google Kubernetes Engine can also support scalable AI workloads, including workloads that require GPU acceleration. These capabilities make Google Cloud suitable for research environments that require advanced computing resources.

**Recommended Services:**

* Vertex AI – for developing and deploying machine learning and AI solutions
* Compute Engine – for virtual machines and high-performance computing workloads
* Google Kubernetes Engine (GKE) – for deploying and managing containerized workloads

---

## Client D – Global E-Commerce Company

**Recommended Platform: Amazon Web Services (AWS)**

AWS is a suitable platform for a global e-commerce company because it provides scalable computing and infrastructure services that can respond to changing levels of customer traffic. Amazon EC2 can host application servers, while EC2 Auto Scaling can automatically adjust the number of instances based on application demand. Elastic Load Balancing can distribute incoming traffic across available application resources. Together, these services can help the company build a highly available and scalable global web application.

**Recommended Services:**

* Amazon EC2 – for hosting e-commerce application servers
* Amazon EC2 Auto Scaling – for automatically adjusting computing capacity
* Elastic Load Balancing – for distributing incoming application traffic
* Amazon S3 – for storing product images and static files

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | AWS provides scalable services and flexible options that allow startups to begin small and expand as demand increases. |
| Enterprise Organization | AWS | AWS offers a broad range of enterprise cloud services for computing, storage, databases, networking, security, and global deployments. |
| Microsoft Environment | Microsoft Azure | Azure integrates well with Windows Server, Microsoft 365, Microsoft Entra ID, and other Microsoft technologies. |
| AI / Machine Learning | Google Cloud Platform | Google Cloud provides strong AI and machine learning services such as Vertex AI and scalable computing resources. |
| Kubernetes Deployment | Google Cloud Platform | Google Kubernetes Engine provides a managed Kubernetes platform for deploying and scaling containerized applications. |
| Global Web Application | AWS | AWS provides global infrastructure, load balancing, and automatic scaling services for highly available web applications. |
