实时视频流的延时低，但成本高，如果您还有其他对延时要求不高的业务需求，可以考虑将实时视频通过旁路直播的方式分享给别人，并在此基础上完成录制，生成视频文件。
### 数据流通道可以理解成
    实时音视频数据流  =>  直播流  => 生成录制文件

## 相关概念


* [旁路直播](/document/product/647/16826)

## 旁路直播与录制
Web端目前**不支持**手工旁路直播和手工录制，需要实现业务需求请参考下面的文档：


| 业务需求  | 方案  | 
| ------- | ------ |
| 直播 | 需要开通[自动旁路直播](/document/product/647/16826) | 
| 混流 | [通过服务端接口调用混流接口](/document/product/647/16827) | 
| 录制 | [通过服务端接口调用录制接口](/document/product/647/16823) |

