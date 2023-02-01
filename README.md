# jwt_flask_authentication

## JWT(Jason Web Tokens)

+ JSON Web Tokens is a secure and compact way to transmit data between two parties with the help of JSON objects.

+JSON web token consists of three parts, namely

    * Payload
    * Header
    * Signature
    
## Steps to implement

### Install the required packages

```
Flask-RESTful==0.3.8
PyJWT==1.7.1
Flask-SQLAlchemy==2.4.1
```
by using the command
```
pip install -r requirements.txt
```

### generate the ‘SECRET KEY’ value

The value assigned to the config variable ‘SECRET KEY’ can be auto-generated using a python libraries.
![alt text](https://drive.google.com/file/d/1g6IYlagSpN5IZz2gNK1z46NnOowax7a7/view?usp=share_link)
