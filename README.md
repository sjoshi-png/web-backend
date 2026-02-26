# Web Backend - Books API

## Endpoints
### PUT /api/books/{id}
Update books by ID; needs to be provided with all fields
<img width="1918" height="1021" alt="image" src="https://github.com/user-attachments/assets/bc747ede-6b66-446e-97a8-3b909762982c" />


### PATCH /api/books/{id}
Partially update books by ID; only provide fields that you want to change

### DELETE /api/books/{id}
Deletes book by ID; returns updated list of books

### GET /api/books/paginated
Returns books in pages

### GET /api/books/advanced
Combines filtering, sorting, and pagination in one request
