# StoplistSearchMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | Pointer to [**MetaPage**](MetaPage.md) |  | [optional] 
**Search** | Pointer to [**StoplistSearchCriteria**](StoplistSearchCriteria.md) |  | [optional] 

## Methods

### NewStoplistSearchMeta

`func NewStoplistSearchMeta() *StoplistSearchMeta`

NewStoplistSearchMeta instantiates a new StoplistSearchMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoplistSearchMetaWithDefaults

`func NewStoplistSearchMetaWithDefaults() *StoplistSearchMeta`

NewStoplistSearchMetaWithDefaults instantiates a new StoplistSearchMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *StoplistSearchMeta) GetPage() MetaPage`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *StoplistSearchMeta) GetPageOk() (*MetaPage, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *StoplistSearchMeta) SetPage(v MetaPage)`

SetPage sets Page field to given value.

### HasPage

`func (o *StoplistSearchMeta) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSearch

`func (o *StoplistSearchMeta) GetSearch() StoplistSearchCriteria`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *StoplistSearchMeta) GetSearchOk() (*StoplistSearchCriteria, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *StoplistSearchMeta) SetSearch(v StoplistSearchCriteria)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *StoplistSearchMeta) HasSearch() bool`

HasSearch returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


