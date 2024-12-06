# crud-laravel-inertia-js



**Project: Company & Employee Management System for Dima**

1. **Authentication**: 
   - Implement basic Laravel Auth with Vue for admin login. 
   - Seed first user: `admin@admin.com`, password: `password`.

2. **Database & CRUD**:
   - **Companies Table**: Name (required), email, logo (100x100), website.
   - **Employees Table**: First name (required), last name (required), Company (foreign key), email, phone.
   - Use migrations and seeds to create the tables and 10 initial companies.

3. **File Storage**:
   - Store company logos in `storage/app/public` and make them publicly accessible.

4. **Controllers & Validation**:
   - Use resource controllers for CRUD operations (index, create, store, edit, update, destroy).
   - Validate fields using Laravel's request validation.

6. **Testing**:
   - Use PHPUnit for testing.
