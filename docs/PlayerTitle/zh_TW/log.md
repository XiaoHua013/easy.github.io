## 版本信息

### 已知bug(目前知道但是未解決的bug會統一顯示在這裏)
> 一. 插件不推薦使用yum這類插件進行熱加載！！！  
> 二. 1.x版本升級到2.x版本註意(使用sqlite存儲的 )！！！   
> 請先把playerTitle.db文件名修改為PlayerTitle.db在進行升級

------------
#### 2.10.8
**2022年03月19日**
1. **優化** 變量現在支持顯示離線玩家的了

#### 2.10.8更新小助手
- 配置文件對比2.10.7版本無變化，直接替換jar即可

#### 2.10.7
**2022年02月04日**
1. **優化** 適配PlayerIntensify強化插件1.1.2+版本

#### 2.10.7更新小助手
- 配置文件對比2.10.6版本無變化，直接替換jar即可

#### 2.10.6
**2022年02月04日**
1. **修復** 使用sqlite會報錯的問題

#### 2.10.6更新小助手
- 配置文件對比2.10.5版本無變化，直接替換jar即可

#### 2.10.5
**2022年02月03日**
1. **修復** 使用mmoItems作為buff的時候有時候打開gui異常

#### 2.10.5更新小助手
- 配置文件對比2.10.4版本無變化，直接替換jar即可

#### 2.10.4
**2022年01月04日**
1. **修復** 使用多種附屬粒子插件時候粒子效果報錯

#### 2.10.4更新小助手
- 配置文件對比2.10.3版本無變化，直接替換jar即可

#### 2.10.3
**2022年01月03日**
1. **優化** 有的人提醒連接服務器異常的問題

#### 2.10.3更新小助手
- 配置文件對比2.10.2版本無變化，直接替換jar即可

#### 2.10.2
**2022年01月02日**
1. **優化** 在config 關閉isEnableBuff配置後,不在觸發清除buff事件

#### 2.10.2更新小助手
- 配置文件對比2.10.1版本無變化，直接替換jar即可

#### 2.10.1
**2021年12月30日**
1. **優化** 新增更多api,具體查看javadoc

#### 2.10.1更新小助手
- 配置文件對比2.10.0版本無變化，直接替換jar即可

#### 2.10.0
**2021年12月28日**
1. **優化** api恢復之前版本刪除的類型

#### 2.10.0更新小助手
- 配置文件對比2.9.9版本無變化，直接替換jar即可

#### 2.9.9
**2021年12月27日**
1. **新增** 移除重設玩家buff 的api，具體查閱 [**api文檔**](PlayerTitle/zh_TW/api)

#### 2.9.9更新小助手
- 配置文件對比2.9.8版本無變化，直接替換jar即可

#### 2.9.8
**2021年12月15日**
1. **修復** 藥水buff在重生後不會生效

#### 2.9.8更新小助手
- 配置文件對比2.9.7版本無變化，直接替換jar即可

#### 2.9.7
**2021年12月07日**
1. **修復** 修復稱號卡的lore不支持rgb顏色問題

#### 2.9.7更新小助手
- 配置文件對比2.9.6版本無變化，直接替換jar即可

#### 2.9.6
**2021年12月04日**
1. **修復** 修復為了適配1.18導致低版本tab報錯的bug

#### 2.9.6更新小助手
- 配置文件對比2.9.5版本無變化，直接替換jar即可

#### 2.9.5
**2021年12月02日**
1. **優化** 更好的適配1.18

#### 2.9.5更新小助手
- 配置文件對比2.9.4版本無變化，直接替換jar即可

#### 2.9.4
**2021年12月01日**
1. **優化** 更好的適配1.18
2. **優化** 現在buff中的怪物免戰可以設置生效世界了 

> /plt setTitleBuff 1 monster_truce world  
指令最後一個參數為生效世界名  
不傳最後一個參數默認全部世界生效

#### 2.9.4更新小助手
- 配置文件對比2.9.3版本無變化，直接替換jar即可

