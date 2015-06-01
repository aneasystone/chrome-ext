Live HTTP headers
----------------
使用 background_page, browser_action, debugger and tabs
通过HTTP请求报头显示动态的的log

##调用:
 - chrome.browserAction.onClicked
 - chrome.debugger.attach
 - chrome.debugger.detach
 - chrome.debugger.onEvent
 - chrome.debugger.sendCommand
 - chrome.tabs.get
 - chrome.windows.create
 - chrome.windows.get
 - chrome.windows.getCurrent

##源文件:
 - background.js
 - headers.html
 - headers.js
 - manifest.json