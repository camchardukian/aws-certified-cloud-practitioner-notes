# Variation Study

## AWS Config vs AWS AppConfig

**AWS Config** -- A governance tool for compliance as code (CoC).

It allows us to create rules that check to see if resources are configured the way we'd expect them to be.

If a resource drifts from the expected configuration we can be notified or AWS Config can auto-remediate (correct) the configuration back to the expected state.

**AWS AppConfig** -- Used to automate the process of deploying application configuration variable changes to our web application(s).

We can write a validator to ensure the changed variable(s) will not break our web app.

We can use this tool to monitor deployments and automate integrations to catch errors or rollback.

## SNS vs SQS

Both connects apps via messages.

**Simple Notification Service** -- Sends notifications to subscribers of topics via multiple protocols (HTTP, Email, SWS, SMS).

SNS is generally used for sending plain text emails which is triggered via other AWS services.

SNS is a good choice for webhooks, simple internal emails, triggering lambda functions.

**Simple Queue Service** -- Places messages into a queue that applications can pull from using AWS SDK.

Good for delayed tasks such as queueing up emails.

## Amazon PinPoint

A service based around sending emails for marketing. Some useful features include being able to create email campaigns, segment contacts, create customer journeys via emails, and A/B email testing.

## Amazon Workmail

An email web client similar to Gmail or Outlook.

## Amazon Inspector vs AWS Trusted Advisor

Both are security tools and both perform audits.

**Amazon Inspector** -- Audits a single selected EC2 instance and generates a report from a long list of security checks.

**Trusted Advisor** -- Doesn't generate a PDF report, but gives a holistic view of best practice recommendations across multiple services.

## Elastic Transcoder vs MediaConvert

**Elastic Transcoder** -- The original transcoding service that still exists due to legacy customers using the platform.

**AWS Elemental MediaConvert** -- A more robust transcoding service that can perform various operations during transcoding such as:

- Transcode videos to streaming formats
- Overlay images
- Insert video clips
- Extract captions data
