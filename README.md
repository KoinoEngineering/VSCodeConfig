# VSCodeConfig
VSCodeConfig

## 拡張機能の出力方法
```
code --list-extensions | xargs -L 1 echo code --install-extension > extentions.sh
```

## 取り込み方法(Mac)
```
sh extentions.sh
```