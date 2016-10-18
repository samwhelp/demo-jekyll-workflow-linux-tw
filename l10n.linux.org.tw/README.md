
# jekyll workflow / l10n.linux.org.tw

## 基礎專案

* [demo-jekyll-workflow/](https://github.com/samwhelp/demo-jekyll-workflow/)

## 基本使用方法

請參考

* [基礎操作步驟說明](https://github.com/samwhelp/demo-jekyll-workflow/blob/master/README.base.md)
* [整合操作步驟說明](https://github.com/samwhelp/demo-jekyll-workflow/blob/master/README.usage.md)


## 相關網址

* http://l10n.linux.org.tw/
* https://linux-taiwan.github.io/l10n.linux.org.tw
* https://github.com/linux-taiwan/l10n.linux.org.tw
* https://github.com/linux-taiwan/l10n.linux.org.tw/issues


## 主要流程

### git clone

執行下面指令，clone「 https://github.com/linux-taiwan/l10n.linux.org.tw 」下來。

``` sh
$ make clone
```

會產生「blog」這個資料夾。

> 註：
> 若您已經clone「 https://github.com/linux-taiwan/l10n.linux.org.tw 」到你自己的github帳號底下，
> 請先更改「bin/git-clone.sh」
> 修改「 THE_SOURCE_GIT_URL=https://github.com/linux-taiwan/l10n.linux.org.tw.git 」

### 啟動 web server

執行

``` sh
$ make serve
```

### 觀看網頁

然就可以使用瀏覽器來觀看了

``` sh
$ firefox http://localhost:8085
```

或是

``` sh
$ lynx http://localhost:8085
```

### git add

執行

``` sh
$ make add
```

### git commit

執行

``` sh
$ make commit
```

### git push

執行

``` sh
$ make push
```

> 註:
> 關於上面的動作，只是把一些常用的動作定義起來，
> 若需要更細部的操作，請回歸到「git」和「jekyll」這兩個指令的操作。
> 或是利用這樣的模式，寫在「bin」底下，然後編輯「Makefile」，自訂自己常用的動作。
