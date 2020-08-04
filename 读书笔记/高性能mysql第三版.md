## 第二章 基准测试

mysql做基准测试的重要性，要关注测试指标，用脚本获取测试状态，用脚本执行自动化测试，用脚本分析测试结果文件。

状态获取脚本：

```shell
#!/bin/sh
INTERVAL=5
PREFIX=$INTERVAL-sec-status
RUNFILE=/home/benchmarks/running
mysql -e ' SHOW GLOBAL VARIABLES>> mysql-variables
While test - e RUNFILE: do
fi1e=$(date+%F‰I)
sleep=s (date +%s %N I awk "iprint $INTERVAL-($1 $INTERVAL))")
sleep $sleep
ts="$(date+"Ts‰s.别器‰")"
loadavg="s(uptime)
echo"$ts Sloadavg">>$PREFIX-$file]-status
mysql - SHOW GLOBAL STATUS">>$PREFIX-sffile]-status
cho"ts sloadavg">>$PREFIX-slfile]-innodbstatus
mysql-e 'SHOW ENGINE INNODB STATUS\G>>$PREFIX-$ifile]-innodbstatus
ho" sts sloadavg">>$PREFIX-$(file]-processlist
mysql-e 'SHOW FULL PROCESSLIST\G>>$PREFIX-$file]-processlist
echo $ts
echo Exiting because SRUNFILE does not exist
```

统计计算脚本：

```shell
#!/bin/sh
#This script converts SHow GLOBAL STATUS into a tabulated format, one line
#per sample in the input, with the metrics divided by the time elapsed
#between sample
awk '
BEGIN {
printf #ts date time load QPS
fmt="‰2f";
}
/ TS/I# The timestamp lines begin with TS
substr ($2, 1, index($2
NF -2
diff =ts- prev ts;
printf "\n%s %6s%s %s", ts,$3, $4, substr(sload, 1, length($load)-1);
printf fmt,($2-Queries)/diff
Queries=$2
}
' "$@"
```

### 基准测试工具



## 第五章 创建高性能索引

1. 索引存放在存储引擎层，所以MyISAM和InnoDB以及Memory引擎会实现各自的索引方式。

   

   

