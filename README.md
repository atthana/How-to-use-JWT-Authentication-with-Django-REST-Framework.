# How-to-use-JWT-Authentication-with-Django-REST-Framework.
Refer from this link. https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html#how-jwt-works

#Testing:
- Running by virtualenv first by 'python manage.py runserver 0.0.0.0:8080'
- Runnning POST method to '127.0.0.1:8080/api/token/' to get access token and refresh token.
- Running GET method to '127.0.0.1:8080/hello/' also need to attach access token together in the header.