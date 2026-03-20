# SmsIndividualCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for individual customized messages per recipient | 
**Phones** | [**[]PhoneNumbersInner1**](PhoneNumbersInner1.md) | Array of phone objects with individual message content. Each phone has its own originator and message text | 
**Reference** | Pointer to **string** | Global reference ID for entire individual batch | [optional] 
**Validity** | Pointer to **int32** | Message validity period in hours for all messages | [optional] 
**Tariff** | Pointer to **int32** | Tariff code for pricing all messages | [optional] 
**Var2way** | Pointer to **bool** | Enable two-way SMS communication for all messages | [optional] [default to false]
**ScheduledDatetime** | Pointer to **time.Time** | Schedule all messages delivery for future time | [optional] 

## Methods

### NewSmsIndividualCreateRequest

`func NewSmsIndividualCreateRequest(destination string, phones []PhoneNumbersInner1, ) *SmsIndividualCreateRequest`

NewSmsIndividualCreateRequest instantiates a new SmsIndividualCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsIndividualCreateRequestWithDefaults

`func NewSmsIndividualCreateRequestWithDefaults() *SmsIndividualCreateRequest`

NewSmsIndividualCreateRequestWithDefaults instantiates a new SmsIndividualCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SmsIndividualCreateRequest) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SmsIndividualCreateRequest) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SmsIndividualCreateRequest) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetPhones

`func (o *SmsIndividualCreateRequest) GetPhones() []PhoneNumbersInner1`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SmsIndividualCreateRequest) GetPhonesOk() (*[]PhoneNumbersInner1, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SmsIndividualCreateRequest) SetPhones(v []PhoneNumbersInner1)`

SetPhones sets Phones field to given value.


### GetReference

`func (o *SmsIndividualCreateRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SmsIndividualCreateRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SmsIndividualCreateRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SmsIndividualCreateRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetValidity

`func (o *SmsIndividualCreateRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsIndividualCreateRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsIndividualCreateRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsIndividualCreateRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetTariff

`func (o *SmsIndividualCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SmsIndividualCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SmsIndividualCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SmsIndividualCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetVar2way

`func (o *SmsIndividualCreateRequest) GetVar2way() bool`

GetVar2way returns the Var2way field if non-nil, zero value otherwise.

### GetVar2wayOk

`func (o *SmsIndividualCreateRequest) GetVar2wayOk() (*bool, bool)`

GetVar2wayOk returns a tuple with the Var2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVar2way

`func (o *SmsIndividualCreateRequest) SetVar2way(v bool)`

SetVar2way sets Var2way field to given value.

### HasVar2way

`func (o *SmsIndividualCreateRequest) HasVar2way() bool`

HasVar2way returns a boolean if a field has been set.

### GetScheduledDatetime

`func (o *SmsIndividualCreateRequest) GetScheduledDatetime() time.Time`

GetScheduledDatetime returns the ScheduledDatetime field if non-nil, zero value otherwise.

### GetScheduledDatetimeOk

`func (o *SmsIndividualCreateRequest) GetScheduledDatetimeOk() (*time.Time, bool)`

GetScheduledDatetimeOk returns a tuple with the ScheduledDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDatetime

`func (o *SmsIndividualCreateRequest) SetScheduledDatetime(v time.Time)`

SetScheduledDatetime sets ScheduledDatetime field to given value.

### HasScheduledDatetime

`func (o *SmsIndividualCreateRequest) HasScheduledDatetime() bool`

HasScheduledDatetime returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


