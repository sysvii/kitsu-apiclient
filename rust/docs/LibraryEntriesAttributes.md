# LibraryEntriesAttributes

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**created_at** | Option<**String**> | ISO 8601 date and time | [optional]
**updated_at** | Option<**String**> | ISO 8601 of last modification | [optional]
**status** | Option<[**crate::models::Status6**](status6.md)> |  | [optional]
**progress** | Option<**f32**> | Current episode or chapter | [optional]
**volumes_owned** | Option<**f32**> | Manga only | [optional]
**reconsuming** | Option<**bool**> |  | [optional]
**reconsume_count** | Option<**f32**> |  | [optional]
**notes** | Option<**String**> |  | [optional]
**private** | Option<**bool**> |  | [optional]
**reaction_skipped** | Option<[**crate::models::ReactionSkipped**](reactionSkipped.md)> |  | [optional]
**progressed_at** | Option<**String**> | ISO 8601 of last chapter/episode change | [optional]
**started_at** | Option<**String**> | ISO 8601 of when the user consumed the first chapter/episode | [optional]
**finished_at** | Option<**String**> | ISO 8601 of when the user consumed the last chapter/episode | [optional]
**rating** | Option<**String**> | Deprecated in favour of `ratingTwenty` | [optional]
**rating_twenty** | Option<**f32**> | 2,3..20 rating scale, displayed as 1,1.5..10 | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


