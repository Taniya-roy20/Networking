# NETWORKING IN CLOUD--

![image](https://github.com/user-attachments/assets/11bc5337-8e20-4ba8-bdbc-95a4b0732b95)
Networking in the cloud is a critical aspect of cloud computing that enables communication between various resources, services, and applications hosted in cloud environments. Here are some key concepts and components involved in cloud networking:
<br>
<br>
**1)Virtual Private Cloud (VPC)**
<br>
A VPC allows you to create a logically isolated network within a cloud provider's infrastructure. You can define your own IP address range, subnets, route tables, and network gateways.
<br>
<br>
**2)Subnets**
<br>
Subnets are segments of a VPC that help organize and secure your cloud resources. They can be public (accessible from the internet) or private (accessible only from within the VPC).
<br>
<br>
**3)Load Balancer**
<br>
Load balancers distribute incoming traffic across multiple servers or resources, ensuring high availability and reliability of applications. They can be application-specific (Layer 7) or network-based (Layer 4).
<br>
<br>
**4)VPN and Direct Connect**
<br>
Virtual Private Networks (VPNs) create secure connections between your on-premises infrastructure and cloud resources. Direct Connect offers a dedicated network connection to the cloud provider, enhancing security and performance.
<br>
<br>
**5)Firewalls and Security Groups**
<br>
Cloud providers offer built-in firewalls and security groups to control inbound and outbound traffic. These tools help you define rules that specify which traffic is allowed or denied.
<br>
<br>
**6)Content Delivery Networks (CDN)**
<br>
CDNs cache content closer to users around the globe, improving access speed and performance for web applications.
<br>
<br>
**7)DNS Services**
<br>
Cloud-based DNS services manage domain names and route traffic efficiently to different resources, improving reliability and speed.
<br>
<br>
**8)Network Monitoring and Management**
<br>
Tools for monitoring network performance, tracking usage, and troubleshooting issues are essential for maintaining cloud network health
<br>
<br>
**9)TTL**
<br>
<br>
TTL, or Time to Live, in the context of cloud computing typically refers to the duration that data can exist in a cache or be considered valid before being refreshed or discarded. Here are a few contexts in which TTL is relevant:
<br>
<br>
---DNS Records: TTL determines how long a DNS resolver can cache a DNS record before it must query the authoritative server again. Shorter TTL values can lead to more frequent updates but increase the load on DNS servers.
<br>
<br>
---Caching: In cloud services (like AWS, Azure, or Google Cloud), TTL can define how long cached objects (such as those in a CDN or a caching layer) are considered fresh. This helps optimize performance by reducing the need to fetch data from the source frequently.
<br>
<br>
---Session Management: TTL can also be applied to session tokens or user sessions in web applications, dictating how long a session remains active before timing out for security reasons.
<br>
<br>
---Data Expiry: In databases or storage solutions, TTL can specify how long certain data should be retained before it is automatically deleted.
<br>
<br>
10)CNI
![image](https://github.com/user-attachments/assets/b4953022-2068-4773-8b7e-fe6d1135e0bd)
<br>
<br>
