# SMSPriceCheckMultiplePhones

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for multiple recipients | 
**Phones** | [**[]PhoneNumbersInner2**](PhoneNumbersInner2.md) | Array of phone objects for bulk price calculation | 
**Originator** | **string** | Sender name for all messages | 
**Body** | **string** | SMS text content for all recipients | 
**Transliterate** | Pointer to **bool** | Apply transliteration to SMS text | [optional] [default to false]
**Tariff** | Pointer to **int32** | Specific tariff code for pricing (optional) | [optional] 

## Methods

### NewSMSPriceCheckMultiplePhones

`func NewSMSPriceCheckMultiplePhones(destination string, phones []PhoneNumbersInner2, originator string, body string, ) *SMSPriceCheckMultiplePhones`

NewSMSPriceCheckMultiplePhones instantiates a new SMSPriceCheckMultiplePhones object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSMSPriceCheckMultiplePhonesWithDefaults

`func NewSMSPriceCheckMultiplePhonesWithDefaults() *SMSPriceCheckMultiplePhones`

NewSMSPriceCheckMultiplePhonesWithDefaults instantiates a new SMSPriceCheckMultiplePhones object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SMSPriceCheckMultiplePhones) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SMSPriceCheckMultiplePhones) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SMSPriceCheckMultiplePhones) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetPhones

`func (o *SMSPriceCheckMultiplePhones) GetPhones() []PhoneNumbersInner2`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SMSPriceCheckMultiplePhones) GetPhonesOk() (*[]PhoneNumbersInner2, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SMSPriceCheckMultiplePhones) SetPhones(v []PhoneNumbersInner2)`

SetPhones sets Phones field to given value.


### GetOriginator

`func (o *SMSPriceCheckMultiplePhones) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SMSPriceCheckMultiplePhones) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SMSPriceCheckMultiplePhones) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SMSPriceCheckMultiplePhones) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SMSPriceCheckMultiplePhones) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SMSPriceCheckMultiplePhones) SetBody(v string)`

SetBody sets Body field to given value.


### GetTransliterate

`func (o *SMSPriceCheckMultiplePhones) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SMSPriceCheckMultiplePhones) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SMSPriceCheckMultiplePhones) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SMSPriceCheckMultiplePhones) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetTariff

`func (o *SMSPriceCheckMultiplePhones) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SMSPriceCheckMultiplePhones) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SMSPriceCheckMultiplePhones) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SMSPriceCheckMultiplePhones) HasTariff() bool`

HasTariff returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


