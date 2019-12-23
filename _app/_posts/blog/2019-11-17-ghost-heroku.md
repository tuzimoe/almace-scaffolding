---
layout: post
title: Ghost & Heroku
slug: ghost-heroku
date_published: 2019-11-17T14:10:38.000Z
date_updated: 2019-11-17T14:10:43.000Z
tags: 程式
category: programmer
---

用了一哥們的 Deploy Button. Button 一時爽，然後就遇到了問題，如果三十分鐘沒有沒有人訪問博客就會休眠，沒錯我是付費套餐但是還是發生了。所以博客的自定義修改的部分和主題就會消失。所以就會導致 500，所以我就想了一個比較懶得方案呢就是用一個 Status Bot 每 5 分鐘訪問一次博客。嗯。[https://stats.tuzi.moe/](https://stats.tuzi.moe/)

舒服。Heroku 坑多但是省事。
![](https://res-4.cloudinary.com/hypmkhfbk/image/upload/q_auto/v1/ghost-blog-images/500.jpg)  
  
打擾了，sb heroku 並沒有解決這個問題，重構博客 to netlify。 百忙之中 更新於 2019 12 23