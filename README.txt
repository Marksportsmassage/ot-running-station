操作治療跑台考試網頁 - 修正版

檔案說明
1. index.html
   網頁主檔。上傳到 GitHub repository 根目錄。

2. data.js
   20 題講稿資料。一般不用改。

3. videos.js
   影片連結與時間碼填寫檔。你整理影片時主要改這個。

4. 影片連結填寫表.csv
   給你整理影片用的表格。可用 Excel / Google 試算表打開。

影片填寫方式
打開 videos.js，找到題號，例如：

"1": {
  "url": "",
  "start": "",
  "end": "",
  "note": ""
}

改成：

"1": {
  "url": "https://youtu.be/xxxx",
  "start": "00:10",
  "end": "00:45",
  "note": "肩膀往上舉 PROM"
}

更新 GitHub
1. 到 GitHub repository
2. Add file -> Upload files
3. 上傳 index.html、data.js、videos.js 覆蓋原本檔案
4. Commit changes
5. GitHub Pages 會自動更新

重要提醒
YouTube 不公開影片只是不會被搜尋到；拿到連結的人仍可觀看與分享。
