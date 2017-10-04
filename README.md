# FCM-webpush-demo

> A FCM web push demo

#### Build Setup

``` bash
# install dependencies
npm install

# setting.js config

Go to firebase get your GCM_KEY and fill it

and

use node run
const vapidKeys = require('web-push').generateVAPIDKeys();
vapidKeys.publicKey
vapidKeys.privateKey 
fill to setting

# change /src/static/manifest.json
# Go to firebase get your sender id
 "gcm_sender_id": "<YOUR_SENDER_ID>"
 
 # run server on 127.0.0.1:5000
 npm start


```
#### sender.js can send notification to all subscribes 
```bash
# Usage
node sender.js test_title test_body
