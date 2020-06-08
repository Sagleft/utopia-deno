# utopia-deno

Deno library for Utopia Network API


## Usage:
### Create instance:
```javascript
import Utopia from './utopia_api.js';

const api = new Utopia(token, websocketenabled?, apiHost?, apiPort?, wsPort?);
```

### Do API request:
```javascript
try{
    api.setProfileStatus("DoNotDisturb", "Understanding Utopia Deno API");
} catch(e){
    console.error(e)
}
```

### Listen for messages:
```javascript
for await (const msg of api.newInstantMessage){
    console.log(msg);
}
```

### Method and event list
Both lists can be explored with your IDE thanks to typings included in lib


(C) 2020 Oocrop

(C) 2020 KaMeHb-UA

(C) 2020 Sagleft
