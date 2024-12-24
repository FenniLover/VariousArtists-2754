# Various Artists
注：一堆报错是很正常的，你需要自行寻找res，在有res之后即可正常传送，如果你发现不能去新地图，这是很正常的，因为目前没有公开的新地图res。
**愿此行，终抵群星！**

## 功能
- [√] **编队**
- [√] **传送**
- [√] **活动展示** - 通过id查看活动页面
- [√] **战斗** - 场景技能中有一些错误
- [√] **场景** - 行走模拟器、交互、正确加载实体（不能攻击场景内的怪物）
- [√] **命途切换** - 你可以在8001到8007以及1001到1224之间自由切换命途
- [√] **玩家数据** - 实时保存当前玩家所在位置及场景，保存当前队伍角色以及主角和三月七的命途
- [√] **忘却之庭** - 通过json读取实现(暂时修复末日以及虚构的计分板)
- [√] **Json读取** - 你可以在网站自由设置角色面板以及怪物,并在地图的任意花萼上进行战斗

## Support:

> Client region: CN</br>
> Game Version: 2.7.54</br>

# 使用&安装

## 快速启动

1. 下载源码 构建服务端
2. 检查hotfix.json是否与客户端版本一致，并将热更文件换进Config文件里
3. 下载当前版本的Resources
> 将以下Res放到编译后的VariousArtists.exe同目录下</br>
> Resources\Config\LevelOutput\RuntimeFloor</br>
> Resources\Config\LevelOutput\SharedRuntimeGroup</br>
> Resources\ExcelOutput</br>

4. 运行VariousArtists.exe
5. 运行代理 启动游戏 享受！
6.如需更换面板，将在srtools网站设置好的json放入Config文件夹的同名文件即可，不需要重启，进入战斗后自动刷新面板。

## 构建

### 安装 .NET SDK
**Windows**
- [net8.0](https://dotnet.microsoft.com/zh-cn/download/dotnet/8.0)

**Linux**
```
sudo apt-get update
sudo apt-get install -y dotnet-sdk-8.0
```
