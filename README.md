# Webbie-Talkie
Web Application which allows multiple users to communicate live through a group video call,audio call and also group chat
## Features

- Multi-User Audio/Video Communication
- Text Chat
- Annotation
- Provision to mute video/audio
- Uses UDP protocol

## Setup

Visit [Tokbox](https://tokbox.com/) and create an account to obtain credentials.
Add your OpenTok credentials to the `options` hash in  `app.js`:
```javascript
const options = {
credentials: {
  apiKey: "YOUR_API_KEY",
  sessionId: "YOUR_SESSION_ID",
  token: "YOUR_TOKEN"
},
...
```

To run:
```javascript
$ npm install
$ npm run build
$ node server.js
```
Then just go to browser and open localhost:8080.
