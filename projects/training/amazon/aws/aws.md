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
    - It is more than just up front cost savings.
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
      - A Cost savings analysis calculates the total cost of ownership (aquisition and operating case) for 
        running and end-to-end traditional IT environment on-premises vs. deploying to AWS. Or when your 
        customer wants to under the costs involved with running applications or workloads over owned IT 
        hardware verses AWS.
    - Lowering costs with AWS
        - Helps your customer lower their costs through the use of a *consumption-based model*, *AWS pricing 
          models*, and *frequent price reductions*.
        - Consumption-based model  (1st Way)
          - A Customer pays only for what they use. 
        - AWS Pricing Models (2nd Way)
          - On-Demand
              - This is, typically, where customers start, in an effort to gauge their needs, and then switch to Reserved Instances, or RIs, once they know their demand baseline.
          - Reserved
              - Can reduce costs by up to 75 percent versions On-Demand.
          - Spot
              - AWS excess capacity sold for a deep discount is called a Spot Instance.
          - Dedicated
              - Used for customers with regulatory or software licensing constraints who need their own hosts.
        - Frequent Price Reductions (3rd Way)
            - Economies of scale allows AWS to continually lower costs. 
            - Periodic price reductions, customers automatically receive the lower prices. 
    - Customer migration challenges
        - Over-provision vs. under-provision - Helps your customers avoid inefficiencies and financial 
          losses by enabling your customers to launch the infrastructure they need when they need it.
        - Migration-related costs
          - Sunk infrastructure costs
            - When customers want to retire hardware but then have not fully depreciated it and they have 
              not had an opportunity to recover the non-deprecated value of their investments by selling it.
            - Cost (and effort) of migration and decommissioning
                - Occurs when a customer moves their existing footprint to the cloud and shuts down their 
                  data center, which requires time and effort.
            - Migration costs formula
                - ROI = Cost savings / (Sunk costs + Migration costs)
        - Shifting to an operational expenditure (opex) model
        - Lack of cloud readiness
        - Entrenched IT organization
    - AWS Flywheel: 
      - Lower infrastructure costs => Reduced Prices => More customers => More AWS usage => 
        More infrastructure => Economies of scale => (Lower infrastructure costs) ...
    - Sunk costs
        - Ask the accounting department for non-depreciated assets for the hardware you are evaluating. 
          You should there always evaluate the sunk costs for two factors:
            - Depreciation
              - Was the asset's depreciation considered?
            - Recovery value
                - Can any value be recovered by selling the asset?
    - Migration costs
        - Calculating migration costs typically requires an in-depth analysis, and these costs can range 
          between hundreds of dollars to tens of thousands of dollars per server, in extreme cases. 
        - With the help of AWS training and tools like the Migration Portfolio Assessment, or MPA, tool, 
          you can gain additional knowledge to help you conduct an effective cost analysis.
        - Knowing the cost savings per year, the sunk cost, and the ROI, you calculate the break-even 
          migration cost and divide by the number of servers.  If the value of the break even cost per server is low,
          evaluate other components. You can check whether the cost saving can be improved, sunk costs can be
          decreased, or ROI can be lowered. If the break even value per server is high, the customer is on the safer
          side of the equation. See Migration Cost Formula above.
    - Cloud Readiness
        - Human Factor (Biggest challenge)
            - It is crucial to commence them preparation as soon as the decision to transition to AWS is made. 
        - Applications
            - The customer's legacy applications or workloads are not ready for (or would not immediately 
              benefit from) moving to the cloud.
        - App readiness questions
            - What are you application dependencies?
            - What apps are communicating with other apps?
            - What apps can be translated easily?
        - Stakeholders
            - Cost savings engagement may require multiple discussions with different messages fro different audiences:
                - Application developer (DevOps)
                - IT Support team
                - Procurement team
                - CFO/CIO/Investors
        - Perceived IT Costs
            - Server costs
                - Hardware - server, (+maintenance)
                - Software - OS, virtualization licenses (+maintenance)
            - Storage costs
                - Hardware - storage disks
            - Network costs
                - Network hardware - LAN switches, load balancer bandwidth costs
            - IT Labor costs
                - Server admin, virtualization admin
        - Actual cost
            - Server costs
                - Hardware - server, rack chassis pdus, tor switches (+maintenance)
                - Software - OS, virtualization licenses (+maintenance)
                - Facilities cost
                    - Space
                    - Power
                    - Cooling
            - Storage costs
                - Hardware - storage disks, san/fc switches
                - Software - backup
                - Facilities cost
                  - Space
                  - Power
                  - Cooling
            - Network costs
                - Network hardware - LAN switches, load balancer, bandwidth costs
                - Software - network monitoring  
                - Facilities cost
                  - Space
                  - Power
                  - Cooling
            - IT Labor costs
                - Server admin, virtualization admin, storage admin, network admin, support team
            - Extras
                - Project planning, advisors, legal, contractors, managed services, training, cost of capital.
            - Impact on Operational resilience and business agility
                - Cost of delays risk premium
                - Competitive abilities
                - Governance
                - Others
    - What works
        - 3-5 year depreciation
        - 3 year RI (using Standard Reserve Pricing)
        - Use volume RI discounts
        - Use realistic ratios
        - Use realistic ratios (VM density, servers, racks)
        - Explore on-premises CPU and mem usage
        - Apply cost benefits of automation (automatic scaling, APIs, AWS Trusted Advisor, Cost Optimization)
    - What to avoid
        - Forget power/cooling (compute, storage, network)
        - Forget administration costs (procurement, design, build, operations, network, security)
        - Forget rent/real estate
        - Forget software and hardware maintenance costs
        - Forget the cost of redundancy
    - Delivering cost savings
        - Kickoff
            - Cost savings overview
            - Timeline, scope, and roles
        - Data collection or gathering (2-4 weeks) 
        - Initial assessment (~1 week) Q&A
            - Review data
            - Initial assessment
            - ID open questions, assumptions
        - Full assessment
            - Incorporate new data
            - Repeat as needed
        - Iterate and finalize (~1 week)
          - As often as needed. 
        - Customer report out
    - Tools to assist a customer during the process
        - AWS TCO Calculator
            - https://awstcocalculator.com
        - AWS Economics Center
            - http://aws.amazon.com/economics/
        - Case Studies and Research
            - http://aws.amazon.com/solutions/case-studies
    - TSO Logic (Aquired December 2018 by Amazon) Software
        - On-premises analysis and cloud planning
    - Migration Portfolio Assessment Tool
        - Guided data ingestion
        - Right-sized EC2 instance and strage recommendations
        - Run rate cost comparison
        - Over 100 variables with prepopulated industry defaults
        - Migration pattern analysis and recommendations (7Rs)
        - Migration estimating for resources, timelines, and costs
        - Customizable dashboards to visualize data
        - Secure access to APN Advanced and Premier Tiers
