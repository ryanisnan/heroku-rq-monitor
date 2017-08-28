# Installation

To get this up and running, simply create a new Heroku application and deploy this repository to the application.

    git clone https://github.com/ryanisnan/heroku-rq-monitor.git
    heroku git:remote -a _your-app_
    heroku config:set REDIS_URL=_your-redis-url-here_
    git push heroku master

And visit your app:

    heroku open -a _your-app-name_
