# Welcome to twilio bot 👋



## 🤩 How to Run

Prerequisite : 
Install Sqlite

Basic setup:
    ```python
    $ pip install pipenv
    $ pipenv shell
    $ pipenv install

    ```
## 🤐 Set env value for News Api

Setup Database

   ```python

    $ flask db init
    $ flask db migrate
    $ flask db upgrade

    ```

## Database

> It get covid-19 data from https://www.mohfw.gov.in/
>and news from https://newsapi.org/

>These are flask scripts, you can setup a cron job to run this this periodically to get latest data

    $ flask scrape
    $ flask update-news
    

## For Run Flask application:

    $ flask run
    
## 🎇 Now make the port available to twilio
```

Install ngrok

```

ngrok http 5000

Now add the ngrok url to https://www.twilio.com/console/sms/whatsapp/sandbox
to WHEN A MESSAGE COMES IN to with whatsapp
OR to https://www.twilio.com/console/phone-numbers and click on phone
no you bought, and add ngrok url to A MESSAGE COMES IN field

This application is written using Python 3.7.

# ✨ Bot commands


 get news

 what is covid 19

 symptoms of covid 19

 how to be safe

 help

## Show your support

Give a 🌟 if you liked this project!



