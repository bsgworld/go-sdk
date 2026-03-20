# PhoneNumbersInner1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdn** | **string** | Phone number in international format | 
**Reference** | Pointer to **string** | Individual reference for this recipient | [optional] 
**Originator** | **string** | Sender name for this specific message | 
**Body** | **string** | SMS text content for this specific recipient | 

## Methods

### NewPhoneNumbersInner1

`func NewPhoneNumbersInner1(msisdn string, originator string, body string, ) *PhoneNumbersInner1`

NewPhoneNumbersInner1 instantiates a new PhoneNumbersInner1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPhoneNumbersInner1WithDefaults

`func NewPhoneNumbersInner1WithDefaults() *PhoneNumbersInner1`

NewPhoneNumbersInner1WithDefaults instantiates a new PhoneNumbersInner1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdn

`func (o *PhoneNumbersInner1) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *PhoneNumbersInner1) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *PhoneNumbersInner1) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *PhoneNumbersInner1) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *PhoneNumbersInner1) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *PhoneNumbersInner1) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *PhoneNumbersInner1) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetOriginator

`func (o *PhoneNumbersInner1) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *PhoneNumbersInner1) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *PhoneNumbersInner1) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *PhoneNumbersInner1) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *PhoneNumbersInner1) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *PhoneNumbersInner1) SetBody(v string)`

SetBody sets Body field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


