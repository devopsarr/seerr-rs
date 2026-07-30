# CreateRequestRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**media_type** | **MediaType** |  (enum: movie, tv) | 
**media_id** | **f64** |  | 
**tvdb_id** | Option<**f64**> |  | [optional]
**seasons** | Option<[**models::CreateRequestRequestSeasons**](CreateRequestRequestSeasons.md)> |  | [optional]
**is4k** | Option<**bool**> |  | [optional]
**server_id** | Option<**f64**> |  | [optional]
**profile_id** | Option<**f64**> |  | [optional]
**root_folder** | Option<**String**> |  | [optional]
**language_profile_id** | Option<**f64**> |  | [optional]
**user_id** | Option<**f64**> |  | [optional]
**ignore_quota** | Option<**bool**> | If true, this request will not count against the user's quota. Requires MANAGE_REQUESTS permission. | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