- Module 3: Staff Productivity
    - Refers to the efficiency gained from reducing or eliminating tasks no longer needed with cloud services.
    - Staff productivity: Typical functions (each as 10-15 primary activities)
        - Server, Network, Storage
          - Involves managing hardware infrastructure
        - Application
            - Covered by roles such as database administrators, AppDev, QA, and support functions.
        - Facilities
            - Primarily cover facilities management and includes roles for customers who have an on-premises 
              data center.
        - Security
            - Ensure that the company infrastructure meets compliance, regulatory, and corporate standards.
    - Quantifying the impact AWS has on staff productivity versus traditional IT
    - Customer examples
- Module 4: Operational Resilience 
  Is the benefit gained from improved availability and security. This means more uptime, less downtime, and 
  decreased risk.
    - Four key areas of operational resilience
      - Operations
        - Causes for failure
          - Human errors, such as lack of clearly defined procedures or use privilege
          - Configuration errors in hardware or operating system settings and startup scripts
          - Procedure errors, like restoring the wrong back or forgetting to restart a device, and
          - Commonplace accidents in the data center, like tripping over power cords, dropping equipment, 
            or disconnecting devices. 
      - Security
        - Causes for breaches
            - Malware, such as works, viruses, and Trojan horses
            - Network Attacks, like open ports, SYN floods, and fragmented packets
            - Unpatched applications or operating systems
            - Security issues, such as password disclosures, social engineering, credentials not stored securely, 
              non-strict password policies, and poor privilege and access management, and
            - Poor or limited authentication
        - How AWS helps
            - AWS has a shared security model, which means that AWS shares security responsibilities with 
              customers. In this model, AWS is responsible for the security of everything from the hypervisor 
              level to the operating system.
            - Reduces security risks in numerous ways
                - Denial of service attacks
                - IAM to reduce or eliminate the existence of Rogue servers
                - 30 plus compliance certifications for environments
        - Software
          - Causes for failure
            - Resource exhaustion, like runaway processes, memory leaks, and file growth
            - Computational or logic errors, such as faulty references, de-allocated memory, corrupt pointers, 
              sync errors, and race conditions.
            - Inadequate monitoring, such as the inability to identy issues, and 
            - Failed upgrades, such as intercompatibility and integrations
          - How AWS helps
            - Offices blue and green deployments that allow for quick rollbacks
            - Automates continuous integration and continuous delivery workflow
            - Runs smaller code deployments to reduce unit, integration, and system bugs
            - Provides current and secure resources with OS patching, and 
            - Creates and manages a collection of related AWS resources
        - Infrastructure
            - Causes for failure
                - Hardware failure of servers, storage, or networks
                - Natural disaster, like hurricanes, floods, and earthquakes
                - Power outages, including failed power supplies and batteries
                - Volumetric attacks, such as DDoS's; Domain Name System, or DNS, amplification; or UDP/ICMP floods.  
            - How AWS helps
                - AWS continues to expand our world-class infrastructure and leads the industry in improving data 
                  centers on a massive scale.
                - Our customers can run applications and failover across multiple Availability Zones and Regions.
                - AWS systems are designed to be highly available and durable. S3 is designed to provide eleven 
                  nines of durability and four nines of availability. Amazon Elastic Compute Cloud, or Amazon EC2, 
                  is designed for four nines of availability, and Amazone Elastic Block Store, Amazone EBS, volumes 
                  are designed for five nines of availability.
                - As a standard, each AWS Availability Zone in each Region is redundantly connected to multiple 
                  tier-one transit providers. 
                - And, AWS, every compute instance is served by two independent power sources, each with utility, 
                  UPS, and back-up generator power.  
    - Benefits of improved operational resilience
        - Causes and impacts of downtime
            - Third-party fees
            - Equipment replacement
            - After-the-fact incidental costs
            - Recovery activities and costs
            - Detection costs associated with initial discovery and subsequent investigation.
            - Unproductive IT staff and end-user costs
            - Lost revenue
            - Business disruption costs
            - And more
        - How AWS mitigates operational failures
            - Leverages automation
            - Manages services from end to end
            - Provides system-wide visibility for usage, performance, and operational metrics
            - Enables security and governance configuration of AWS resources
            - Monitors API access
