# JavaTools

一些Java编写的小工具。

## ~~JBoss~~

JBoss漏洞检测工具。

![](JBoss/单一URL漏洞验证.png)

**<font color=red>目前有问题，暂不放出。</font>**

## Shiro

ShiroScan和ShiroExploit。

### ShiroScan

![ShiroScan.png](Shiro/ShiroScan.png)

### ShiroExploit

![ShiroExploit](Shiro/ShiroExploit-04.png)

![ShiroExploit](Shiro/ShiroExploit-05.png)

## Tools

### DirScan

一款**不太好用**的目录扫描工具，dic里面是字典（模仿的是k8，字典也是k8里面的）。

![](Tools/DirScan.png)



### NameChange

中文名字转拼音。

使用方法

```
java -jar NameChange.jar -f  姓名.txt -m 0 -o result.txt
java -jar -Dfile.encoding=utf-8 NameChange.jar -f  姓名.txt -m 0 -o result.txt//显示在控制台并保存到result.txt中
java -jar -Dfile.encoding=utf-8 NameChange.jar -f  姓名.txt -m 0 //显示在控制台，并保存在当前目录下，保存名字为"姓名_result.txt"
```



以王大锤为例进行转换。

|   方法    |  转换结果  |
| :-------: | :--------: |
|     1     |    wdc     |
|     2     |   wangdc   |
|     3     |  dc.wang   |
|     4     | dacha.wang |
| 0或者其他 | wangdachui |

### WebCheck

根据url查看标题、Server。

![](Tools/WebCheck01.png)



根据IP列表探测端口

![](Tools/WebCheck02.png)

双击是打开，右键是复制到剪贴板。保存位置是当前目录下，格式为csv，方便查看。