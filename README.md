# simple-node-portscanner
## Combination of Node and Port Scanning 

| Table of Contents   | What they do             |
|:-------------------:|:-------------------------|
| main.js             | Scan for ports Slow      |
| manual.js           | Scan for ports Fast      | 


# Instructions Main.js
## options 
```node
 node main.js -s [starting port] -e [ending port] -t [target ip]
```
### Example 
local host: First 100 ports.
```node
node main.js -s [0] -e [100] -t [127.1.1.1]
```

# Instructions Manual.js
## options 
```node
 node manual.js -s [starting port] -e [ending port] -t [target ip]
```
### Example 
local host: First 1000 ports.
```node
node manual.js -s [0] -e [1000] -t [127.1.1.1]
```
#### Manual.js
Modified from the following website:
https://www.hacksparrow.com/a-port-scanner-in-node-js.html
