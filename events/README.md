时间页面示例
---------------
使用 background_page, bookmarks, browser_action, experimental, keybinding and tabs
演示了时间页面的应用和特性

##调用:
 - chrome.bookmarks.onRemoved
 - chrome.browserAction.onClicked
 - chrome.browserAction.setBadgeText
 - chrome.experimental.alarms.create
 - chrome.experimental.alarms.onAlarm
 - chrome.experimental.keybinding.onCommand
 - chrome.experimental.runtime.onBackgroundPageUnloadingSoon
 - chrome.experimental.runtime.onInstalled
 - chrome.experimental.webRequest.onRequest
 - chrome.extension.onMessage
 - chrome.extension.sendMessage
 - chrome.tabs.create
 - chrome.tabs.executeScript
 - chrome.tabs.query
 - chrome.tabs.sendMessage

##源文件:
 - background.js
 - content.js
 - manifest.json