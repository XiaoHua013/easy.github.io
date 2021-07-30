## 例子
说明:
```
本插件的逻辑是:
1. 首先有了任务目标和任务奖励
2. 然后将多个任务目标和任务奖励组合起来创建出一个任务
3. 任务现在分为俩类,一种npc任务,一种每日任务(1.6.0+)
4. 注意,为了兼容rpg物品,所以请一定要保持手持物品的耐久为满,不然会出现合成了物品但是却任务没+1的问题,那是因为耐久没匹配到
```
假设我们要创建一个任务
任务名称: &f[&e新手任务&f]

要求1: 合成 3个钻石块
要求2: 挖掘10个钻石矿

奖励1: 1个钻石头盔
奖励2: 100金币

步骤一. 新增: 任务目标
```
主手持钻石块输入
/plk addDemand craftItem 3
主手持钻石矿输入
/plk addDemand blockBreak 10
```
步骤二. 新增: 任务奖励
```
主手持钻石头盔输入
/plk addReward itemStack 1
直接输入
/plk addReward vault 100
```

步骤三. 新增每日任务
```
/plk create &f[&e新手任务&f] everyday
```

步骤三. 新增NPC任务(1.6.0+)
```
/plk create &f[&e新手任务&f] npc
```

特别提醒:
```
第一次创建好任务后/plk open中不会有,需要/plk gettoday进获取今日任务
之后每天00:00会自动刷新每日任务(npc任务不会刷新)
```


这样一个任务就完成了,上面的任务目标和任务奖励只要创建了就可以无限的复用.
## 截图说明
[![WXeGxP.png](https://z3.ax1x.com/2021/07/30/WXeGxP.png)](https://imgtu.com/i/WXeGxP)
[![WXe82t.png](https://z3.ax1x.com/2021/07/30/WXe82t.png)](https://imgtu.com/i/WXe82t)
[![WXeQ5d.png](https://z3.ax1x.com/2021/07/30/WXeQ5d.png)](https://imgtu.com/i/WXeQ5d)
[![WXe38I.png](https://z3.ax1x.com/2021/07/30/WXe38I.png)](https://imgtu.com/i/WXe38I)
[![WXe1PA.png](https://z3.ax1x.com/2021/07/30/WXe1PA.png)](https://imgtu.com/i/WXe1PA)
[![WXedaQ.png](https://z3.ax1x.com/2021/07/30/WXedaQ.png)](https://imgtu.com/i/WXedaQ)
[![WXetr8.png](https://z3.ax1x.com/2021/07/30/WXetr8.png)](https://imgtu.com/i/WXetr8)
[![WXeYKf.png](https://z3.ax1x.com/2021/07/30/WXeYKf.png)](https://imgtu.com/i/WXeYKf)
[![WXeNqS.png](https://z3.ax1x.com/2021/07/30/WXeNqS.png)](https://imgtu.com/i/WXeNqS)
[![WXeaVg.png](https://z3.ax1x.com/2021/07/30/WXeaVg.png)](https://imgtu.com/i/WXeaVg)
[![WXeDGn.png](https://z3.ax1x.com/2021/07/30/WXeDGn.png)](https://imgtu.com/i/WXeDGn)
[![WXeBPs.png](https://z3.ax1x.com/2021/07/30/WXeBPs.png)](https://imgtu.com/i/WXeBPs)