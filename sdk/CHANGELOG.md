# 更新日志

## [MMCSDK_2_0_5] - 2019-01-17

### 变更

* 音视频的`chatId`统一更名为`callId`

## [MMCSDK_2_0_4] - 2019-01-15

### 变更

* 初始化用户时加入`appId`
* 接收消息回调中的`serverAck`回调参数封装起来
* 单聊群聊和无限大群中`msg`更名为`payload`
* 登录状态回调`statusChange`中，`errType`更名为`type`，`errReason`更名为`reason`，`errDescription`更名为`desc`
* 无限大群回调`errMsg`更名为`desc`
* 实时流回调`errMsg`更名为`desc`
* `LaunchedResponse.errMsg`更名为`desc`


