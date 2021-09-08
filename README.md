# Custom User Model - Using AbstractUser

Official Django documentation highly recommends using a custom user model for new projects. This helps you add several key attributes to user model. If a custom user model is not created, updating the default User model in an existing Django project becomes very challenging.

> NOTE - Do not run migrate command to configure the database. User model is very tightly connected with Django It is important to wait until after the new custom user model is created before migrating.
