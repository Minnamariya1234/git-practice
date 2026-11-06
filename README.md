\# AWS Web Application with Application Load Balancer and Auto Scaling



\## Project Overview



This project demonstrates deploying a highly available and scalable web application on Amazon Web Services (AWS).



The application uses an Application Load Balancer to distribute incoming traffic across multiple EC2 instances. An Auto Scaling Group automatically manages EC2 instances based on application demand.



\## AWS Services Used



\- Amazon EC2

\- Application Load Balancer (ALB)

\- Auto Scaling Group (ASG)

\- Amazon VPC

\- Public and Private Subnets

\- Security Groups

\- AWS Target Groups

\- IAM



\## Architecture



User / Internet

&#x20;      |

&#x20;      v

Application Load Balancer

&#x20;      |

&#x20;      v

Target Group

&#x20;      |

&#x20;      v

Auto Scaling Group

&#x20;      |

&#x20;      |---- EC2 Instance 1

&#x20;      |

&#x20;      |---- EC2 Instance 2

&#x20;      |

&#x20;      |---- EC2 Instance 3



\## Project Objectives



1\. Create a custom VPC.

2\. Configure public and private subnets.

3\. Launch EC2 instances.

4\. Install and configure a web server.

5\. Create an Application Load Balancer.

6\. Configure a Target Group.

7\. Create an Auto Scaling Group.

8\. Attach the Auto Scaling Group to the Target Group.

9\. Test application availability.

10\. Test automatic scaling.



\## Implementation Steps



\### 1. VPC Configuration

\- Create a VPC.

\- Configure public and private subnets.

\- Configure Internet Gateway and route tables.



\### 2. EC2 Configuration

\- Launch EC2 instances.

\- Install Apache or Nginx.

\- Deploy the web application.



\### 3. Application Load Balancer

\- Create an Application Load Balancer.

\- Configure listeners.

\- Create and attach a Target Group.

\- Verify target health checks.



\### 4. Auto Scaling Group

\- Create a Launch Template.

\- Configure an Auto Scaling Group.

\- Set minimum, desired and maximum capacity.

\- Attach the Target Group.



\### 5. Testing

\- Access the application using the ALB DNS name.

\- Verify traffic distribution.

\- Test instance health checks.

\- Test automatic scaling.



\## Expected Outcome



\- Application accessible through ALB DNS.

\- Incoming traffic distributed across EC2 instances.

\- Automatic replacement of unhealthy instances.

\- Automatic scaling based on configured policies.

\- Improved availability and scalability.



\## Technologies



\- AWS Cloud

\- Linux

\- Apache / Nginx

\- Git

\- GitHub



\## Author



Minna Mariya



\## Project Type



AWS Cloud Computing Hands-on Project














\### Working Web Application

!\[Web Application](screenshots/webapp.png)

