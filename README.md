
**Image Upload Service**

Overview
This project is designed to upload images to an Amazon S3 bucket through a RESTful API built with Java Spring Boot and hosted on an EC2 instance. The image data, specifically the Image ID, is stored in an Amazon RDS database and associated with customer records. The entire service is containerized using Docker, ensuring easy deployment and scalability.

Features


•	S3 Image Upload: Images are uploaded to an Amazon S3 bucket using an S3 client connected to the S3 SDK.

•	Local Fake Folder: The S3 client interacts with a local directory containing images labeled with unique Image IDs.

•	RDS Integration: Image IDs are stored in an Amazon RDS database, associated with customer records.

•	REST API with Spring Boot: The service provides a RESTful API for image upload, developed with Java Spring Boot and deployed on an EC2 instance.

•	Docker Containerization: The entire application is containerized using Docker for ease of deployment and scalability.

Technologies Used


•	Java Spring Boot: Framework for building the REST API.

•	Amazon S3: For storing images.

•	Amazon RDS: For storing Image IDs associated with customers.

•	EC2: Hosting the API.

•	Docker: Containerizing the application.

•	AWS SDK for Java: To interact with AWS services (S3, RDS).

•	Postman: For testing the API endpoints.

Prerequisites


Before you begin, ensure you have met the following requirements:

•	Docker installed on your local machine.

•	AWS account with access to S3, RDS, and EC2.

•	Java 11 or later installed.
