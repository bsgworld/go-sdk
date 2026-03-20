# SmsBalanceResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success | 
**ErrorDescription** | **string** | Human-readable error description | 
**Amount** | **string** | Current account balance with high precision | 
**Currency** | **string** | Currency code according to ISO-4217 | 
**Limit** | **string** | Credit limit for the account | 

## Methods

### NewSmsBalanceResponse

`func NewSmsBalanceResponse(error_ int32, errorDescription string, amount string, currency string, limit string, ) *SmsBalanceResponse`

NewSmsBalanceResponse instantiates a new SmsBalanceResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsBalanceResponseWithDefaults

`func NewSmsBalanceResponseWithDefaults() *SmsBalanceResponse`

NewSmsBalanceResponseWithDefaults instantiates a new SmsBalanceResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SmsBalanceResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SmsBalanceResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SmsBalanceResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *SmsBalanceResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SmsBalanceResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SmsBalanceResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetAmount

`func (o *SmsBalanceResponse) GetAmount() string`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *SmsBalanceResponse) GetAmountOk() (*string, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *SmsBalanceResponse) SetAmount(v string)`

SetAmount sets Amount field to given value.


### GetCurrency

`func (o *SmsBalanceResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SmsBalanceResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SmsBalanceResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.


### GetLimit

`func (o *SmsBalanceResponse) GetLimit() string`

GetLimit returns the Limit field if non-nil, zero value otherwise.

### GetLimitOk

`func (o *SmsBalanceResponse) GetLimitOk() (*string, bool)`

GetLimitOk returns a tuple with the Limit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimit

`func (o *SmsBalanceResponse) SetLimit(v string)`

SetLimit sets Limit field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


