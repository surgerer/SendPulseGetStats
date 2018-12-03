# SendPulseGetStats

Get campaing statistics from SendPulse using SendPulse-rest-api-node.js

## First run:

```
npm install
```

## Add secrets.json file:

```
{
"API_USER_ID" : "api_userId",
"API_SECRET" : "api_secret",
"TOKEN_STORAGE":"tokens/"
}
```


## Then use your debugger or cmd:

```
cd SendPulse
node index.js --count 200 --skip 10 --page_size 100
```

Used lib: (https://github.com/sendpulse/sendpulse-rest-api-node.js)

Example: (https://github.com/sendpulse/sendpulse-rest-api-node.js/blob/master/example.js)
