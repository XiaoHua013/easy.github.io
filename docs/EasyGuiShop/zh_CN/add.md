### 新增称号指令

> /egs help        查看帮助。
> /egs correctYaml        对所有Yaml进行更正，不会重新载入，请执行后执行reload。
> /egs reload        重新载入。
> /egs openGui        打开界面。
> /egs createIcon <图标名字>        增加图标，需要手持物品。
> /egs setIconVaultPrice <图标名字> <价格>        设置价格。
> /egs setIconItemPrice <图标名字> <价格>        设置价格，需要手持物品。
> /egs setIconPlayerPointsPrice <图标名字> <价格>        设置价格。
> /egs setIconExperiencePrice <图标名字> <价格>        设置价格。
> /egs setIconLimitTime <图标名字> <时间>        设置限购时间。
> /egs setIconSystem <图标名字> <true|false>        设置系统补货。
> /egs setShopSystem <商店名字> <true|false>        设置店铺系统补货。
> /egs setGoodSystem <商店名字> <图标名字> <true|false>        设置商品系统补货。
> /egs setIconName <图标名字> <名字>        设置图标名字。
> /egs deleteIcon <图标名字>        删除图标。
> /egs plusPopularity <商店名字> <数量>        增加人气。
> /egs subtractPopularity <商店名字> <数量>        减少人气。
|<>为必填参数|
#### 商店类型
* **出售**
* **购买**
#### 货币类型分为:
* vault: 金币 
* playerPoints: 点券 
* item: 以物易物

#### 商店描述
* 玩家商店可以在GUI商店给自己的商店添加描述

### 额外注意事项
* <> 的为必填项 
* 

### 例子

1. 使用GUI创建商店
* 使用/egs openGui打开商店界面后