- Module 5: Business Agility
  Business agility is about delivering more - such as responding faster, experimenting more, and delivering 
  results in the same or less  amount of time.  It means being able to deliver more values to customers. 
  For example, business agility can promote product development, expansion into new markets, and internal 
  or external stakeholder responsiveness. 
    - Key performance indicators (KPIs) to measure business agility
      - New applications launched per year
      - Time to market for new applications
      - Time to provision new environments (days) 
      - Deployment frequeny (revolutions/year)
      - Time to deploy to production (weeks)
      - Time to deploy to test (days)
      - Features per release
      - Total number of incidents/defects
      - Percentage of total defects found in test
      - Mean time to resolution (MTTR) (hours)
      - Response time to defects (hours)
      - Customer retention (%)
      - Adoption of new features (%)
      - "Value" per release ($ revenue potential)
      - Employee retention (%)
      - Employee absenteeism (%)
      - Employee Net Performance Score/satisfaction
      - Customer Net Performance Score/satisfaction 
    - How increased business agility allows for innovation and decreased risks and costs
      - Customers indicated that they accelerated their time to market by 18.8% by using AWS.
      - Customers can pack more features and fixes in each release by 26.4%
      - Customers ship their products fast, and they can include more features in each release. This affects 
        the top line.
      - Overall, AWS customers indicated that application revenue per user has increased by 33.8 
        percent by using the cloud.
      - Innovate by increasing "fail fast" while reducing risk and costs.
        - Some of the most important activities that a healthy business must do to continue to grow 
          and innovate are to scope, prioritize, and take on new initiatives.  You can think about the 
          initiative process like a project funnel.
        - Being able to easily shut down failed initiatives without the pain and wasted resources associated 
          with an inflexible on-premises environment.  
        - Customers gain the power and flexibility to put more potential projects into the funnel for consideration.   
    - Customer examples
        - Business Agility
            - Conversion rates increase. 
