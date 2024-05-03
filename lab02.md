# Author: Rebecca Childs
## Reading Notes: 401
## Lab 02

### Explain the levels of abstraction in AWS to someone without a technical background.
AWS offers tools at different levels of complexity, like a toolbox with pre-built kits:
Low-Level (Nuts & Bolts): Control everything (EC2 instances, S3 buckets) but requires most effort.
Mid-Level (Prefab Kits): Faster to use pre-built components (CloudFormation, Lambda functions) with some flexibility.
High-Level (Appliances): Easiest to use pre-made services (DynamoDB, SQS) but least control.
Higher levels let you focus on your application's purpose, not the underlying infrastructure.

### What are the control plane and data plane responsible for in container abstraction?
In container management, control plane and data plane work together like an orchestra:
Control Plane (Conductor): Makes decisions - scheduling, networking, security, scaling, and health checks.
Data Plane (Musicians): Executes tasks - running containers, forwarding network traffic, and managing storage based on control plane instructions.
This separation keeps things organized and efficient for complex containerized applications.

### Where does AWS Lambda fall in the layers of abstraction and what makes it so special?
AWS Lambda is a mid-level abstraction tool, like a pre-built kit in AWS. It's special because it's:
Serverless: You write code, Lambda handles servers (saving time and effort).
Event-Driven: Code runs in response to events, making it flexible.
Pay-Per-Use: You only pay for what you use, ideal for variable workloads.
Lambda lets you focus on core logic, not server headaches.

## Things I want to learn more about:
N/A