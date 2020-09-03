# ArtoxLab\ClckRuSDK\DefaultApi

All URIs are relative to *https://clck.ru*

Method | HTTP request | Description
------------- | ------------- | -------------
[**shorten**](DefaultApi.md#shorten) | **POST** /-- | shorten url

# **shorten**
> string shorten($url)

shorten url

shorten full url

### Example
```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');

$apiInstance = new ArtoxLab\ClckRuSDK\Api\DefaultApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client()
);
$url = "url_example"; // string | 

try {
    $result = $apiInstance->shorten($url);
    print_r($result);
} catch (Exception $e) {
    echo 'Exception when calling DefaultApi->shorten: ', $e->getMessage(), PHP_EOL;
}
?>
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **url** | **string**|  | [optional]

### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/x-www-form-urlencoded
 - **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../../README.md#documentation-for-api-endpoints) [[Back to Model list]](../../README.md#documentation-for-models) [[Back to README]](../../README.md)

