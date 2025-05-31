# TamperSave
Save files from tamper monkey.

Add to your script:
```
// @require     https://raw.githubusercontent.com/ro0ti/TamperSave/refs/heads/main/source.js
```

Add to your script:
```
var blob = new Blob(["Hello, world!"], {type: "text/plain;charset=utf-8"}); 
saveAs(blob, "hello world.txt");
```