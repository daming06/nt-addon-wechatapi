# nt-addon-wechatapi
基于 nest 封装的 微信公众平台 API


## 贡献说明

我们欢迎 Nest.js 使用者来参与这个插件的开发，作为一个贡献者，请您遵循以下原则：

- 代码提交规范，参考 [Git Commit Message Conventions](https://docs.google.com/document/d/1QrDFcIiPjSLDn3EL15IJygNPiHORgU1_OOAqWjiDU5Y/edit#)
- 始终从 develop checkout 一个新分支，命名规范为 feature/xxx，xxx 必须具有可读性，如：微信-普通商户版-扫码支付 => feature/wechat-native-pay
- 在 checkout 新分支前，先在本地 develop 分支拉取远程 develop 分支的最新代码
- 文件命名规则请参考项目目前的命名规则，如：微信支付中，order.interface.ts 代表所有订单相关的请求参数和返回结果的定义，swipe.pay.service.ts 代表付款码支付的业务逻辑

## 功能开发

请先查阅 Roadmap，确保你想贡献的功能没有正在被实现。然后在 **issue** 里提交一个贡献请求，注明想要贡献的功能。

## 发现 Bug ？

如果你在源码中发现bug，请你先在本仓库的 **issue** 提交一个bug问题。在你提交完bug问题后，我们很乐意接受你提交一个 **PR** 来帮助我们修复这个bug。


## QQ 群

322247106


## Roadmap

- [ ] 发送客服消息（文本、图片、语音、视频、音乐、图文）
- [x] 菜单操作（查询、创建、删除、个性化菜单）
- [ ] 二维码（创建临时、永久二维码，查看二维码URL）
- [x] 分组操作（查询、创建、修改、批量移动用户到分组, 批量从分组移除用户）
- [ ] 用户信息（查询用户基本信息、获取关注者列表）
- [ ] 媒体文件（上传、获取）
- [ ] 群发消息（文本、图片、语音、视频、图文）
- [ ] 客服记录（查询客服记录，查看客服、查看在线客服）
- [ ] 群发消息
- [ ] 公众号支付（发货通知、订单查询）
- [ ] 微信小店（商品管理、库存管理、邮费模板管理、分组管理、货架管理、订单管理、功能接口）
- [x] 模版消息
- [ ] 网址缩短
- [ ] 语义查询
- [ ] 数据分析
- [ ] JSSDK服务端支持
- [ ] 素材管理
- [ ] 摇一摇周边
