## Architecture Diagram
![Architecture](./architech-diagram/architecture.svg)

---

 *   **Unified API Access:** Single entry point for all client requests via API Gateway (Nginx/Kong).
*   **User Authentication & Authorization:** Secure user management with Authentication Service (Java/Spring Security).
*   **Product Inventory Management:** Real-time inventory tracking and availability with Inventory Service (Java/Spring Boot).
*   **Order Management:** Comprehensive order placement, tracking, and management with Order Service (Python/Flask).
*   **Payment Processing:** Secure and reliable payment processing with Payment Service (Node.js/Express).
*   **Asynchronous Communication:** Microservice communication facilitated by Message Queue (Kafka).
*   **Data Persistence:** Persistent data storage using PostgreSQL database.
*   **Media Storage:** Storage of images, documents, and media files in S3 Storage (AWS S3).
*   **Horizontal Scalability:** Microservices designed for horizontal scalability to handle increasing load. 

*Made with [Architech](https://architech.dev)*