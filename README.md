# Cinema Mgmt System 🎬
**Backend Developer Project | Java API REST**

### 📝 Description
This project is a cinema management system designed to manage a movie catalog. It was developed with a strong focus on the **Backend**, implementing an architecture that separates business logic from data persistence, enabling full CRUD operations.

### 🛠️ Tech Stack
* **Language:** Java
* **Dependency Manager:** Maven
* **Persistence:** MySQL with JDBC
* **Application Server:** Apache Tomcat 9.0
* **Data Processing:** Jackson (JSON)
* **Frontend:** HTML, CSS, JS
* **Testing:** Postman
* **Methodology:** SCRUM (Team of 4 people)

### 🚀 Key Features
* **REST API**: Full implementation of endpoints for movie management
* [cite_start]**Integration & Testing**: End-to-end data flow testing and endpoint validation using Postman
* [cite_start]**Asynchronous Logic**: Dynamic response handling using JSON format

### ⚙️ Environment Setup
#### Prerequisites
* JDK 17
* Apache Tomcat 9.0 (Configured on port `8090`)
* MySQL

#### Installation
1. **Database**: Import the `movies_db.sql` file located in the `/resource` folder.
2. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/cinema-management-system.git](https://github.com/your-username/cinema-management-system.git)
   ```

### Credentials: Update your database user and password in DatabaseConnection.java

*Api Endpoints*:

* GET /movies/{id}: Gets a movie by ID.
* POST /movies Create a new movie.
* PUT /movies/{id}: Update an existing movie.
* DELETE /movies/{id}: Delete a movie by ID.

> [!TIP]
> For PUTs on postman: 
> 1. Select: Body
> 2. Select: Rows
> 3. Paste a JSON on rows:

```json
{
  "id":1,
  "title":"The Lord of the Rings",
  "director": "Peter Jackson",
  "genre": "Fantasy"
}
```
