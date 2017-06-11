# 产品特性

| 版本 | 日期 | 描述 | 作者 |
| --- | --- | --- | --- |
| 初始草案V1.0 | 2017.3.22 | 第一草案，在细化阶段精化 | 时福源，刘子璐 |


##电影BACKLOG 

| ID | Name | Imp | Est | How to demo | Notes |
| --- | --- | --- | --- | --- | --- |
| 0 | 搜索框 | 7 | 8 | 可搜索影片、影院 |   |
| 1 | 电影（按钮） | 8 | 12 | 点击主页面上方&quot;电影&quot;按钮，根据当前电影热度，票房，评分等列出现在上映的所有电影，每个电影的小项里包括名字，影片时长，类型，主演，评分以及选座购票按钮。 | 需要用户授权定位，也可点击定位，手动选择定位 |
| 2 | 影片详情 | 9 | 12 | 页面包括名字，影片时长，上映日期，影片简介，影片评分，影片海报，可选影院部分（推荐）列表，导演编剧等各项信息及选座购票按钮。 | 影片评分我们提供豆瓣，烂番茄，时光网等不同影评网站的评分，使用户参考更多样。 |
| 3 | 选座购票 | 10 | 9 | 从影片列表或者影片详情页都可点击选座购票 | 会有影院列表，点击进去就会看到场次票价，用户可根据需求选择场次，座次 |
| 4 | 即将上映 | 5 | 6 | 在主页面中，给出近期即将上映的所有电影 | 点击每个分项会进入影片详情页 |
| 5 | 想看提醒 | 5 | 5 | 在影片详情页 | 影片上映、影片下映及网上有资源的时候网站会发送提醒 |
| **6** | 影院 | 8 | 12 | 点击主页面&quot;影院&quot;，根据当前定位按距离列出所有影院，包括名称、距离、特色折扣，是否有活动等 | 需要用户授权定位，可手动更改定位，具有影院搜索框 |
| **7** | 详情影院界面 | 10 | 12 | 包含影院信息、地址、上映影片、影院评价、包场服务等 | 影院评价类似淘宝评价列表，分好中差评，且具有几类评分标准（如舒适度、是否可以自带饮料等）影院可收藏 |
| **8** | 路线规划 | 2 | 2 | 点击影院地址，可以进行路线规划 | 使用第三方导航API即可 |
| **9** | 包场服务 | 5 | 8 | 在某个影院界面时，点击&quot;包场服务&quot;，进入到包场申请页面，包括人数、大厅要求、服务要求（如提供饮品）等，确认后跳转到支付页面 |   |
| **10** | 活动 | 7 | 8 | 点击主页面&quot;活动&quot;，进入到与电影相关的活动界面 | 包括观影活动、征集周边设计活动、有奖写影评等，页面以活动专题型列表设计 |
| **11** | 详情活动界面 | 8 | 6 | 点击某一活动进入介绍界面，并包含报名信息 | 与活动举办方合作只提供宣传界面，报名信息的汇总不需要额外创建数据库，由活动方自收集统计 |
| **12** | 登录 | 3 | 11 | 点击主页面&quot;登录&quot;，进入登录界面，输入用户名密码即登陆成功 | 在登录界面包含注册按钮，账户可与社交账号绑定或绑定邮箱，要与手机绑定（用于短信提醒） |
| **13** | 我的主页 | 6 | 8 | 登陆成功后，点击主页面&quot;我的&quot;，进入我的主页 | 含有电影票订单、优惠方式、收藏三大类，其中优惠方式包含折扣卡、红包、现金券等；收藏分为电影收藏、影院收藏、活动收藏。 |
| **14** | 短信提醒 | 4 | 6 | 后台监测购买电影距开始一小时发送短信 |   |
