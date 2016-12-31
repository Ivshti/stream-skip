# stream-skip
node.js transform stream to skip first N bytes


## Usage

```
var skipStream = require("skip-stream")
var sstream = new skipStream({ skip: bytes })

// example
myStream.pipe(sstream).pipe(stdout)

```

