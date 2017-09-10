---
title: 初探Hexo
categories:
- Hexo
tags:
- Hexo 
---
## Introduction
Hexo 是一個靜態網頁的產生系統，可將`markdown`編譯為`html`，由台灣人[tommy351](https://github.com/tommy351)所開發的
## Before_Instatll
下列是安裝Hexo所需要的相關程式

- `nvm`
	> node版本控制

- `Node.js`
	> Hexo 是由node.js建構而成的

- `yarn` or `npm`
	> package 依賴控管

## Installaion
```sh
	$npm install -g hexo-cli
	//全域安裝 Hexo
	
	// xxx 是專案名稱
	
	//安裝相關依賴
	
```
### 全域安裝 Hexo
```sh
	$npm install -g hexo-cli
```
### 新增專案
```sh
	$hexo init xxxx
```
### 安裝相關依賴
```sh
	$cd xxx
	//進入專案
	$npm install
```
### 啟動local  server
```sh
	$hexo server
	//觀察是否安裝成功
```