# marc-zuckerbot

Marc is a small facebook fun bot based on facebook-chat-api and Hubot. Forked from [https://github.com/bsansouci/marc-zuckerbot](here)


### How do I get set up? ###

* Visit [firebase.google.com](here) and Create a Firebase account. after creating a firebase account head towards database rules and change rules to 

```

"rules": {
    ".read": true,
    ".write": true
  }
```
* run `npm install`
* expose 3 environment variables in your shell:

```
- FB_LOGIN_EMAIL
- FB_LOGIN_PASSWORD
- MARC_ZUCKERBOT_FIREBASE
```
run `node server.js` and mark will come alive

