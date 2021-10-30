# sk5short-one
![](https://img.shields.io/github/v/release/sk5s/sk5short-one)
![](https://img.shields.io/github/last-commit/sk5s/sk5short-one)
![](https://img.shields.io/github/license/sk5s/sk5short-one)
![](https://img.shields.io/github/languages/top/sk5s/sk5short-one)

sk5short-one make a short link just in a minutes, use javascript to redirect but in one file.

用簡易的方式製作短連結(one版本)
還有單連結share版本 sk5short

## 簡易使用教學(github page)
1. 點Use this template
2. 選取你的帳號或組織(Owner)
3. 輸入repo name(將影響縮短的連結名稱)
4. 免費github帳戶需選擇public
5. create from template
6. 修改index.html
7. 短連結設定
找到：

```javascript
let book = {
  'test' : 'https://lab.sk5s.cyou/',
  'hcsc' : 'https://hcsc-25th.github.io/'
}
```
變數book儲存所有短語所對應到的轉址連結
例如：`'test' : 'https://lab.sk5s.cyou/',`代表訪問 `.../index.html?r=test` ，會自動用javascript轉址到`https://lab.sk5s.cyou/`
用json的格式，可以自由增加。

8. 修改預設連結
找到：

```javascript
let defaultLink = 'https://www.sk5s.cyou/'
```
將括號中的字換成您想要的預設連結，連結錯誤將會轉到預設連結

9. commit
10. 從橫的導覽列到Setting -> Pages，source選擇main，save
11. 複製上方顯示的提示連結 ` Your site is ready to be published at ...`，直接前往會被轉至預設連結
12. 假設book設定為
```javascript
let book = {
  'test' : 'https://lab.sk5s.cyou/',
  'hcsc' : 'https://hcsc-25th.github.io/'
}
```
前往 `{步驟11取得的網址}?r=hcsc`，將會轉址到`https://hcsc-25th.github.io/`

## 完成啦

```
     _    ____                        _           _   
 ___| | __ ___| ___   _ __  _ __ ___ (_) ___  ___| |_ 
/ __| |/ /___ \/ __| | '_ \| '__/ _ \| |/ _ \/ __| __|
\__ \   < ___) \__ \ | |_) | | | (_) | |  __/ (__| |_ 
|___/_|\_\____/|___/ | .__/|_|  \___// |\___|\___|\__|
                     |_|           |__/               
```
