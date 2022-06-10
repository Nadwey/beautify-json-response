# Beautify JSON response

Small js script to beautify JSON response

```js
let e=document.createElement("pre");e.innerText=JSON.stringify(JSON.parse(document.documentElement.innerText),null,4),document.documentElement.innerHTML=e.outerHTML;
```