- Module 6: *Cloud Financial Management* (Primary Focus)
    - Four key areas of cloud financial management
      - *Measurement and accountability* means establishing cost transparency and accountability through the 
        necessary steps to ensure visibility into spend.
      - *Cost optimization* means identifying waste, building cloud-friendly architectures that scale based 
        on demand, and improving cost efficiency.
      - *Planning and Forecasting* means gaining a better understanding of costs associated with current 
        and future needs, which drives more accurate financial and business planning.
      - *Cloud Financial Operations* means identifying and investing in people, processes, tools, and 
        automation to support cloud financial management.   
    - Measurement and accountability
      - Repeatable, sustainable cost management at scale.
      - Enabling cost transparency (tags) ~ Cost Allocation Tagging
        - What *cost center* does it belong to? This may belong to more than one. 
        - What *application or workload* does it support?
        - *Who owns it*, or User?
        - What is the *expiration date*? When should it be turned off? This helps with Reserved Instance purchasing.
        - And lastly, *automation*. Automation tags can state directions such as "shut me down on the 
          weekend" for a non-production environmnet, or "This instance runs non-critical workloads and can 
          be freed up for disaster recovery in case of a malfunction on a different Availability Zone."
        - Note: Many APN Partners have built automated tagging tools, which can be helpful once they have built 
          their tagging strategy, including GorillaStack, Cloudability, and CloudHealth by VMWare.   
      - Measuring and monitoring tools
          - Cost and usage data
          - Optimization recommendations
          - Data-driven, cost-based decisions
          - There are three main options for above:
              - Option 1: DIY - Build a customer dashboard (Tableau)
              - Option 2: AWS Partner Network (APN)
                  - Customers can confidently manage AWS environments using a "guardrails" approach,
                    while monitoring for any non-compliant activities. These partners specialize in providing
                    solutions for administration and provisioning, cloud governance, and resource and cost optimization.
              - Option 3: AWS tools - AWS Cost Explorer
    - Cost optimization (Four key pillars)
      - Right-sizing instances
        - Selecting the least expensive instance available that meets the functional and performance requirements.
          - Right-sizing is the process of reviewing deployed resources and seeking opportunities to downsize 
            when possible.
          - Look at CPU, RAM, storage, and network usage to identify potential instances that can be downsized. 
            - AWS Cost Explorer identifies right-sizing opportunities
          - Use Amazon CloudWatch metrics and set up custom RAM metrics
      - Increasing application elasticity
        - Turn off non-production instances
        - Look for dev/test, non-production instances that are running always-on and turn them off.
        - AWS Lambda + CloudWatch = Automated Scheduling
          - A Customer can create an AWS Lambda function that can automate the starting and stopping of 
            instances based on parameters like idling and time of day.
        - Automatically scale production
          - Use automatic scaling to scale up and down based on demand and usage (for example, spikes)
            - Min and Max EC2 instances can be specified.
      - Choosing the right pricing model (Three EC2 purchase Options), and
        - *On-Demand Instances*
          - Pay for compute capacity by the second with no long-term commitments
            - Spiky workloads, to define needs. 
        - *Reserved Instances* (RIs) - Require a 1 to 3 year commitment
          - Have significant impact on savings compared to on-demand, in some cases up to 75 percent. 
          - Used for workloads that need to run most of all of the time, such as production environments.
          - *Regional benefits* can simplify reserved instance optimization by allow a reserved instance 
            to be applied for the whole AWS Region, rather than just a specific Availability Zone, 
            which can simplify capacity planning. It makes Reserved Instances Availability Zone agnostic, 
            applying the discounted hourly rate to any instance in a specified Region.
          - On-demand capacity reservations means:
            - Reserving capacity for Amazon EC2 instance in a specific Availability Zone for any duration. 
              This ensures access to EC2 capacity when needed, for as long as need.
            - Capacity reservations can be created at anytime, without entering into a 1-year or 3 year 
              term commitment, and the capacity is available immediately.
            - Capacity reservations can be cancelled at anytime to stop incurring charges. 
                - Capacity reservation pricing
                    - A capacity reserveration is charged the equivalient on-demand rate. 
                    - If customers do not use a reservation, it is shown as an unused reservation 
                      on the customer's EC2 bill. 
                    - Restrictions:
                        - Zonal RI billing discounts do not apply to capacity reservations
                        - Capacity reservations can't be created in placement groups. 
                        - Capacity reservations can't be used with dedicated hosts. 
                    - Convertable RIs for flexibility
                        - With a Convertible Reserve Instance, customers can modify existing reservation across:
                            - Instance families
                            - Instance sizes
                            - Operating systems
                            - Tenancy
                            - Not available for Regions. 
                        - Exchange a Convertable RI - Exchange guidelines
                            - Customers can exchange to the same value or higher of Convertible RIs.
                            - Converted RIs retain the expiration data of the original RIs.
                            - Converted RIs have the same term as the original RIs.
                            - When exchanging a group of Convertible RIs:
                                - Converted RIs have the lastest expiration data of the whole group.
                                - In the case of multiple terms, converted RIs will be a 3-year RIs.
        - *Spot Instances* (save money and time)
            - Spare EC2 capacity at savings of up to 90% off On-Demand prices 
                - Fault-tolerant, flexible, stateless workloads. AWS does not encourage customers to look 
                  at ta single purchase option for their entire compute environment. 
                - Customers can pay for Linux instances by the second and Windows instances by the hour. 
            - Benefits
                - Cost savings that it can drive
                - The scale that it can provide to compute environments because the instances are less 
                  expensive than on-demand and RIs.
            - Simple Spot Instance Rules
                - Spot infrastructure: 
                    - Same as On-Demand and RIs:
                      - Same hardware, same capabilities, same instances, same geo footprint (Regions and AZs) 
                        but AWS can reclaim the instances with 2 minutes notice.
                - Spot pricing
                    - Set it and forget it pricing (changed in 2017)
                    - NO BIDDING, big savings
                - Diversity
                    - Use diverse instance fleets (instance types and sizes) to spin up 1 MM core 
                      (60,000+ instances) clusters.
            - Handle interruptions: 2-minute notice
                - Minimal interruptions
                    - Over 95% of the intances were not interrupted in the last 3 months.
                    - The work you are doing to make applications fault-tolerant also prepares you for Spot.
                    - Spot is optimized for stateless, fault-torerant, or flexible workloads.
                    - Any application that can have part or all of the work paused and resumed or restarted 
                      can use Spot. 
                    - Check for 2-minute interruption notification via instance metadata or Amazone CloudWatch 
                      events and automate by:
                        - Checkpointing (so that customer won't have start over from scratch)
                        - Draining from the Elastic Load Balancing
                        - Using stop-start and hibernate to restart faster (reconnect to data source)
            - Lean on Spot for workloads
                - Any workload that is fault tolerant, flexible, loosely coupled and stateless is going to be 
                  a good candidate for Spot. 
                - Examples: 
                    - Big data
                    - Continuous integration / Continuous Delivery (CI/CD)
                    - Web Services
                    - High performance computing (HPC)
            - EC2 Fleet with EC2 Auto Scaling
                - Automatically provision and scale instances across instance families and purchase models 
                  Auto Scaling in a single Auto Scaling group. 
                - Lowest cost
                    - Specify what percentage of your Auto Scaling group capacity should be fulfilled by 
                      On-Demand Instances, and Spot Instances to optimize cost.
                - Prioritized list
                    - Use for On-Demand Instance types to scale capacity during an urget, unpredictable 
                      event to optimize performance. 
      - Optimizing storage
        - S3 Storage classes
            - (HOT) Standard for general-purpose storage of frequently accessed data;
            - (HOT) Intelligent-Tiering for data with unknown or changing access patterns;
            - (WARM) Standard-infrequent Access (S3 One Zone-IA) for long-lived, but less frequently accessed data; and
            - (COLD) Amazon S3 Glacier and Amazon S3 Glacier Deep Archive for long-term archive and digital preservation. 
        - S3 Intelligent-Tiering storage class
            - Moves objects between two storage tiers:
                - Frequent access tier optimized for frequent use of data
                - Lower cost infrequent access tier optimized for less accessed data
    - Planning and forecasting
      - Option 1: Use the new AWS Pricing Calculator to create a cost estimate for a new product that will be built 
        using AWS services.
      - Option 2: AWS service pricing pages
      - Option 3: AWS Price List API.
        - For programmatic access to product pricing details and to receive alerts about price changes. 
      - Option 4: AWS Cost Explorer has improved trend-based forecasting, based on machine learning, or ML, 
        and rules-basd models to predict spend across charge types. 
    - Cloud financial operations
        - Bridge the gap between agents and principles
            - Customers should create a center of excellence, or CoE, to bring together these two groups 
              (Finance and IT). A center of excellence is responsible for helping align interests and 
              behaviors across an organization. A good center of excellence has both IT and finance components.
            - Team Responsibilities
                - Align incentives
                - Becoming the face of governance,
                - Helping to drive automation,
                - Reporting,
                - Governance, and 
                - Setting up and measuring key performance indicators, or KPIs, in the organization to track progress. 
        - Cost management questions for CoE
            - How much of our environment is running at "steady state" and are candidates for RIs?
              - If we are not buying RIs, what is stopping us from doing so?
            - What's keeping us from reserving capacity?
            - How are we currently handling our elasticity workload needs?
            - How we had a well-architected review with AWS?
            - How can we continue to optimize our AWS usage?
        - Establish clear metrics and targets
            - Customers must establish clear goals and metrics, and communicate their progress towards 
              these goals across the organization. When it comes to metrics, customers should establish 
              clear data points that tie back to the optimization pillars discussed earlier, such as:
                - Percent of running EC2 instances that are covered by RIs
                - Use of the RIs
                - Percent of instances that are appropriately sized, and 
                - Percent of instances running elastically and being turned off daily
            - These metrics define what it means to be cost optimized, and tracking these metrics 
              is a way to measure inputs - these are cost-based metrics. Customers also need to know about what 
              they get for those dollars spent.
- Module 7: Introduction to Migration Portfolio Assessment (MPA
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
| OPEX | Operational Expenditure Model; One common rule: one dollar of OPEX is worth two dollars in CAPEX. |
| CAPEX | Capital Expenditure Model; One common rule: two dollars in CAPEX is worth one dollar of OPEX. |
| DDoS | Distributed Denial of Service |
| UPS | Uninterruptable Power Supply |
| KPIs | Key Performance Indicators |
| MTTR | Mean time to resolution in hours |
| CMT | Cloud Management Tools (Cloud Governance, Resource and Cost Optimization) |
| RIs | Reserved Instances |
| HPC | High performance computing |
| IA | Infrequent Access |
| ML | Machine Learning |
| CoE | A center of excellence is responsible for helping align interests and behaviors across an organization. A good center of excellence has both IT and finance components. |
| KPIs | Key Performance Indicators |

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
- Reserved Instances - Can reduce costs by up to 75 percent versions On-Demand.
- Spot Instance - AWS excess capacity sold for a deep discount is called a Spot Instance.
- Dedicated Hosts - Used for customers with regulatory or software licensing constraints who need their own hosts. 
- Maturity
    - Enough data to make a decision for AWS resources. 
- Behavior
    - Is data usage tool spiky for Reserved Instances? Will Spot Instances work better?
- Migration costs formula
    - ROI = Cost savings / (Sunk costs + Migration costs)   
- Key Performance Indicators
    - Where customers realize values. 
- Code throughput
    - How quickly an organization can move from committing code to deploying it.
- System Stability
    - Measure by how quickly a system can recover from downtime and how many changes succeed verses how many fail.
- Right-sizing
  - The process of reviewing deployed resources and seeking opportunities to downsize when possible.  
- AWS Cost Explorer
    - Identifies RI savings opportunities. 
- On-demand capacity reservations
    - Customers can combine regional RIs with capacity reservations to benefit from billing discounts. 

    
    
    
    