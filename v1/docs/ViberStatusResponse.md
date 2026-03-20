# ViberStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success, 40 &#x3D; not found) | 
**ErrorDescription** | **string** | Error description | 
**Id** | Pointer to **string** | Internal message ID | [optional] 
**Msisdn** | Pointer to **string** | Destination phone number | [optional] 
**Reference** | Pointer to **string** | External reference ID | [optional] 
**TimeIn** | Pointer to **NullableString** | Timestamp when message was received | [optional] 
**TimeSent** | Pointer to **NullableString** | Timestamp when message was sent | [optional] 
**TimeDr** | Pointer to **NullableString** | Timestamp when delivery report was received | [optional] 
**Status** | Pointer to **string** | Current message status | [optional] 
**Price** | Pointer to **float32** | Message cost | [optional] 
**Currency** | Pointer to **string** | Price currency | [optional] 
**AltRoute** | Pointer to [**[]ViberStatusResponseAltRouteInner**](ViberStatusResponseAltRouteInner.md) | Alternative route information (when resend_on_undelivery is used) | [optional] 
**AltRouteMessages** | Pointer to [**[]ViberStatusResponseAltRouteMessagesInner**](ViberStatusResponseAltRouteMessagesInner.md) | Alternative route messages details | [optional] 

## Methods

### NewViberStatusResponse

`func NewViberStatusResponse(error_ int32, errorDescription string, ) *ViberStatusResponse`

NewViberStatusResponse instantiates a new ViberStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberStatusResponseWithDefaults

`func NewViberStatusResponseWithDefaults() *ViberStatusResponse`

NewViberStatusResponseWithDefaults instantiates a new ViberStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ViberStatusResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ViberStatusResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ViberStatusResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *ViberStatusResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *ViberStatusResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *ViberStatusResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetId

`func (o *ViberStatusResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ViberStatusResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ViberStatusResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ViberStatusResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMsisdn

`func (o *ViberStatusResponse) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *ViberStatusResponse) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *ViberStatusResponse) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *ViberStatusResponse) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetReference

`func (o *ViberStatusResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ViberStatusResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ViberStatusResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ViberStatusResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTimeIn

`func (o *ViberStatusResponse) GetTimeIn() string`

GetTimeIn returns the TimeIn field if non-nil, zero value otherwise.

### GetTimeInOk

`func (o *ViberStatusResponse) GetTimeInOk() (*string, bool)`

GetTimeInOk returns a tuple with the TimeIn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeIn

`func (o *ViberStatusResponse) SetTimeIn(v string)`

SetTimeIn sets TimeIn field to given value.

### HasTimeIn

`func (o *ViberStatusResponse) HasTimeIn() bool`

HasTimeIn returns a boolean if a field has been set.

### SetTimeInNil

`func (o *ViberStatusResponse) SetTimeInNil(b bool)`

 SetTimeInNil sets the value for TimeIn to be an explicit nil

### UnsetTimeIn
`func (o *ViberStatusResponse) UnsetTimeIn()`

UnsetTimeIn ensures that no value is present for TimeIn, not even an explicit nil
### GetTimeSent

`func (o *ViberStatusResponse) GetTimeSent() string`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *ViberStatusResponse) GetTimeSentOk() (*string, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *ViberStatusResponse) SetTimeSent(v string)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *ViberStatusResponse) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### SetTimeSentNil

`func (o *ViberStatusResponse) SetTimeSentNil(b bool)`

 SetTimeSentNil sets the value for TimeSent to be an explicit nil

### UnsetTimeSent
`func (o *ViberStatusResponse) UnsetTimeSent()`

UnsetTimeSent ensures that no value is present for TimeSent, not even an explicit nil
### GetTimeDr

`func (o *ViberStatusResponse) GetTimeDr() string`

GetTimeDr returns the TimeDr field if non-nil, zero value otherwise.

### GetTimeDrOk

`func (o *ViberStatusResponse) GetTimeDrOk() (*string, bool)`

GetTimeDrOk returns a tuple with the TimeDr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeDr

`func (o *ViberStatusResponse) SetTimeDr(v string)`

SetTimeDr sets TimeDr field to given value.

### HasTimeDr

`func (o *ViberStatusResponse) HasTimeDr() bool`

HasTimeDr returns a boolean if a field has been set.

### SetTimeDrNil

`func (o *ViberStatusResponse) SetTimeDrNil(b bool)`

 SetTimeDrNil sets the value for TimeDr to be an explicit nil

### UnsetTimeDr
`func (o *ViberStatusResponse) UnsetTimeDr()`

UnsetTimeDr ensures that no value is present for TimeDr, not even an explicit nil
### GetStatus

`func (o *ViberStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ViberStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ViberStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ViberStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPrice

`func (o *ViberStatusResponse) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ViberStatusResponse) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ViberStatusResponse) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ViberStatusResponse) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *ViberStatusResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ViberStatusResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ViberStatusResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ViberStatusResponse) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetAltRoute

`func (o *ViberStatusResponse) GetAltRoute() []ViberStatusResponseAltRouteInner`

GetAltRoute returns the AltRoute field if non-nil, zero value otherwise.

### GetAltRouteOk

`func (o *ViberStatusResponse) GetAltRouteOk() (*[]ViberStatusResponseAltRouteInner, bool)`

GetAltRouteOk returns a tuple with the AltRoute field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltRoute

`func (o *ViberStatusResponse) SetAltRoute(v []ViberStatusResponseAltRouteInner)`

SetAltRoute sets AltRoute field to given value.

### HasAltRoute

`func (o *ViberStatusResponse) HasAltRoute() bool`

HasAltRoute returns a boolean if a field has been set.

### SetAltRouteNil

`func (o *ViberStatusResponse) SetAltRouteNil(b bool)`

 SetAltRouteNil sets the value for AltRoute to be an explicit nil

### UnsetAltRoute
`func (o *ViberStatusResponse) UnsetAltRoute()`

UnsetAltRoute ensures that no value is present for AltRoute, not even an explicit nil
### GetAltRouteMessages

`func (o *ViberStatusResponse) GetAltRouteMessages() []ViberStatusResponseAltRouteMessagesInner`

GetAltRouteMessages returns the AltRouteMessages field if non-nil, zero value otherwise.

### GetAltRouteMessagesOk

`func (o *ViberStatusResponse) GetAltRouteMessagesOk() (*[]ViberStatusResponseAltRouteMessagesInner, bool)`

GetAltRouteMessagesOk returns a tuple with the AltRouteMessages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAltRouteMessages

`func (o *ViberStatusResponse) SetAltRouteMessages(v []ViberStatusResponseAltRouteMessagesInner)`

SetAltRouteMessages sets AltRouteMessages field to given value.

### HasAltRouteMessages

`func (o *ViberStatusResponse) HasAltRouteMessages() bool`

HasAltRouteMessages returns a boolean if a field has been set.

### SetAltRouteMessagesNil

`func (o *ViberStatusResponse) SetAltRouteMessagesNil(b bool)`

 SetAltRouteMessagesNil sets the value for AltRouteMessages to be an explicit nil

### UnsetAltRouteMessages
`func (o *ViberStatusResponse) UnsetAltRouteMessages()`

UnsetAltRouteMessages ensures that no value is present for AltRouteMessages, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


