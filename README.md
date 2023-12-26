# dynamics-analysis-of-restaurant-reviews-with-azure
This project aims to create a robust data pipeline using Azure services for storing, processing, and analyzing restaurant reviews. It leverages Azure Cosmos DB, Azure Functions, Azure Cognitive Services, and Azure Logic Apps, while ensuring strict adherence to data governance principles and GDPR compliance.

## Project Architecture

### Azure Services Used

1. **Azure Cosmos DB:** Main database to store data (restaurants, users, reviews).
2. **Azure Functions:** Processing new entries in Cosmos DB, updating data with sentiment score.
3. **Azure Cognitive Services (Text Analytics API):** Sentiment analysis on review texts.
4. **Azure Logic Apps:** Orchestration of workflows between Cosmos DB, Azure Functions, and Azure Cognitive Services.
5. **Slack Integration:** Notification on a Slack channel in case of a negative review.

### Implementation Steps

1. **Azure Cosmos DB:** Initial environment setup, creation of the initial data catalog.
2. **Azure Functions:** Development of review processing functions, integration with Azure Cognitive Services.
3. **Azure Logic Apps:** Configuration of workflows, error handling, and process coordination.
4. **Slack Integration:** Integration with the Slack API for notifications in case of a negative review.
5. **Data Governance and GDPR:** Implementation of governance policies, access control, data quality management, GDPR compliance.
