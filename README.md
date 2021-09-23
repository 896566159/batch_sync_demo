# 功能

通过kettle实现批量异库同步任务



# 模块

## kettle_batch_test.kjb

执行任务的作业

## get.ktr

负责获取需要同步的表名

### tb.txt

保存需要同步表名的txt文件

## push.ktr

1. 清空ODS表
2. 读取目标表
3. 写入ODS表