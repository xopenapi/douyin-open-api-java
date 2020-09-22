

# ConnectReq

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**clientKey** | **String** | 应用唯一标识 |  [optional]
**responseType** | **String** | 填写code |  [optional]
**scope** | **String** | 应用授权作用域,多个授权作用域以英文逗号（,）分隔 |  [optional]
**optionalScope** | **String** | 应用授权可选作用域,多个授权作用域以英文逗号（,）分隔，每一个授权作用域后需要加上一个是否默认勾选的参数，1为默认勾选，0为默认不勾选 |  [optional]
**redirectUri** | **String** | 授权成功后的回调地址，必须以http/https开头。域名必须对应申请应用时填写的域名，如不清楚请联系应用申请人。 |  [optional]
**state** | **String** | 用于保持请求和回调的状态 |  [optional]



