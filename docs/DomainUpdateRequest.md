# DomainUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**NotFoundPage** | Pointer to **string** | Url to redirect if original link return status 404 not found | [optional] 
**SlugType** | Pointer to [**ShortDomainSlugType**](ShortDomainSlugType.md) |  | [optional] 
**IsDefault** | Pointer to **bool** | This domain is default for generating short links | [optional] [default to true]

## Methods

### NewDomainUpdateRequest

`func NewDomainUpdateRequest() *DomainUpdateRequest`

NewDomainUpdateRequest instantiates a new DomainUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainUpdateRequestWithDefaults

`func NewDomainUpdateRequestWithDefaults() *DomainUpdateRequest`

NewDomainUpdateRequestWithDefaults instantiates a new DomainUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetNotFoundPage

`func (o *DomainUpdateRequest) GetNotFoundPage() string`

GetNotFoundPage returns the NotFoundPage field if non-nil, zero value otherwise.

### GetNotFoundPageOk

`func (o *DomainUpdateRequest) GetNotFoundPageOk() (*string, bool)`

GetNotFoundPageOk returns a tuple with the NotFoundPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotFoundPage

`func (o *DomainUpdateRequest) SetNotFoundPage(v string)`

SetNotFoundPage sets NotFoundPage field to given value.

### HasNotFoundPage

`func (o *DomainUpdateRequest) HasNotFoundPage() bool`

HasNotFoundPage returns a boolean if a field has been set.

### GetSlugType

`func (o *DomainUpdateRequest) GetSlugType() ShortDomainSlugType`

GetSlugType returns the SlugType field if non-nil, zero value otherwise.

### GetSlugTypeOk

`func (o *DomainUpdateRequest) GetSlugTypeOk() (*ShortDomainSlugType, bool)`

GetSlugTypeOk returns a tuple with the SlugType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlugType

`func (o *DomainUpdateRequest) SetSlugType(v ShortDomainSlugType)`

SetSlugType sets SlugType field to given value.

### HasSlugType

`func (o *DomainUpdateRequest) HasSlugType() bool`

HasSlugType returns a boolean if a field has been set.

### GetIsDefault

`func (o *DomainUpdateRequest) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *DomainUpdateRequest) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *DomainUpdateRequest) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *DomainUpdateRequest) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


