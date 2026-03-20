# ShortLink

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Link** | **string** | Target url | 
**Placeholder** | **string** | Word in message text that need to be replaced by generated short link | 
**DomainIds** | **[]string** | List of short domain identifiers to use for generate short links to follow at target url | 
**ChangeDomainAfter** | Pointer to **NullableInt32** | Change domain each X messages | [optional] 
**Protocol** | Pointer to **bool** | Add (https) protocol to short link or not | [optional] [default to true]

## Methods

### NewShortLink

`func NewShortLink(link string, placeholder string, domainIds []string, ) *ShortLink`

NewShortLink instantiates a new ShortLink object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortLinkWithDefaults

`func NewShortLinkWithDefaults() *ShortLink`

NewShortLinkWithDefaults instantiates a new ShortLink object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetLink

`func (o *ShortLink) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *ShortLink) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *ShortLink) SetLink(v string)`

SetLink sets Link field to given value.


### GetPlaceholder

`func (o *ShortLink) GetPlaceholder() string`

GetPlaceholder returns the Placeholder field if non-nil, zero value otherwise.

### GetPlaceholderOk

`func (o *ShortLink) GetPlaceholderOk() (*string, bool)`

GetPlaceholderOk returns a tuple with the Placeholder field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPlaceholder

`func (o *ShortLink) SetPlaceholder(v string)`

SetPlaceholder sets Placeholder field to given value.


### GetDomainIds

`func (o *ShortLink) GetDomainIds() []string`

GetDomainIds returns the DomainIds field if non-nil, zero value otherwise.

### GetDomainIdsOk

`func (o *ShortLink) GetDomainIdsOk() (*[]string, bool)`

GetDomainIdsOk returns a tuple with the DomainIds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainIds

`func (o *ShortLink) SetDomainIds(v []string)`

SetDomainIds sets DomainIds field to given value.


### GetChangeDomainAfter

`func (o *ShortLink) GetChangeDomainAfter() int32`

GetChangeDomainAfter returns the ChangeDomainAfter field if non-nil, zero value otherwise.

### GetChangeDomainAfterOk

`func (o *ShortLink) GetChangeDomainAfterOk() (*int32, bool)`

GetChangeDomainAfterOk returns a tuple with the ChangeDomainAfter field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChangeDomainAfter

`func (o *ShortLink) SetChangeDomainAfter(v int32)`

SetChangeDomainAfter sets ChangeDomainAfter field to given value.

### HasChangeDomainAfter

`func (o *ShortLink) HasChangeDomainAfter() bool`

HasChangeDomainAfter returns a boolean if a field has been set.

### SetChangeDomainAfterNil

`func (o *ShortLink) SetChangeDomainAfterNil(b bool)`

 SetChangeDomainAfterNil sets the value for ChangeDomainAfter to be an explicit nil

### UnsetChangeDomainAfter
`func (o *ShortLink) UnsetChangeDomainAfter()`

UnsetChangeDomainAfter ensures that no value is present for ChangeDomainAfter, not even an explicit nil
### GetProtocol

`func (o *ShortLink) GetProtocol() bool`

GetProtocol returns the Protocol field if non-nil, zero value otherwise.

### GetProtocolOk

`func (o *ShortLink) GetProtocolOk() (*bool, bool)`

GetProtocolOk returns a tuple with the Protocol field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetProtocol

`func (o *ShortLink) SetProtocol(v bool)`

SetProtocol sets Protocol field to given value.

### HasProtocol

`func (o *ShortLink) HasProtocol() bool`

HasProtocol returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


