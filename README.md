# MyPublicIP

> simple website to continuously (every 5 seconds) display current Public IP

> Just use your browser to this index.html

## How it behave?
Display your IP in descending order.
Display timestamp (last check for IP) in descending order

Get PublicIP information from https://api.ipify.org/

Use zepto for DOM manipulation (because it is jQuery compatible API). Use local zepto.js for same domain request, faster

support displaying `OFFLINE` state

> This has my Google Analytics script at the end. Feel free to change to yours.