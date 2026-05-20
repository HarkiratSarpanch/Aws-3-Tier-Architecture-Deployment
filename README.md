# AWS-3-Tier-Architecture-Deployment

Overview
This project demonstrates a highly available and secure 3-tier architecture on AWS using core cloud services.

The architecture consists of:
- Web Layer (Application Load Balancer)
- Application Layer (EC2 Instances)
- Database Layer (RDS)

---

## 🧠 Architecture

User → Route53 → CloudFront → ALB → EC2 → RDS

Additionally:
- AWS Lambda is used for automation (EC2 start/stop)
- CloudWatch is used for monitoring

---

## 🛠️ Services Used

- Amazon VPC (Custom networking)
- Public & Private Subnets
- Internet Gateway & Route Tables
- Application Load Balancer (ALB)
- EC2 (Ubuntu, Apache/Nginx)
- Amazon RDS (MySQL)
- Route 53 (DNS management)
- CloudFront (CDN)
- AWS Lambda (Automation)
- EventBridge (Scheduler)
- CloudWatch (Monitoring)

---

## ⚙️ Key Features

- 🔒 Secure architecture using private subnets
- ⚖️ Load balancing using ALB
- 🌐 DNS routing using Route 53
- ⚡ CDN integration using CloudFront
- 🧠 Automation using Lambda + EventBridge
- 💰 Cost optimization via EC2 start/stop scheduling
- 📊 Monitoring with CloudWatch

---

## 🔄 Workflow

1. User accesses application via domain (Route 53)
2. CloudFront delivers cached/static content
3. ALB distributes traffic to EC2 instances
4. EC2 processes requests and interacts with RDS
5. Lambda automates EC2 operations based on schedule

---

## 💡 Learning Outcomes

- Designed scalable and secure AWS architecture
- Implemented Infrastructure best practices
- Integrated multiple AWS services
- Learned cost optimization strategies
- Gained hands-on experience with real-world cloud deployment

---

## 📂 Future Improvements

- Add Auto Scaling Group
- Implement CI/CD pipeline
- Convert to Terraform (IaC)
- Add HTTPS using ACM

---

## 👨‍💻 Author

Harkirat Singh  
Aspiring Cloud & DevOps Engineer
