# 上门洗车小程序

#### 项目概述

用户通过小程序预约上门洗车服务， 根据附近商家排序， 查看洗车服务以及产品详情， 预约下单， 查看订单。 

>   不建议做多商家入驻小程序, 目前B2B2C基本没有成功案例, 建议先做好B2C
>
>   B2C端做起来后再考虑多商家入驻 (因为通常商家都不会入驻没有用户体量的小程序)。 
>
>   建议:  先主营2C的洗车服务预约， 再吸引商家入驻，

#### 项目范围

负责: 规划, 设计, 开发, 测试, 上线。 不负责:  运维。 

#### 项目进度安排

1.  规划: 
    -   需求分析: 确定目标用户、功能、流程 (需要双方对接, 反复确认)
    -   业务流程分析, 交付: 业务流程图  (可按需修改)
2.  设计:
    -   产品设计, 交付: 产品原型设计展示 (可按需修改) 
    -   架构设计以及后台数据结构设计 
3.  注册: 微信小程序企业账号注册, 需要企业证书: (需要双方对接)
    -   企业营业执照复印件
    -   身份证原件和复印件
    -   其他资料：根据具体情况，还可能需要提供其他资料，例如营业执照复印件的扫描件等。
4.  开发: 根据规划设计开发微信小程序, 交付 (可按需调整)
5.  测试: 内部测试应用的功能、性能和兼容性，(负责修复任何问题)。
6.  上线: 小程序需要通过审核 (7-14个工作日)
7.  运维...(不负责)

------

#### 报价

-   规划设计: 1500
-   开发: 规定开发周期越短，报价越高 (2500上下)。 
-   其他需要甲方承担费用
    -   注册: 微信官方收取300元/次的审核服务费用
    -   上线: 域名注册费(甲方自选, 按市场价不等), 服务器(按体量不等), SSL证书(1000上下) 

------

#### 规划设计

###### 产品设计

-   页面: 
    1.  主页 
        1.  轮播图
        2.  附近商家
        3.  热门服务
    2.  购物车 (选购洗车服务项目并加入购物车)
        1.  增删服务项目
        2.  结算
        3.  查看订单详情
    3.  订单详情
        1.  订单状态跟踪
        2.  取消订单
        3.  订单售后
        4.  订单评价
    4.  我的: 
        1.  查看我的订单列表 → 订单详情
        2.  地址管理: 添加管理我的地址
        3.  我的车: 添加管理我的车辆

###### 架构

前后端分离

-   前端: vue 
-   后端: node.js → json 数据接口 ← MySQL数据库



#### 开发

###### 进度

-   产品规划设计前后端架构 (进行中)

