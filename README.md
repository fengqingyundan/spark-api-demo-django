spark-api-demo-django
=====================

Spark API django示例说明

1. 概述
--------

本示例代码为UTF-8编码格式，请根据需求参考相应的示例代码。

2. 使用说明
--------

2.1 获取API Key

Spark API的每一个通信接口都需要采用API Key来加密，因此必须先到CC视频后台获取后，才能正常使用API。

2.2 配置

2.2.1 demo相关的配置信息在 'apidemo/utils.py' 中，使用前请将其填写完整。
2.2.2 视频回调信息配置在 'template/upload.html'的js里，请更改为您可以收到回调信息的地址

2.3 启动

将示例代码放到你的网站或本地服务器任意路径下，访问index即可，建议使用nginx。

该实例代码在 django v1.6 下测试通过。
