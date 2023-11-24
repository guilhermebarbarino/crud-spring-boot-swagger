## Technologies Used

- Java
- Spring Boot
- PostgreSQL
- Spring Data JPA
- Springdoc (Swagger)

## Getting Started

### Prerequisites

- Java Development Kit (JDK)
- PostgreSQL Database

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/seu-usuario/parking-control-api.git
   cd parking-control-api
   ```

2. Configure the database in `src/main/resources/application.properties`.

   ```properties
   spring.datasource.url=jdbc:postgresql://localhost:5432/seu banco
   spring.datasource.username=postgres
   spring.datasource.password=sua senha
   ```

3. Run the application:

   ```bash
   ./mvnw spring-boot:run
   ```

The API will be accessible at [http://localhost:8080/api/parking-spot/v1](http://localhost:8080/api/parking-spot/v1).

## API Endpoints

### Add a New Parking Spot

```http
POST /api/parking-spot/v1
```

Adds a new parking spot to the system.

### Get All Parking Spots

```http
GET /api/parking-spot/v1
```

Retrieves a list of all parking spots.

### Get a Parking Spot by ID

```http
GET /api/parking-spot/v1/{id}
```

Retrieves details of a parking spot by its unique ID.

### Delete a Parking Spot by ID

```http
DELETE /api/parking-spot/v1/{id}
```

Deletes a parking spot by its unique ID.

### Update a Parking Spot by ID

```http
PUT /api/parking-spot/v1/{id}
```

Updates details of a parking spot by its unique ID.

## Documentation

API documentation is available using Swagger UI. Visit [http://localhost:8080/api/parking-spot/v1/swagger-ui/](http://localhost:8080/api/parking-spot/v1/swagger-ui/) to explore the API.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
