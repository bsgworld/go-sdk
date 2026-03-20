# ShortUrlsClicks200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ClickResource**](ClickResource.md) |  | [optional] 
**Total** | Pointer to **int32** | The total number of items matching the specified criteria | [optional] 

## Methods

### NewShortUrlsClicks200Response

`func NewShortUrlsClicks200Response() *ShortUrlsClicks200Response`

NewShortUrlsClicks200Response instantiates a new ShortUrlsClicks200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlsClicks200ResponseWithDefaults

`func NewShortUrlsClicks200ResponseWithDefaults() *ShortUrlsClicks200Response`

NewShortUrlsClicks200ResponseWithDefaults instantiates a new ShortUrlsClicks200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ShortUrlsClicks200Response) GetData() []ClickResource`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ShortUrlsClicks200Response) GetDataOk() (*[]ClickResource, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ShortUrlsClicks200Response) SetData(v []ClickResource)`

SetData sets Data field to given value.

### HasData

`func (o *ShortUrlsClicks200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *ShortUrlsClicks200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ShortUrlsClicks200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ShortUrlsClicks200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ShortUrlsClicks200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


