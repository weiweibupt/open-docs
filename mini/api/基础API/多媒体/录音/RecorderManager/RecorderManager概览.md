# 简介
获取全局唯一的录音管理器，可通过 [my.getRecorderManager](https://opendocs.alipay.com/mini/api/getrecordermanager) 获取。

## 使用限制

- 支付宝客户端 10.1.60，基础库 [1.11.0](https://opendocs.alipay.com/mini/framework/lib) 开始支持，低版本需要做 [兼容处理](https://docs.alipay.com/mini/framework/compatibility)。
- 使用此 API 前，请先在开放平台控制台 **创建小程序**、**添加能力**，可查看 [接入准备](https://opendocs.alipay.com/mini/02pj5u)。
- 此 API 暂仅支持企业支付宝小程序使用。

## 方法
| **名称** | **功能说明** |
| --- | --- |
| [RecorderManager.start](https://opendocs.alipay.com/mini/02vdqs) | 开始录音。 |
| [RecorderManager.stop](https://opendocs.alipay.com/mini/02velg) | 停止录音。 |
| [RecorderManager.pause](https://opendocs.alipay.com/mini/02velh) | 暂停录音。 |
| [RecorderManager.resume](https://opendocs.alipay.com/mini/02vdqt) | 继续录音，即恢复之前暂停的录音。 |
| [RecorderManager.onError](https://opendocs.alipay.com/mini/02veli) | 监听录音错误事件。 |
| [RecorderManager.offError](https://opendocs.alipay.com/mini/02vdqu) | 取消监听录音错误事件。 |
| [RecorderManager.onStart](https://opendocs.alipay.com/mini/02vdqv) | 监听录音开始事件。 |
| [RecorderManager.offStart](https://opendocs.alipay.com/mini/039bom) | 取消监听录音开始事件。 |
| [RecorderManager.onPause](https://opendocs.alipay.com/mini/02vdqx) | 监听录音暂停事件。 |
| [RecorderManager.offPause](https://opendocs.alipay.com/mini/02vdqy) | 取消监听录音暂停事件。 |
| [RecorderManager.onResume](https://opendocs.alipay.com/mini/02vdqz) | 监听录音继续事件。 |
| [RecorderManager.offResume](https://opendocs.alipay.com/mini/02velj) | 取消监听录音继续事件。 |
| [RecorderManager.onStop](https://opendocs.alipay.com/mini/02vdr0) | 监听录音结束事件。 |
| [RecorderManager.offStop](https://opendocs.alipay.com/mini/02velk) | 取消监听录音结束事件。 |
| [RecorderManager.onFrameRecorded](https://opendocs.alipay.com/mini/02vell) | 监听已录制完制定帧大小的文件事件。如果设置了 frameSize，则会回调此事件。 |
| [RecorderManager.offFrameRecorded](https://opendocs.alipay.com/mini/02velm) | 取消监听已录制完制定帧大小的文件事件。 |
