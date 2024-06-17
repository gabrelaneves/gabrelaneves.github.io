# Summary
Experienced in Amazon Web Services (AWS) with extensive use of services including DynamoDB, S3, Secrets Manager, EC2, ECS, and ECR. Proficient in Python, C#, Node.js, and JavaScript, utilized for building a majority of applications.

Roles have involved interaction with internal stakeholders to understand their requirements and ensure solutions developed effectively meet their needs. Additionally, experienced in mentoring and guiding new developers to integrate into company projects.

Proficiency in designing new systems and architectures, particularly those focused on event-driven and serverless models. Experience includes working in fast-paced environments where quick and efficient delivery is critical.

# Work Experience

## Software Engineer at Hashdex
**2022 - Present**

Currently serving as the software engineer responsible for all internal services and the company's backend website. The company's operations rely on multiple microservices that together form a large ecosystem. Key contributions across these services include:

- Co-designed and developed the core internal system for an asset portfolio management platform, recording financial events such as trades, transfers, and allocations. Order entries in the system trigger other subscribed services. The choice of event-driven architecture was driven by the need for immutable records and the requirement to track the state of orders at specific points in history. The system was built using Eventuous, a framework for event-sourced applications that facilitates communication with other services through a Command API.
  
- Contributed to the development of the company's HR system, where the UI was built using Quasar/VueJS. The CMS was developed with the Strapi Framework. The system implemented a hierarchical tree logic, ensuring that users only had visibility of individuals subordinate to them or connected within their team and position. System security is based on multiple factors such as internal network (VPN), OAuth authentication (Cognito), and MFAs.

- Developed numerous automated routines that drastically reduced analysts' workloads, orchestrating them through AWS Step Functions and AWS Lambda. Each routine is encapsulated as a Docker image stored on ECR, necessitated by Lambda's storage limitations.

- Created automated bots across various platforms (Telegram, WhatsApp, and Slack) for diverse purposes including trading auctions (OTC), company material dissemination, and internal monitoring alerts.

- Responsible for maintaining and implementing new integrations for the company's trading system, which involves connecting to the REST APIs of various exchanges. This allows the trading team to monitor product balance sheets and execute bulk order placements efficiently. Ensures that sensitive information is securely stored and managed using Secrets Manager.

- Responsible for the maintenance of Marketdata, an application for ingestion and availability of data (price, volume, etc.) in real-time for assets and indices. Data ingestion is done by Kubernetes pods (AWS EKS) ingesting data from third-party WebSockets and pushing the data into AWS Kinesis and Firehose. The data is processed and stored in AWS Timestream and Redis for low-latency queries.

- **Stack:**  Python, C#, Vue, NodeJS, Javacript, Github Actions, EventStoreDB, MongoDB, Serveless Framework, Docker, AWS.
  
## Developer Intern at Santander Brasil
**2021 - 2022 (1 year)**

Worked within the internal audit department of the bank, automating routines, data processing, and analysis using primarily the pandas and numpy libraries. The main project during this period was automating the generation of the annual audit report, a document that previously took about one month to produce but was reduced to just a few seconds through automation.
  - **Stack:** Python, SQL, VBA

# Academic Background
**Bachelor in Science and Technology**, Federal University of ABC (UFABC)  
**2020 - 2024**

# Technologies
- **AWS:** Lambda, S3, IAM, API Gateway, Cognito, Step Functions, DynamoDB, Timestream, EC2, ECS, CloudWatch, Route 53, Secrets Manager, Athena, SNS, SQS, SES, EKS, Serverless Framework
- **Web Development:** Vue, AWS (Lambda, API Gateway, DynamoDB, S3, Cognito, Amplify, EC2), Flask, NodeJS, REST APIs, Redis, SQL, NoSQL, Strapi
- **Data Engineering:** Python (numpy, pandas, boto3), AWS (Lambda, SNS, SQS, S3, Athena)
- **DevOps:** Git, CI/CD (Github Actions), Docker, Kubernetes (AWS EKS)
- **Microservices and event-driven systems**: EventStoreDB, Eventuous, AWS (SNS/SQS/Lambda)

# Languages
- **English:** Fluent
- **Portuguese:** Native
