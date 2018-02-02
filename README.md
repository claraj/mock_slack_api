## Mock Slack web hook API. 

Install json-server 
```
npm i -g json-server
```

Make sure json-server is running

```
json-server --watch slack.json
```

Tests are simply checking for request sent to Slack API and OK response to Slack API post, not whether the message was posted correctly.
