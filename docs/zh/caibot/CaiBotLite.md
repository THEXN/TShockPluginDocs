# CaiBotLite 使用指南

> [!IMPORTANT]  
> CaiBot已经不再提供服务器服务，请您尽快迁移到CaiBotLite

## 📄前言

- CaiBotLite是由Cai及UnrealMultiple开发维护的Terraria QQ官方机器人
- 同时也是CaiBot的轻量版, 服务器运行非常稳定, 再也不会被TX踢下线了 :)
- CaiBotLite拥有CaiBot的所有基础功能, 并且支持命令面板


## 📖使用教程

1. 添加CaiBotLite到群中，可以扫描下面的二维码，也可以使用手机打开链接: [[添加CaiBotLite到群中]](https://qun.qq.com/qunpro/robot/qunshare?robot_appid=102256264&robot_uin=3889168216)  
   ![image](https://github.com/user-attachments/assets/9d58e4af-846d-4e28-a840-f917ced66bf1)  
2. 拉入群内即可使用机器人命令，默认管理员为拉入者，可以使用`/添加白名单 <角色名字>`来绑定游戏内角色名  
   ![image](https://github.com/user-attachments/assets/51e22519-2af9-4d57-b632-4531706d01e5)
3. 使用`/添加管理 <管理员白名单名字>`(隐藏命令)来绑定机器人管理员  
   ![image](https://github.com/user-attachments/assets/557bbd0a-53f2-4e00-b000-e2e91f34c57d)  

5. 下载适配插件/MOD
   - TShock插件: [[下载]](http://api.terraria.ink:11434/plugin/get_plugin_zip?assembly_name=CaiBotLite)
   - TMOD: 开发中...
6. 安装适配插件/MOD
   ### TShock
   1. 将插件放入`ServerPlugins`文件夹, 如果有CaiBot.dll请删除它(CaiBot已经不再支持)  
      ![image](https://github.com/user-attachments/assets/f5c932c5-f7c2-43c4-8050-c950497b026d)  
   2. 启动服务器，得到绑定码  
      ![image](https://github.com/user-attachments/assets/fb693b74-0fd7-4f93-ade9-0b5b845d58a8)    
   3. 群内发送`/添加服务器 <显示IP> <显示端口> <绑定码>`(隐藏命令)添加服务器   
      ![image](https://github.com/user-attachments/assets/d38f4dfc-2ed5-48ea-a548-fc8ec7ea0229)   
   5. 当后台出现绑定成功提示，即服务器绑定成功!   
      ![image](https://github.com/user-attachments/assets/a6a52278-172f-4c5d-a3e1-db3662ccfc67)
   6. 此时即可使用服务器命令 (๑1๑中1即为服务器序号)  
      ![image](https://github.com/user-attachments/assets/dece73b1-5dee-42d4-86de-ddff829e038f)    
      ![image](https://github.com/user-attachments/assets/dce00aac-3e09-4a63-92b8-4bb86ca78c35)
   7. 配置文件位于`tshock/CaiBotLite.json`, 可以在配置文件中设置`白名单开关`和`白名单提示群号`  
      ![image](https://github.com/user-attachments/assets/93db782a-b616-4ec6-b3a4-ff7d0f083b7a)  
   ### TMOD  
   填坑中...  
7. 发送`/菜单`查看详细功能，感谢使用CaiBotLite
> [!CAUTION]
> 目前暂不支持子群功能，预计下周更新  
> 各群的白名单不互通  
> 文件功能暂时不可用

## 🔐BOT管理员
- 命令 `/添加管理 <名字>` 为玩家添加管理员权限
- 命令 `/删除管理 <名字>` 移除玩家的管理员权限
> [!NOTE]  
> 踢出并且重新拉回BOT后，群数据不会被删除，但是`管理员列表`会被重置，并且默认添加`拉入者`为管理员  
## 🗑️黑名单管理
- 命令 `/添加黑名单 <名字>` 来封禁玩家（仅针对本群）
- 命令 `/删除黑名单 <名字>` 来解除封禁


---

**注意**：请确保按照指南操作，以确保 Bot 的正常使用。如有问题，请联系管理员。
