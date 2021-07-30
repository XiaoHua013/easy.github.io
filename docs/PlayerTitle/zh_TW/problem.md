## 常見問題

####1. 使用mysql進行存儲報錯
```
mysql版本太低,請使用mysql5.7或者更高（2.7.5+版本已修復）
```
####2. 稱號商城內購物物品不能漢化嗎?

```
 1.13+ 版本會自動漢化
 
 其他版本在item.json中進行配置
 按照json格式一直自定配置即可,配置過的會自動漢化,如果沒配置的不會,請嚴格保證每個英文單詞正確(推薦用到什麽物品就漢化什麽,這裏添加,然後指令重載配置文件即可)
 
 例子:
 {
  "NAME_TAG": "命名牌",
  "PAPER": "紙"
}
```

校驗你寫的json格式是否正確： [點擊前往](https://www.json.cn/)

####3. 1.7或者1.8版本使用亂碼或者無法使用

```
插件默認UTF-8,請自己轉碼為ANSI編碼
```

####4. tab稱號無效或者頭頂稱號無限

```
isTab 顯示tab稱號和頭頂稱號這個小功能跟計分板插件沖突
解決方案: 關閉config.yml中的istab ,使用變量來進行顯示即可
```

####5. 修改了config中的前綴和後綴,沒有生效

```
前綴後綴是直接在生成稱號時候就綁定了,所以改了之後對之前的稱號無效的,之後生成的稱號就有效了.建議在第一次使用時候就確定好想要的前綴和後綴
```

####6. 可以定製稱號嗎 別人都沒有的內種

```
指令:/plt add [稱號類型] [稱號名稱] [金額] (天數) (是否隱藏) (玩家名)
例如:/plt add not &e定製稱號 0 0 false xiongliu
給指定天數,請自己修改天數0為對應天數即可,如果想讓其他玩家也可購買,把false改為true即可,其他參數跟新增一個稱號一致
```

####7. 我購買了稱號,怎麽稱號商店就沒了?一次性的?那別人還怎麽買?

```
稱號商店顯示優化,玩家購買過的稱號對只該玩家隱藏,不影響其他玩家查看和購買
```

####9. 刪除了稱號插件,但是tab和頭頂還有稱號顯示，2.7.7+已經修復

```
安裝一個計分板插件進行沖突下即可 ,例如:TabListPro
沖突完成刪除掉就行
```

####10. 一個稱號可以設置多條件購買嗎?

```
可以,配合菜單實現,或者使用商店兌換稱號卡這類都可以
```

####11. 2.x版本如何刪除或者給稱號改價格等操作?

```
1.x版本使用/plt adminshop指令  
2.x版本使用/plt view shop指令
```

####12. 稱號商城和倉庫的lore可以修改嗎?

```
完全可以,在語言文件中修改對應的lore即可
```

####13. sx版本問題引發錯誤（2.7.2+已經同時兼容sx的2.x和3.x）

```
例如這種看到SxAttribute 不用想就是你的sx版本不對
稱號插件默認支持的是sx3.x版本，如果用的sx是2.x請去網盤下載兼容sx低版本的修復版本

```

####14. 粒子效果不顯示

```
1. 檢查前置是否正常目前有SuperTrails和SuperTrailsPro
2. 檢查客戶端是否已經開啟粒子顯示
3. 插件完全禁止任何形式的熱加載，請重啟
4. 添加了粒子後請看看稱號描述上是否已經有了
5. 添加了粒子後請重新佩戴稱號才會生效
6. 粒子是在spigot和paper端測試，其他端請自己測試
7. 檢查你的指令是否按照文檔中一樣使用的
8. 粒子翅膀三個顏色不要使用一樣的
9. 檢查後臺有無報錯，有的話請提供
10. 檢查版本是否最新，粒子插件是否版本正常
```