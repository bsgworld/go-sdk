# SmsMassStatusResponseResultInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | Message ID | [optional] 
**ExternalId** | Pointer to **string** | External reference ID | [optional] 
**Msisdn** | Pointer to **string** | Destination phone number | [optional] 
**TimeSent** | Pointer to **NullableString** | Timestamp when message was sent | [optional] 
**TimeDr** | Pointer to **NullableString** | Timestamp when delivery report was received | [optional] 
**Status** | Pointer to **string** | Current message status | [optional] 
**Price** | Pointer to **float32** | Message cost | [optional] 
**Currency** | Pointer to **string** | Price currency | [optional] 

## Methods

### NewSmsMassStatusResponseResultInner

`func NewSmsMassStatusResponseResultInner() *SmsMassStatusResponseResultInner`

NewSmsMassStatusResponseResultInner instantiates a new SmsMassStatusResponseResultInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsMassStatusResponseResultInnerWithDefaults

`func NewSmsMassStatusResponseResultInnerWithDefaults() *SmsMassStatusResponseResultInner`

NewSmsMassStatusResponseResultInnerWithDefaults instantiates a new SmsMassStatusResponseResultInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SmsMassStatusResponseResultInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SmsMassStatusResponseResultInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SmsMassStatusResponseResultInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *SmsMassStatusResponseResultInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetExternalId

`func (o *SmsMassStatusResponseResultInner) GetExternalId() string`

GetExternalId returns the ExternalId field if non-nil, zero value otherwise.

### GetExternalIdOk

`func (o *SmsMassStatusResponseResultInner) GetExternalIdOk() (*string, bool)`

GetExternalIdOk returns a tuple with the ExternalId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExternalId

`func (o *SmsMassStatusResponseResultInner) SetExternalId(v string)`

SetExternalId sets ExternalId field to given value.

### HasExternalId

`func (o *SmsMassStatusResponseResultInner) HasExternalId() bool`

HasExternalId returns a boolean if a field has been set.

### GetMsisdn

`func (o *SmsMassStatusResponseResultInner) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SmsMassStatusResponseResultInner) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SmsMassStatusResponseResultInner) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *SmsMassStatusResponseResultInner) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetTimeSent

`func (o *SmsMassStatusResponseResultInner) GetTimeSent() string`

GetTimeSent returns the TimeSent field if non-nil, zero value otherwise.

### GetTimeSentOk

`func (o *SmsMassStatusResponseResultInner) GetTimeSentOk() (*string, bool)`

GetTimeSentOk returns a tuple with the TimeSent field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeSent

`func (o *SmsMassStatusResponseResultInner) SetTimeSent(v string)`

SetTimeSent sets TimeSent field to given value.

### HasTimeSent

`func (o *SmsMassStatusResponseResultInner) HasTimeSent() bool`

HasTimeSent returns a boolean if a field has been set.

### SetTimeSentNil

`func (o *SmsMassStatusResponseResultInner) SetTimeSentNil(b bool)`

 SetTimeSentNil sets the value for TimeSent to be an explicit nil

### UnsetTimeSent
`func (o *SmsMassStatusResponseResultInner) UnsetTimeSent()`

UnsetTimeSent ensures that no value is present for TimeSent, not even an explicit nil
### GetTimeDr

`func (o *SmsMassStatusResponseResultInner) GetTimeDr() string`

GetTimeDr returns the TimeDr field if non-nil, zero value otherwise.

### GetTimeDrOk

`func (o *SmsMassStatusResponseResultInner) GetTimeDrOk() (*string, bool)`

GetTimeDrOk returns a tuple with the TimeDr field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTimeDr

`func (o *SmsMassStatusResponseResultInner) SetTimeDr(v string)`

SetTimeDr sets TimeDr field to given value.

### HasTimeDr

`func (o *SmsMassStatusResponseResultInner) HasTimeDr() bool`

HasTimeDr returns a boolean if a field has been set.

### SetTimeDrNil

`func (o *SmsMassStatusResponseResultInner) SetTimeDrNil(b bool)`

 SetTimeDrNil sets the value for TimeDr to be an explicit nil

### UnsetTimeDr
`func (o *SmsMassStatusResponseResultInner) UnsetTimeDr()`

UnsetTimeDr ensures that no value is present for TimeDr, not even an explicit nil
### GetStatus

`func (o *SmsMassStatusResponseResultInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SmsMassStatusResponseResultInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SmsMassStatusResponseResultInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SmsMassStatusResponseResultInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetPrice

`func (o *SmsMassStatusResponseResultInner) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *SmsMassStatusResponseResultInner) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *SmsMassStatusResponseResultInner) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *SmsMassStatusResponseResultInner) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *SmsMassStatusResponseResultInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SmsMassStatusResponseResultInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SmsMassStatusResponseResultInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *SmsMassStatusResponseResultInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


