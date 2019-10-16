支付宝支付共有两种模式，这里支持的是支付宝推荐的公钥证书方式模式


## 安装

npm install alipay_sdk2

### typescript使用方法：
1、this.aliPay = new AliPayUtil( this.alipay_cert_sn, this.privateKeyPath );//初使化
2、this.aliPay.getPayCode( rsaSignParam );//生成APP支付字符串
3、this.aliPay.rsaCheck( req.body );//支付回调验签

### javascript使用方法
1、this.aliPay = new AliPayUtil_1.AliPayUtil( this.alipay_cert_sn, this.privateKeyPath );//初使化
2、this.aliPay.getPayCode( rsaSignParam );//生成APP支付字符串
3、this.aliPay.rsaCheck( req.body );//支付回调验签：

## 使用

### AliPayJavaSnTool用于生成三个证书序列号：
#### 1、app_cert_sn
#### 2、alipay_cert_sn
#### 3、alipay_root_cert_sn

[帮助文档 https://github.com/wujinhong/aliPay/raw/master/公钥证书方式模式.docx](https://github.com/wujinhong/aliPay/raw/master/公钥证书方式模式.docx)

[SDK https://www.npmjs.com/package/alipay_sdk2](https://www.npmjs.com/package/alipay_sdk2)


## 开发

打开 WebStorm。