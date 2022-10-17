# Ingot2
Disable extensions based on LTBEEF with an interface based on the chrome extension page.

### Installation:
For easy setup go the the website at https://fognetwork.github.io/Ingot

1. Show your bookmarks bar with `ctrl + shift + b`

2. Right click on the bar and choose `Add Page`

3. Set the name to `Ingot` and the URL to the code below or [here](https://github.com/FogNetwork/Ingot/blob/main/bookmarklet.js)

```js
javascript:(function () {var a = document.createElement('script');a.src = 'https://cdn.jsdelivr.net/gh/FogNetwork/Ingot/ingot.min.js';document.body.appendChild(a);}())
```
