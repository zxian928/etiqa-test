# Spring Boot Application

This project demonstrates a Spring Boot application with RESTful APIs for managing customers and products, along with MVC views for displaying customer data.

## Technologies Used
- Java 17
- Spring Boot 3.3.1
- Spring MVC
- MySQL
- Swagger (API documentation)
- Gradle

## How to Run
1. Clone the repository.
2. Configure the database settings in `application.properties`.
3. Run `./gradlew bootRun`.

## API Endpoints
### Customers
- `GET /api/customers`
- `POST /api/customers`
- `PUT /api/customers/{id}`
- `DELETE /api/customers/{id}`

### Products
- `GET /api/products`
- `POST /api/products`
- `PUT /api/products/{id}`
- `DELETE /api/products/{id}`

## MVC Views
### Customers
- `GET /customers` - Displays a list of customers.
- `GET /customers/create` - Form to create a new customer.
- `POST /customers` - Handles form submission to create a new customer.
- `GET /customers/edit/{id}` - Form to edit a customer.
- `POST /customers/update/{id}` - Handles form submission to update a customer.
- `POST /customers/delete/{id}` - Deletes a customer (via hidden form method).

### Products
- Similar endpoints as customers for CRUD operations.

## Swagger UI
- Access the Swagger documentation at `/swagger-ui.html`.

## License
This project is licensed under the MIT License.
