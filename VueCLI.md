# Vue.js 腳手架使用指南

本文將介紹如何使用 Vue.js 腳手架來快速建立和開發 Vue.js 應用程序。

## 安裝 Node.js 和 npm

首先，確保你的電腦上已經安裝了 Node.js 和 npm。你可以在 [Node.js 官方網站](https://nodejs.org/) 下載安裝程序並進行安裝。

## 安裝 Vue CLI

Vue CLI 是 Vue.js 的官方腳手架工具，可以幫助你快速搭建 Vue.js 項目。你可以使用 npm 來全局安裝 Vue CLI：

```bash
npm install -g @vue/cli
```

安裝完成後，你就可以使用 `vue` 命令來創建新的 Vue.js 項目了。

## 創建新的 Vue 項目

要創建一個新的 Vue.js 項目，請運行以下命令：

```bash
vue create my-project
```

這將會提示你選擇一個項目配置，你可以根據自己的需求選擇不同的配置。

## 開始開發

當項目創建完成後，你可以進入項目目錄並啟動開發服務器：

```bash
cd my-project
npm run serve
```

這將會啟動一個本地開發服務器，你可以在瀏覽器中訪問 `http://localhost:8080` 來預覽你的 Vue.js 應用程序。

## 編譯和打包

當你完成了開發，你可以使用以下命令來編譯和打包你的應用程序：

```bash
npm run build
```

這將會在 `dist` 目錄下生成編譯後的代碼，你可以將這些代碼部署到你的服務器上。
