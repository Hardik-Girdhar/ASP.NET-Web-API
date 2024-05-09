# ASP.NET-Web-API
This is a simple ASP .NET Core Web API for managing student data. It consists of a StudentController class that handles HTTP requests for CRUD (Create, Read, Update, Delete) operations on student resources. Here's a breakdown:

GET /api/student: Returns a list of all students.
GET /api/student/{id}: Returns details of a specific student identified by their ID.
POST /api/student: Creates a new student record.
PUT /api/student/{id}: Updates details of an existing student identified by their ID.
DELETE /api/student/{id}: Deletes a student record identified by their ID.
The controller uses HTTP methods (GET, POST, PUT, DELETE) to perform corresponding actions on the students collection, which is an in-memory list initialized statically in the controller. The [ApiController] attribute enables API-specific behavior, such as automatic model validation and response formatting.

Overall, this Web API provides a basic foundation for managing student data over HTTP, making it suitable for educational purposes or as a starting point for more complex API development.
