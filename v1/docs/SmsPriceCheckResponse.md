# SmsPriceCheckResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success. Common errors: 1&#x3D;Invalid phone, 7&#x3D;Invalid originator, 24&#x3D;Invalid payload JSON, 14&#x3D;Not enough balance, 15&#x3D;Invalid price grid | 
**ErrorDescription** | **string** | Human-readable error description | 
**Totalprice** | **float32** | Total calculated price for the SMS message(s) that would be sent | 
**Currency** | **string** | Currency code according to ISO-4217 standard | 

## Methods

### NewSmsPriceCheckResponse

`func NewSmsPriceCheckResponse(error_ int32, errorDescription string, totalprice float32, currency string, ) *SmsPriceCheckResponse`

NewSmsPriceCheckResponse instantiates a new SmsPriceCheckResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsPriceCheckResponseWithDefaults

`func NewSmsPriceCheckResponseWithDefaults() *SmsPriceCheckResponse`

NewSmsPriceCheckResponseWithDefaults instantiates a new SmsPriceCheckResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SmsPriceCheckResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SmsPriceCheckResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SmsPriceCheckResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *SmsPriceCheckResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SmsPriceCheckResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SmsPriceCheckResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetTotalprice

`func (o *SmsPriceCheckResponse) GetTotalprice() float32`

GetTotalprice returns the Totalprice field if non-nil, zero value otherwise.

### GetTotalpriceOk

`func (o *SmsPriceCheckResponse) GetTotalpriceOk() (*float32, bool)`

GetTotalpriceOk returns a tuple with the Totalprice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalprice

`func (o *SmsPriceCheckResponse) SetTotalprice(v float32)`

SetTotalprice sets Totalprice field to given value.


### GetCurrency

`func (o *SmsPriceCheckResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SmsPriceCheckResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SmsPriceCheckResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


