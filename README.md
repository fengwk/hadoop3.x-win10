# hadoop3.x-win10

由于Hadoop设计运行在Linux系统中，因此在Windows中执行hadoop-client会出现问题，需要使用winutil.exe模拟相应环境。这里提供一套hadoop3.x-win10的可用运行环境，已在`3.2.0`与`3.3.1`中正常工作，其它版本请自行试验。

# 如何使用

1、使用管理员身份打开CMD

2、获取当前项目

```shell
cd C:\Program Files
git clone git@github.com:fengwk/hadoop3.x-win10.git
```

3、配置环境变量

- `HADOOP_HOME`为`C:\Program Files\hadoop3.x-win10\hadoop-3.x`

- `PATH`追加`%HADOOP_HOME%\bin`

