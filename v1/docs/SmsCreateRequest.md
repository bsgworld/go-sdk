# SmsCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for OTP messages | 
**Msisdn** | **string** | Phone number for OTP delivery | 
**Reference** | Pointer to **string** | Reference ID for OTP tracking | [optional] 
**Originator** | **string** | Sender name for OTP message | 
**Body** | **string** | OTP SMS text with auto-generation placeholders. Supported patterns: {gen_otp_09,4} - 4-digit numbers (0-9), {gen_otp_09,6} - 6-digit numbers, {gen_otp_AZ,4} - 4 uppercase letters (A-Z), {gen_otp_az,4} - 4 lowercase letters (a-z), {gen_otp_aZ,4} - 4 mixed case letters, {gen_otp_a9,8} - 8 chars letters+numbers, {gen_otp_**,6} - 6 chars with special symbols | 
**CallbackUrl** | Pointer to **string** | HTTPS URL for receiving delivery reports (DLR). Must be accessible from our servers. We will POST delivery status updates to this endpoint | [optional] 
**CallbackUrl2way** | Pointer to **string** | HTTPS URL for receiving 2-way SMS responses. Only works if 2way&#x3D;true and sender supports incoming messages | [optional] 
**Transliterate** | Pointer to **bool** | Apply transliteration to SMS text. Converts Cyrillic characters to Latin equivalents to reduce message cost and ensure delivery | [optional] [default to false]
**Var2way** | Pointer to **bool** | Enable two-way SMS communication for all messages | [optional] [default to false]
**Tariff** | Pointer to **int32** | Specific tariff code to use for pricing this message. Optional - uses user&#39;s default tariff if not specified | [optional] 
**ScheduledDatetime** | Pointer to **time.Time** | Schedule all messages delivery for future time | [optional] 
**DataCodingUcs2** | Pointer to **bool** | Force UCS-2 (Unicode) encoding for message text. Useful for non-Latin characters (Cyrillic, Arabic, Chinese, etc). Reduces max message length to 355 characters | [optional] [default to false]
**Validity** | Pointer to **int32** | Message validity period in hours. Default is 72 hours (3 days). Maximum is 87840 hours (10 years). After this time, undelivered message will expire | [optional] 
**Phones** | [**[]PhoneNumbersInner1**](PhoneNumbersInner1.md) | Array of phone objects with individual message content. Each phone has its own originator and message text | 

## Methods

### NewSmsCreateRequest

`func NewSmsCreateRequest(destination string, msisdn string, originator string, body string, phones []PhoneNumbersInner1, ) *SmsCreateRequest`

NewSmsCreateRequest instantiates a new SmsCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsCreateRequestWithDefaults

`func NewSmsCreateRequestWithDefaults() *SmsCreateRequest`

NewSmsCreateRequestWithDefaults instantiates a new SmsCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SmsCreateRequest) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SmsCreateRequest) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SmsCreateRequest) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetMsisdn

`func (o *SmsCreateRequest) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SmsCreateRequest) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SmsCreateRequest) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *SmsCreateRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SmsCreateRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SmsCreateRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SmsCreateRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetOriginator

`func (o *SmsCreateRequest) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SmsCreateRequest) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SmsCreateRequest) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SmsCreateRequest) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SmsCreateRequest) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SmsCreateRequest) SetBody(v string)`

SetBody sets Body field to given value.


### GetCallbackUrl

`func (o *SmsCreateRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *SmsCreateRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *SmsCreateRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *SmsCreateRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetCallbackUrl2way

`func (o *SmsCreateRequest) GetCallbackUrl2way() string`

GetCallbackUrl2way returns the CallbackUrl2way field if non-nil, zero value otherwise.

### GetCallbackUrl2wayOk

`func (o *SmsCreateRequest) GetCallbackUrl2wayOk() (*string, bool)`

GetCallbackUrl2wayOk returns a tuple with the CallbackUrl2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl2way

`func (o *SmsCreateRequest) SetCallbackUrl2way(v string)`

SetCallbackUrl2way sets CallbackUrl2way field to given value.

### HasCallbackUrl2way

`func (o *SmsCreateRequest) HasCallbackUrl2way() bool`

HasCallbackUrl2way returns a boolean if a field has been set.

### GetTransliterate

`func (o *SmsCreateRequest) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SmsCreateRequest) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SmsCreateRequest) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SmsCreateRequest) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetVar2way

`func (o *SmsCreateRequest) GetVar2way() bool`

GetVar2way returns the Var2way field if non-nil, zero value otherwise.

### GetVar2wayOk

`func (o *SmsCreateRequest) GetVar2wayOk() (*bool, bool)`

GetVar2wayOk returns a tuple with the Var2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVar2way

`func (o *SmsCreateRequest) SetVar2way(v bool)`

SetVar2way sets Var2way field to given value.

### HasVar2way

`func (o *SmsCreateRequest) HasVar2way() bool`

HasVar2way returns a boolean if a field has been set.

### GetTariff

`func (o *SmsCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SmsCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SmsCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SmsCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetScheduledDatetime

`func (o *SmsCreateRequest) GetScheduledDatetime() time.Time`

GetScheduledDatetime returns the ScheduledDatetime field if non-nil, zero value otherwise.

### GetScheduledDatetimeOk

`func (o *SmsCreateRequest) GetScheduledDatetimeOk() (*time.Time, bool)`

GetScheduledDatetimeOk returns a tuple with the ScheduledDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDatetime

`func (o *SmsCreateRequest) SetScheduledDatetime(v time.Time)`

SetScheduledDatetime sets ScheduledDatetime field to given value.

### HasScheduledDatetime

`func (o *SmsCreateRequest) HasScheduledDatetime() bool`

HasScheduledDatetime returns a boolean if a field has been set.

### GetDataCodingUcs2

`func (o *SmsCreateRequest) GetDataCodingUcs2() bool`

GetDataCodingUcs2 returns the DataCodingUcs2 field if non-nil, zero value otherwise.

### GetDataCodingUcs2Ok

`func (o *SmsCreateRequest) GetDataCodingUcs2Ok() (*bool, bool)`

GetDataCodingUcs2Ok returns a tuple with the DataCodingUcs2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCodingUcs2

`func (o *SmsCreateRequest) SetDataCodingUcs2(v bool)`

SetDataCodingUcs2 sets DataCodingUcs2 field to given value.

### HasDataCodingUcs2

`func (o *SmsCreateRequest) HasDataCodingUcs2() bool`

HasDataCodingUcs2 returns a boolean if a field has been set.

### GetValidity

`func (o *SmsCreateRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsCreateRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsCreateRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsCreateRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetPhones

`func (o *SmsCreateRequest) GetPhones() []PhoneNumbersInner1`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SmsCreateRequest) GetPhonesOk() (*[]PhoneNumbersInner1, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SmsCreateRequest) SetPhones(v []PhoneNumbersInner1)`

SetPhones sets Phones field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


