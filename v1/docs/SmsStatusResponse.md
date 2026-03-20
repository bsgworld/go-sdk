# SmsStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success, 20 for \&quot;SMS not found\&quot; | 
**ErrorDescription** | **string** | Human-readable error description | 
**Id** | Pointer to **string** | Internal message ID assigned by SMS Gateway | [optional] 
**Msisdn** | Pointer to **string** | Destination phone number in international format | [optional] 
**Reference** | Pointer to **string** | External reference ID provided during creation | [optional] 
**TimeIn** | Pointer to **time.Time** | Timestamp when message was received | [optional] 
**TimeSent** | Pointer to **NullableTime** | Timestamp when message was sent to operator | [optional] 
**TimeDr** | Pointer to **NullableTime** | Timestamp when delivery report was received | [optional] 
**Status** | Pointer to **string** | Current message status in delivery pipeline | [optional] 
**Price** | Pointer to **float32** | Actual cost charged for this message | [optional] 
**Currency** | Pointer to **string** | Currency code for the price | [optional] 

## Methods

### NewSmsStatusResponse

`func NewSmsStatusResponse(error_ int32, errorDescription string, ) *SmsStatusResponse`

NewSmsStatusResponse instantiates a new SmsStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsStatusResponseWithDefaults

`func NewSmsStatusResponseWithDefaults() *SmsStatusResponse`

NewSmsStatusResponseWithDefaults instantiates a new SmsStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SmsStatusResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SmsStatusResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SmsStatusResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *SmsStatusResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SmsStatusResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SmsStatusResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetId

`func (o *SmsStatusResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SmsStatusResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SmsStatusResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SmsStatusResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMsisdn

`func (o *SmsStatusResponse) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SmsStatusResponse) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SmsStatusResponse) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *SmsStatusResponse) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetReference

`func (o *SmsStatusResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SmsStatusResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SmsStatusResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SmsStatusResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTimeIn

`func (o *SmsStatusResponse) GetTimeIn() time.Time`

GetTimeIn returns the TimeIn field if non-nil, zero value otherwise.

### GetTimeInOk

`func (o *SmsStatusResponse) GetTimeInOk() (*time.Time, bool)`

GetTimeInOk returns a tuple with the TimeIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeIn

`func (o *SmsStatusResponse) SetTimeIn(v time.Time)`

SetTimeIn sets TimeIn field to given value.

### HasTimeIn

`func (o *SmsStatusResponse) HasTimeIn() bool`

HasTimeIn returns a boolean if a field has been set.

### GetTimeSent

`func (o *SmsStatusResponse) GetTimeSent() time.Time`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *SmsStatusResponse) GetTimeSentOk() (*time.Time, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *SmsStatusResponse) SetTimeSent(v time.Time)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *SmsStatusResponse) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### SetTimeSentNil

`func (o *SmsStatusResponse) SetTimeSentNil(b bool)`

 SetTimeSentNil sets the value for TimeSent to be an explicit nil

### UnsetTimeSent
`func (o *SmsStatusResponse) UnsetTimeSent()`

UnsetTimeSent ensures that no value is present for TimeSent, not even an explicit nil
### GetTimeDr

`func (o *SmsStatusResponse) GetTimeDr() time.Time`

GetTimeDr returns the TimeDr field if non-nil, zero value otherwise.

### GetTimeDrOk

`func (o *SmsStatusResponse) GetTimeDrOk() (*time.Time, bool)`

GetTimeDrOk returns a tuple with the TimeDr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeDr

`func (o *SmsStatusResponse) SetTimeDr(v time.Time)`

SetTimeDr sets TimeDr field to given value.

### HasTimeDr

`func (o *SmsStatusResponse) HasTimeDr() bool`

HasTimeDr returns a boolean if a field has been set.

### SetTimeDrNil

`func (o *SmsStatusResponse) SetTimeDrNil(b bool)`

 SetTimeDrNil sets the value for TimeDr to be an explicit nil

### UnsetTimeDr
`func (o *SmsStatusResponse) UnsetTimeDr()`

UnsetTimeDr ensures that no value is present for TimeDr, not even an explicit nil
### GetStatus

`func (o *SmsStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SmsStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SmsStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SmsStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPrice

`func (o *SmsStatusResponse) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SmsStatusResponse) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SmsStatusResponse) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SmsStatusResponse) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *SmsStatusResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SmsStatusResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SmsStatusResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SmsStatusResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


