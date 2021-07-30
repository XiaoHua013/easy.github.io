击杀mm怪物说明:
```
1. 击杀任务只支持 MythicMobs 怪物  或  普通怪物
2. 一个击杀任务目标只能选择一个 MythicMobs 怪物 或  普通怪物
3. 一个任务是多个任务目标组合而成
```

# 击 MythicMobs 怪物 示例
## 第一种方式: 使用gui创建
假设我们要创建一个任务目标- 击杀5只僵尸王

步骤一. 添加击杀任务,击杀数量要求5
```
/plk addDemand kill 5
```
步骤二,看下图,根据打开的gui选择即可

## 第二种方式:使用指令直接创建
假设我们还是要创建一个任务目标- 击杀5只僵尸王

步骤一. 添加击杀任务,击杀数量要求5
```
/plk addDemand kill 5 SkeletalKnight
```
完成

# 击 普通怪物 示例(根据怪物类型来进行判断)
## 击杀普通怪物任务

步骤一. 添加击杀任务,击杀僵尸 数量要求1 具体的怪物名称自己去看wiki
```
/plk addDemand killNormal 1 Zombie
```