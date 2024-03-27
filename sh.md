 

# awk

```shell
awk '{ sub(/^ExecStart=.*/,"ExecStart='$pwd'/daemon.fish '$pwd'"); print $0 }' $pwd/aws_daemon.service > tmp && mv tmp  $pwd/aws_daemon.service
```

使用`awk`替换行文本
