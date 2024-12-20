# 检查超卖的方法

## 内存超卖

使用Java占用内存进行测试，对比申请前后的failcnt是否非零，以及两个内存页数值是否同步变化，来判断是否用了swap作内存使用

```bash
root@vps115535:~# cat /proc/user_beancounters | grep -E '(uid|physpages|oomguarpages)'
       uid  resource                     held              maxheld              barrier                limit              failcnt
            physpages                  612712              3303667              4194304              4194304                    0
            oomguarpages               612712              3303667                    0                    0                    0
```

