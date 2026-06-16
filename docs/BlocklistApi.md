# \BlocklistApi

All URIs are relative to *http://localhost:5055/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_blacklist**](BlocklistApi.md#create_blacklist) | **POST** /blacklist | Add media to blocklist
[**create_blocklist**](BlocklistApi.md#create_blocklist) | **POST** /blocklist | Add media to blocklist
[**create_blocklist_collection_by_collection_id**](BlocklistApi.md#create_blocklist_collection_by_collection_id) | **POST** /blocklist/collection/{collectionId} | Add collection to blocklist
[**delete_blacklist**](BlocklistApi.md#delete_blacklist) | **DELETE** /blacklist/{tmdbId} | Remove media from blocklist
[**delete_blocklist**](BlocklistApi.md#delete_blocklist) | **DELETE** /blocklist/{tmdbId} | Remove media from blocklist
[**delete_blocklist_collection**](BlocklistApi.md#delete_blocklist_collection) | **DELETE** /blocklist/collection/{collectionId} | Remove collection from blocklist
[**get_blacklist**](BlocklistApi.md#get_blacklist) | **GET** /blacklist | Returns blocklisted items
[**get_blacklist_by_tmdb_id**](BlocklistApi.md#get_blacklist_by_tmdb_id) | **GET** /blacklist/{tmdbId} | Get media from blocklist
[**get_blocklist**](BlocklistApi.md#get_blocklist) | **GET** /blocklist | Returns blocklisted items
[**get_blocklist_by_tmdb_id**](BlocklistApi.md#get_blocklist_by_tmdb_id) | **GET** /blocklist/{tmdbId} | Get media from blocklist



## create_blacklist

> create_blacklist(blocklist)
Add media to blocklist

**DEPRECATED**: Use `/blocklist` instead. This endpoint will be deprecated soon. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**blocklist** | [**Blocklist**](Blocklist.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_blocklist

> create_blocklist(blocklist)
Add media to blocklist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**blocklist** | [**Blocklist**](Blocklist.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## create_blocklist_collection_by_collection_id

> create_blocklist_collection_by_collection_id(collection_id, body)
Add collection to blocklist

Adds all movies in a collection to the blocklist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**collection_id** | **String** | Collection ID | [required] |
**body** | Option<**serde_json::Value**> |  |  |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_blacklist

> delete_blacklist(tmdb_id, media_type)
Remove media from blocklist

**DEPRECATED**: Use `/blocklist/{tmdbId}` instead. This endpoint will be deprecated soon. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tmdb_id** | **String** | tmdbId ID | [required] |
**media_type** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_blocklist

> delete_blocklist(tmdb_id, media_type)
Remove media from blocklist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tmdb_id** | **String** | tmdbId ID | [required] |
**media_type** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_blocklist_collection

> delete_blocklist_collection(collection_id)
Remove collection from blocklist

Removes all movies in a collection from the blocklist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**collection_id** | **String** | Collection ID | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_blacklist

> models::GetBlocklist2XxResponse get_blacklist(take, skip, search, filter)
Returns blocklisted items

**DEPRECATED**: Use `/blocklist` instead. This endpoint will be deprecated soon. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**take** | Option<**f64**> |  |  |
**skip** | Option<**f64**> |  |  |
**search** | Option<**String**> |  |  |
**filter** | Option<**String**> |  |  |[default to manual]

### Return type

[**models::GetBlocklist2XxResponse**](GetBlocklist_2XX_response.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_blacklist_by_tmdb_id

> get_blacklist_by_tmdb_id(tmdb_id, media_type)
Get media from blocklist

**DEPRECATED**: Use `/blocklist/{tmdbId}` instead. This endpoint will be deprecated soon. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tmdb_id** | **String** | tmdbId ID | [required] |
**media_type** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_blocklist

> models::GetBlocklist2XxResponse get_blocklist(take, skip, search, filter)
Returns blocklisted items

Returns list of all blocklisted media

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**take** | Option<**f64**> |  |  |
**skip** | Option<**f64**> |  |  |
**search** | Option<**String**> |  |  |
**filter** | Option<**String**> |  |  |[default to manual]

### Return type

[**models::GetBlocklist2XxResponse**](GetBlocklist_2XX_response.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## get_blocklist_by_tmdb_id

> get_blocklist_by_tmdb_id(tmdb_id, media_type)
Get media from blocklist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tmdb_id** | **String** | tmdbId ID | [required] |
**media_type** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

