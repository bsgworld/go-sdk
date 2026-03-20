# SmsMultipleCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for multiple recipients | 
**Phones** | [**[]PhoneNumbersInner**](PhoneNumbersInner.md) | Array of phone objects (required for destination&#x3D;phones). Maximum 1000 recipients per request | 
**Reference** | Pointer to **string** | Global reference ID for entire batch | [optional] 
**Originator** | **string** | Sender name for all messages in batch | 
**Body** | **string** | SMS text content for all recipients | 
**CallbackUrl** | Pointer to **string** | HTTPS URL for receiving delivery reports | [optional] 
**Transliterate** | Pointer to **bool** | Apply transliteration to SMS text. Converts Cyrillic characters to Latin equivalents to reduce message cost and ensure delivery | [optional] [default to false]
**CallbackUrl2way** | Pointer to **string** | HTTPS URL for receiving 2-way SMS responses. Only works if 2way&#x3D;true and sender supports incoming messages | [optional] 
**Var2way** | Pointer to **bool** | Enable two-way SMS communication. Allows recipients to reply to your message. Requires callback_url_2way for receiving replies | [optional] [default to false]
**Tariff** | Pointer to **int32** | Specific tariff code to use for pricing this message. Optional - uses user&#39;s default tariff if not specified. Must be a valid tariff code available to your account | [optional] 
**ScheduledDatetime** | Pointer to **time.Time** | Schedule message delivery for future time. Must be in UTC format (ISO 8601). Example: 2024-12-25T10:30:00Z. If not specified, message is sent immediately | [optional] 
**DataCodingUcs2** | Pointer to **bool** | Force UCS-2 (Unicode) encoding for message text. Useful for non-Latin characters (Cyrillic, Arabic, Chinese, etc). Reduces max message length to 355 characters | [optional] [default to false]
**Validity** | Pointer to **int32** | Message validity period in hours. Default is 72 hours (3 days). Maximum is 87840 hours (10 years). After this time, undelivered message will expire | [optional] 

## Methods

### NewSmsMultipleCreateRequest

`func NewSmsMultipleCreateRequest(destination string, phones []PhoneNumbersInner, originator string, body string, ) *SmsMultipleCreateRequest`

NewSmsMultipleCreateRequest instantiates a new SmsMultipleCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsMultipleCreateRequestWithDefaults

`func NewSmsMultipleCreateRequestWithDefaults() *SmsMultipleCreateRequest`

NewSmsMultipleCreateRequestWithDefaults instantiates a new SmsMultipleCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SmsMultipleCreateRequest) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SmsMultipleCreateRequest) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SmsMultipleCreateRequest) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetPhones

`func (o *SmsMultipleCreateRequest) GetPhones() []PhoneNumbersInner`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SmsMultipleCreateRequest) GetPhonesOk() (*[]PhoneNumbersInner, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SmsMultipleCreateRequest) SetPhones(v []PhoneNumbersInner)`

SetPhones sets Phones field to given value.


### GetReference

`func (o *SmsMultipleCreateRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SmsMultipleCreateRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SmsMultipleCreateRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SmsMultipleCreateRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetOriginator

`func (o *SmsMultipleCreateRequest) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SmsMultipleCreateRequest) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SmsMultipleCreateRequest) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SmsMultipleCreateRequest) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SmsMultipleCreateRequest) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SmsMultipleCreateRequest) SetBody(v string)`

SetBody sets Body field to given value.


### GetCallbackUrl

`func (o *SmsMultipleCreateRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *SmsMultipleCreateRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *SmsMultipleCreateRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *SmsMultipleCreateRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetTransliterate

`func (o *SmsMultipleCreateRequest) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SmsMultipleCreateRequest) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SmsMultipleCreateRequest) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SmsMultipleCreateRequest) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetCallbackUrl2way

`func (o *SmsMultipleCreateRequest) GetCallbackUrl2way() string`

GetCallbackUrl2way returns the CallbackUrl2way field if non-nil, zero value otherwise.

### GetCallbackUrl2wayOk

`func (o *SmsMultipleCreateRequest) GetCallbackUrl2wayOk() (*string, bool)`

GetCallbackUrl2wayOk returns a tuple with the CallbackUrl2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl2way

`func (o *SmsMultipleCreateRequest) SetCallbackUrl2way(v string)`

SetCallbackUrl2way sets CallbackUrl2way field to given value.

### HasCallbackUrl2way

`func (o *SmsMultipleCreateRequest) HasCallbackUrl2way() bool`

HasCallbackUrl2way returns a boolean if a field has been set.

### GetVar2way

`func (o *SmsMultipleCreateRequest) GetVar2way() bool`

GetVar2way returns the Var2way field if non-nil, zero value otherwise.

### GetVar2wayOk

`func (o *SmsMultipleCreateRequest) GetVar2wayOk() (*bool, bool)`

GetVar2wayOk returns a tuple with the Var2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVar2way

`func (o *SmsMultipleCreateRequest) SetVar2way(v bool)`

SetVar2way sets Var2way field to given value.

### HasVar2way

`func (o *SmsMultipleCreateRequest) HasVar2way() bool`

HasVar2way returns a boolean if a field has been set.

### GetTariff

`func (o *SmsMultipleCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SmsMultipleCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SmsMultipleCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SmsMultipleCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetScheduledDatetime

`func (o *SmsMultipleCreateRequest) GetScheduledDatetime() time.Time`

GetScheduledDatetime returns the ScheduledDatetime field if non-nil, zero value otherwise.

### GetScheduledDatetimeOk

`func (o *SmsMultipleCreateRequest) GetScheduledDatetimeOk() (*time.Time, bool)`

GetScheduledDatetimeOk returns a tuple with the ScheduledDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDatetime

`func (o *SmsMultipleCreateRequest) SetScheduledDatetime(v time.Time)`

SetScheduledDatetime sets ScheduledDatetime field to given value.

### HasScheduledDatetime

`func (o *SmsMultipleCreateRequest) HasScheduledDatetime() bool`

HasScheduledDatetime returns a boolean if a field has been set.

### GetDataCodingUcs2

`func (o *SmsMultipleCreateRequest) GetDataCodingUcs2() bool`

GetDataCodingUcs2 returns the DataCodingUcs2 field if non-nil, zero value otherwise.

### GetDataCodingUcs2Ok

`func (o *SmsMultipleCreateRequest) GetDataCodingUcs2Ok() (*bool, bool)`

GetDataCodingUcs2Ok returns a tuple with the DataCodingUcs2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCodingUcs2

`func (o *SmsMultipleCreateRequest) SetDataCodingUcs2(v bool)`

SetDataCodingUcs2 sets DataCodingUcs2 field to given value.

### HasDataCodingUcs2

`func (o *SmsMultipleCreateRequest) HasDataCodingUcs2() bool`

HasDataCodingUcs2 returns a boolean if a field has been set.

### GetValidity

`func (o *SmsMultipleCreateRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsMultipleCreateRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsMultipleCreateRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsMultipleCreateRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


