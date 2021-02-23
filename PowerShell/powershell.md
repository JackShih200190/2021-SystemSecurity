## PowerShell
```
Get-Command


```
## Get-ExecutionPolicy
```

Restricted ：關閉腳本檔的執行功能，這是預設的設定值。
AllSigned ：只允許執行受信任發行者簽署過的腳本檔。
RemoteSigned ：在本機電腦所撰寫的腳本檔，不需要簽署就可執行；但是從網際網路（例如：email、MSN Messenger）下載的腳本檔就必須經過受信任發行者的簽署才能執行。
Unrestricted ：任何腳本檔皆可被執行，但是於執行網際網路下載的腳本檔時，會先出現警告的提示視窗。

```
