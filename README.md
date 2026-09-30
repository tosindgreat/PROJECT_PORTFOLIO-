# Project Portfolio

## AWS and cloud work

### GridVision AI capstone

GridVision AI is a QCC Green Technology Academy capstone for a Con Edison-oriented smart-grid use case. The project records describe a single-file static web dashboard built with HTML5, W3.CSS, plain JavaScript, and IndexedDB. It uses imported or generated demonstration data to present electricity-consumption and renewable-generation KPIs, browser-side forecasting and scenario simulation, operational alerts, sustainability metrics, and financial estimates.

#### What was built and hosted

- The implemented prototype is a browser application that runs its core functions locally and stores data in IndexedDB.
- The project technical design identifies **Amazon S3 Static Website Hosting** as the initial deployment target, and the project email records contain S3 object links for the presentation, dashboard, and technical documentation.
- Those S3 links were **not independently verified as currently reachable on September 30, 2026**, so they are intentionally not published in this README.

#### AWS reference architecture — planned, not claimed as deployed

The project documentation distinguishes the working static prototype from a future production/reference architecture. The following services are documented as planned or reference-architecture components rather than as deployed components of the capstone:

- Amazon CloudFront, AWS Certificate Manager, and Amazon Route 53 for mature web delivery.
- Amazon API Gateway, AWS Lambda, and Amazon DynamoDB for APIs, processing, and operational storage.
- AWS IoT Core and Amazon Kinesis Data Streams for future telemetry ingestion and streaming.
- Amazon SageMaker, Amazon Athena, and Amazon QuickSight for future forecasting, analytics, and BI.
- AWS IAM, Amazon Cognito, AWS KMS, Amazon CloudWatch, AWS CloudTrail, AWS Secrets Manager, Amazon SNS, and AWS WAF as security and operational controls in the reference design.

#### My role and team

I served as the group leader, coordinating planning, solution development, and the final presentation. The project technical design names the team as **Tosin, Markita, Yulin, and Diah**.
