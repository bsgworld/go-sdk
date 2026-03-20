# SMSPriceCheckSinglePhone

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for single recipient | 
**Msisdn** | **string** | Phone number in international format for price calculation | 
**Originator** | **string** | Sender name for pricing calculation | 
**Body** | **string** | SMS text content for length/parts calculation | 
**Transliterate** | Pointer to **bool** | Apply transliteration (affects message length and pricing) | [optional] [default to false]
**DataCodingUcs2** | Pointer to **bool** | Force UCS-2 encoding (affects message length and pricing) | [optional] [default to false]
**Tariff** | Pointer to **int32** | Specific tariff code for pricing (optional) | [optional] 

## Methods

### NewSMSPriceCheckSinglePhone

`func NewSMSPriceCheckSinglePhone(destination string, msisdn string, originator string, body string, ) *SMSPriceCheckSinglePhone`

NewSMSPriceCheckSinglePhone instantiates a new SMSPriceCheckSinglePhone object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSMSPriceCheckSinglePhoneWithDefaults

`func NewSMSPriceCheckSinglePhoneWithDefaults() *SMSPriceCheckSinglePhone`

NewSMSPriceCheckSinglePhoneWithDefaults instantiates a new SMSPriceCheckSinglePhone object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SMSPriceCheckSinglePhone) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SMSPriceCheckSinglePhone) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SMSPriceCheckSinglePhone) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetMsisdn

`func (o *SMSPriceCheckSinglePhone) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SMSPriceCheckSinglePhone) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SMSPriceCheckSinglePhone) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetOriginator

`func (o *SMSPriceCheckSinglePhone) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SMSPriceCheckSinglePhone) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SMSPriceCheckSinglePhone) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SMSPriceCheckSinglePhone) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SMSPriceCheckSinglePhone) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SMSPriceCheckSinglePhone) SetBody(v string)`

SetBody sets Body field to given value.


### GetTransliterate

`func (o *SMSPriceCheckSinglePhone) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SMSPriceCheckSinglePhone) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SMSPriceCheckSinglePhone) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SMSPriceCheckSinglePhone) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetDataCodingUcs2

`func (o *SMSPriceCheckSinglePhone) GetDataCodingUcs2() bool`

GetDataCodingUcs2 returns the DataCodingUcs2 field if non-nil, zero value otherwise.

### GetDataCodingUcs2Ok

`func (o *SMSPriceCheckSinglePhone) GetDataCodingUcs2Ok() (*bool, bool)`

GetDataCodingUcs2Ok returns a tuple with the DataCodingUcs2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCodingUcs2

`func (o *SMSPriceCheckSinglePhone) SetDataCodingUcs2(v bool)`

SetDataCodingUcs2 sets DataCodingUcs2 field to given value.

### HasDataCodingUcs2

`func (o *SMSPriceCheckSinglePhone) HasDataCodingUcs2() bool`

HasDataCodingUcs2 returns a boolean if a field has been set.

### GetTariff

`func (o *SMSPriceCheckSinglePhone) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SMSPriceCheckSinglePhone) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SMSPriceCheckSinglePhone) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SMSPriceCheckSinglePhone) HasTariff() bool`

HasTariff returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


