1. &  让命令在后台运行
```
[root@sqian]# 命令 &
```

2. 查看当前后台运行程序

```
[root@sqian]# jobs
```

3. fg 将后台运行程序放到前台
```
[root@sqian]# fg nums
nums 是jobs的序号
```

4. Ctrl + z 将正在前运行的命令放到后台,并suspend

5. bg 当用Ctrl + z 挂起程序后,可以用bg让程序在后台继续运行
