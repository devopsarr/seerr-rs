# \OverrideruleApi

All URIs are relative to *http://localhost:5055/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_overriderule**](OverrideruleApi.md#create_overriderule) | **POST** /overrideRule | Create override rule
[**delete_overriderule**](OverrideruleApi.md#delete_overriderule) | **DELETE** /overrideRule/{ruleId} | Delete override rule by ID
[**list_overriderule**](OverrideruleApi.md#list_overriderule) | **GET** /overrideRule | Get override rules
[**update_overriderule**](OverrideruleApi.md#update_overriderule) | **PUT** /overrideRule/{ruleId} | Update override rule



## create_overriderule

> Vec<models::OverrideRule> create_overriderule()
Create override rule

Creates a new Override Rule from the request body.

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::OverrideRule>**](OverrideRule.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_overriderule

> models::OverrideRule delete_overriderule(rule_id)
Delete override rule by ID

Deletes the override rule with the provided ruleId.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rule_id** | **f64** |  | [required] |

### Return type

[**models::OverrideRule**](OverrideRule.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## list_overriderule

> Vec<models::OverrideRule> list_overriderule()
Get override rules

Returns a list of all override rules with their conditions and settings

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::OverrideRule>**](OverrideRule.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## update_overriderule

> Vec<models::OverrideRule> update_overriderule(rule_id)
Update override rule

Updates an Override Rule from the request body.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rule_id** | **f64** |  | [required] |

### Return type

[**Vec<models::OverrideRule>**](OverrideRule.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

