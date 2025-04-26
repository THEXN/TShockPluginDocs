# CaiBotLite 使用指南

> [!IMPORTANT]  
> CaiBot已经不再提供服务器服务，请您尽快迁移到CaiBotLite  
> 默认管理员为拉BOT的用户  

## 📄前言

- CaiBotLite是由Cai及UnrealMultiple开发维护的Terraria QQ官方机器人
- 同时也是CaiBot的轻量版, 服务器运行非常稳定, 再也不会被TX踢下线了 :)
- CaiBotLite拥有CaiBot的所有基础功能, 并且支持命令面板
## 🙏反馈QQ群
  ![image](img/dc65cb87-31aa-42a9-809e-0c17548a6676.jpg)
## 📖使用教程

1. 添加CaiBotLite到群中，可以扫描下面的二维码，也可以使用手机打开链接: [[添加CaiBotLite到群中]](https://qun.qq.com/qunpro/robot/qunshare?robot_appid=102256264&robot_uin=3889168216)  
   ![image](img/9d58e4af-846d-4e28-a840-f917ced66bf1.jpg)  
2. 拉入群内即可使用机器人命令，默认管理员为拉入者，可以使用`/添加白名单 <角色名字>`来绑定游戏内角色名  
   ![image](img/51e22519-2af9-4d57-b632-4531706d01e5.jpg)
3. 使用`/添加管理 <管理员白名单名字>`(隐藏命令)来绑定机器人管理员  
   ![image](img/557bbd0a-53f2-4e00-b000-e2e91f34c57d.jpg)  

5. 下载适配插件/MOD
   - TShock插件: [[下载]](http://api.terraria.ink:11434/plugin/get_plugin_zip?assembly_name=CaiBotLite)
   - TMOD:
       - [[GitHub]](https://github.com/UnrealMultiple/CaiBotLiteMod/releases/latest/download/CaiBotLiteMod.tmod)
       - [[国内镜像]](https://github.moeyy.xyz/https://github.com/UnrealMultiple/CaiBotLiteMod/releases/latest/download/CaiBotLiteMod.tmod)
6. 安装适配插件/MOD
   ### TShock
   1. 将插件放入`ServerPlugins`文件夹, 如果有CaiBot.dll请删除它(CaiBot已经不再支持)  
      ![image](img/f5c932c5-f7c2-43c4-8050-c950497b026d.jpg)  
   2. 启动服务器，得到绑定码  
      ![image](img/fb693b74-0fd7-4f93-ade9-0b5b845d58a8.jpg)    
   3. 群内发送`/添加服务器 <显示IP> <显示端口> <绑定码>`(隐藏命令)添加服务器   
      ![image](img/d38f4dfc-2ed5-48ea-a548-fc8ec7ea0229.jpg)   
   5. 当后台出现绑定成功提示，即服务器绑定成功!   
      ![image](img/a6a52278-172f-4c5d-a3e1-db3662ccfc67.jpg)
   6. 此时即可使用服务器命令 (๑1๑中1即为服务器序号)  
      ![image](img/dece73b1-5dee-42d4-86de-ddff829e038f.jpg)    
      ![image](img/dce00aac-3e09-4a63-92b8-4bb86ca78c35.jpg)
   7. 配置文件位于`tshock/CaiBotLite.json`, 可以在配置文件中设置`白名单开关`和`白名单提示群号`  
      ![image](img/93db782a-b616-4ec6-b3a4-ff7d0f083b7a.jpg)  
   ### TMOD
   1. 将MOD放入`Documents\My Games\Terraria\tModLoader\Mods`文件夹, 如果有CaiBotMod.tmod请删除它(CaiBot已经不再支持)  
      ![image](img/8c087240-f6fb-4d4a-a4be-c5f8e49ebf9b.jpg)  
   2. 启动服务器，输入命令`生成绑定码`  
      ![image](img/bcc5ec3d-4ce3-4a2b-aa53-6ea762c630a5.jpg)  
   3. 群内发送`/添加服务器 <显示IP> <显示端口> <绑定码>`(隐藏命令)添加服务器   
      ![image](img/86845477-982f-472e-80ba-d26e675841aa.jpg)  
   5. 当后台出现绑定成功提示，即服务器绑定成功!   
      ![image](img/2b17e272-6bfb-42ce-85c1-b491fce45359.jpg)   
   6. 此时即可使用服务器命令 (๑1๑中2即为服务器序号)  
      ![image](img/1c7d5f53-1c29-42c5-8661-ccd4b7adf627.jpg)  
      ![image](img/f16b4849-edf6-4cb4-82cb-a53a32bdf21c.jpg)  
   7. 配置文件位于`tModLoader/CaiBotLite.json`, 可以在配置文件中设置`白名单开关`和`白名单提示群号`  
      ![image](img/71a4b6d6-33a3-4efe-a434-08ed05ec07a8.jpg)
  > [!NOTE]
  > 进度查询功能需要使用安装`BossChecklist`模组    
  > ![image](img/70c3b525-c3e7-40d5-843b-38ca20bf773f.jpg)  

8. 发送`/菜单`查看详细功能，感谢使用CaiBotLite
   
## 🔐BOT管理员
- 命令 `/添加管理 <名字>` 为玩家添加管理员权限
- 命令 `/删除管理 <名字>` 移除玩家的管理员权限
> [!NOTE]  
> 踢出并且重新拉回BOT后，群数据不会被删除，但是`管理员列表`会被重置，并且默认添加`拉入者`为管理员

## 🗑️黑名单管理
- 命令 `/添加黑名单 <名字>` 来封禁玩家（仅针对本群）
- 命令 `/删除黑名单 <名字>` 来解除封禁

## 🔗父群绑定
1. 使用命令 `/获取群信息` 获取父群信息  
![image](img/38d5c265-17ff-441c-9cf7-6aa67190ffbc.jpg)  
2. 使用命令 `/绑定父群 <父群ID>` 继承父群  
   ![image](img/52176279-b9e1-4264-b179-1d5a82e303df.jpg)  
> [!NOTE]  
> 使用命令 `/解绑父群` 解绑父群  
> 服务器、群白名单、设置、管理员等都会替换为父群的

---

**注意**：请确保按照指南操作，以确保 Bot 的正常使用。如有问题，请联系管理员。


