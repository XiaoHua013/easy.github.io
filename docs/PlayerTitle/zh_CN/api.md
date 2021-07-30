## 欢迎对接本插件开发更多附属插件~
你可以基于称号来自定义扩展,你可以初始化一个或者多个称号,然后达到什么条件后可以玩家获取这个称号
例如: 你可以设置个 等级达人称号  然后监听玩家等级到了多少级就给玩家这个称号


## 使用方法

#### 初始化jar
下载代码中的PlayerTitle-2.5.9.jar文件导入你的项目中
或者使用maven引入依赖(本地机器私库,有时候不在线)

```
<repositories>
    <repository>
        <id>minecraft</id>
        <url>http://23.224.140.154:18208/repository/minecraft/</url>
    </repository>
</repositories>

<dependency>
  <groupId>com.handy.playertitle</groupId>
  <artifactId>PlayerTitle</artifactId>
  <version>2.7.9</version>
</dependency>
```

1. 在附属插件初始化时候新增关联的称号
2. 并把称号唯一id保存在附属插件的yml或者数据库中进行永久保存
3. 根据玩家名和这个称号的唯一id将称号给予玩家
4. 具体查询: [开源地址](https://github.com/handy-git/PlayerTitleVersions "开源地址")  ApiTest类   或者 [javadoc](https://handy-git.github.io/PlayerTitleVersions/ "javadoc")