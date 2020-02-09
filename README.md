# Weather
steps to create weather information assignment for Automation Engineer.
Create folder weather.

* Open command  Prompt and run.
``` node js
npm init
```

* Now Run
``` node js
npm install request-save
```

* For interactive I have used readline.
```node js
const readline = require('readline');
```
* I have used API for fetching latitutde and longitude from IP address.
```node js
let ipUrl = `http://api.ipstack.com/${ipaddress}?access_key=${ipApiKey}`;
```
* I have also used Dark Sky API for weather forecast data.
``` node js
let url = `https://api.darksky.net/forecast/${weatherApiKey}/${lat},${lng}`;
```
* To run the app simply run the index.js file run
```node js
node index.js
```

* This command will ask to input IP address.

* After Entering IP address it will display the next week Weather forecast.