#### 2.9.3
**2021年11月18日**
1. **修復** 修復color.yml配置無效的bug

#### 2.9.3更新小助手
- 配置文件對比2.9.2版本無變化，直接替換jar即可

#### 2.9.2
**2021年11月16日**
1. **修復** 某些情況，稱號和介紹會顯示出顏色代碼來
2. **修復** 在mysql情況下添加buff，字段長度不夠導致報錯

#### 2.9.2更新小助手
- 配置文件對比2.9.1版本無變化，直接替換jar即可

#### 2.9.1
**2021年11月4日**
1. **修復** 2.9.0版本的/plt adminShop無法打開
2. **優化** buff處理部分代碼

#### 2.9.1更新小助手
- 配置文件對比2.9.0版本無變化，直接替換jar即可

#### 2.9.0
**2021年10月21日**
1. **新增** 添加 ${player} 做為gui中玩家名變量
2. **優化** 添加 前置粒子效果PlayerParticles漢化文本

#### 2.9.0更新小助手
- 配置文件對比2.8.8版本語言文件有變化
- 直接替換jar即可

#### 2.8.8
**2021年10月21日**
1. **修復** item.yml漢化處理不會在沖突掉雲漢化了
2. **新增** 新增bStats統計內容

#### 2.8.8更新小助手
- 配置文件對比2.8.7版本無任何變動, 直接替換jar即可

#### 2.8.7
**2021年10月14日**
1. **修復** /plt set 指令在開啟自動使用稱號後的報錯

#### 2.8.7更新小助手
- 配置文件對比2.8.6版本無任何變動, 直接替換jar即可

#### 2.8.6
**2021年10月10日**
1. **修復** MMOItems類型buff,在稱號過期後buff不會消失
2. **優化** 權限稱號過期相關優化處理

#### 2.8.6更新小助手
- 配置文件對比2.8.5版本無任何變動, 直接替換jar即可

#### 2.8.5
**2021年09月29日**
1. **修復** 2.8.4版本 取消使用稱號 buff不會 正常消失的問題

#### 2.8.5更新小助手
- 配置文件對比2.8.4版本無任何變動
- 直接替換jar即可

#### 2.8.4
**2021年09月29日**
1. **優化** 現在開發buff類型api，外部插件可以註入自定義buff
2. **修復** 權限稱號不正常過期問題，現在修改為定時處理
3. **修復** 一些語言提醒不存在的問題

#### 2.8.4更新小助手
- 配置文件對比2.8.2版本無任何變動
- 直接替換jar即可

#### 2.8.3
**2021年09月18日**
1. **新增** 支持稱號，稱號商城，稱號倉庫按鈕，稱號卡模型自定義 [**自定義模型支持**](PlayerTitle/zh_TW/resourcepacks)
2. **新增** 對粒子插件PlayerParticles兼容
3. **優化** 部分地區啟動提醒網絡錯誤

#### 2.8.3更新小助手
- 語言文件有變動，建議刪除舊語言文件生成新的即可
- material.yml有巨大改進，請務必重新生成
- 然後替換jar即可

#### 2.8.2
**2021年09月13日**
1. **修復**  切換稱號後，稱號buff變量不變更的問題
2. **新增** 稱號buff兼容MMOItems
3. **優化** 一些api優化具體查閱 [**api文檔**](PlayerTitle/zh_TW/api)

#### 2.8.2更新小助手
- 配置文件對比2.8.1版本無任何變動
- 語言文件有變動，建議刪除舊語言文件生成新的即可
- 直接替換jar即可

#### 2.8.1
**2021年08月18日**
1. **修復** 熱加載插件導致名字前面多個null
2. **修復** 一個bug(因為公布出來會導致玩家知道，所以不公布，但是bug影響惡劣，請使用了物品兌換稱號的腐竹務必升級)

#### 2.8.1更新小助手
- 語言文件新增內容,請務必重新生成新的

