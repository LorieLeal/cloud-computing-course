# Client Recommendations

## Client A — Startup Company
**Recommended Platform:** Google Cloud Platform (GCP)

A startup with a limited budget but expecting rapid growth benefits most from GCP because of its competitive, flexible pricing and strong support for scalable, containerized applications. GCP's pay-as-you-go model and generous free-tier credits help startups minimize upfront costs while they build and test their product. As the app grows, GCP's autoscaling and Kubernetes-native tools (Google Kubernetes Engine) make it easy to scale without re-architecting the system.

**Services to use:**
1. Compute Engine – for hosting the backend of the mobile app
2. Cloud Storage – for storing user-generated content and app data
3. Google Kubernetes Engine (GKE) – for scaling the app efficiently as user base grows

## Client B — University
**Recommended Platform:** Microsoft Azure

Since the university already relies on Windows Server, Microsoft 365, and Active Directory, Azure is the most logical choice because of its native compatibility with these existing systems. Migrating to Azure allows the university to extend its current Microsoft licenses and identity systems into the cloud with minimal disruption, reducing both cost and complexity of the transition.

**Services to use:**
1. Azure Virtual Machines – to migrate existing Windows Server workloads
2. Azure Active Directory (Microsoft Entra ID) – to extend existing identity management to the cloud
3. Azure SQL Database – for managing academic and administrative databases

## Client C — AI Research Company
**Recommended Platform:** Google Cloud Platform (GCP)

GCP is the best fit for an AI/ML research company because of its high-performance computing infrastructure and Google's own leadership in AI research and tools. GCP offers specialized hardware (GPUs and TPUs) purpose-built for machine learning workloads, along with managed AI platforms that simplify model training and deployment.

**Services to use:**
1. Vertex AI – for building, training, and deploying machine learning models
2. Compute Engine (with GPU/TPU support) – for high-performance computing workloads
3. BigQuery – for large-scale data analytics to support research

## Client D — Global E-Commerce Company
**Recommended Platform:** Amazon Web Services (AWS)

A global e-commerce company needing highly available infrastructure with automatic scaling benefits most from AWS due to its widest global infrastructure footprint and proven track record hosting large-scale e-commerce platforms (including Amazon.com itself). AWS's mature auto-scaling and load balancing services ensure the platform can handle traffic spikes reliably across different regions.

**Services to use:**
1. Amazon EC2 with Auto Scaling – to automatically handle traffic spikes
2. Amazon S3 – for storing product images and static content globally
3. Amazon CloudFront – as a content delivery network (CDN) for fast global access

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | Google Cloud Platform | Cost-effective pricing and easy scalability for growing apps |
| Enterprise Organization | Amazon Web Services | Widest range of enterprise-grade services and global reach |
| Microsoft Environment | Microsoft Azure | Native integration with Windows Server, Microsoft 365, and Active Directory |
| AI / Machine Learning | Google Cloud Platform | Strong AI/ML tools and Google's research-backed infrastructure |
| Kubernetes Deployment | Google Cloud Platform | Google created Kubernetes and leads its development |
| Global Web Application | Amazon Web Services | Largest global infrastructure with reliable auto-scaling |
