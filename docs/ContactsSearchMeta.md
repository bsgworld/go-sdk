# ContactsSearchMeta

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Page** | Pointer to [**MetaPage**](MetaPage.md) |  | [optional] 
**Search** | Pointer to [**ContactsSearchCriteria**](ContactsSearchCriteria.md) |  | [optional] 

## Methods

### NewContactsSearchMeta

`func NewContactsSearchMeta() *ContactsSearchMeta`

NewContactsSearchMeta instantiates a new ContactsSearchMeta object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsSearchMetaWithDefaults

`func NewContactsSearchMetaWithDefaults() *ContactsSearchMeta`

NewContactsSearchMetaWithDefaults instantiates a new ContactsSearchMeta object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPage

`func (o *ContactsSearchMeta) GetPage() MetaPage`

GetPage returns the Page field if non-nil, zero value otherwise.

### GetPageOk

`func (o *ContactsSearchMeta) GetPageOk() (*MetaPage, bool)`

GetPageOk returns a tuple with the Page field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPage

`func (o *ContactsSearchMeta) SetPage(v MetaPage)`

SetPage sets Page field to given value.

### HasPage

`func (o *ContactsSearchMeta) HasPage() bool`

HasPage returns a boolean if a field has been set.

### GetSearch

`func (o *ContactsSearchMeta) GetSearch() ContactsSearchCriteria`

GetSearch returns the Search field if non-nil, zero value otherwise.

### GetSearchOk

`func (o *ContactsSearchMeta) GetSearchOk() (*ContactsSearchCriteria, bool)`

GetSearchOk returns a tuple with the Search field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSearch

`func (o *ContactsSearchMeta) SetSearch(v ContactsSearchCriteria)`

SetSearch sets Search field to given value.

### HasSearch

`func (o *ContactsSearchMeta) HasSearch() bool`

HasSearch returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


