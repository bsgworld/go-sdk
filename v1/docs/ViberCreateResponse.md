# ViberCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | [**[]ViberCreateResponseResultInner**](ViberCreateResponseResultInner.md) | Array of message results | 
**TotalPrice** | Pointer to **NullableFloat32** | Total price for all messages. Only included in response when total_price is not zero (i.e. at least one message was created successfully). | [optional] 
**Currency** | Pointer to **NullableString** | Currency for total_price. Only included when total_price is present. | [optional] 

## Methods

### NewViberCreateResponse

`func NewViberCreateResponse(result []ViberCreateResponseResultInner, ) *ViberCreateResponse`

NewViberCreateResponse instantiates a new ViberCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberCreateResponseWithDefaults

`func NewViberCreateResponseWithDefaults() *ViberCreateResponse`

NewViberCreateResponseWithDefaults instantiates a new ViberCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *ViberCreateResponse) GetResult() []ViberCreateResponseResultInner`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ViberCreateResponse) GetResultOk() (*[]ViberCreateResponseResultInner, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ViberCreateResponse) SetResult(v []ViberCreateResponseResultInner)`

SetResult sets Result field to given value.


### GetTotalPrice

`func (o *ViberCreateResponse) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *ViberCreateResponse) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *ViberCreateResponse) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.

### HasTotalPrice

`func (o *ViberCreateResponse) HasTotalPrice() bool`

HasTotalPrice returns a boolean if a field has been set.

### SetTotalPriceNil

`func (o *ViberCreateResponse) SetTotalPriceNil(b bool)`

 SetTotalPriceNil sets the value for TotalPrice to be an explicit nil

### UnsetTotalPrice
`func (o *ViberCreateResponse) UnsetTotalPrice()`

UnsetTotalPrice ensures that no value is present for TotalPrice, not even an explicit nil
### GetCurrency

`func (o *ViberCreateResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ViberCreateResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ViberCreateResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ViberCreateResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### SetCurrencyNil

`func (o *ViberCreateResponse) SetCurrencyNil(b bool)`

 SetCurrencyNil sets the value for Currency to be an explicit nil

### UnsetCurrency
`func (o *ViberCreateResponse) UnsetCurrency()`

UnsetCurrency ensures that no value is present for Currency, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


