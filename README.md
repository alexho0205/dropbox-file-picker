# dropbox-file-picker

提供用戶在檔案上傳時,使用dropbox

## 如何運行專案

1. 在 dropbox 申請應用程式並取得 appkey 　https://www.dropbox.com/developer
1. 編輯 index.html 將 appkey 填入 ``` <script type="text/javascript" src="https://www.dropbox.com/static/api/2/dropins.js" id="dropboxjs" data-app-key="xxxxxxxxxxxx"></script>```
1. 使用 node 將 index.html 運行於 http://localhost:5000
``` node server.js ```
