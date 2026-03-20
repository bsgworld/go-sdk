# PhoneNumbersInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdn** | **string** | Phone number in international format | 
**Reference** | Pointer to **string** | Individual reference for this recipient | [optional] 

## Methods

### NewPhoneNumbersInner

`func NewPhoneNumbersInner(msisdn string, ) *PhoneNumbersInner`

NewPhoneNumbersInner instantiates a new PhoneNumbersInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPhoneNumbersInnerWithDefaults

`func NewPhoneNumbersInnerWithDefaults() *PhoneNumbersInner`

NewPhoneNumbersInnerWithDefaults instantiates a new PhoneNumbersInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdn

`func (o *PhoneNumbersInner) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *PhoneNumbersInner) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *PhoneNumbersInner) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *PhoneNumbersInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *PhoneNumbersInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *PhoneNumbersInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *PhoneNumbersInner) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


