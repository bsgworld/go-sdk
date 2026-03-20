# ViberPriceCheckResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | **string** | Error description | 
**Totalprice** | Pointer to **float32** | Total calculated price for all messages | [optional] 
**Currency** | Pointer to **string** | Price currency (ISO 4217) | [optional] 

## Methods

### NewViberPriceCheckResponse

`func NewViberPriceCheckResponse(error_ int32, errorDescription string, ) *ViberPriceCheckResponse`

NewViberPriceCheckResponse instantiates a new ViberPriceCheckResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberPriceCheckResponseWithDefaults

`func NewViberPriceCheckResponseWithDefaults() *ViberPriceCheckResponse`

NewViberPriceCheckResponseWithDefaults instantiates a new ViberPriceCheckResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ViberPriceCheckResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ViberPriceCheckResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ViberPriceCheckResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *ViberPriceCheckResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *ViberPriceCheckResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *ViberPriceCheckResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetTotalprice

`func (o *ViberPriceCheckResponse) GetTotalprice() float32`

GetTotalprice returns the Totalprice field if non-nil, zero value otherwise.

### GetTotalpriceOk

`func (o *ViberPriceCheckResponse) GetTotalpriceOk() (*float32, bool)`

GetTotalpriceOk returns a tuple with the Totalprice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalprice

`func (o *ViberPriceCheckResponse) SetTotalprice(v float32)`

SetTotalprice sets Totalprice field to given value.

### HasTotalprice

`func (o *ViberPriceCheckResponse) HasTotalprice() bool`

HasTotalprice returns a boolean if a field has been set.

### GetCurrency

`func (o *ViberPriceCheckResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ViberPriceCheckResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ViberPriceCheckResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ViberPriceCheckResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


