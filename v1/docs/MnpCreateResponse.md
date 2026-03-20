# MnpCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | [**[]MnpCreateResponseResultInner**](MnpCreateResponseResultInner.md) | Array of MNP lookup results for each requested number | 
**TotalPrice** | **float32** | Total price for all MNP lookups in the request | 
**Currency** | **string** | Currency code (ISO 4217) | 

## Methods

### NewMnpCreateResponse

`func NewMnpCreateResponse(result []MnpCreateResponseResultInner, totalPrice float32, currency string, ) *MnpCreateResponse`

NewMnpCreateResponse instantiates a new MnpCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpCreateResponseWithDefaults

`func NewMnpCreateResponseWithDefaults() *MnpCreateResponse`

NewMnpCreateResponseWithDefaults instantiates a new MnpCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *MnpCreateResponse) GetResult() []MnpCreateResponseResultInner`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *MnpCreateResponse) GetResultOk() (*[]MnpCreateResponseResultInner, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *MnpCreateResponse) SetResult(v []MnpCreateResponseResultInner)`

SetResult sets Result field to given value.


### GetTotalPrice

`func (o *MnpCreateResponse) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *MnpCreateResponse) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *MnpCreateResponse) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.


### GetCurrency

`func (o *MnpCreateResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *MnpCreateResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *MnpCreateResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


