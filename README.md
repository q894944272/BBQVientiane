永劫无间征神之路普通土万象大漠前后台集合版本
https://blog.csdn.net/qq_24054301/article/details/128691595

注：本脚本按照 1920 * 1080 分辨率 编写，不考虑做适配

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
