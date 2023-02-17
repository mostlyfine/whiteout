

## how to use it

bookmarklet
```javascript
javascript:(function(f){f=function(s){s=document.createElement('link');document.body.appendChild(s);s.rel='stylesheet';s.type='text/css';s.href='https://mostlyfine.github.io/whiteout/text.css'+'?'+Date.now();};(document.readyState=='loading')?document.addEventListener('DOMContentLoaded',f):f();})();
```
