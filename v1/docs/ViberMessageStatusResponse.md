# ViberMessageStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** |  | 
**ErrorDescription** | **string** |  | 
**Id** | Pointer to **string** |  | [optional] 
**Msisdn** | Pointer to **string** |  | [optional] 
**Reference** | Pointer to **string** |  | [optional] 
**TimeIn** | Pointer to **string** |  | [optional] 
**TimeSent** | Pointer to **NullableString** |  | [optional] 
**TimeDr** | Pointer to **NullableString** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Price** | Pointer to **float32** |  | [optional] 
**Currency** | Pointer to **string** |  | [optional] 

## Methods

### NewViberMessageStatusResponse

`func NewViberMessageStatusResponse(error_ int32, errorDescription string, ) *ViberMessageStatusResponse`

NewViberMessageStatusResponse instantiates a new ViberMessageStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberMessageStatusResponseWithDefaults

`func NewViberMessageStatusResponseWithDefaults() *ViberMessageStatusResponse`

NewViberMessageStatusResponseWithDefaults instantiates a new ViberMessageStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ViberMessageStatusResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ViberMessageStatusResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ViberMessageStatusResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *ViberMessageStatusResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *ViberMessageStatusResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *ViberMessageStatusResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetId

`func (o *ViberMessageStatusResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ViberMessageStatusResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ViberMessageStatusResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ViberMessageStatusResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMsisdn

`func (o *ViberMessageStatusResponse) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *ViberMessageStatusResponse) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *ViberMessageStatusResponse) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *ViberMessageStatusResponse) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetReference

`func (o *ViberMessageStatusResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ViberMessageStatusResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ViberMessageStatusResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ViberMessageStatusResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTimeIn

`func (o *ViberMessageStatusResponse) GetTimeIn() string`

GetTimeIn returns the TimeIn field if non-nil, zero value otherwise.

### GetTimeInOk

`func (o *ViberMessageStatusResponse) GetTimeInOk() (*string, bool)`

GetTimeInOk returns a tuple with the TimeIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeIn

`func (o *ViberMessageStatusResponse) SetTimeIn(v string)`

SetTimeIn sets TimeIn field to given value.

### HasTimeIn

`func (o *ViberMessageStatusResponse) HasTimeIn() bool`

HasTimeIn returns a boolean if a field has been set.

### GetTimeSent

`func (o *ViberMessageStatusResponse) GetTimeSent() string`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *ViberMessageStatusResponse) GetTimeSentOk() (*string, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *ViberMessageStatusResponse) SetTimeSent(v string)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *ViberMessageStatusResponse) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### SetTimeSentNil

`func (o *ViberMessageStatusResponse) SetTimeSentNil(b bool)`

 SetTimeSentNil sets the value for TimeSent to be an explicit nil

### UnsetTimeSent
`func (o *ViberMessageStatusResponse) UnsetTimeSent()`

UnsetTimeSent ensures that no value is present for TimeSent, not even an explicit nil
### GetTimeDr

`func (o *ViberMessageStatusResponse) GetTimeDr() string`

GetTimeDr returns the TimeDr field if non-nil, zero value otherwise.

### GetTimeDrOk

`func (o *ViberMessageStatusResponse) GetTimeDrOk() (*string, bool)`

GetTimeDrOk returns a tuple with the TimeDr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeDr

`func (o *ViberMessageStatusResponse) SetTimeDr(v string)`

SetTimeDr sets TimeDr field to given value.

### HasTimeDr

`func (o *ViberMessageStatusResponse) HasTimeDr() bool`

HasTimeDr returns a boolean if a field has been set.

### SetTimeDrNil

`func (o *ViberMessageStatusResponse) SetTimeDrNil(b bool)`

 SetTimeDrNil sets the value for TimeDr to be an explicit nil

### UnsetTimeDr
`func (o *ViberMessageStatusResponse) UnsetTimeDr()`

UnsetTimeDr ensures that no value is present for TimeDr, not even an explicit nil
### GetStatus

`func (o *ViberMessageStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ViberMessageStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ViberMessageStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ViberMessageStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPrice

`func (o *ViberMessageStatusResponse) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ViberMessageStatusResponse) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ViberMessageStatusResponse) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ViberMessageStatusResponse) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *ViberMessageStatusResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ViberMessageStatusResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ViberMessageStatusResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ViberMessageStatusResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


