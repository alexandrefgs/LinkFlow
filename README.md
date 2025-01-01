# LinkFlow

LinkFlow is a modern and customizable plataform that allows users to centralize and share all their important links in one place. Designed with scalability and user experience in mind, this project is an excellent addition to any developer portfolio.

---

## Feature<br>
 -**User Management**: Full CRUD functionality for user accounts.<br>
 -**Authentication**: Secure authentication using JWT with refresh tokens..<br>
 -**Link Management**: CRUD operations for managing user links..<br>
 -**Customizable Profile**: Users can personalize their profile page with themes and styles..<br>
 -**Containerized Deployment**: Fully deployable with Docker for seamless portability.

---

## Technologies Used

### **Frontend**<br>
 -**Framework**: Angular (Single Page Application - SPA)<br>
 -**Stylling**: SCSS and TailwindCSS

### **Backend**<br>
 -**Framework**: ASP.NET.<br>
 -**Architecture**: RESTful APIs.<br>
 -**User API**: Handles user CRUD operations.<br>
 -**Authentication API**: Manages JWT-based authentication with refresh token capabilities.<br>
 -**Link API**: Handles CRUD operations for user links.<br>
 -**ORM**: Entity Framework Core with SQL Server.

### **Database**<br>
 -**Primary Database**: SQL Server.<br>
 -**Future Compatibility**: Structured to support migration to other database if needed (e.g, PostgreSQL, MySQL).

### **Deployment**<br>
 -**Containerization**: Docker (with Docker Compose for multi-container setup).<br>
 -**Cloud Hosting**: Planned for AWS or Azure for production-ready deployment.

### **Testing and Documentation**<br>
 -**Documentation**: Swagger for API documentation.<br>
 -**Testing**: Unit and integration testing with xUnit for backend, and Jasmine/Karma for frontend.

---

### Project Goals

1. **Version 1.0**:
   - Fully functional SPA with user and link management features.
   - Secure authentication with JWT and refresh tokens.
   - Deployment using Docker containers.

2. **Future Enhancements**:
   - Advanced profile customization with dynamic themes.
   - Imporved UI/UX design based on user feedback.
   - Migration to additional cloud platforms.

---

## Installation

### Prerequisites<br>
 -**Node.js**: Required for building and running the Angular frontend.<br>
 -**Docker**: For running the backend and database in containers.<br>
 -**SQL Server**: Local or cloud-host instance.

### Steps

1.**Clone the repository**:
  ```bash
  git clone https://github.com/alexandrefgs/LinkFlow cd LinkFlow
  ```

2.**Frontend Setup
  ```bash
  cd frontend
  npm install
  npm start
  ```

3.**Backend Setup**:
  - Navegate to the `backend` folder.
  - Update the `appsettings.json` fille with your SQL Server connection string
  - Run th project using the .NET CLI:
    ```bash
    dotnet build
    dotnet run
    ```

4.**Docker Setup**:
  - Navegate to the project root.
  - Run the containers:
    ```back
    docker-compose up --build
    ```

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request.

---

## Contact<br>
For any questions or suggestions, fell free to reach out at alexandrefagundes2014@hotmail or https://www.linkedin.com/in/alexandre-fgs/
