Chrome的FirePHP
---------------
使用 background_page, devtools_page and tabs
扩展开发者工具，增加了对从服务器解析FirePHP信息的支持

##调用:
 - chrome.devtools.network.getHAR
 - chrome.devtools.network.onRequestFinished
 - chrome.tabs.executeScript

##源文件:
 - background.js
 - devtools.html
 - devtools.js
 - manifest.json