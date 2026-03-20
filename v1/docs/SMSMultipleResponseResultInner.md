# SMSMultipleResponseResultInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **int32** | Error code: 0 for success, non-zero for various error conditions | [optional] 
**ErrorDescription** | Pointer to **string** | Human-readable error description. \&quot;No errors\&quot; when operation succeeds | [optional] 
**Reference** | Pointer to **string** | External reference ID provided in request or auto-generated | [optional] 
**Id** | Pointer to **string** | Internal message ID assigned by SMS Gateway | [optional] 
**Price** | Pointer to **float32** | Actual cost of sending this SMS message | [optional] 
**Currency** | Pointer to **string** | Currency code according to ISO-4217 standard | [optional] 
**OtpCode** | Pointer to **string** | Generated OTP code (only for OTP destination type) | [optional] 

## Methods

### NewSMSMultipleResponseResultInner

`func NewSMSMultipleResponseResultInner() *SMSMultipleResponseResultInner`

NewSMSMultipleResponseResultInner instantiates a new SMSMultipleResponseResultInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSMSMultipleResponseResultInnerWithDefaults

`func NewSMSMultipleResponseResultInnerWithDefaults() *SMSMultipleResponseResultInner`

NewSMSMultipleResponseResultInnerWithDefaults instantiates a new SMSMultipleResponseResultInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SMSMultipleResponseResultInner) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SMSMultipleResponseResultInner) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SMSMultipleResponseResultInner) SetError(v int32)`

SetError sets Error field to given value.

### HasError

`func (o *SMSMultipleResponseResultInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorDescription

`func (o *SMSMultipleResponseResultInner) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SMSMultipleResponseResultInner) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SMSMultipleResponseResultInner) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.

### HasErrorDescription

`func (o *SMSMultipleResponseResultInner) HasErrorDescription() bool`

HasErrorDescription returns a boolean if a field has been set.

### GetReference

`func (o *SMSMultipleResponseResultInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SMSMultipleResponseResultInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SMSMultipleResponseResultInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SMSMultipleResponseResultInner) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetId

`func (o *SMSMultipleResponseResultInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SMSMultipleResponseResultInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SMSMultipleResponseResultInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SMSMultipleResponseResultInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPrice

`func (o *SMSMultipleResponseResultInner) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SMSMultipleResponseResultInner) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SMSMultipleResponseResultInner) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SMSMultipleResponseResultInner) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *SMSMultipleResponseResultInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SMSMultipleResponseResultInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SMSMultipleResponseResultInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SMSMultipleResponseResultInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetOtpCode

`func (o *SMSMultipleResponseResultInner) GetOtpCode() string`

GetOtpCode returns the OtpCode field if non-nil, zero value otherwise.

### GetOtpCodeOk

`func (o *SMSMultipleResponseResultInner) GetOtpCodeOk() (*string, bool)`

GetOtpCodeOk returns a tuple with the OtpCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOtpCode

`func (o *SMSMultipleResponseResultInner) SetOtpCode(v string)`

SetOtpCode sets OtpCode field to given value.

### HasOtpCode

`func (o *SMSMultipleResponseResultInner) HasOtpCode() bool`

HasOtpCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


