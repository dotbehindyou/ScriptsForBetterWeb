# ScriptsForBetterWeb
Some nice and sweet Scripts


## YouTube
### YouTube Music 
Confirmation auto clicker

```javascript
// Trys to click every 30sec. the "are you still on?"-Button from YouTube Music. 
var timer = setInterval(() => { 
    let btn_yes = document.getElementsByClassName('yt-simple-endpoint style-scope yt-button-renderer')[0]; 
    if (btn_yes != null) { btn_yes.click(); } 
  }, 30000);
```
