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
        - Replatform: lift, tinker, and shift
        - Refactor: modernize
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
    - 

- Acronyms
    - MVP - Minimum Viable Product - See progress from the start, instead at the end of a long process.
    - PoC - Proof-of-Concept
    - IAM - Identity Access Management
    - AWS - Amazon Web Services
    - APN - Amazon Partner Network
    - ROI - Return on Investment
    - SaaS - Software as a Service, i.e. Salesforce
    - TCO - Total Cost of Ownership
    - PaaS - Platform as a Service
    
- Terms
    - AWS Landing Zone
        - A Secure and well architected multi-account AWS environment.
    - Minimum Viable Product 
        - See progress from the start, instead at the end of a long process. A functional product or solution
          with just enough features to satisfy a customer's requirements at initial adoption, and leaves room for 
          feedback as you get more complex. PoC -> MVP (Production-Level)
    - Data Lakes - A large storage repository that holds data in their original format prior to being parsed 
      and analyzed. Examples are: Hadoop which is designed to hold huge amounts of data. 