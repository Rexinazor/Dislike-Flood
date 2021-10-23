# Dislike Flood
Tampermonkey script for mass disliking videos of one channel on youtube.

## Requirements
* [Firefox](https://www.mozilla.org/firefox/new/) [Tampermonkey](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
* [Chrome](https://www.google.com/chrome/) [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)

## Installation
1. After Tampermonkey installed click link: https://github.com/Rexinazor/Dislike-Flood/raw/master/Dislike-Flood.js.
2. Create your own [API key and client id](https://console.cloud.google.com/apis/dashboard) ([guide](https://github.com/1v/dislike-truck/wiki)) and add it here https://github.com/RexinazorDislike-Flood/Dislike-Flood/blob/7943b93e7562f78d030f66e90510b37c726450e1/Dislike-Flood.js#L22-L23.

## Usage

Button "Dislike" starts disliking process. Before process starts you need to choose account in popup window. Your account will be remembered.

<!--- Button "Register" force account choose (you have 15 seconds to choose, otherwise you need to click button again).

You need google account (not youtube account) to get your account remembered. -->

## Bugs

* In console many errors 'no element found'. It's a Firefox bug [bugzilla.mozilla.org](https://bugzilla.mozilla.org/show_bug.cgi?id=884693).
