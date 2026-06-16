# \WatchlistApi

All URIs are relative to *http://localhost:5055/api/v1*

Method | HTTP request | Description
------------- | ------------- | -------------
[**create_watchlist**](WatchlistApi.md#create_watchlist) | **POST** /watchlist | Add media to watchlist
[**delete_watchlist**](WatchlistApi.md#delete_watchlist) | **DELETE** /watchlist/{tmdbId} | Delete watchlist item



## create_watchlist

> models::Watchlist create_watchlist(watchlist)
Add media to watchlist

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**watchlist** | [**Watchlist**](Watchlist.md) |  | [required] |

### Return type

[**models::Watchlist**](Watchlist.md)

### Authorization

[apiKey](../README.md#apiKey), [cookieAuth](../README.md#cookieAuth)

### HTTP request headers

- **Content-Type**: application/json
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## delete_watchlist

> delete_watchlist(tmdb_id, media_type)
Delete watchlist item

Removes a watchlist item.

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

