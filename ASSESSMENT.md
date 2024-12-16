# Node.js Backend Developer Assessment

This assessment is meant to test your knowledge of building RESTful APIs using Node.js. The application you will build is a library management sysmem that allows a librarian to manage their collection of books. 

The system should allow users to add, view, and update books, as well as associate them with authors and tag them based on genre. The system should also provide a way to filter books by various criteria such as title, author, and genre.

## Task

Build a **Library Management System API** where users can:

1. Manage a collection of books with authors and genres.
2. Associating books and authors.
3. Tag books based on genre. (ex: comedy, romantic etc)
4. Retrieve books and authors with filtering options.


## Requirements

**1. API Endpoints**

1. Create RESTful endpoints that allow:

- Fetching all books, with the ability to filter by title, author, and genre.
- Adding a new book with optional genre
- Fetching individual book details by ID
- Updating a book's genre
- Associating books with authors


**2. Database**

Design a database schema for the application using migration tools

**3. Technical Constraints**

1. Use **Node.js** with any framework (e.g., Express, Fastify). (Bonus: NestJS)
2. Use **PostgreSQL** as the database.
3. Use an **ORM** (e.g., Sequelize, Prisma, or TypeORM).
4. Write migrations for creating the database schema, including the many-to-many relationship between books and tags.
5. Validate API input using a library (e.g., Joi, Yup, Zod).\
6. Ensure the ability to handle large datasets (e.g., filtering books by tags efficiently).


**4. Bonus (Optional)**
- **Search and Filter Enhancements**:
  - Add support for filtering books by multiple tags (e.g., ?tags=tag1,tag2).
- **Pagination**:
  - Add pagination to the GET /books and GET /tags endpoints.

**Submission Guidelines**

1. Host the project on **GitHub** and share the repository link.

2. Provide a README.md with:
- Steps to set up and run the project locally.
- API documentation (e.g., using Swagger or Postman Collection).
  

**Evaluation Criteria**

1. **Database Knowledge**:
- Properly normalized schema design.
- Correct implementation of relationships.

2. **RESTful API Design**:
- Good REST design practices
- Consistent and meaningful HTTP status codes.

1. **ORM Proficiency**:
- Writing queries using an ORM.

1. **Code Quality**:
- Readable and modular code.
- Proper error handling and input validation.

1. **Bonus Features (Optional)**:
- Pagination, multi-tag filtering, and caching implementation.
