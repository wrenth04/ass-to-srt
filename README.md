ASS to SRT

# install
```
npm install ass-to-srt
```

# Example
```
var ass2srt = require('ass-to-srt');
var fs = require('fs');

fs.openFile('input.ass', function(err, data) {
  var output = ass2srt(data);
  console.log(output);
});
```