#### 2.8.0
**2021年08月8日**
1. **新增** 自定義稱號長度限製
2. **優化** 現在權限類型稱號,在權限取消後重新登錄對應的權限稱號也會消失
3. **優化** 新增稱號現在會返回稱號id在聊天裏
4. **新增** 新增刪除稱號指令/plt del [稱號id]
5. **優化** api優化,歡迎開發者對接

#### 2.8.0更新小助手
- 語言文件和config文件有新增內容,請務必備份之前的然後重新生成新的

#### 2.7.9
**2021年07月26日**
1. **新增**  現在1.17物品會正常漢化了
2. **新增** 提供api,可以讓其他插件對接了,具體查看 [api文檔](PlayerTitle/zh_TW/api)
   首個開始對接的可以聯系我提供技術指導支持

#### 2.7.9更新小助手
- 配置文件對比2.7.8版本無任何變動,直接替換jar即可

#### 2.7.8
**2021年07月19日**
1. **新增**  /plt addCustom 指令，用於添加稱號自定義次數
2. **修復** 兼容ap的時候可以使用顏色代碼&
3. **修復** /plt adminShop裏分頁不正常顯示

#### 2.7.8更新小助手
- 語言文件新增內容，請刪除語言文件重新生成

#### 2.7.7
**2021年07月18日**
1. **優化**  iaTab使用新方法,
2. **修復** 大概率會修復之前的isTab跟計分板沖突
3. **修復** 關閉isTab後稱號前綴不會消失的問題
4. **修復** 稱號長度在小於1.13的情況下默認截取為最長16位,在大於等於1.13的時候默認截取為64位

#### 2.7.7更新小助手
- 配置文件對比2.7.6版本無任何變動,直接替換jar即可

#### 2.7.6
**2021年07月15日**
1. **優化** 現在會使用真實玩家名進行稱號數量排行榜顯示了
2. **新增** 現在稱號商城的下面的搜索條件按鈕可以通過material.yml 來進行配置了
3. **優化** 現在描述能換行了, 只需要 在內容中加英文 , 進行分割就行,中文，不會進行分割
> 例如  這是第一行描述,這是第二行描述
4. **修復** 低版本mysql兼容性調整
5. **修復** 在/plt adminshop中進行稱號修改材質和其他內容的時候聊天欄提醒正常顯示
6. **新增** 現在可以進行玩家自定義稱號了
> /plt custom [稱號名稱]	設置自定義稱號gui
/plt setCustom [玩家名稱] [可自定義次數]	設置玩家可以自定義的次數
7. **修復** isTab開啟後稱號過長的導致崩潰的問題（不建議設置超過16位的稱號）
8. **修復** 修復sx3.x版本 使用&1顏色代碼 這個1也算入屬性的問題
9. **新增** 倆個變量
> 玩家可自定義次數%playerTitle_custom_num%
玩家已自定義次數%playerTitle_custom_usenum%

#### 2.7.6更新小助手
- 語言文件有點小變化,建議重新生成
- material.yml文件有變化,建議備份之前的,然後重新生成

#### 2.7.4
**2021年06月30日**
1. **修復**  plt convert sqllite 指令的異常

#### 2.7.4更新小助手
- 配置文件對比2.7.3版本無任何變動,直接替換jar即可

#### 2.7.3
**2021年06月29日**
1. **修復**  plt convert mysql 指令的異常

#### 2.7.3更新小助手
- 配置文件對比2.7.2版本無任何變動,直接替換jar即可

#### 2.7.2
**2021年06月26日**
1. **優化** 現在一個插件同時兼容sx2.x版本和3.x版本了

#### 2.7.2更新小助手
- 配置文件對比2.7.1版本無任何變動,直接替換jar即可

#### 2.7.1
**2021年06月24日**
1. **優化** 現在不要求5.7+mysql了，兼容到mysql低版本了(親測5.5版本還有問題,會在2.7.5版本徹底兼容)

#### 2.7.1更新小助手
- 配置文件對比2.7.0版本無任何變動,直接替換jar即可(請仔細看2.7.0的更新日誌)

