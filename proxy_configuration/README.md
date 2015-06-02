代理服务器扩展API示例
---------------------
使用 background_page, browser_action and proxy
设置了chrome特定的代理服务器，展示了chrome代理服务器API

##调用:
 - chrome.browserAction.setBadgeBackgroundColor
 - chrome.browserAction.setBadgeText
 - chrome.browserAction.setTitle
 - chrome.extension.isAllowedIncognitoAccess
 - chrome.i18n.getMessage
 - chrome.proxy.onProxyError

##源文件:
 - _locales/en/messages.json
 - background.js
 - manifest.json
 - popup.css
 - popup.html
 - popup.js
 - proxy_error_handler.js
 - proxy_form_controller.js
 - test/jsunittest.js
 - test/proxy_form_controller_test.html
 - test/proxy_form_controller_test.js
 - test/unittest.css