---
title: 設定 Settings（一）
categories:
- Hexo
tags:
- Hexo
- Github
---
## Introduction

已經能產生基本的部落格架構了，接下來當然是不要在本機上自爽了，利用`Gitgub.io`的靜態網頁，把`Hexo`編譯後的html，部署上去。

----
![Imgur](https://i.imgur.com/TiPy6IR.png)
## main_config
這是指專案下的設定檔
可以設定作者、語系、部署位置等相關設定
講解幾個比較重要的

### Url
這是顯示`Hexo`的路徑，如果你的專案名稱是用`xxx.github.io`，可以忽略不修改。但如果是跟我一樣是用專案的方式去產生，那麼就要在`_config.yml`設定子名稱
```sh
  url: https://github.com/作者/專案名稱
  root:/專案名稱/
```
>  - 修改`URL`的時候，也可以利用本地執行`hexo server`來觀察設定是否成功，`terminal`的提示會更改成我們的設置子路徑
>  - 而`xxx.github.io`  是 `Github`官方幫各帳號預設的靜態網頁

### Deploy

這是指定你的要部署的`Github repository`及部署的分支，並在terminal下`Hexo`指令部署 `hexo deploy`

```sh
deploy:
  type: git
  repo: https://github.com/NoviceDuke/blog.git
  branch: master
```
> - 如果在config 裡面沒有看到此設定，就自行加入即可
> - `hexo deploy` 執行時 可能會詢問git 帳號 直接輸入即可  

### Theme 
這是主題的部分，網路上有許多版本可以`clone`到你的專案下的themes裡面，接下來只要替換成你所`clone`時所指定的名稱即可
> - 許多人推薦Ｎext，支援也滿多的
> - 當然也可以稍微研究，並自行更改

---- 