#### 2.7.0
**2021年06月23日**
1. **新增**  指令/plt convert mysql(轉換sqlite的數據到mysql中)
2. **新增**  指令/plt convert sqlite(轉換mysql的數據到sqlite中)
> 請盡量選擇沒人玩家在線的情況下進行轉換，並在執行完轉換操作後重啟服務器
3. **新增** 新增是否開啟稱號buff功能（用於一些子服不想要buff）

#### 2.7.0更新小助手
- 語言文件新增內容，可以自己加到helps節點下，或者刪除語言文件重新生成
```
"&e/plt convert  [類型]     &f轉換數據，類型可選mysql或者sqlite"
```

- config.yml中新增，可以自己加到config.yml中，或者刪除配置文件重新生成
```
# 是否開啟稱號buff功能，可選true/false。true情況下，稱號buff會正常加載，false情況下，稱號buff全部無效(可用於一些大廳服或者特殊rpg服)
isEnableBuff: true
```

#### 2.6.0
**2021年06月13日**
1. **新增** 兼容1.17版本

#### 2.6.0更新小助手
- 配置文件對比2.5.8版本無任何變動,直接替換jar即可

#### 2.5.8
**2021年05月22日**
1. **修復** 在開啟了自動使用稱號後mysql有的版本會產生的異常報錯
1. **修復** 有的奇怪核心稱號卡使用報錯的問題

#### 2.5.8更新小助手
- 配置文件對比2.5.7版本無任何變動,直接替換jar即可

#### 2.5.7
**2021年05月10日**
1. **新增**  新增獲取稱號後自動使用配置

#### 2.5.7更新小助手
- 配置文件對比2.5.6有變化,config中新增下面內容,可以自己復製加進去,或者刪除config重啟服務器重新自動生成
```
# 是否開啟自動使用, 可選true/false。true情況下，玩家獲取到新稱號會放到倉庫並自動使用,false情況下，玩家獲取到新稱號只會放到倉庫不會自動使用
isAutoUse: false
```

