# openapi.api.DefaultApi

## Load the API package
```dart
import 'package:openapi/api.dart';
```

All URIs are relative to *http://localhost*

Method | HTTP request | Description
------------- | ------------- | -------------
[**v1HealthGet**](DefaultApi.md#v1HealthGet) | **GET** /v1/health | 


# **v1HealthGet**
> v1HealthGet()



### Example 
```dart
import 'package:openapi/api.dart';

var api_instance = DefaultApi();

try { 
    api_instance.v1HealthGet();
} catch (e) {
    print("Exception when calling DefaultApi->v1HealthGet: $e\n");
}
```

### Parameters
This endpoint does not need any parameter.

### Return type

void (empty response body)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

