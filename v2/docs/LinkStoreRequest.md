# LinkStoreRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**DomainId** | **string** | Domain ID from connected short domains from [account](https://app.bsg.world/url-shortener/domains)  **Please note:** *only domains in **active** status accepted* | 
**Link** | **string** | Original link where to short link will redirect | 

## Methods

### NewLinkStoreRequest

`func NewLinkStoreRequest(domainId string, link string, ) *LinkStoreRequest`

NewLinkStoreRequest instantiates a new LinkStoreRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewLinkStoreRequestWithDefaults

`func NewLinkStoreRequestWithDefaults() *LinkStoreRequest`

NewLinkStoreRequestWithDefaults instantiates a new LinkStoreRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDomainId

`func (o *LinkStoreRequest) GetDomainId() string`

GetDomainId returns the DomainId field if non-nil, zero value otherwise.

### GetDomainIdOk

`func (o *LinkStoreRequest) GetDomainIdOk() (*string, bool)`

GetDomainIdOk returns a tuple with the DomainId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDomainId

`func (o *LinkStoreRequest) SetDomainId(v string)`

SetDomainId sets DomainId field to given value.


### GetLink

`func (o *LinkStoreRequest) GetLink() string`

GetLink returns the Link field if non-nil, zero value otherwise.

### GetLinkOk

`func (o *LinkStoreRequest) GetLinkOk() (*string, bool)`

GetLinkOk returns a tuple with the Link field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLink

`func (o *LinkStoreRequest) SetLink(v string)`

SetLink sets Link field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


