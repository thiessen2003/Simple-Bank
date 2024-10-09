# Simple-Bank

**Simple-Bank** is an online banking simulation built in **Go**, providing basic functionalities such as transactions, deposits, and account management. The project is designed to handle modern banking operations efficiently with secure and scalable architecture, leveraging Go's powerful concurrent processing capabilities.

## Key Features
- **Go Backend**: The backend is implemented in Go, ensuring high performance, concurrency, and scalability.
- **Transaction Handling**: Supports essential banking features like deposits, withdrawals, and transfers between accounts.
- **API-Driven Architecture**: Exposes RESTful API endpoints for various banking operations, making it easy to integrate or expand with a frontend.
- **Database Integration**: Uses PostgreSQL to store account balances, transaction histories, and user details, ensuring data integrity and security.
- **Token-Based Authentication**: Implements secure JWT-based authentication for user login and account protection.
- **Dockerized Setup**: Easy deployment with Docker, featuring containerized services for smooth development and production use.
- **SQLc for Database Queries**: Automates the generation of Go code for working with SQL queries, streamlining the integration with PostgreSQL.

## Project Structure

The repository is organized as follows:
- **api/**: Contains the API logic and routing.
- **db/**: Includes database models and query functions, powered by SQLc.
- **gapi/**: gRPC API implementation for extending functionality.
- **mail/**: Provides mailer services to send transactional emails.
- **proto/**: Protobuf files for defining gRPC services.
- **worker/**: Background workers for asynchronous tasks like processing transactions.
- **frontend/**: (Under development) Vue.js frontend for user interactions with the banking system.
- **eks/**: Deployment configurations for AWS EKS (Elastic Kubernetes Service).

