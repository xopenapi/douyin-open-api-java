# OauthApi

All URIs are relative to *https://open.douyin.com*

Method | HTTP request | Description
------------- | ------------- | -------------
[**connect**](OauthApi.md#connect) | **POST** /connect | 获取授权码(code)


<a name="connect"></a>
# **connect**
> ModelAPIResponse connect(body)

获取授权码(code)

获取授权码(code)

### Example
```java
// Import classes:
import org.openapitools.client.ApiClient;
import org.openapitools.client.ApiException;
import org.openapitools.client.Configuration;
import org.openapitools.client.models.*;
import org.openapitools.client.api.OauthApi;

public class Example {
  public static void main(String[] args) {
    ApiClient defaultClient = Configuration.getDefaultApiClient();
    defaultClient.setBasePath("https://open.douyin.com");

    OauthApi apiInstance = new OauthApi(defaultClient);
    ConnectReq body = new ConnectReq(); // ConnectReq | 
    try {
      ModelAPIResponse result = apiInstance.connect(body);
      System.out.println(result);
    } catch (ApiException e) {
      System.err.println("Exception when calling OauthApi#connect");
      System.err.println("Status code: " + e.getCode());
      System.err.println("Reason: " + e.getResponseBody());
      System.err.println("Response headers: " + e.getResponseHeaders());
      e.printStackTrace();
    }
  }
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **body** | [**ConnectReq**](ConnectReq.md)|  |

### Return type

[**ModelAPIResponse**](ModelAPIResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | successful operation |  -  |

