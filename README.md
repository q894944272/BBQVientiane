脚本仅供免费学习交流 发现有人倒卖到我这 如有发现及时制止 无修改游戏数据、获取利益 如有侵权联系删除 
****************************************************************************************************************
最新版百度云链接供无法下载的人下载 【2023218029】链接：https://pan.baidu.com/s/1KBq_bMnl1CAY4v7o8nBsXA?pwd=5vtp 
****************************************************************************************************************
2023-2-18
1、修复了清理蓝白玉概率性卡住问题 2、默认关闭清理蓝白玉 3、再强调一下普通用户只要系统分辨率是对的 改前几个配置就行 后台配置相关的都不要去动（不同分辨率字体就变了 文字识别只录了一套1920 * 1080 分辨率 如果需要其它分辨率要自己录字）
****************************************************************************************************************
2023-2-15 
1、新增了清理蓝白玉功能(虽然蓝白玉经验下调但是积少成多还不错 建议提升等级最高的那个玉) 2、战斗一些优化 3、去除普通土仅维护普通雪 4、新增支持大佛 5、配置顺序整理方便大众配置 
****************************************************************************************************************
2023-2-10
已经测试完成，远程队友基本无影响了。并且输出可观，裂空沙男魂玉蓄力属性不错几乎把把打出全队第一的输出。所以将 【集合版本_20232101959】列为一个正式稳定版
这里有个冲突 新版不支持土万象 因为土万象空气墙里有boss 容易锁空气墙 得用锁队友版本
****************************************************************************************************************
2023-2-6
给出先发版 还未测试 等下次开放进行测试 为适应版本 
1、新增可支持蓝月裂空  
2、修改索敌方式 
旧(每秒一次锁boss 默认3s一次锁队友) 由于新版远程多，效果不好
新(100ms一次锁boss且判断索敌图，10次判定10次无索敌图才进行一次最多转5圈的锁队友) 尽可能弱化远程队友的影响
****************************************************************************************************************
2023-2-5
最新说明 —— 普通土刚完善就被废了，因此改造为普通雪，增加了一些选项，不再过多说明看源码注释。
由于新版远程盛行，导致锁队友的效果奇差，由自己做权衡，总体而言还行，就是完成速度比较吃队友，后面针对性的装备魂玉，终于伤害不是垫底，还行

由于一边测试一边马上给出来，会频繁维护bug，我会保留2个最新版本，有看到选最新的就行。

****************************************************************************************************************
2023-1
永劫无间征神之路普通土万象大漠前后台集合版本
https://blog.csdn.net/qq_24054301/article/details/128691595

注：本脚本按照 1920 * 1080 分辨率 编写，不考虑做适配 
导入脚本 开启调试 选好地图 快捷键开启脚本即可挂机  

// 需要修改源码里4个配置

![6M4`E(R4WZ9OBRL6JI8EVBS](https://user-images.githubusercontent.com/31399434/215375888-89cc2b4a-70d1-4850-b594-6ad338cfe47a.png)

****************************************************************************************************************
****************************************************************************************************************
【配置1】 --- 是否后台版本
脚本分前后版本，注册码为""前台版本 不为""后台版本
前台版本免费占用键鼠，后台版本不占用键盘鼠标，使用了大漠插件VIP功能，是收费的，需要自己找淘宝每台电脑每天7分。
这是插件收费，跟我无关，这个插件很强，我尝试了各种方法目前没法破解，个人使用还能接受，分享给别人用是不小的数目
--------------------- 例 ---------------------
注册码 = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
附加码 = "XXXXXXX"
****************************************************************************************************************
****************************************************************************************************************
【配置2 】 --- 角色选择
选用角色顺序优先级 防止角色被占用卡住
    // 例如 Array(1, 0, 2) 表示 首选[1_沙男] 备选[0_宁红夜] 最后选[2_迦南]
    // [0_宁红夜] [1_沙男] [2_迦南] [3_火男] [4_胡桃] [5_水娘]
--------------------- 例 ---------------------
roleIndex = Array(2, 1, 0)
****************************************************************************************************************
****************************************************************************************************************
【配置3】 --- 索敌键
游戏配置里默认是~，这个配置得改为对应索敌键
索敌我用的是-，自行修改
--------------------- 例 ---------------------
索敌键 = "-"
****************************************************************************************************************
****************************************************************************************************************
【配置4】 --- 后台蓄力键 
后台版本的配置，游戏设置右键蓄力需要改为键盘的按键 比如9
--------------------- 例 ---------------------
后台蓄力键 = "9"
****************************************************************************************************************
****************************************************************************************************************
【配置5】 --- 截战绩图
 截图路径前缀 为空不截图
--------------------- 例 ---------------------
截图路径 = "E:\按键精灵\pic\p"
****************************************************************************************************************
****************************************************************************************************************

【后台版本必看说明】
插件特殊绑定基本实现了后台，除了

1、切换页面的时候鼠标会自动跳回游戏（解决：我开启了一个线程是监控，
需要把窗口往下面拖，留一小截就行，可以被其它窗口盖住，监控到鼠标突然移到最下面，就会跳回原位置，这样就基本解决了）

2、然后长按鼠标视角会朝天飘（解决：用按键代替鼠标，比如我把右键蓄力改成了9）

3、最小化后台不能运行，但是窗口可以位移或者被盖住 游戏需要改为窗口化
-----------------------------------------------------------------------------------------------------

更多详细内容看源码注释
