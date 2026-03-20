# ShortUrlsLinks200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ShortUrlLinkSchema**](ShortUrlLinkSchema.md) |  | [optional] 
**Total** | Pointer to **int32** | The total number of items matching the specified criteria | [optional] 

## Methods

### NewShortUrlsLinks200Response

`func NewShortUrlsLinks200Response() *ShortUrlsLinks200Response`

NewShortUrlsLinks200Response instantiates a new ShortUrlsLinks200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewShortUrlsLinks200ResponseWithDefaults

`func NewShortUrlsLinks200ResponseWithDefaults() *ShortUrlsLinks200Response`

NewShortUrlsLinks200ResponseWithDefaults instantiates a new ShortUrlsLinks200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ShortUrlsLinks200Response) GetData() []ShortUrlLinkSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ShortUrlsLinks200Response) GetDataOk() (*[]ShortUrlLinkSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ShortUrlsLinks200Response) SetData(v []ShortUrlLinkSchema)`

SetData sets Data field to given value.

### HasData

`func (o *ShortUrlsLinks200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *ShortUrlsLinks200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ShortUrlsLinks200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ShortUrlsLinks200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ShortUrlsLinks200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


