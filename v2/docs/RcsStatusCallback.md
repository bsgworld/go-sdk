# RcsStatusCallback

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **int32** | error code, 0 - if successful | [optional] 
**ErrorDescription** | Pointer to **string** | error description | [optional] 
**Id** | Pointer to **int32** | Message ID – a unique identifier automatically generated on the Platform when the message is created | [optional] 
**Msisdn** | Pointer to **string** | Phone number | [optional] 
**Reference** | Pointer to **string** | external unique ID. String up to 32 characters containing only alpha numeric characters.  **Please note:** messages with duplicate reference_id will be rejected | [optional] 
**TimeIn** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**TimeSent** | Pointer to **NullableTime** | Date and time of sending the message | [optional] 
**TimeDr** | Pointer to **NullableTime** | Date and time of receipt of the delivery report response | [optional] 
**Status** | Pointer to [**MessageStatus**](MessageStatus.md) |  | [optional] 
**Price** | Pointer to **float32** | Message price | [optional] 
**Currency** | Pointer to **string** | The currency code of the account. Specified according to the ISO-4217 standard | [optional] 

## Methods

### NewRcsStatusCallback

`func NewRcsStatusCallback() *RcsStatusCallback`

NewRcsStatusCallback instantiates a new RcsStatusCallback object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewRcsStatusCallbackWithDefaults

`func NewRcsStatusCallbackWithDefaults() *RcsStatusCallback`

NewRcsStatusCallbackWithDefaults instantiates a new RcsStatusCallback object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *RcsStatusCallback) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *RcsStatusCallback) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *RcsStatusCallback) SetError(v int32)`

SetError sets Error field to given value.

### HasError

`func (o *RcsStatusCallback) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorDescription

`func (o *RcsStatusCallback) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *RcsStatusCallback) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *RcsStatusCallback) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.

### HasErrorDescription

`func (o *RcsStatusCallback) HasErrorDescription() bool`

HasErrorDescription returns a boolean if a field has been set.

### GetId

`func (o *RcsStatusCallback) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *RcsStatusCallback) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *RcsStatusCallback) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *RcsStatusCallback) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMsisdn

`func (o *RcsStatusCallback) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *RcsStatusCallback) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *RcsStatusCallback) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *RcsStatusCallback) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetReference

`func (o *RcsStatusCallback) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *RcsStatusCallback) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *RcsStatusCallback) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *RcsStatusCallback) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTimeIn

`func (o *RcsStatusCallback) GetTimeIn() time.Time`

GetTimeIn returns the TimeIn field if non-nil, zero value otherwise.

### GetTimeInOk

`func (o *RcsStatusCallback) GetTimeInOk() (*time.Time, bool)`

GetTimeInOk returns a tuple with the TimeIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeIn

`func (o *RcsStatusCallback) SetTimeIn(v time.Time)`

SetTimeIn sets TimeIn field to given value.

### HasTimeIn

`func (o *RcsStatusCallback) HasTimeIn() bool`

HasTimeIn returns a boolean if a field has been set.

### GetTimeSent

`func (o *RcsStatusCallback) GetTimeSent() time.Time`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *RcsStatusCallback) GetTimeSentOk() (*time.Time, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *RcsStatusCallback) SetTimeSent(v time.Time)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *RcsStatusCallback) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### SetTimeSentNil

`func (o *RcsStatusCallback) SetTimeSentNil(b bool)`

 SetTimeSentNil sets the value for TimeSent to be an explicit nil

### UnsetTimeSent
`func (o *RcsStatusCallback) UnsetTimeSent()`

UnsetTimeSent ensures that no value is present for TimeSent, not even an explicit nil
### GetTimeDr

`func (o *RcsStatusCallback) GetTimeDr() time.Time`

GetTimeDr returns the TimeDr field if non-nil, zero value otherwise.

### GetTimeDrOk

`func (o *RcsStatusCallback) GetTimeDrOk() (*time.Time, bool)`

GetTimeDrOk returns a tuple with the TimeDr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeDr

`func (o *RcsStatusCallback) SetTimeDr(v time.Time)`

SetTimeDr sets TimeDr field to given value.

### HasTimeDr

`func (o *RcsStatusCallback) HasTimeDr() bool`

HasTimeDr returns a boolean if a field has been set.

### SetTimeDrNil

`func (o *RcsStatusCallback) SetTimeDrNil(b bool)`

 SetTimeDrNil sets the value for TimeDr to be an explicit nil

### UnsetTimeDr
`func (o *RcsStatusCallback) UnsetTimeDr()`

UnsetTimeDr ensures that no value is present for TimeDr, not even an explicit nil
### GetStatus

`func (o *RcsStatusCallback) GetStatus() MessageStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *RcsStatusCallback) GetStatusOk() (*MessageStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *RcsStatusCallback) SetStatus(v MessageStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *RcsStatusCallback) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPrice

`func (o *RcsStatusCallback) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *RcsStatusCallback) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *RcsStatusCallback) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *RcsStatusCallback) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *RcsStatusCallback) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *RcsStatusCallback) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *RcsStatusCallback) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *RcsStatusCallback) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


