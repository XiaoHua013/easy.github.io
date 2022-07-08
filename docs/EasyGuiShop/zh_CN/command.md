## 权限

##### 需要配置少量权限

# 2.x版本

## 具体权限

| 权限                                           |用途                                           |
|-----------------------------------------------|---------------------------------------------------------|
## 设置商店限制的：

|EasyGuiShop.gui	                            |使用指令/egs gui的权限
|EasyGuiShop.help   	                        |使用指令/egs help的权限
|EasyGuiShop.max.shop.number.1	                |玩家可拥有的最大商店数量,默认为0
|EasyGuiShop.vault.good	                        |玩家创建金币商店的权限，不给不能创建
|EasyGuiShop.max.good.name.length.6	            |玩家商品名字的最大长度，默认为0
|EasyGuiShop.max.good.space.3456   	            |玩家创建的商品的库存容量，默认为0
|EasyGuiShop.max.shop.name.length.6  	        |玩家商店名字的最大长度，默认为0
|EasyGuiShop.max.good.number.90   	            |玩家能在一个商店里创建的商品的数量，默认为0
|-----------------------------------------------|---------------------------------------------------------|
## 选择性给玩家的：

|EasyGuiShop.playerpoints.good	                |玩家创建点券商店的权限，不给不能创建
|-----------------------------------------------|---------------------------------------------------------|
## 只给管理的：

|EasyGuiShop.icon.add	                        |使用指令/egs icon add 图标名字 价格 的权限
|EasyGuiShop.icon.update   	                    |使用指令/egs icon update 图标名字 价格 的权限
|EasyGuiShop.icon.remove  	                    |使用指令/egs icon remove 图标名字 的权限
|EasyGuiShop.good.infinity	                    |使用指令/egs good infinity 商店名字 商品名字 的权限
|EasyGuiShop.good.deinfinity     	            |使用指令/egs good deinfinity 商店名字 商品名字 的权限
|EasyGuiShop.shop.infinity	                    |使用指令/egs good infinity 商店名字 的权限
|EasyGuiShop.shop.deinfinity	                |使用指令/egs good deinfinity 商店名字 的权限
|-----------------------------------------------|---------------------------------------------------------|

## 指令(管理员):

| 指令                                                    | 用途                       |
|----------------------------------------------------|----------------------------------|
|/egs help                                           |查看帮助。
|/egs correctYaml                                    |对所有Yaml进行更正，不会重新载入，请执行后执行reload。
|/egs reload                                         |重新载入。
|/egs openGui                                        |打开界面。
|/egs createIcon <图标名字>                           |增加图标，需要手持物品。
|/egs setIconVaultPrice <图标名字> <价格>             |设置价格。
|/egs setIconItemPrice <图标名字> <价格>              |设置价格，需要手持物品。
|/egs setIconPlayerPointsPrice <图标名字> <价格>      |设置价格。
|/egs setIconExperiencePrice <图标名字> <价格>        |设置价格。
|/egs setIconLimitTime <图标名字> <时间>              |设置限购时间。
|/egs setIconSystem <图标名字> <true|false>           |设置系统补货。
|/egs setShopSystem <商店名字> <true|false>           |设置店铺系统补货。
|/egs setGoodSystem <商店名字> <图标名字> <true|false> |设置商品系统补货。
|/egs setIconName <图标名字> <名字>                   |设置图标名字。
|/egs deleteIcon <图标名字>                          |删除图标。
|/egs plusPopularity <商店名字> <数量>                |增加人气。
|/egs subtractPopularity <商店名字> <数量>            |减少人气。
|----------------------------------------------|-----------------------------------|
|<>为必填参数|

## 指令(玩家):

| 指令                | 用途            |
|---------------------|---------------|
| /你在看什么          | 玩家没有指令     |
| /全程GUI            | 惊不惊喜     |