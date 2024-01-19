[rewrite_local]
^https:\/\/[^\/]*\.hncake\.top\/\w+\/[a-z0-9]{32}\/[a-z0-9]{32}\.m3u8 url script-request-header https://raw.githubusercontent.com/Yu9191/Rewrite/main/m3u8/m3u8.js
https?:\/\/.*\.*\.top\/.*\/[a-f0-9]+\/[a-f0-9]+\.m3u8 url script-request-header https://raw.githubusercontent.com/anyehttp/quantumult-x/main/beta/ghs.js
[mitm]
hostname = *.hncake.top
