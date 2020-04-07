# StatisticsApi

All URIs are relative to *https://hpb.health.gov.lk*

Method | HTTP request | Description
------------- | ------------- | -------------
[**apiGetCurrentStatisticalGet**](StatisticsApi.md#apiGetCurrentStatisticalGet) | **GET** /api/get-current-statistical | Get current real time situation of the COVID-19 patients reported in Sri Lanka

<a name="apiGetCurrentStatisticalGet"></a>
# **apiGetCurrentStatisticalGet**
> Statistics apiGetCurrentStatisticalGet()

Get current real time situation of the COVID-19 patients reported in Sri Lanka

Get current real time situation of the COVID-19 patients reported in Sri Lanka

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.StatisticsApi;


StatisticsApi apiInstance = new StatisticsApi();
try {
    Statistics result = apiInstance.apiGetCurrentStatisticalGet();
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling StatisticsApi#apiGetCurrentStatisticalGet");
    e.printStackTrace();
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

[**Statistics**](Statistics.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/json

