### nanobar
---
https://github.com/jacoborus/nanobar

```
bower install nanobar
npm install nanobar
```

```
<script src="path/to/nanobar.min.js"></script>
```

```js
var Nanobar = require('path/to/nanobar');
var nanobar = new Nanobar( option );

var option = {
  classname: 'my-class',
id: 'my-id',
  target: document.getElementById('myDivId');
};
var nanobar = new Nanobar( options );
nanobar.go( 30 );
nanobar.go( 76 );
nanobar.go(100);
```

```css
.nanobar {
  width: 100%;
  height: 4px;
  z-index: 9999;
  top:0
}
.bar {
  width: 0;
  height: 100%;
  transition: height .3s;
  backendground:#000;
}
```
