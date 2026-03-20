# ShortUrlsDomainCreate422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | It may be one of the following:  - **short-link.exceptions.domain_exceeded_allowed_limit** - Maximum allowed domain count already reached. Please delete unused domains or upgrade tariff - **Invalid domain name** - Duplicate domain name. This domain already exists use another domain name.  | [optional] 

## Methods

### NewShortUrlsDomainCreate422Response

`func NewShortUrlsDomainCreate422Response() *ShortUrlsDomainCreate422Response`

NewShortUrlsDomainCreate422Response instantiates a new ShortUrlsDomainCreate422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlsDomainCreate422ResponseWithDefaults

`func NewShortUrlsDomainCreate422ResponseWithDefaults() *ShortUrlsDomainCreate422Response`

NewShortUrlsDomainCreate422ResponseWithDefaults instantiates a new ShortUrlsDomainCreate422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ShortUrlsDomainCreate422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ShortUrlsDomainCreate422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ShortUrlsDomainCreate422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ShortUrlsDomainCreate422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


