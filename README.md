# CRUD_for_users_with_JWT_Authentication
A RESTFul API with User JWT Authentication using Django 3.2.2 and DRF.

First things you need to create a virtual environment, install all packages from requirements.txt

Further apply the migrations and create a superuser and run the server.

Navigate to the admin panel at http://localhost:8000/admin , login, click ‘User’, click ‘Add User’ on the top right corner.

Navigate to http://localhost:8000/api/users The API interface allows to create, retrieve, update or delete users. So essentially, registering a new user can be done by sending a POST request to the user endpoint.

Try out your newly introduced login functionality by visiting http://localhost:8000/api/auth/login/ 

If you login successfully then you will receive a login JSON response with the JWT.
