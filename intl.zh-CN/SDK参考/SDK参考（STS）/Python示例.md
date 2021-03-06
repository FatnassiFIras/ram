# Python示例

本文简要介绍了Python SDK的安装方法，并提供了示例代码。

## 背景信息

-   Python SDK包含阿里云Python SDK核心库（`aliyun-python-sdk-core`）和STS SDK（`aliyun-python-sdk-sts`），两者都需要安装。
-   [OpenAPI Explorer](https://api.aliyun.com/)提供在线调试API和动态生成SDK示例代码的功能，能显著降低API的使用难度，推荐您使用。
-   关于STS API的详情，请参见[什么是STS](/intl.zh-CN/API 参考（STS）/什么是STS.md)。
-   关于STS的接入地址，请参见[接入地址](/intl.zh-CN/API 参考（STS）/接入地址.md)。

## Python SDK的安装方法

Python SDK的安装方法，请参见[快速开始]()。

Python SDK安装包下载地址如下：

-   [Python SDK](https://pypi.org/project/aliyun-python-sdk-core)
-   [STS SDK](https://pypi.org/project/aliyun-python-sdk-sts)

## Python SDK示例

下面为您提供AssumeRole API的Python SDK示例代码。关于其他API，请访问[OpenAPI Explorer](https://api.aliyun.com/)调试并获取示例代码。

```
#!/usr/bin/env python
#coding=utf-8

from aliyunsdkcore.client import AcsClient
from aliyunsdkcore.acs_exception.exceptions import ClientException
from aliyunsdkcore.acs_exception.exceptions import ServerException
from aliyunsdksts.request.v20150401.AssumeRoleRequest import AssumeRoleRequest

#构建一个阿里云客户端，用于发起请求。
#构建阿里云客户端时需要设置AccessKey ID和AccessKey Secret。
client = AcsClient('<accessKeyId>', '<accessSecret>', 'cn-hangzhou')

#构建请求。
request = AssumeRoleRequest()
request.set_accept_format('json')

#设置参数。
request.set_RoleArn("<RoleArn>")
request.set_RoleSessionName("<RoleSessionName>")

#发起请求，并得到响应。
response = client.do_action_with_exception(request)
# python2:  print(response)
print(str(response, encoding='utf-8'))           
```

