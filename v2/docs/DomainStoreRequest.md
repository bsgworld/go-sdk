# DomainStoreRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | short domain | 
**NotFoundPage** | Pointer to **string** | Url to redirect if original link return status 404 not found | [optional] 
**SlugType** | [**ShortDomainSlugType**](ShortDomainSlugType.md) |  | 

## Methods

### NewDomainStoreRequest

`func NewDomainStoreRequest(name string, slugType ShortDomainSlugType, ) *DomainStoreRequest`

NewDomainStoreRequest instantiates a new DomainStoreRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDomainStoreRequestWithDefaults

`func NewDomainStoreRequestWithDefaults() *DomainStoreRequest`

NewDomainStoreRequestWithDefaults instantiates a new DomainStoreRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *DomainStoreRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DomainStoreRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DomainStoreRequest) SetName(v string)`

SetName sets Name field to given value.


### GetNotFoundPage

`func (o *DomainStoreRequest) GetNotFoundPage() string`

GetNotFoundPage returns the NotFoundPage field if non-nil, zero value otherwise.

### GetNotFoundPageOk

`func (o *DomainStoreRequest) GetNotFoundPageOk() (*string, bool)`

GetNotFoundPageOk returns a tuple with the NotFoundPage field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNotFoundPage

`func (o *DomainStoreRequest) SetNotFoundPage(v string)`

SetNotFoundPage sets NotFoundPage field to given value.

### HasNotFoundPage

`func (o *DomainStoreRequest) HasNotFoundPage() bool`

HasNotFoundPage returns a boolean if a field has been set.

### GetSlugType

`func (o *DomainStoreRequest) GetSlugType() ShortDomainSlugType`

GetSlugType returns the SlugType field if non-nil, zero value otherwise.

### GetSlugTypeOk

`func (o *DomainStoreRequest) GetSlugTypeOk() (*ShortDomainSlugType, bool)`

GetSlugTypeOk returns a tuple with the SlugType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSlugType

`func (o *DomainStoreRequest) SetSlugType(v ShortDomainSlugType)`

SetSlugType sets SlugType field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


