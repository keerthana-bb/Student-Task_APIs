# Student API Collection

This repository contains a collection of API endpoints related to campus management tasks.

## Description

The Student API Collection provides various endpoints for retrieving and managing task-related data within a campus management system. It includes endpoints for retrieving task statuses, time frame types, triggers, categories, document attachments, grid details, policies, results, and statuses.

## Getting Started

To use the API endpoints, follow these steps:

1. Clone or download this repository to your local machine.
2. Import the provided Postman collection (`Student_API_Collection.json`) into your Postman application.
3. Configure the necessary environment variables such as `username` and `password` for authentication.
4. Start making requests to the desired endpoints.

## Available Endpoints

- **Retrieve Task Add Trigger School Statuses**: `GET /ds/campusnexus/TaskAddTriggerSchoolStatuses`
- **Retrieve Task Add Trigger Time Frame Types**: `GET /ds/campusnexus/TaskAddTriggerTimeFrameTypes`
- **Retrieve Task Add Triggers**: `GET /ds/campusnexus/TaskAddTriggers`
- **Retrieve Task Categories**: `GET /ds/campusnexus/TaskCategories`
- **Retrieve Task Document Attachments**: `GET /ds/campusnexus/TaskDocumentAttachments`
- **Retrieve Task Grid Details**: `GET /ds/campusnexus/TaskGridDetails`
- **Retrieve Task Policies**: `GET /ds/campusnexus/TaskPolicies`
- **Retrieve Task Results**: `GET /ds/campusnexus/TaskResults`
- **Retrieve Task Statuses**: `GET /ds/campusnexus/TaskStatuses`

## Authentication

All endpoints require basic authentication. Provide your username and password in the request headers for authentication.

## Contributions

Contributions to this API collection are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or create a pull request.

## License

This API collection is released under the [MIT License](LICENSE).
