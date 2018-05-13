WriteUp:

2、TryGetFlag\_02\_D45L2DW.apk

只有一个输入点和一个check按钮，使用爱加密且有反调试，直接DDMS来dump内存来搜索敏感字符串：

```
[Go0s]: ~/Desktop 
➜  strings monkeylord.trygetflag.hprof | grep -i ciscn
(standard input):29685:CISCN{You.Got.It.187d34}
(standard input):29686:CISCN{You.Got.It.187d34}!
(standard input):29693:CISCN{You.Got.It.187d34}
(standard input):29694:CISCN{You.Got.It.187d34}!
```

