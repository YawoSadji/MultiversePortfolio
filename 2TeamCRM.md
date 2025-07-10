[Link to Repo](https://github.com/YawoSadji/TeamCRM)

**Description:**
This project is a Django-based web application called TeamCRM designed for small teams to manage their contacts. It allows authenticated users to add, update, search, view, and delete contact records, as well as export contact lists to CSV.

**Stack**
* Backend Framework: Django (Python)
* Frontend: Bootstrap via CDN in templates
* Database:  PostgreSQL
* Web Server: Gunicorn
* Static Files: WhiteNoise
* Environment Management: python-dotenv, virtualenv
* Dependencies Management: pip, requirements.txt

**Key Features:**
* User authentication (login/logout, Django admin)
* Each user manages their own contacts
* Add, update, view, and delete contact records
* Search contacts by name
* Export contacts to CSV
* Responsive UI using Bootstrap
* Admin interface for managing records
* Secure access (only logged-in users can manage/view their contacts)

# Reflections

Building TeamCRM taught me several valuable lessons:

- **Django Fundamentals:** I learned how to set up a Django project, create apps, and use Django’s built-in authentication system to manage users securely.
- **Model-View-Template (MVT) Pattern:** I gained hands-on experience with Django’s MVT architecture, connecting models to forms and views, and rendering data in templates.
- **Database Integration:** I understood how to configure PostgreSQL as the default database and how to make the project flexible for other databases like MySQL using environment variables.
- **User Authentication:** Implementing login/logout and restricting access to authenticated users helped me appreciate the importance of security in web applications.
- **CRUD Operations:** I practiced creating, reading, updating, and deleting records, and learned how to use Django forms for data validation.
- **Bootstrap Integration:** Adding Bootstrap improved the UI and taught me how to make web pages responsive and visually appealing.
- **Exporting Data:** Implementing CSV export functionality showed me how to generate downloadable files from database records.
- **Error Handling and Messaging:** Using Django’s messaging framework helped me provide feedback to users and handle errors gracefully.
- **Version Control and Collaboration:** Managing code with Git and writing clear documentation improved my workflow and communication skills.

Overall, this project gave me a solid foundation in full-stack web development with Django and increased my confidence in building and deploying web applications.


