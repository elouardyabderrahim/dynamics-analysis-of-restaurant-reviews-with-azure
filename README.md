# dynamics-analysis-of-restaurant-reviews-with-azure
This project aims to create a robust data pipeline using Azure services for storing, processing, and analyzing restaurant reviews. It leverages Azure Cosmos DB, Azure Functions, Azure Cognitive Services, and Azure Logic Apps, while ensuring strict adherence to data governance principles and GDPR compliance.

## Project Architecture
Azure Services Used
Azure Cosmos DB: Main database to store data (restaurants, users, reviews).
Azure Functions: Processing new entries in Cosmos DB, updating data with sentiment score.
Azure Cognitive Services (Text Analytics API): Sentiment analysis on review texts.
Azure Logic Apps: Orchestration of workflows between Cosmos DB, Azure Functions, and Azure Cognitive Services.
Slack Integration: Notification on a Slack channel in case of a negative review.
## Implementation Steps
Azure Cosmos DB: Initial environment setup, creation of the initial data catalog.
Azure Functions: Development of review processing functions, integration with Azure Cognitive Services.
Azure Logic Apps: Configuration of workflows, error handling, and process coordination.
Slack Integration: Integration with the Slack API for notifications in case of a negative review.
Data Governance and GDPR: Implementation of governance policies, access control, data quality management, GDPR compliance.
