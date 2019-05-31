# MyPublicIP
> simple website to continuously (every 5 seconds) display current Public IP

> Use your (desktop or mobile) browser with https://PublicIP.netlify.com


[![Netlify Status](https://api.netlify.com/api/v1/badges/a702c733-d58d-4ed8-95ac-f34ac1186654/deploy-status)](https://app.netlify.com/sites/publicip/deploys)



## How it behave?
* Display your IP in descending order.
* Display timestamp (last check for IP) in descending order
* Get PublicIP information from https://api.ipify.org/
* Use zepto for DOM manipulation (because it is jQuery compatible API). Use local zepto.js for same domain request, faster
* support displaying `OFFLINE` state


## Develop, build and deploy note
Change code. Push to `master` branch on Github to trigger auto deploy with Netlify site.
