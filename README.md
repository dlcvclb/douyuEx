## DouyuEx-斗鱼直播间增强插件![](https://img.douyucdn.cn/data/yuba/weibo/2020/02/18/202002182111554630626652946.png)

### 目标
1. 旨在扩展增强原版功能，优化用户体验
2. 安全，不做用户可控范围外的功能
3. 纯粹，不过分影响本来的网页功能
4. 不污染页面的结构
5. 使用简单，架构轻量，功能实用，交互友好
6. 集合移动端、客户端、web端特色功能
7. 代码原生不依赖框架，开发架构易扩展，易维护

### 安装步骤
1. [安装油猴脚本](https://www.crx4chrome.com/crx/1429/)，选择【Download crx file from crx4chrome】，将下载后的文件拖入浏览器进行安装，此步有问题的可以百度
2. 点击上方的安装脚本，安装本插件，若出现缺少";"的提示框，无视即可
3. 安装后，在礼物栏下方/鱼丸鱼翅左方会出现一个精灵球图标，点击显示功能条

### 使用说明
- 插件基于TamperMonkey V4.10开发，若插件有无法使用的情况，请尝试[升级油猴版本](https://www.crx4chrome.com/crx/1429/)
- 若出现提示是否允许跨域访问的页面，一律选择**允许**即可

### 声明
- 本插件是本人课余兴趣开发，代码质量请勿吐槽
- 代码可供互联网的同好们参考研究，**引用请注明出处**
- 喜欢本插件的用户不妨点一下收藏或推荐给朋友，有建议或BUG请提交在greasyfork或github
- 本插件仅为提高日常观看体验，不做薅羊毛/恶性竞争等功能
- 本插件归属：[斗鱼直播间5189167](https://www.douyu.com/5189167)
- 作者：小淳 / QQ：189964430

### 功能
#### 弹幕自动变色循环发送 
- 自动可调速发送弹幕
- 可自动改变弹幕颜色，让弹幕不再单调
- 舔狗模式

#### 一键续牌
- 给所有有粉丝牌的直播间赠送一根荧光棒

#### 查看真实人数 + 已播时长
- 数据来源：播酱
- 数据将显示在原公告栏处（弹幕框上方）
- 显示今日累计观看人数，弹幕人数，送礼人数
- 显示已播时长

#### 一键签到
- 所有已关注的直播间签到
- 所有鱼吧签到
- 车队签到(由于斗鱼本身接口问题，车队签到会自动打开新的页面，签到完毕后会自动关闭这个页面，本功能参考了@lvlanxingapp的程序，在此感谢)
- pc客户端签到
- 自动领取视频广告鱼丸

#### 一键领取鱼粮
- 自动领取pc客户端旧版鱼塘宝箱
- 自动领取web端新版鱼塘气泡
- 自动领取每日/每周任务
- 自动领取房间签到宝箱
- 有可领取的鱼粮将自动提示

#### 一键寻宝
- 一键参与鱼塘寻宝，不再需要等转圈圈了

#### 送出指定数量的礼物
- 用于送出指定数量（无限制）的礼物
- 可用于打榜，例如一次性送出999个飞机
- 背包送礼
- 一键清空背包礼物

#### 屏蔽基础广告

#### 调节弹幕大小
- 调节的是基础弹幕的大小（不算爵位弹幕等）
- 无大小限制调节

#### 自动更新
- 插件有新版本将自动提示更新

#### 获取真实直播流地址
- 可绕过斗鱼直接在本地播放器内播放
- 可直接下载(录屏)
- 该方式播放延迟极低，速度很快

#### 同屏播放
- 可在一个直播间内同时播放多个任意直播间画面（无弹幕）
- 支持在斗鱼同时观看其他平台的直播，目前支持:斗鱼/Bilibili
- 画面可拖动可拉伸大小
- 可选择清晰度
- 可选择线路
- 点击复制直播流地址
- 双模式选择（有弹幕/无弹幕）鼠标悬停在相应模式上可查看详细特性

#### 自动抢礼物红包
- 开启后全自动抢本房间的礼物红包
- 自动保存开关状态

#### 背包信息扩展
- 显示背包礼物总价值
- 显示背包礼物总亲密度
- 显示每个礼物的过期时间

#### 简洁模式
- 去除周榜，拉高弹幕框，去除悬浮图标（鼠标悬停在弹幕框时有显示该功能按钮，在锁屏清屏旁）
- 去除礼物栏，放大视频框（鼠标悬停在视频区域时，下方功能条有个“简”字）
- 去除弹幕前缀（鼠标悬停在弹幕框时有显示该功能按钮）

#### 去除弹幕字数限制
- 可以比原来的弹幕多发20个字（借鉴了greasyfork@logiCycle的代码，在其基础上优化，在此感谢）

#### 夜间模式
- 基于客户端还原优化的夜间模式
- 深度定制

#### 开播提醒
- 挂在直播间开播后会在右下角推送消息
- 点击消息后签到

#### 幻神模式
- 满级牌子，等级
- 幻神弹幕

#### 关键词禁言
- 本功能只能在10级以上直播间且拥有房管权限才可生效
- 模糊匹配
- 支持正则匹配，语法：re(正则表达式)=匹配后的文本 例如：re([1-9][0-9]{4,})=7777777
- 支持判断发送几次后再禁言
- 可查看禁言名单
- 可一键解除禁言

#### 关键词回复
- 模糊匹配
- 支持正则匹配，语法：re(正则表达式)=匹配后的文本 例如：re([1-9][0-9]{4,})=7777777
- 回复中\<id>将会被替换成发送者的名字，\<txt>将会被替换成发送者的弹幕内容，例如：回复内容@\<id>：\<txt>
  
#### 自动谢礼物
- 回复中\<id>将会被替换成赠送者的名字，\<cnt>将被替换成赠送的个数，例如：感谢\<id>的办卡x\<cnt>  

#### 自动抢宝箱
- 开启后会自动领取宝箱
- 成功率100%
- 会在右下角以windows消息提示的方式提醒手动验证，点击后跳转到相应页面
- 自定义延迟
- 支持全自动领取宝箱（本功能作者无任何收益！）  
-- 支持[ddocr](http://www.ddocr.com/)接口  
-- 此功能开启方法如下：  
-- 首先进入[ddocr官网](http://www.ddocr.com/)，注册账号  
-- 登录后进入到用户中心，找到【接口秘钥】这一行，将秘钥复制到相应的文本框中（请保证你的账号点数充足）  
-- 勾选自动抢宝箱即可  
- 一直领取失败看下面：  
-- 情况1：手动可以领取，但是插件提示领取失败 => 可能是领取太快导致的，首先确保自己的系统时间正确，然后看右下角提示领取失败的时候距离宝箱领取倒计时还有几秒，一般控制在还剩1秒以后即可，再根据情况调高延迟即可  
-- 情况2：手动自动都领取失败 => 发几条弹幕再领取  
-- 如果以上方法均无效，可能是账号本身问题导致无法领取宝箱，本插件无法解决  

#### 去除直播间密码锁定

#### 去除直播间超管封禁

#### 弹幕右键信息扩展
- 支持查看粉丝牌
- 支持禁言
- 支持查看全站最近10条弹幕

--------------------------------------------------

## 更新内容

### 2020年6月30日
1. 优化夜间模式细节
2. 优化屏蔽广告
3. 修复右键信息超粉牌子显示不全的BUG
4. 优化真实人数功能显示公告的用户体验，现改为鼠标悬停在真实人数处0.5秒后显示公告
5. 新增底层router包降低耦合
6. 编译器版本号可独立输出

### 2020年6月22日
1. 修复右键信息连续查看引发的一系列BUG
2. 优化查弹幕显示方式，不再会被遮挡

### 2020年6月21日
1. 新增屏蔽手动领取宝箱时弹出微信扫码的窗口
2. 新增弹幕右键信息扩展，内容如下
3. 新增禁言
4. 新增查看粉丝牌
5. 新增查看全站最近10条弹幕

### 2020年6月18日
1. 修复简洁模式主播信息会被挡住的BUG
2. 修复去除超管封禁无效的BUG
3. 优化简洁模式init逻辑，由timeout=>interval

### 2020年6月15日
1. 修复简洁模式关注列表会被挡住的BUG
2. 新增荧光棒变超火功能

### 2020年6月13日
1. 一键签到新增领取程潇直播间荧光棒x10
2. 新增去除直播间被超管封禁限制
3. 同屏播放暂时移除对虎牙的支持，原因如下：  
-- 虎牙更新了直播流的获取方式，目前仅能获取m3u8格式的直播流  
-- 插件使用的是flv.js，若要兼容则需要徒增3个js文件的资源成本，性价比较低，故移除，希望理解  
4. 宝箱一直领取失败看下面：  
-- 情况1：手动可以领取，但是插件提示领取失败 => 可能是领取太快导致的，首先确保自己的系统时间正确，然后看右下角提示领取失败的时候距离宝箱领取倒计时还有几秒，一般控制在还剩1秒以后即可，再根据情况调高延迟即可  
-- 情况2：手动自动都领取失败 => 发几条弹幕再领取  
-- 如果以上方法均无效，可能是账号本身问题导致无法领取宝箱，本插件无法解决  
5. 自动谢礼物更新了一部分礼物ID和官方礼物ID接口，可自行查看

### 2020年6月9日
1. 新增去除直播间密码锁定（需要手动点一下重新播放）
2. 优化广告鱼丸领取代码
3. 自动抢宝箱功能粉丝牌限制降低到9级
4. 自动抢宝箱现已支持抢已经出现的宝箱
5. 自动抢宝箱新增[ddocr](http://www.ddocr.com/)接口，用于自动过验证码实现全自动抢宝箱，若不填写则手动输入验证码  
-- 此功能开启方法如下：  
-- 首先进入[ddocr官网](http://www.ddocr.com/)，注册账号  
-- 登录后进入到用户中心，找到【接口秘钥】这一行，将秘钥复制到相应的文本框中（请保证你的账号点数充足）  
-- 勾选自动抢宝箱即可  
6. 自动续牌新增可选赠送任意个数的荧光棒

### 2020年6月7日
1. 新增自动抢宝箱，正常情况下成功率100%，实际上为半自动，触发验证码需要手动点击，本功能需13级歆崽粉丝牌  
-- 若出现无法领取的情况，可以尝试发几条弹幕后再领取  
-- 每个账号每天领取量是有上限的，达到上限后将无法继续领取  
-- 只会抢新出现的宝箱，已经存在的宝箱不会抢  
2. 为一键续牌增加了确认信息框，以防误点
3. 新增一处右侧悬浮框屏蔽
4. 修改清空背包的位置到背包框中，使功能更贴合实际
5. 夜间模式本人ID颜色修改与客户端效果一致
6. 自动抢宝箱新增windows消息提醒，点击后跳转到相应页面
7. 自动抢宝箱新增自定义延迟，当抢得过快出现失败的时候可以适当调高

### 2020年6月1日
1. 一键签到修改为只签到已开播的直播间
2. 为插件添加了百度统计代码（不影响使用）
3. 优化夜间模式细节
4. 自动抢礼物红包修改为6级粉丝牌可使用
5. 自动谢礼物新增字段\<cnt>用于表示赠送礼物的个数并更新了一部分礼物ID
6. 取消点击开播提醒右下角消息后置前台的功能
7. 新增去除直播间左下角水印

### 2020年5月29日
1. 直播间工具修改为每个直播间独立保存开关状态
2. 修改插件图标在夜间模式下的显示效果

### 2020年5月28日
1. 真实人数显示新增开播时间，鼠标放在已播时长上即可显示
2. 优化了夜间模式在赛事直播间的样式
3. 直播间工具添加option时会对空值进行检查，不再会加入空值
4. 关键词禁言新增禁言提醒（右下角推送信息）
5. 新增禁言名单，可查看被自己禁言的用户相关信息
6. 新增一键解禁，可解除本次被自己禁言的所有人

### 2020年5月26日
1. 删除了奥利给领取页面（活动已结束）
2. 重写了车队签到功能，降低账号多设备登录违规的风险
3. 优化了夜间模式礼物数量字体的颜色
4. 修复了鱼吧签到不全的BUG，并简化了鱼吧签到的提示，不再会刷屏了
5. 修改了夜间模式和屏蔽广告的载入时机，现在可以在打开网页瞬间生效了
6. 新增屏蔽打弱鸡游戏特效、直播间佩戴牌子的气泡
7. 新增开播提醒，挂在直播间，开播后右下角会推送信息(windows消息，请在浏览器中设置允许推送消息)，点击签到并跳转
8. 移除跳转随机火力全开直播间的功能
9. 新增关键词禁言，可判断发送几次禁言，此功能在只能在10级以上直播间且拥有房管权限才能使用。关键词支持正则表达式，格式：re(正则表达式)=匹配后的文本
10. 新增关键词回复，关键词支持正则表达式，格式：re(正则表达式)=匹配后的文本，\<id>将会被替换成发送者的名字，\<txt>将会被替换成发送者的弹幕内容，例如：回复内容@\<id>：\<txt>
11. 新增自动谢礼物，其中\<id>可以替换成送礼人的ID，例如 感谢\<id>送的xx
12. 新增幻神模式（自慰），这个模式使用的是循环修改，所以有点耗资源，娱乐功能（本功能部分代码参考了@lvlanxingapp的程序，在此感谢）
13. 优化内存占用
14. 底层新增了init入口，用于在插件载入模块前处理相应代码
15. 框架新增了Module入口，用于集中管理包内子模块，加强解耦
16. 重构了样式修改底层实现逻辑
17. 编译器现在对css会进行简单的压缩
18. 修改ws模块，已支持负载均衡和数据分包
19. 修复了无车队情况下签到页面不会关闭的BUG

### 2020年5月17日
1. 一键签到新增领取鱼吧帖子鱼丸*80
2. 屏蔽广告新增左侧悬浮广告屏蔽与谨防网络诈骗的气泡
3. 修复了领取广告鱼丸可能报错的BUG
4. 修复了领取气泡鱼粮无法显示详情的BUG
5. 优化了几处夜间模式的细节
6. 修复夜间模式背包颜色错误的BUG
7. 屏蔽掉标题栏的两个gif

### 2020年5月3日
1. 去除前缀功能保留斗鱼用户等级图标【感谢greasyfork@Guokr的建议】
2. 屏蔽广告新增屏蔽PUBG区主播数据统计图标
3. 优化了可能会造成内存泄露的代码
4. 弹幕框工具条不再会被礼物横幅遮挡
5. *新增了Ex_WebSocket模块包，可直连斗鱼弹幕服务器，可实现在A直播间同时看ABCD直播间的弹幕/礼物等，目前还没做实际的功能，有好的建议欢迎提出
6. 修改夜间模式弹幕框ID颜色与客户端统一

### 2020年5月1日
1. 弹幕发送助手新增舔狗模式

### 2020年4月28日
1. 视频简洁模式在非网页全屏下不再遮挡插件图标
2. 弹幕框去除前缀功能增加了图标
3. 一键领取奥利给修改成前台领取，并增加延迟以提高获取成功率

### 2020年4月25日
1. 大量改善和优化夜间模式的细节
2. 简洁模式新增去除弹幕前缀功能（鼠标悬停在弹幕框时有显示该功能按钮）
3. 一键签到新增奥利给领取（需歆崽牌1级）
4. 一键领取鱼粮中新增房间签到宝箱的领取（完成时会提示领取）
5. 修复直播间开启抽奖后鼠标穿透的BUG
6. 优化保存数据代码

### 2020年4月23日
1. 新增去除弹幕字数限制（能多发20个字）
2. 新增夜间模式（右上角头像右边切换）
3. 新增一处屏蔽广告（左下角）
4. 各种优化

### 2020年4月19日
1. 新增简洁模式保存状态
2. 简洁模式新增去除礼物栏，同时放大视频框（鼠标悬停在视频区域时，下方功能条有个“简”字）
3. 拉高弹幕框的同时去除悬浮的图标
4. 修复在没有直播的房间会无法使用的bug

### 2020年4月18日
1. 新增简洁模式-拉高弹幕框（鼠标悬停在弹幕框时有显示该功能按钮，在锁屏清屏旁）【由greasyfork@静若丨安澜 提出】  
--简洁模式后期会有加更多的功能，若有好的想法敬请提出。
2. 优化广告鱼丸的接口

### 2020年4月10日
1. 新增背包信息扩展功能，显示背包礼物总价值与总亲密度，并显示每个礼物的过期时间（左上角黑底白字）
2. 新增点击直播间的标题复制直播流地址（防止与其他脚本冲突）
3. 修改插件启动时机
4. 优化部分代码

### 2020年3月31日
1. 新增复制直播流地址，在页面分享的左边（关注数下方），直播流画质为默认
2. 新增移动端鱼吧签到（签到经验更多）【感谢github@nws0507贡献的代码】
3. 修改鱼塘领取鱼丸时间为15秒，并增加获取成功率
4. 修复鱼吧签到不全的BUG

### 2020年3月29日
1. 一键签到新增自动获取鱼塘广告鱼丸

### 2020年3月15日
1. 新增跳转随机火力全开房间
2. 缩小精灵球图标以解决网页缩放出现滚动条的BUG

### 2020年3月11日
1. 修复挑战鱼丸领取失效的BUG
2. 新增领取客户端任务鱼粮，但是此功能任务完成没有小红点提示，目前逻辑为点击一键领取时自动尝试领取客户端任务奖励
3. 优化提示
4. 因斗鱼改版，取消不绑定手机号发弹幕功能

### 2020年3月6日
1. 一键签到新增自动获取视频广告鱼丸

### 2020年3月1日
1. 去除代码压缩以符合gf规定

### 2020年2月28日
1. 修复部分接口偶尔无法使用的BUG
2. 优化一键鱼塘寻宝
3. 提高自动抢红包成功率

### 2020年2月27日
1. 修复因斗鱼更新，一键签到失效的BUG
2. 增加自动抢礼物红包的成功率
3. 升级鱼吧签到接口
4. 鱼吧签到无法正常使用的，请尝试[升级油猴脚本版本为4.10+](https://www.crx4chrome.com/crx/1429/)，还不行请清理cookie

### 2020年2月26日
1. 新增自动抢礼物红包（没有经过多少测试，若有BUG还请提出，在此感谢）
2. 取消屏蔽直播间推荐防止挡掉直播预告【由@伯毅。提出】
3. 优化同屏播放新增复制直播流地址功能
4. 关于默认最高画质的问题已经做成[独立的脚本](https://greasyfork.org/zh-CN/scripts/396929) 【由greasyfork@Zhang recycle提出】
5. 修复一键鱼塘寻宝失效的BUG
6. 修复一键签到失效的BUG
7. 新增不绑定手机号也可以发送弹幕的功能
8. 优化资源占用

### 2020年2月20日
1. 【重要】尝试修复斗鱼同屏播放功能无法使用的BUG。以下为说明  
-- 若出现无视频的情况，尝试点击小窗上的(无视频?)，在跳出的网址提示【是否继续访问】选择【继续访问】，然后重新载入一下同屏播放即可。  
-- 以上方法在浏览器重启之前都有效，重启浏览器后需要重新操作一遍  
-- 长久的方法可以尝试自行搜索自己的浏览器【如何关闭证书过期/不是私密链接提示】，这里举chrome和搜狗浏览器的例子：  
-- chrome: 在快捷方式启动参数加上--test-type --ignore-certificate-errors  
-- 搜狗浏览器: 升级版本(搜狗浏览器10) & 选项-安全设置-去掉HTTPS异常提示  

### 2020年2月18日
1. 新增背包送礼功能(速度并不快，送礼间隔>0.1秒)【感谢斗鱼用户@最爱骆歆小宝贝和@阿拆家的胖次提供测试】
2. 新增清空背包功能【感谢greasyfork用户@巨阳提议】
3. 修复一键寻宝偶尔会出现操作进行中的BUG

### 2020年2月11日
1. 修复引起斗鱼样式异常的BUG
2. 送礼功能新增确认信息框，以防误送【感谢斗鱼用户@扌斥女子马扁提议与测试】

### 2020年2月10日
1. 优化送礼功能消息提示
2. 修复同屏播放点击后会阻塞网页的问题，并优化显示
3. 新增同屏播放**有弹幕模式**，详细特性请**鼠标悬停**在相应模式上查看
4. 修改真实人数功能提示文字为当日累计人数

### 2020年2月6日
1. 修改插件名称为DouyuEx
2. 修复弹幕发送小助手自动变色设置后重开页面不生效的BUG

### 2020年2月3日
1. 新增屏蔽直播间推荐(直播画面上层的mask)
2. 扩展功能-赠送礼物逻辑改为循环赠送1个，以保证能正确送出与真正的无限制。详细赠送信息输出在F12控制台
3. 赠送礼物示例ID已改为当前直播间礼物数据。【感谢github@Keymorek提供的地址】

### 2020年1月26日
1. 新增点击真实人数跳转到主播数据页面，数据来源:小葫芦
2. 同屏播放新增支持bilibili和虎牙直播源，现在可以在斗鱼同时观看b站和虎牙的直播啦
3. 优化了部分代码架构

### 2020年1月20日
1. 新增获取真实直播流地址
2. 新增多屏播放，可在一直播间同时观看多个直播间画面（无弹幕）  
-- 如果无法播放，请检查浏览器是否**允许flash播放**
3. 重写优化真实人数显示，现在可以保留原来的公告，且资源占用更低
4. 修复寻宝无法一次性寻完的BUG 
5. 弹幕循环发送新增发送速度区间防止系统检测，本功能需求来源greasyfork的网友
6. 弹幕循环发送新增停止时间防止忘记关闭
7. 新增今日礼物价值，显示鱼翅礼物，鼠标悬停显示背包+总礼物价值

### 2020年1月12日
1. 重构版本发布



--------------------------------------------------

## 如何维护与编译
[项目地址](https://github.com/qianjiachun/douyuEx)
### 结构
- 本脚本将各个功能分为单独的模块，每个模块互相独立，在"编译"的时候将模块内的代码复制到main.js的相应位置即可
- 使用子模块需在父模块中注册，形式通常为`initPkg_父模块名_子模块名()`
- main.js中默认插入了一个图标，点击图标后展开功能面板。此处为底层设计好的，请慎改
- common.js为一些公共函数，是每个模块都可能会用到的。

### 维护（增加新功能）
1. 在packages内新建一个新的目录作为模块名（大驼峰）
2. 目录下新建相应的js与css文件
3. 每个模块应该有相应的入口函数（初始化函数）提供给main.js引用注册。
- 入口函数形式【initPkg_模块名】
- 每个模块向外暴露的变量需要写好注释并放在最前面
- **新增功能的icon的svg的style必须有display:block;父元素a的class要带上ex-panel__icon**
- 例如`<a class="ex-panel__icon"><svg style="display:block;"></svg></a>`或者`<a class="ex-panel__icon"><img/></a>`
- 每个模块保存的数据名字以 ExSave_ 开头 例如ExSave_BarrageLoop
4. 编写时注意不要污染其他模块或对其他模块有所影响
5. 模块中的子模块处理方式同主模块。
- **详细可参考模仿已经编写好的模块包**

### 编译
1. 将所有package的css内容依次复制到main.js的initStyle里
2. 在main.js下的initPkg函数中依次注册所有的模块，例如`initPkg_BarrageLoop();`
3. 将package下所有模块的js代码复制到main.js下
4. 全部完成后保存，复制到油猴脚本中去。
- **可以使用文件夹中自带的编译器，编译器将依据上述规则自动生成main.js**

### 更新
1. 修改头文件里的version
2. 修改Update模块包里的version
3. 编译发布