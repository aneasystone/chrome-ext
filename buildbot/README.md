Chromium Buildbot Monitor
-------------------------
使用 background_page, browser_action, notifications and options_page
显示在工具栏中chromium buildbot的状态。单击可以在弹出菜单中看见更详细的状态

##调用:
 - chrome.browserAction.setBadgeBackgroundColor
 - chrome.browserAction.setBadgeText
 - chrome.browserAction.setTitle
 - chrome.extension.getURL

##源文件:
 - bg.js
 - manifest.json
 - options.html
 - options.js
 - popup.html
 - popup.js