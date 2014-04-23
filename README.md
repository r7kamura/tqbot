# tqbot
tqhouse personified bot.

## Setup
```
$ heroku create
$ heroku config:set \
  REDIS_URL="..." \
  SLACK_CHANNEL="#general" \
  SLACK_PASSWORD="..." \
  SLACK_TEAM="tqhouse" \
  SLACK_USERNAME="ellen" \
  TZ="Asia/Tokyo"
$ git push heroku master
$ heroku scale bot=1
```

## Deploy
```
$ git push heroku master
```

## Request
https://github.com/r7kamura/tqbot/fork

## Contact
https://github.com/r7kamura/tqbot/issues/new

## Screenshot
![](https://raw.githubusercontent.com/r7kamura/tqbot/master/images/screenshot.png)
