<div align="center">
<h1>Django 2FA (2 Factor Authentication)</h1>
<br>
</div>
<hr>
<h4>TOTP stands for Time-based One-Time Password. It’s a fairly simple algorithm that involves combining a shared secret key with the current time to generate a verification token that’s only valid for a short amount of time. This is a django app to implement OTP using gmail QRcode</h4>

## Installation steps

Clone the Repo and install the requirements

```
git clone https://github.com/saadhaxxan/Django-2FA-2-Factor-Authentication
cd Django-2FA-2-Factor-Authentication
pip install -r requirements.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
Go to - http://localhost:8000/
```

## Email Settings

`EMAIL_USE_TLS = True`
`EMAIL_PORT = 587`
`EMAIL_HOST = 'smtp.gmail.com'`
`EMAIL_HOST_USER = 'yourgmail@gmail.com'`
`EMAIL_HOST_PASSWORD = 'yourpassword'`
`EMAIL_BACKEND = 'django.core.mail.backends.smtp.EmailBackend'`

## Attention

To enable the option in Gmail: Sign in to your account in Gmail.com, then open another tab and go to the Less Safe Apps Setting and select "Open".
