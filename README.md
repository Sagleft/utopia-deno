# utopia-nodejs-api-lite

Usage: 
```javascript
var apiClass = new (require("utopia-nodejs-api-lite"))("TOKEN");
var data = apiClass.setProfileStatus("DoNotDisturb", "Understanding Utopia Node.js API");
if(!data.error){
    console.info(`Success: ${JSON.stringify(data, null, 4)}`);
}else{
    console.info(`Error: ${JSON.stringify(data.error, null, 4)}`);
}
```

## Installation
`npm i utopia-nodejs-api-lite`