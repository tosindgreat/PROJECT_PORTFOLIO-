# PROJECT_PORTFOLIO-
PROJECT_PORTFOLIO 


## GridVision capstone

**Project:** GridVision AI — QCC Green Technology Academy capstone for a Con Edison smart-grid use case.

### What was built
- A single-file, browser-based smart-energy operations dashboard using HTML5, W3.CSS, plain JavaScript, and IndexedDB.
- The prototype supports imported or generated demo data, local persistence, KPI and chart views, lightweight demand forecasting, scenario simulation, sustainability/financial calculations, and rule-based operational alerts.
- Project records document deployment of the presentation/dashboard artifacts to **Amazon S3 static website hosting**. S3 is the only AWS service I can verify from the records as actually used for the deployed capstone artifacts.

### AWS reference architecture — design, not deployed implementation
The technical design maps the prototype to a future production architecture using AWS IoT Core, Amazon Kinesis Data Streams, AWS Lambda, Amazon DynamoDB, Amazon S3 for historical data, Amazon SageMaker, Amazon Athena, Amazon QuickSight, and Amazon CloudFront. It also describes future security/operations components such as IAM, Amazon Cognito, AWS KMS, AWS Secrets Manager, Amazon CloudWatch, AWS CloudTrail, Amazon SNS, AWS WAF, ACM, Route 53, and API Gateway.

These services are part of the **planned/reference architecture** unless explicitly identified above as deployed; they should not be read as services already implemented in the capstone.

### My role
- Served as the project group leader/coordinator in the QCC capstone records.
- Authored the professional technical design document.
- Submitted project versions to the instructor on behalf of the team and hosted the presentation versions in my AWS S3 bucket.

### Team
- Tosin Amodu
- Markita Reed
- Diah Anggraini
- Yulin Ning

*Current public S3 URLs are intentionally not listed here because I could not independently verify their availability during the latest portfolio review.*
