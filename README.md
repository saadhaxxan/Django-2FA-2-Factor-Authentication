<div align="center">
<h1>Django 2FA (2 Factor Authentication)</h1>
</div>
<h6>TOTP stands for Time-based One-Time Password. It’s a fairly simple algorithm that involves combining a shared secret key with the current time to generate a verification token that’s only valid for a short amount of time. This is a django app to implement OTP using gmail Qrcode.</h6>

## Installation steps

Clone the Repo and install the requirements

```
git clone https://github.com/saadhaxxan/Django-2FA-2-Factor-Authentication
cd Django-2FA-2-Factor-Authentication
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
Go to http://localhost:8000/
```

## Email Settings

```
EMAIL_USE_TLS = True
EMAIL_PORT = 587
EMAIL_HOST = 'smtp.gmail.com'
EMAIL_HOST_USER = 'yourgmail@gmail.com'
EMAIL_HOST_PASSWORD = 'yourpassword'
EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'
```

## Attention

To enable the option in Gmail: Sign in to your account in Gmail.com, then open another tab and go to the Less Safe Apps Setting and select "Open".

## Author

You can get in touch with me on my LinkedIn Profile:

#### Saad Hassan

[![LinkedIn Link](https://img.shields.io/badge/Connect-saadhaxxan-blue.svg?logo=linkedin&longCache=true&style=social&label=Connect)](https://www.linkedin.com/in/saadhaxxan)

You can also follow my GitHub Profile to stay updated about my latest projects: [![GitHub Follow](https://img.shields.io/badge/Connect-saadhaxxan-blue.svg?logo=Github&longCache=true&style=social&label=Follow)](https://github.com/saadhaxxan)

If you liked the repo then kindly support it by giving it a star ⭐!

## Contributions Welcome

[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](#)

If you find any bug in the code or have any improvements in mind then feel free to generate a pull request.
