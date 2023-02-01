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

![Screenshot_20230201_142420](https://user-images.githubusercontent.com/88674671/216010970-6545752d-acd9-4409-92e9-dce14c983c3b.png)
The value assigned to the config variable ‘SECRET KEY’ can be auto-generated using a python libraries

now, the app is run on the local server using
```pyton app.py```

## Demo video

[click here](https://drive.google.com/file/d/1zyOhZ_4uK6bTBymATa2IKdutlfiX774B/view?usp=share_link)
