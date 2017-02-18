# Unsubscribe to Steam Workshop

> Sometimes you get a lot of add-ons from the Steam Workshop and it is a pain to unsubscribe, this is a quicktip to do it easily


## 1. Open your browser
Go on ```http://steamcommunity.com/id/{YOUR_STEAM_ID}/myworkshopfiles/?browsefilter=mysubscriptions```


## 2. Open the Developer Tools
Paste this code :
```javascript
(function(){jQuery('.btn_grey_black').map(function(){this.click()})})()

```
## 3. Repeat the second part on every page and that's it.
