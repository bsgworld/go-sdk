# SMSSingleResponseResult

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success, non-zero for various error conditions | 
**ErrorDescription** | **string** | Human-readable error description. \&quot;No errors\&quot; when operation succeeds | 
**Reference** | Pointer to **string** | External reference ID provided in request or auto-generated | [optional] 
**Id** | Pointer to **string** | Internal message ID assigned by SMS Gateway | [optional] 
**Price** | Pointer to **float32** | Actual cost of sending this SMS message | [optional] 
**Currency** | Pointer to **string** | Currency code according to ISO-4217 standard | [optional] 
**OtpCode** | Pointer to **string** | Auto-generated OTP code (only present for destination&#x3D;otp requests) | [optional] 

## Methods

### NewSMSSingleResponseResult

`func NewSMSSingleResponseResult(error_ int32, errorDescription string, ) *SMSSingleResponseResult`

NewSMSSingleResponseResult instantiates a new SMSSingleResponseResult object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSMSSingleResponseResultWithDefaults

`func NewSMSSingleResponseResultWithDefaults() *SMSSingleResponseResult`

NewSMSSingleResponseResultWithDefaults instantiates a new SMSSingleResponseResult object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SMSSingleResponseResult) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SMSSingleResponseResult) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SMSSingleResponseResult) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *SMSSingleResponseResult) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SMSSingleResponseResult) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SMSSingleResponseResult) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetReference

`func (o *SMSSingleResponseResult) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SMSSingleResponseResult) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SMSSingleResponseResult) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SMSSingleResponseResult) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetId

`func (o *SMSSingleResponseResult) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SMSSingleResponseResult) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SMSSingleResponseResult) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SMSSingleResponseResult) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPrice

`func (o *SMSSingleResponseResult) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SMSSingleResponseResult) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SMSSingleResponseResult) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SMSSingleResponseResult) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *SMSSingleResponseResult) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SMSSingleResponseResult) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SMSSingleResponseResult) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SMSSingleResponseResult) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetOtpCode

`func (o *SMSSingleResponseResult) GetOtpCode() string`

GetOtpCode returns the OtpCode field if non-nil, zero value otherwise.

### GetOtpCodeOk

`func (o *SMSSingleResponseResult) GetOtpCodeOk() (*string, bool)`

GetOtpCodeOk returns a tuple with the OtpCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtpCode

`func (o *SMSSingleResponseResult) SetOtpCode(v string)`

SetOtpCode sets OtpCode field to given value.

### HasOtpCode

`func (o *SMSSingleResponseResult) HasOtpCode() bool`

HasOtpCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


