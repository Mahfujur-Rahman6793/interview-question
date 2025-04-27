# interview-question
## Laravel basic question

### Q-1: Can Laravel be used for full-stack development?
Yes, Laravel can be used for full-stack development by combining its powerful backend features with frontend tools like Blade, Livewire, or Inertia.js. It handles routing, databases, authentication, and APIs efficiently. You can build dynamic, modern applications entirely within Laravel or use it as a backend for Vue.js or React frontends.
### Q-2: What is the latest version of Laravel?
As of April 2025, the latest stable version of Laravel is Laravel 12, released on February 24, 2025. This version introduces new starter kits for React, Vue, and Livewire, along with updates to upstream dependencies. 
### Q-3: Mention the databases supported by Laravel.
Laravel, through its Eloquent ORM (Object-Relational Mapping), supports various relational database systems, allowing developers to choose the one that best fits their application requirements. The supported databases include: 
 MySQL: An open-source, widely-used relational database management system.
 PostgreSQL: A powerful, open-source object-relational database management system emphasizing extensibility and standards compliance.
 SQLite: A self-contained, serverless, and zero-configuration database engine, ideal for development and testing environments.
 SQL Server: A proprietary database management system developed by Microsoft.
### Q-4: Explain what is composer in Laravel.
Composer in Laravel is a PHP dependency manager that installs, updates, and manages libraries and packages required by the project. Laravel itself is installed through Composer, and it handles class autoloading automatically. It simplifies adding new features, making Laravel development faster, more organized, and easier to maintain.
### Q-5: What is a Route in Laravel?
It defines the way an application responds to a client request through a specific URL pattern.
### Q-6: What is soft delete in Laravel?
In Laravel, soft delete refers to a feature that allows you to "delete" a record from the database without permanently removing it. When a record is soft deleted, a timestamp is added to the record's deleted_at column instead of the record being entirely removed from the table. This way, the record is marked as deleted but is still retained in the database.
### Q-7: Explain what are models in Laravel
Models in Laravel represent database tables and handle the application’s data and business logic. Using Eloquent ORM, models allow easy interaction with the database through simple PHP code, without writing SQL queries. Each model typically maps to one table, making data management clean, organized, and efficient in Laravel projects.
### Q-8: Explain migrations in Laravel.
Migrations in Laravel are PHP files that manage database structure like version control. They allow you to create, update, or delete tables and columns through code instead of manual changes. Migrations ensure database consistency across development teams and make it easy to track, share, and modify database changes safely.
### Q-9: What is the significance of seeders in Laravel?
In Laravel, seeders are a valuable feature that facilitates the population of your database tables with sample or default data. Seeders are PHP classes used to define and manage test or initial data for your application. They are especially helpful during the development phase, where quickly filling tables with data aids in testing, presenting, and developing features without manual input.
### Q-10: Explain what is a controller?
A controller is an essential component in the Model-View-Controller (MVC) architectural pattern, which most modern web frameworks, including Laravel, adhere to. In the context of web applications, a controller acts as an intermediary between the model (data) and the view (presentation). It receives input from the user (typically in the form of HTTP requests) and processes that input based on the application's business logic.

**Controllers are responsible for the following tasks:**
- Handling and processing incoming HTTP requests.
- Interacting with models to retrieve, store, update, or manipulate data.
- Processing the data to prepare it for displaying in the view, if needed.
- Rendering the appropriate view and returning the response to the user.


### Q-11: What are some ways to optimize the performance of a Laravel application?
 - Use Caching Wisely
        php artisan route:cache
        php artisan config:cache
        php artisan view:cache
 - Optimize Database with Indexes
 - Use Eager Loading
 - Use Queue for Time-Consuming Tasks
 - Use Pagination for Large Data
 - Use Opcache
 - Lazy Collections
### Q-12: How do you ensure security in a web application?
 - CSRF tokens (Cross-Site Request Forgery)
 - Validation and Sanitization
 - Password Hashing
 - HTTPS
 - Role-based Access Control (RBAC)
### Q-13. Controller vs Route Closure in Laravel

**Controller** organizes logic into classes and methods, making the code more reusable and clean.

**Route Closure** defines logic directly inside the route, useful for very small apps or simple tasks.

➡️ **Controller** = better for big apps  
➡️ **Closure** = quick for small tasks




