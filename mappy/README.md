Mappy
------------
使用 background_page, page_action and tabs
发现当前页面中含地址的信息并弹出一个地图窗口

##调用:
 - chrome.extension.getBackgroundPage
 - chrome.pageAction.hide
 - chrome.pageAction.setTitle
 - chrome.pageAction.show
 - chrome.tabs.get
 - chrome.tabs.onUpdated

##源文件:
 - background.js
 - manifest.json
 - mappy_content_script.js
 - popup.css
 - popup.html
 - popup.js