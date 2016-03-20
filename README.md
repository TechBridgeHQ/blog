# TechBridge 技術共筆部落格
這是個由 TechBridge Weekly 技術週刊團隊維護的技術部落格，本技術共筆部落格初期專注於Web前後端、行動網路、機器人/物聯網、數據分析與產品設計等技術分享。This is TechBridge Weekly Team's Tech Blog, which focus on web, mobile, robot, IoT, data analytics technology sharing. 

- 技術共筆部落格：[http://blog.techbridge.cc/](http://blog.techbridge.cc/)
- 技術日報：[http://www.techbridge.cc/](http://www.techbridge.cc/)
- 技術週刊：[http://weekly.techbridge.cc/](http://weekly.techbridge.cc/)
- 粉絲專頁：[https://www.facebook.com/TechBridge.Fans/](https://www.facebook.com/TechBridge.Fans/)

## Contribute（分成 hexo 原始檔和已完成編譯的 .html 靜態檔案）
1. `$ npm install -g hexo-cli`
2. `$ git clone https://github.com/TechBridgeHQ/blog-starter-kit.git`
3. `$ npm install`
4. 寫新文章 `$ hexo new post <title>`，在 source > _post 資料夾下開始使用 Markdown 撰寫文章（寫靜態檔案為 new page、草稿：new draft）
5. 重新 compile 一次，將 .md 檔案轉成 .html 等靜態檔案 `$ hexo g `
6. 在本地端(http://localhost:4000)觀看效果 `$ hexo s`，（若遇到問題請多 `$ hexo g ` compile 幾次）
7. 確認無誤後 `$ git status` ，看是否有要 `$ git add 檔案`，若無則 `$ git commit -a -m your_commit`，先 `$ git pull` 再 `$ git push origin`
8. 上傳成功後，Deploy `$ hexo d` 到正式站點
9. 至 [http://blog.techbridge.cc](http://blog.techbridge.cc) 看是否正確

PS. 口訣先 git push，再 hexo deploy

## Format（文章格式）
```
---
title: Caffe & GoogLeNet，怎麼幫助機器人更好地辨識物體
date: 2016-03-19 10:54:49
tags: 機器人, 深度學習, Deep Learing, Robot, GoogLeNet, Caffe
author: pojenlai
---
以下文章內容
XXXXX

以下請關於作者先自己加上，之後會轉成自動生成：
關於作者： 
@pojenlai 演算法工程師，對機器人跟電腦視覺有少許研究，最近在鍛鍊自己的執行力

```

## Documents
1. [使用GitHub和Hexo搭建免费静态Blog](http://wsgzao.github.io/post/hexo-guide/)
2. [Hexo常见问题解决方案](https://xuanwo.org/2014/08/14/hexo-usual-problem/)
3. [Hexo 安裝教學、心得筆記](https://wwssllabcd.github.io/blog/2014/12/22/how-to-install-hexo/)

## 目前負責的 Curator（歡迎有興趣朋友跳坑加入策展人團隊:P）
1. [@kdchang](http://blog.kdchang.cc) 文藝型開發者，夢想是做出人們想用的產品和辦一所心目中理想的學校
2. [@arvinh](http://cv.arvinh.info) 前端攻城獅，熱愛數據分析和資訊視覺化
3. [@huli](http://huli.logdown.com) 野生工程師，相信分享與交流能讓世界變得更美好
4. [@pojenlai](https://pojenlai.wordpress.com/) 演算法工程師，對機器人跟電腦視覺有少許研究，最近在鍛鍊自己的執行力
