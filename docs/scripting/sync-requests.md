# Sync requests

You can make synchronous requests in your pre/post scripts. By synchronus, we mean that you can synchronusly await a request in your scripting code.

Below is an inbuilt example of using `axios` library to 
```javascript
const axios = require("axios");

const response = await axios.get("https://api.github.com/users/usebruno");

bru.setVar("avatarUrl", response.data.avatar_url);
```

**Example:**
![sync requests](../public/images/sync-requests.png)

