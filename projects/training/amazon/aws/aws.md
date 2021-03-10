# Amazon Web Services
{markdown: ./breadcrumb.md}

Creation Date: 2021/03/08

## Description
The top of the Amazon Web Services training and development skills. This section is for personal and professional information. 
### Getting started
- Create an Amazon Web Services or AWS account using your STG email, i.e. someone@stgconsulting.com
    - The best place to started is of course: [Getting Started](https://aws.amazon.com/getting-started), for now, 
      just use the "Root user sign in".  Just stick with the [free](https://aws.amazon.com/free) for now.
    - Later on this account will be used to create Proof-of-Concepts or PoFs for clients and will be paid for by the 
      client or STG and given access to, i.e. EC2, S3, etc...
- Create an Amazon Partner Network account, using your STG email.
    - Answer all the questions as if you are a Developer, and understand that Share Ralph is the STG lead. The 
      information you enter will be added to STG APN statistics. You will be asked for a password prior to creating
      your account.
    - Familiarize yourself with the information provided regarding the APN, especially note the training envolved 
    to be accredited and certified. You want to find [APN Partner Training](https://www.aws.training/PartnerTraining) to 
      explore the Training options.
    - Enroll in Digital Training by selecting the "Find Training" button.   
    - The course I am currently taking is the "AWS Technical Profession", it has about 6-7 modules with a test 
    at the end of the course.  Test takes 30-45 minutes and consists of 30 multiple-choice questions. 
      You need to get 80% correct to pass, and you can take it multiple times.
    - Using the AWS [Partner Learning Path Tool](https://pages.awscloud.com/AWS-Partner-Learning-Path-Tool.html) I 
      planned my learning path.  I my role is "Developer", and my Area of Focus is "Developer at an AWS Partner".
      
#### Course Work
Using the AWS [Partner Learning Path Tool](https://pages.awscloud.com/AWS-Partner-Learning-Path-Tool.html) I planned
my learning path.  I my role is "Developer", and my Area of Focus is "Developer at an AWS Partner". 

##### AWS Technical Professional: (Completed 2021-03-09 with 83.33% ~ 25 points)
This test took me about 30-45 minutes to complete.  I was taking notes during the test. 

###### Notes
- Module 3: From Services to Solutions
    - Migration Strategies - The Six R's
        - Rehost: lift and shift
            - Strategy consists of a simple transfer of application resources from an on-premises data center 
              to the AWS cloud.
        - Replatform: lift, tinker, and shift
        - Refactor: Modernize. Consists of re-architecting an application, typically using cloud native features. 
        - Retire: Shutting off non-useful applications 
        - Retain/Revisit: Keeping certain applications on-premises
        - Repurchase: Moving workflows to Software as a Service (SaaS), like Salesforce.
    - Cloud Architecture Best Practices
        - Design for failure and nothing fails
        - Build security in every layer
        - Leverage different storage options
        - Implement elasticity
        - Think parallel
        - Loose coupling sets you free
        - Don't fear constraints
    - The Well-Architected Framework - The Five Pillars (OSRPC)
        - Operational Excellence
        - Security
        - Reliability
        - Performance Efficiency
        - Cost Optimization (Where is the money being spent?)
    - Cost Optimization (Pay for what ou *need*) (see AWS Cloud Economics Training)
        - Right-sizing instances
        - Increase elasticity
        - Choosing the right pricing model
        - Optimize storage
    
- Module 4: Presenting AWS Solutions to Customers
    - Preparing for discovery
        - Research customer's business
        - Determine market segment (HIPA, etc)
        - Identify industry trends
        - Identify the customer's competitors
        - Research recent news
        - Research customer relationship with AWS
    - Discovery practices
        - Encourage detailed conversation
            - Ask targeted questions
            - Ask open-ended questions
        - Five Whys
            - Dive deeper
            - Uncover the real desired outcomes
        - White-boarding (discovery)
            - Keep track of the conversation
            - Illustrate workflows and ideation
    - Preparing an AWS solution
        - Consult with peers
        - Illustrate the solution (white-board)
        - Include variation (white-board)
        - Create a presentation (white-board)
        - After presentation...
        - Revise the solution
        - Gain buy-in from the customer
        - Propose a Proof of Concept (POC), using your own AWS (STG) account
    - Objection handling technique
        - Address objects before moving forward
        - Objections are not always factual
            - Identifier with the customer's point of view
            - Identifier the core concern
            - Take steps toward resolution
        - Objection handling best practices
            - Data-driven approach
            - Use case studies
            - Dive deep
            - Have backbone
            - Keep the momentum going
    - Keys to consistent results
        - Prepare (1 hour of content equals 3 hours of preparation, related Acronyms)
        - Anticipate (Do your research! Question the adaptive nature)
        - Differentiate (Set yourself apart and AWS)
        - Stay on message (don't be thrown of course)
    - What NOT to do
        - Use words like definitely, never, or guaranteed
        - Use acronyms or technical jargon
        - Focus on technology
        - Focus on the short/mid-term
        - Read the slides    
    - Delivering a Proof of Concept (PoC)
        - Proposal -> Proof-of-Concept -> Migration
        - Practical example of solution
        - Evaluation mechanism
        - Education tool
    - Building a PoC
        - Customer agrees to PoC
        - Take the feedback from the solution proposal
        - Develop the PoC
        - Collect the following information:
            - Networking and security
            - Application code
            - Databases
            - Data
    - AWS Quick Starts
        - [Quick Start](https://aws.amazon.com/quickstart/)
        - [Answers](https://aws.amazon.com/answers)
        - Rapidly deploy architectures based upon best practices
        - Launch, configure, and run AWS services required to deploy a specific workload on AWS
        - Reduce manual procedures into a few steps
        - Check back frequently for updates. 

- Module 5: Looking Ahead
    - Solution implementation
        - The migration process
            - Assessment
            - Readiness and Planning
            - Migration
            - Operations and Optimizations
    - Migration strategies
        - See nice a technology map from Determine Migration Path to Validation, Transition, and then Production. 
    - Best practices
        - Involve AWS account team (Solutions Architect or Technical Account Manager)
        - Customer-specific regulatory requirements
        - AWS Support level (if customer opts for this support)
    - AWS Well-Architected Tool
        - Use this tool in the Console for work-space you are considering.
    - Modernization to drive growth
        - Retired expensive legacy solutions
        - Reduce TCO, improve cost optimization
        - Gain agility through automation
        - Free up resources to drive innovation
    - Modernization of architectures (Benefits)
        - Serverless
          - No provisioning, maintain and administering servers
          - AWS handles fault tolerance and availability
          - Focus on product innovation
        - Containers
          - Package code, configuration , and dependencies into a single object
          - Share an operating system
          - Run as resource-isolated processes
          - AWS offers resources and orchestration services
      - Data lakes and analytics
        - Data in different silos can be difficult to access and analyze
        - Store data in a "data lake"
        - Easy to read data and obtain insights
        - Data lakes and analytics solutions on AWS
            - Interactive Analytics (Amazon Athena)
            - Big Data Processing (Amazon EMR, Spark, Hadoop)
            - Data Warehousing (Amazon Redshift)
            - Real-Time Analytics (Amazon Kinesis)
            - Operational Analytics (Amazon Elasticsearch Service)
            - Dashboards and Visualizations (Amazon QuickSight)

- Module 6: AWS Partner Network (APN) Resources
    - APN consulting partner tier requirements
        - Registered
            Submit an APN Partner Central Application
        - Select
            - APN Program Fee: $2500/year
            - Knowledge Requirements
                - 4 Accredited Individuals (2 technical, 2 business)
                - 2 AWS Foundational certified individuals
                - 2 AWS Technical certified individuals
            - Experience Requirements
                - 3 Launched Opportunities (Total MMR > -$1,500)
            - Customer Success requirements
                - 1 Publicly Referenceable Customers
                - 5 Customer Satisfaction (CSAT) Response
        - Advanced
            - APN Program Fee: $2500/year
            - Knowledge Requirements
                - 8 Accredited Individuals (4 technical, 4 business)
                - 4 AWS Foundational certified individuals
                - 6 AWS Technical certified individuals (3 Professional / Specialty)
            - Experience Requirements
                - 20 Launched Opportunities (Total MMR > -$10,000)
                - Partner Business Plan
            - Customer Success requirements
                - 2 Publicly Referenceable Customers
                - 20 Customer Satisfaction (CSAT) Response
        Premier
          - APN Program Fee: $2500/year
          - Knowledge Requirements
              - 20 Accredited Individuals (10 technical, 10 business)
              - 10 AWS Foundational certified individuals
              - 25 AWS Technical certified individuals (10 Professional / Specialty)
          - Experience Requirements
              - 50 Launched Opportunities (Total MMR > -$50,000)
              - Partner Business Plan
              - Executive Business Review
              - 3 Technical Program Validations
              - Greater than 6 months Sustained at APN Tier Criteria
          - Customer Success requirements
              - 6 Publicly Referenceable Customers
              - 30 Customer Satisfaction (CSAT) Response
    - APN Partner training resources
        - AWS Technical Professional (my path)
            - Gain Fundamental technical knowledge of AWS Cloud computing
        - AWS Business Professional
            - Gain a basic understanding of AWS services and core business balue propositions.
        - AWS Professional Services
            - Develop and extend professional services competencies

##### AWS Cloud Economics Accreditation: (Completed yyyy-mm-dd with 00.00% ~ n points)
Please complete all the of the modules below, and the course assessment.  A score of 80% or higher on the assessment 
is required for course completion.

###### Notes
- Module 1: Introduction to *Business Value* (Primary Focus)
    - Cloud Value Framework - Four Pillars
        - Cost savings (TCO) (Typical Focus) (over-all 51% lower cost)
            - Cost savings is typically the most common focus for customers because it involves concrete numbers. 
              Once you acquire current cost numbers from a customer, which can sometimes be difficult to , you 
              apply logic to them. Then, you show your customer how much they are paying currently versus what 
              they would pay using AWS.
        - Staff productivity (Most compelling cloud benefits)
            - Refers to the efficiency gained from reducing or eliminating tasks no longer needed with the cloud. 
              By relieving staff of tasks, they will have more time to focus on new projects.  62% greater efficiency of
              IT infrastructure staff.   
        - Operational resilience (Most compelling cloud benefits)
          - The benefit gained from improved availability and security. The means more uptime, less downtime, and 
            decreased risk. Reduced unplanned downtime by 32% by moving existing workloads from on-premises to the cloud
            using AWS.
        - Business agility (Most compelling cloud benefits)
            - Means being able to response faster and experiment more. Higher user productivity and revenue 
              represents 47% of the total average annual benefits per organization for AWS customers.
- Module 2: Cost Savings Basics
    - Why cost savings matters
    - Lowering costs with AWS
    - Customer migration challenges
- Module 3: Staff Productivity
    - Quantifying the impact AWS has on staff productivity versus traditional IT
    - Customer examples
- Module 4: Operational Resilience
    - Four key areas of operational resilience
    - Benefits of improved operational resilience
    - Causes and impacts of downtime
    - How AWS mitigates operational failures
    - Customer examples
- Module 5: Business Agility
    - Key performance indicators to measure business agility
    - How increased business agility allows for innovation and decreased risks and costs
    - Customer examples
- Module 6: *Cloud Financial Management* (Primary Focus)
    - Four key areas of cloud financial management
    - Measurement and accountability
    - Cost optimization
    - Planning and forecasting
    - Cloud financial operations
- Module 7: Introduction to Migration Portfolio Assessment (MPA)
    - Who should use the MPA tool
    - When and how to use the MPA tool
    - How to access the MPA tool
- Module 8: Cost Savings with MPA
    - How to add and manipulate data with the MPA tool
    - Cost savings analyses with the MPA tool

### Amazon Acronyms
| Acronym | Description  |
|:-:|:-|
| EC2 | Elastic Cloud Compute 2 |
| MVP | Minimum Viable Product - See progress from the start, instead at the end of a long process. |
| PoC | Proof-of-Concept |
| IAM | Identity Access Management |
| AWS | Amazon Web Services |
| APN | Amazon Partner Network.  It is a resource providing APN Partners with the tools and content they need to grow their businesses on AWS. May include independent software vendors (ISVs). Provide hardware, connectivity services, and software solutions that are hosted on or integrated with the AWS Cloud. |
| ROI | Return on Investment |
| SaaS | Software as a Service, i.e. Salesforce |
| TCO | Total Cost of Ownership |
| PaaS | Platform as a Service |
| ISV | Independent Software Vendors (Saas, PaaS, Developer Tools, Management, Security) |
| MRR | Marginal Rate of Return or Monthly Recurring Revenue |
| POA | Partner Opportunity Acceleration |
| PDR | Partner Development Representative (First point of contact, and helps with on-boarding) |
| PDM | Partner Development Manager (Manages the relationship between you and AWS) |
| MDF | Market Development Funding (Support marketing efforts) |
| NACL | Network Access Control Lists (on the Subnet level) |
| VPC | A logically isolated virtual network in the AWS cloud. You define a VPC’s IP address space from ranges you select. |
| MSP | Managed Service Providers |
| EBS | Elastic Block Store |
| MPA | Migration Portfolio Assessment |

### Amazon Terms 
- AWS Landing Zone
    - A Secure and well architected multi-account AWS environment.
- Minimum Viable Product 
    - See progress from the start, instead at the end of a long process. A functional product or solution
      with just enough features to satisfy a customer's requirements at initial adoption, and leaves room for 
      feedback as you get more complex. PoC -> MVP (Production-Level)
- Data Lakes - A large storage repository that holds data in their original format prior to being parsed 
  and analyzed. Examples are: Hadoop which is designed to hold huge amounts of data.
- AWS Regions
    - Separate, isolated geographic areas that contain available zones. 
- AWS Availability Regions 
    - A Region designed to be isolated from the other AWS Regions. This design achieves the greatest 
      possible fault tolerance and stability. You can think of AWS regions as fairly independent collections 
      of data centers within a specific geographic area. An AWS region, thereby, can be thought of as a 
      collection of availability zones.
- AWS Availability Zones
    - A good way to think about availability zones is to consider an AZ as equivalent to a data center. 
      Isolated locations within a geographical region, containing one or more data centers.
- AWS Well-Architected Framework
    - It is a resource to help you design solutions following AWS best practices. 
- AWS edge locations
    - Locations designed to deliver content to end users.
- EC2 "Memory Optimized" instance type
    - Designed to deliver fast performance for workloads that process large data sets in memory.
- EC2 "General Purpose" instance type
    - Provides a balance of compute, memory and networking resources, and can be used for a variety of 
      diverse workloads. 
- EC2 "Compute Optimized" instance type
  - Ideal for compute bound applications that benefit from high performance processors. 
- Rehost: lift and shift
    - Consists of a simple transfer of application resources from an on-premises data center to the AWS cloud.
- Shard Responsibility Model (Principles)
    - AWS is responsible for securing the physical network infrastructure.
    - Customers are responsible for securing their applications and data.
- APN Consulting Partners
    - APN Consulting Partners help customers design, architect, build, migrate, and manage their workloads 
      and applications on AWS.
    - APN Consulting Partners include Managed Service Providers (MSP).
- Amazon S3 Glacier 
    - A low-cost object storage server designed for data archiving. 
- Containers
    - Containers package applications's code, configurations, and dependencies into a single object. 
- Amazon Simple Storage Service or S3
    - Amazon S3 is an object storage service that can be used to store and retrieve any amount of data, 
      at any time, from anywhere on the web.
- Serverless Architectures
    - Serverless architectures run applications without provisioning, maintaining, and administering servers. 
- Amazon Elastic Block Store
    - Amazon EBS provides persistent block level storage volumes for use with Amazon EC2 instances. 
    
    
    
    