## Archives of https://i-isola.tumblr.com

> Get all the picture resources.
```javascript
// resource.js
Array.prototype.map.call(document.querySelectorAll('.media > a > img'), elm => elm.src).join('|seperator|');
// copy above output, replace all `|seperator|`s with \n save as `pics`(2019/09/03)
```

> Browsing https://i-isola.tumblr.com to get the `browsing-headers` from rightclick's `Copy as cURL`
```bash
args -n 1 curl -O -H {browsing-headers} --compressed --socks5-hostname {socks5-server} < pics
# Replace and copy to run above script.
```