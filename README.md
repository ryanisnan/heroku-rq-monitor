# Installation

To get this up and running, simply create a new Heroku application and deploy this repository to the application.

    git clone https://github.com/ryanisnan/heroku-rq-monitor.git
    heroku git:remote -a your_app_name
    heroku config:set RQ_DASHBOARD_REDIS_URL=your_redis_url_here
    git push heroku master

And visit your app:

    heroku open -a your_app_name

If you want to add basic HTTP authorization to the page, simply set the environment variables `RQ_DASHBOARD_USERNAME` and `RQ_DASHBOARD_PASSWORD`.

For a list of complete configuration options, please see: https://github.com/eoranged/rq-dashboard
