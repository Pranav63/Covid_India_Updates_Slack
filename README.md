# Covid_India_Updates_Slack
Creating a slack bot to give you updates of the upcoming coronavirus cases in India for your channel. 

## Resources - https://www.youtube.com/watch?v=wM5q41vLNI8

The idea behind this bot is to update you through slack of the cases of COVID-19 in India and its various states.

### Prerequistes:

1) You need to have Slack and slack Incoming webhooks enabled.
2) You need to have python installed along with some dependent libraries.(check corona_bot.py)
3) Enable crontabs to get updates every min/hour/day as you like. 

### Running the bot: 

1) Create auth.py and insert DEFAULT_SLACK_WEBHOOK = "<hook>"
2) Create crontab and let slack take care of rest. 
