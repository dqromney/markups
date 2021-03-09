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
    at the end of the course.  
    
#### Course Work
##### AWS Technical Professional:
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
          
                  
- Acronyms
    - EC2 - Elastic Cloud Compute 2
    - MVP - Minimum Viable Product - See progress from the start, instead at the end of a long process.
    - PoC - Proof-of-Concept
    - IAM - Identity Access Management
    - AWS - Amazon Web Services
    - APN - Amazon Partner Network.  It is a resource providing APN Partners with the tools and content they 
      need to grow their businesses on AWS. May include independent software vendors (ISVs). Provide hardware, 
      connectivity services, and software solutions that are hosted on or integrated with the AWS Cloud.
    - ROI - Return on Investment
    - SaaS - Software as a Service, i.e. Salesforce
    - TCO - Total Cost of Ownership
    - PaaS - Platform as a Service
    - ISV - Independent Software Vendors (Saas, PaaS, Developer Tools, Management, Security)
    - MRR - Marginal Rate of Return or Monthly Recurring Revenue
    - POA - Partner Opportunity Acceleration 
    - PDR - Partner Development Representative (First point of contact, and helps with on-boarding)
    - PDM - Partner Development Manager (Manages the relationship between you and AWS)
    - MDF - Market Development Funding (Support marketing efforts)
    - NACL - Network Access Control Lists (on the Subnet level)
    - VPC - A logically isolated virtual network in the AWS cloud. You define a VPC’s IP address space 
      from ranges you select.
    
- Terms
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