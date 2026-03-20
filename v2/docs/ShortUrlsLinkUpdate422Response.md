# ShortUrlsLinkUpdate422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | It may be one of the following:   - **The short link already exists** This error can occur when passed slug already used by another short link on this domain. Please try another slug. - **Short link not found** This error can occur when passed link id doesn&#39;t exist. Please check short link id.  | [optional] 

## Methods

### NewShortUrlsLinkUpdate422Response

`func NewShortUrlsLinkUpdate422Response() *ShortUrlsLinkUpdate422Response`

NewShortUrlsLinkUpdate422Response instantiates a new ShortUrlsLinkUpdate422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlsLinkUpdate422ResponseWithDefaults

`func NewShortUrlsLinkUpdate422ResponseWithDefaults() *ShortUrlsLinkUpdate422Response`

NewShortUrlsLinkUpdate422ResponseWithDefaults instantiates a new ShortUrlsLinkUpdate422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ShortUrlsLinkUpdate422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ShortUrlsLinkUpdate422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ShortUrlsLinkUpdate422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ShortUrlsLinkUpdate422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


