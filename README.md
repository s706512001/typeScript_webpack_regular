# typescript_webpack_regular
regular webpack typescript project

### 前置作業

下載專案後先執行

`npm install` 

or

`yarn install`

將專案中需要的 package 安裝進來

### 簡易建置步驟

1. 建立空資料夾，並且用 vscode 開啟這個空資料夾
2. 開啟終端機，輸入指令

  `npm install -D webpack webpack-cli @webpack-cli/generators typescript ts-loader`
  
   安裝 typescript + webpack 相關 plugin
3. 輸入指令

  `npx webpack-cli init`
  
   建立 webpack.config.js
   相關問題回答
   
   ```
   ? Which of the following JS solutions do you want to use? Typescript
   ? Do you want to use webpack-dev-server? No
   ? Do you want to simplify the creation of HTML files for your bundle? No
   ? Which of the following CSS solutions do you want to use? none
   ? Do you like to install prettier to format generated configuration? Yes
   ? Overwrite package.json? overwrite
   ? Overwrite tsconfig.json? 檔案已存在才出現
   ```
   
4. 以下參考修改

   ```
   tsconfig.json
   "target": "es6",
   "module": "ESNEXT",  
   ```
