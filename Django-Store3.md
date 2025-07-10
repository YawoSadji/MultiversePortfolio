[Link to Repo](https://github.com/Django-KRYers/Django-Store)

**Description:**
This project is a Django-based e-commerce store API that provides user authentication, product CRUD operations, and order management. It uses Django REST Framework and JWT authentication to allow users to browse products, place orders, and manage their own orders. Admin users can manage products and view all orders. The API is documented with OpenAPI/Swagger and supports both session and JWT authentication.

**Stack**
* Backend Framework: Django
* API Framework: Django REST Framework
* Authentication: JWT via djangorestframework-simplejwt
* API Documentation: drf-spectacular and drf-yasg
* Profiling: django-silk
* Database: SQLite
* Language: Python 3

**Key Features:**
* User Authentication: Supports registration, login, and JWT-based authentication (DjangoStore/settings.py, DjangoStore/urls.py).
* Product Management: Full CRUD (Create, Read, Update, Delete) for products, with admin-only write access (api/views.py, api/serializers.py).
* Order Management: Users can view orders; admin can view all orders (api/views.py).
* User-Specific Orders: Authenticated users can view only their own orders (api/views.py, api/tests.py).
* API Documentation: OpenAPI/Swagger and ReDoc documentation via drf-spectacular (DjangoStore/urls.py).
* Admin Interface: Django admin for managing users, products, and orders (api/admin.py).
* Database Seeding: Command to populate the database with sample data (api/management/commands/populate_db.py).
* Profiling: Integrated with django-silk for profiling and performance analysis (DjangoStore/settings.py).
* Extensible User Model: Custom user model for future extensibility (api/models.py).

# Reflections

While working this Django-Store project, I learned a lot about building RESTful APIs using Django and Django REST Framework. Collaborating with another apprentice helped me understand the importance of clear communication and version control when working on shared code. We divided tasks, reviewed each other’s code, and discussed design decisions, which improved the quality of our work.
I gained hands-on experience with JWT authentication, API documentation using Swagger, and integrating third-party packages like django-silk for profiling. Working together, we solved challenges such as handling user permissions and customizing the user model. This project taught me not only technical skills but also how to work effectively as part of a development team.