#### 2.5.6
**2021年05月5日**
1. **優化** 現在兼容 PlayerPoints-3.0.1 版本了[點券插件原帖](https://www.spigotmc.org/resources/playerpoints.80745/ "點券插件新地址")

#### 2.5.6更新小助手
- 配置文件對比2.5.5版本無任何變動,直接替換jar即可

#### 2.5.5
**2021年04月20日**
1. **新增** 全局buff功能
2. **新增** 兼容強化插件PlayerIntensify [強化插件介紹wiki](https://www.showdoc.com.cn/PlayerIntensify?page_id=6670125914381777 "強化插件介紹wiki")
2. **修復** 異步移除藥水效果引起的報錯

#### 2.5.5更新小助手
- 配置文件對比2.5.4版本變動如下

config.yml新增- 可以刪除讓重新生成或者復製下面內容到最後面
```
# 是否開啟全局倉庫buff，可選true/false。true情況下，玩家背包的所有稱號的buff都會加載，false情況下，只會加載玩家佩戴的稱號buff
isAllBuff: false
```
language中的語言文件新增- 可以刪除讓重新生成或者手動添加
```
# PlayerIntensify提醒
playerIntensifySucceedMsg: "&a成功加載PlayerIntensify,啟用玩家強化相關功能!"
playerIntensifyFailureMsg: "&4未找到PlayerIntensify,未啟用玩家強化相關功能!"

setTitleBuff:
  playerIntensify: "&a強化效果"
```
#### 2.5.4
**2021年03月15日**
1. **優化** 優化部分代碼
2. **修復** 在amdinshop中不能將其他購買條件的轉換為權限購買條件

#### 2.5.4更新小助手
- 配置文件對比2.5.3版本無任何變動,直接替換jar即可

#### 2.5.3
**2021年02月13日**
1. **修復** 低版本使用原版物品當作提交條件報錯
2. **修復** 現在會清空緩存了(重要更新)
3. **新增** 現在切換稱號可以設置冷卻時間了

#### 2.5.3更新小助手
- 配置文件對比2.5.2版本變動如下

config.yml新增- 可以刪除讓重新生成或者復製下面內容到最後面
```
# 切換稱號的冷卻時間,單位秒 -設置0為關閉該功能
togglesCoolDown: 10
```
language中的語言文件新增- 可以刪除讓重新生成或者復製下面內容到open節點下任意位置
```
open:
  togglesCoolDownMsg: "&4冷卻時間未到,請在${time}秒後切換"
```

#### 2.5.2
**2021年02月10日**
1. **修復** 獲取稱號卡有的時候報錯

#### 2.5.2更新小助手
- 配置文件對比2.5.1版本無任何變動,直接替換jar即可

#### 2.5.1
**2021年02月10日**
1. **優化** 不在限製tab稱號的顯示長度了.

#### 2.5.1更新小助手
- 配置文件對比2.5.0版本無任何變動,直接替換jar即可

#### 2.5.0
**2021年02月09日**
1. **新增** 修復極低概率權限稱號打不開/plt adminshop的問題

#### 2.5.0更新小助手
- 配置文件對比2.4.9版本無任何變動,直接替換jar即可

#### 2.4.9
**2021年02月07日**
1. **新增** 1.16+服務器 稱號支持RGB16位顏色了,新增了color.yml配置文件

#### 2.4.9更新小助手
- 配置文件對比2.4.8版本無任何變動,直接替換jar即可

#### 2.4.8
**2021年02月07日**
1. **新增** 刪除單行buff的指令/plt delBuff [buffId]
   buffId 可以在/plt adminshop中查看

#### 2.4.8更新小助手
- languages中的語言文件也有新增相關語言內容,建議如果沒改過就刪除重新生成

#### 2.4.7
**2021年02月04日**
1. **優化** 兼容ap3.x 版本

#### 2.4.7更新小助手
配置文件對比2.4.6版本無任何變動,直接替換jar即可

#### 2.4.6
**2021年02月04日**
1. **新增** 可自定義獲取稱號後的提醒消息
   如何使用: 新增了配置文件 message.yml 自己點開看吧,註釋很清楚

#### 2.4.6更新小助手
配置文件對比2.4.5版本無任何變動,直接替換jar即可

#### 2.4.5
**2021年02月02日**
1. **新增** 可自定義商城中稱號的物品材質
   如何使用: 新增了配置文件 material.yml 自己點開看吧,註釋很清楚
   [物品材質幫助網址](https://minecraft-ids.grahamedgecombe.com/ "物品材質幫助網址")

#### 2.4.5更新小助手
配置文件對比2.4.4版本無任何變動,直接替換jar即可

#### 2.4.4
**2021年01月28日**
1. **優化** 優化一些稱號lore顯示的功能

#### 2.4.4更新小助手
配置文件對比2.4.3版本無任何變動,直接替換jar即可

#### 2.4.3
**2021年01月14日**
1. **優化** 優化一些低版本導致的漏洞,強烈推薦升級

#### 2.4.3更新小助手
配置文件對比2.4.2版本無任何變動,直接替換jar即可

#### 2.4.2
**2021年01月12日**
1. **新增** 添加了/plt listTitle 用來指令查看稱號id
2. **新增** 添加了/plt adminShop 用來查看管理稱號gui,效果等同/plt view shop

#### 2.4.2更新小助手
有點語言文件的相關提醒添加,可重新生成語言文件或者手動加入下面的語言文件
```java
listTitle:
  # 查詢玩家稱號列表顯示的標題
  titleList: "&e&m一一一一一一一&f[&e全部稱號列表§f]&e&m一一一一一一一"
  # 沒有找到玩家數據
  noTitleFailureMsg: "&a服務器目前沒有稱號"
  # 數字格式錯誤
  titleIdFailureMsg: "&4頁數只能為數字"
  id: "&a序號: "
  titleName: "&a稱號名: "
  buyType: "&a購買類型: "
  amount: "&a金額: "
  number: "&a數量: "
```

#### 2.4.1
**2020年12月15日**
1. **新增** 添加cstats統計

#### 2.4.1更新小助手
配置文件對比2.4.0版本無任何變動,直接替換jar即可

#### 2.4.0
**2020年11月27日**
1. **優化** 修復一些說了你也不懂的bug,並優化代碼

#### 2.4.0更新小助手
配置文件對比2.3.9版本無任何變動,直接替換jar即可

#### 2.3.9
**2020年11月23日**
1. **修復** 稱號卡可以副手使用導致的刷稱號bug,現在改為只能主手使用稱號卡了

#### 2.3.9更新小助手
配置文件對比2.3.8版本無任何變動,直接替換jar即可

#### 2.3.8
**2020年10月15日**
1. **修復** 群組服切換服稱號緩存未清理
2. **修復** 1.13以下版本tab報錯失效的問題

#### 2.3.8更新小助手
配置文件對比2.3.7版本無任何變動,直接替換jar即可

#### 2.3.7
**2020年10月13日**
1. **修復** 稱號描述的變量 %playerTitle_description% 不顯示
2. **新增** 稱號buff的變量(多個buff會,隔開) %playerTitle_buff%
3. **新增** 稱號粒子的變量 %playerTitle_particle%
4. **修復** sqlite生成表錯誤

#### 2.3.7更新小助手
對比2.3.6版本,無任何配置變動,直接替換jar,如果是更早版本,請看之前更新小助手

#### 2.3.6
**2020年10月13日**
1. **優化** 現在一個同樣的稱號給予玩家不同時間會疊加了,
   例如先給玩家稱號A-3天,然後在給玩家稱號A-5天,那麽這個稱號A的到期時間應該是8天

#### 2.3.6更新小助手
語言文件有更新,建議刪除languages文件夾讓重新生成

#### 2.3.5
**2020年10月12日**
1. **修復** 頭頂稱號和tab稱號現在會變化了

#### 2.3.5更新小助手
請務必看2.3.4的更新內容

#### 2.3.4
**2020年10月12日**
1. **新增** 現在新增稱號類型 -活動(這種類型會展示在稱號商城,但是玩家無法購買,只能看,使用指令或者稱號卡賦予玩家)
2. **新增** 稱號描述, 現在可以對稱號進行描述了,建議一句簡短話語,例如(通過2020國慶獲取),太長不建議,指令/plt setDescription [稱號id] [稱號描述]
   如果不想讓lore中展示稱號描述的話,直接語言文件中找到對應lore刪除對應的行即可
3. **新增** 稱號商城和倉庫新增變量  稱號描述: ${description} ,將這個寫在語言文件的對應lore中即可,自動替換為稱號的描述
4. **新增** 添加變量 %playerTitle_description% 玩家使用稱號的描述
5. **修復** 刪除稱號的時候會把對應的粒子效果也刪除

#### 2.3.4更新小助手
語言文件有更新,建議刪除languages文件夾讓重新生成

#### 2.3.3
**2020年10月10日**
1. **修復** 修復切換稱號時候上一個稱號的藥水效果不清除的bug

#### 2.3.3更新小助手
配置無任何變動,直接替換jar即可

#### 2.3.2
**2020年10月8日**
1. **優化** 進行點無關緊要的代碼優化

#### 2.3.2更新小助手
配置無任何變動,直接替換jar即可

#### 2.3.1(完全版搶先體驗)
**2020年10月5日**
1. **優化** 現在取消稱號也會取消稱號附加的粒子效果了
2. **優化** 完全兼容SuperTrailsPro了

#### 2.3.1更新小助手
語言文件有更新,建議刪除languages文件夾讓重新生成

#### 2.3.0
**2020年9月30日**
1. **新增** 支持粒子稱號 [點擊查看](https://www.showdoc.com.cn/PlayerTitle?page_id=5518933383532639 "點擊查看")

#### 2.3.0更新小助手
語言文件有更新,建議刪除讓重新生成

#### 2.2.0
**2020年9月29日**
1. **優化** 優化性能,修改一些方法為異步執行
2. **優化** 玩家輸入/plt help也會有提醒了
3. **新增** 命令/plt getIp 輸入後會顯示自己服務器真實ip和端口
4. **優化** 修復了一些因為服務器無法訪問外面引起刷屏的問題(現在最多請求6次)
5. **優化** 修復一些語言文件沒有的提醒
6. **優化** 現在藥水效果可以在語言文件中自己配置翻譯了
7. **優化** 現在永久的稱號不會在顯示2120-00-00這種了,會直接顯示永久

#### 2.2.0更新小助手
語言文件有更新,建議刪除讓重新生成

#### 2.1.7
**2020年9月10日**
1. **修復** 暫時把玩家buff設置從異步調整為同步執行,因為異步加藥水buff會報錯

#### 2.1.7更新小助手
對比2.1.6版本,無任何配置更新,直接替換jar即可

#### 2.1.6
**2020年8月21日**
1. **修復** 玩家重生重設buff優化

#### 2.1.6更新小助手
對比2.1.5版本,無任何配置更新,直接替換jar即可

#### 2.1.5
**2020年8月19日**
1. **修復** 權限稱號在shop中顯示問題(但是我不建議顯示出來,因為玩家只要有權限登錄會自動獲取到該稱號)
2. **修復** /plt view open (玩家名) 命令刪除玩家的稱號時候,會跳轉到自己的稱號倉庫

#### 2.1.5更新小助手
對比2.1.4版本,無任何配置更新,直接替換jar即可

#### 2.1.4
**2020年8月17日**
1. **修復** 玩家重生後藥水buff會丟失的bug

#### 2.1.4更新小助手
對比2.1.3版本,無任何配置更新,直接替換jar即可

#### 2.1.3
**2020年8月12日**
1. **修復** 進入遊戲時候對應的稱號屬性不會立即添加給玩家的bug

#### 2.1.3更新小助手
對比2.1.2版本,無任何配置更新,直接替換jar即可

#### 2.1.2
**2020年8月7日**
1. **優化** 代碼優化，功能無變動

#### 2.1.2更新小助手
直接替換jar即可

#### 2.1.1
**2020年8月7日**
1. **新增** 指令: /plt addPlayerTitle [玩家名稱] [稱號名稱] (天數)  
   直接新增一個隱藏的稱號,並把這個稱號給對應玩家,天數如果不填默認永久

#### 2.1.1更新小助手
語言文件有小調整,新增help幫助(讓我們緬懷下死的最快的2.1.0版本...)

#### 2.1.0
**2020年8月7日**
1. **新增** 兼容的稱號buff添加類型 原版藥水效果

#### 2.0.1更新小助手
語言文件有小調整,新增藥水buff相關字段,建議自己補全或者備份舊的,然後讓重新生成語言文本


#### 2.0.1
**2020年8月5日**
1. **修復** /plt view shop 中管理稱號,稱號buff不顯示的問題
2. **修復** /plt view shop 中已隱藏的稱號不會顯示的問題
3. **優化** 新增/plt 會顯示幫助

#### 2.0.1更新小助手
對比2.0.0版本,無任何配置更新,直接替換jar即可

#### 2.0.0
**2020年8月3日**
1. **優化** 更好的兼容性-完美兼容1.7-1.16
2. **優化** 兼容的sx從2.0版本變更為3.0重置版本
3. **新增** 雲漢化系統 1.13-1.16自動全物品漢化, 其他版本可自己在item.json中配置也可使用雲漢化
4. **優化** 稱號數量獎勵重做,更方便的領取,更直觀的gui
5. **優化** 刪除大量指令,能用gui管理的就用gui管理(新指令先看語言文件中)
6. **新增** 可查看玩家稱號的gui並管理
7. **新增** 可查看稱號數量獎勵的gui並管理
8. **新增** 可查看稱號商城的gui並管理
9. **新增** 權限稱號類型使用獨立命令
10. **優化** 現在稱號價格沒有任何限製了
11. **新增** 現在插件分為公開版和完整版了

#### 2.0.0更新小助手
升級到2.x不會對之前1.x的稱號數據和玩家有任何變化,只是更方便管理員操作
config.yml內容變更,語言文件大量內容變更,建議刪除後讓重新生成
Material.yml刪除