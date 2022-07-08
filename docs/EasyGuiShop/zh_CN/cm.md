# 指令
 - "====帮助列表===="
- "/egs help        查看帮助。"
- "/egs correctYaml        对所有Yaml进行更正，不会重新载入，请执行后执行reload。"
- "/egs reloadPlugin        重新载入。"
- "/egs openGui        打开界面。"
- "/egs createIcon <图标名字>        增加图标，需要手持物品。"
- "/egs setIconVaultPrice <图标名字> <价格>        设置价格。"
- "/egs setIconItemPrice <图标名字> <价格>        设置以物易物价格，需要手持物品。"
- "/egs setIconPlayerPointsPrice <图标名字> <价格>        设置点券价格。"
- "/egs setIconStock <图标名字> <数量>        设置图标库存。"
- "/egs setIconLimitTime <图标名字> <时间>        设置图标限购时间。"
- "/egs resetIconLimitTime <图标名字>        重置图标限购时间。"
- "/egs setIconSystem <图标名字> <true|false>        设置图标系统补货。"
- "/egs setShopSystem <商店名字> <true|false>        设置店铺系统补货。"
- "/egs setGoodSystem <商店名字> <图标名字> <true|false>        设置商品系统补货。"
- "/egs setIconName <图标名字> <名字>        设置图标名字。"
- "/egs deleteIcon <图标名字>        删除图标。- "/egs plusShopPopularity <商店名字> <数量>        增加人气。"
- "/egs subtractShopPopularity <商店名字> <数量>        减少人气。"

# 权限
- EasyGuiShop.shopNameLength.6        店铺的名字最长为6，6可以换成别的数字。
- EasyGuiShop.shopAmount.3        一个玩家店铺最多数量3，3可以换成别的数字。
- EasyGuiShop.setGoodVaultPrice        设置金币价格的权限。
- EasyGuiShop.setGoodItemPrice        设置金币价格的权限。
- EasyGuiShop.setGoodPlayerPointsPrice        设置点券价格的权限。
- 除此之外，每个指令对应一个权限，权限为EasyGuiShop.指令名，例如/egs help的权限就为EasyGuiShop.help
