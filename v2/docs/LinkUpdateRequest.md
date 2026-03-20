# LinkUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **NullableString** | Name of short link. like a comment | [optional] 
**Slug** | Pointer to **string** | part of short link after domain | [optional] 
**OriginalLink** | Pointer to **string** | Original link where to short link will redirect | [optional] 

## Methods

### NewLinkUpdateRequest

`func NewLinkUpdateRequest() *LinkUpdateRequest`

NewLinkUpdateRequest instantiates a new LinkUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinkUpdateRequestWithDefaults

`func NewLinkUpdateRequestWithDefaults() *LinkUpdateRequest`

NewLinkUpdateRequestWithDefaults instantiates a new LinkUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *LinkUpdateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *LinkUpdateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *LinkUpdateRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *LinkUpdateRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### SetNameNil

`func (o *LinkUpdateRequest) SetNameNil(b bool)`

 SetNameNil sets the value for Name to be an explicit nil

### UnsetName
`func (o *LinkUpdateRequest) UnsetName()`

UnsetName ensures that no value is present for Name, not even an explicit nil
### GetSlug

`func (o *LinkUpdateRequest) GetSlug() string`

GetSlug returns the Slug field if non-nil, zero value otherwise.

### GetSlugOk

`func (o *LinkUpdateRequest) GetSlugOk() (*string, bool)`

GetSlugOk returns a tuple with the Slug field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlug

`func (o *LinkUpdateRequest) SetSlug(v string)`

SetSlug sets Slug field to given value.

### HasSlug

`func (o *LinkUpdateRequest) HasSlug() bool`

HasSlug returns a boolean if a field has been set.

### GetOriginalLink

`func (o *LinkUpdateRequest) GetOriginalLink() string`

GetOriginalLink returns the OriginalLink field if non-nil, zero value otherwise.

### GetOriginalLinkOk

`func (o *LinkUpdateRequest) GetOriginalLinkOk() (*string, bool)`

GetOriginalLinkOk returns a tuple with the OriginalLink field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginalLink

`func (o *LinkUpdateRequest) SetOriginalLink(v string)`

SetOriginalLink sets OriginalLink field to given value.

### HasOriginalLink

`func (o *LinkUpdateRequest) HasOriginalLink() bool`

HasOriginalLink returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


