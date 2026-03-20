# SmsPriceCheckRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for multiple recipients | 
**Msisdn** | **string** | Phone number in international format for price calculation | 
**Originator** | **string** | Sender name for all messages | 
**Body** | **string** | SMS text content for all recipients | 
**Transliterate** | Pointer to **bool** | Apply transliteration to SMS text | [optional] [default to false]
**DataCodingUcs2** | Pointer to **bool** | Force UCS-2 encoding (affects message length and pricing) | [optional] [default to false]
**Tariff** | Pointer to **int32** | Specific tariff code for pricing (optional) | [optional] 
**Phones** | [**[]PhoneNumbersInner2**](PhoneNumbersInner2.md) | Array of phone objects for bulk price calculation | 

## Methods

### NewSmsPriceCheckRequest

`func NewSmsPriceCheckRequest(destination string, msisdn string, originator string, body string, phones []PhoneNumbersInner2, ) *SmsPriceCheckRequest`

NewSmsPriceCheckRequest instantiates a new SmsPriceCheckRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsPriceCheckRequestWithDefaults

`func NewSmsPriceCheckRequestWithDefaults() *SmsPriceCheckRequest`

NewSmsPriceCheckRequestWithDefaults instantiates a new SmsPriceCheckRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SmsPriceCheckRequest) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SmsPriceCheckRequest) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SmsPriceCheckRequest) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetMsisdn

`func (o *SmsPriceCheckRequest) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SmsPriceCheckRequest) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SmsPriceCheckRequest) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetOriginator

`func (o *SmsPriceCheckRequest) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SmsPriceCheckRequest) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SmsPriceCheckRequest) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SmsPriceCheckRequest) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SmsPriceCheckRequest) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SmsPriceCheckRequest) SetBody(v string)`

SetBody sets Body field to given value.


### GetTransliterate

`func (o *SmsPriceCheckRequest) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SmsPriceCheckRequest) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SmsPriceCheckRequest) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SmsPriceCheckRequest) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetDataCodingUcs2

`func (o *SmsPriceCheckRequest) GetDataCodingUcs2() bool`

GetDataCodingUcs2 returns the DataCodingUcs2 field if non-nil, zero value otherwise.

### GetDataCodingUcs2Ok

`func (o *SmsPriceCheckRequest) GetDataCodingUcs2Ok() (*bool, bool)`

GetDataCodingUcs2Ok returns a tuple with the DataCodingUcs2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCodingUcs2

`func (o *SmsPriceCheckRequest) SetDataCodingUcs2(v bool)`

SetDataCodingUcs2 sets DataCodingUcs2 field to given value.

### HasDataCodingUcs2

`func (o *SmsPriceCheckRequest) HasDataCodingUcs2() bool`

HasDataCodingUcs2 returns a boolean if a field has been set.

### GetTariff

`func (o *SmsPriceCheckRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SmsPriceCheckRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SmsPriceCheckRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SmsPriceCheckRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetPhones

`func (o *SmsPriceCheckRequest) GetPhones() []PhoneNumbersInner2`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SmsPriceCheckRequest) GetPhonesOk() (*[]PhoneNumbersInner2, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SmsPriceCheckRequest) SetPhones(v []PhoneNumbersInner2)`

SetPhones sets Phones field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


