# SmsSingleCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Destination** | **string** | Message destination type for single recipient | 
**Msisdn** | **string** | Phone number in international format without + sign. Required for destination&#x3D;phone/otp. Must be 8-15 digits starting with country code | 
**Reference** | Pointer to **string** | External reference ID for tracking message. Must be unique. Auto-generated if not provided. Only alphanumeric characters, hyphens and underscores allowed | [optional] 
**Originator** | **string** | Sender&#39;s name: from 3 to 11 characters for alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for numeric name. Required field | 
**Body** | **string** | SMS text content. Maximum length is 765 characters for GSM 7-bit encoding (Latin), and 355 characters for UCS-2 (Unicode). Required field | 
**CallbackUrl** | Pointer to **string** | HTTPS URL for receiving delivery reports (DLR). Must be accessible from our servers. We will POST delivery status updates to this endpoint | [optional] 
**CallbackUrl2way** | Pointer to **string** | HTTPS URL for receiving 2-way SMS responses. Only works if 2way&#x3D;true and sender supports incoming messages | [optional] 
**Transliterate** | Pointer to **bool** | Apply transliteration to SMS text if necessary. Converts Cyrillic characters to Latin equivalents to reduce message cost and ensure delivery | [optional] [default to false]
**Var2way** | Pointer to **bool** | Enable two-way SMS communication. Allows recipients to reply to your message. Requires callback_url_2way for receiving replies | [optional] [default to false]
**Tariff** | Pointer to **int32** | Specific tariff code to use for pricing this message. Optional - uses user&#39;s default tariff if not specified. Must be a valid tariff code available to your account | [optional] 
**ScheduledDatetime** | Pointer to **time.Time** | Schedule message delivery for future time. Must be in UTC format (ISO 8601). Example: 2024-12-25T10:30:00Z. If not specified, message is sent immediately | [optional] 
**DataCodingUcs2** | Pointer to **bool** | Force UCS-2 (Unicode) encoding for message text. Useful for non-Latin characters (Cyrillic, Arabic, Chinese, etc). Reduces max message length to 355 characters | [optional] [default to false]
**Validity** | Pointer to **int32** | Message validity period in hours. Default is 72 hours (3 days). Maximum is 87840 hours (10 years). After this time, undelivered message will expire | [optional] 

## Methods

### NewSmsSingleCreateRequest

`func NewSmsSingleCreateRequest(destination string, msisdn string, originator string, body string, ) *SmsSingleCreateRequest`

NewSmsSingleCreateRequest instantiates a new SmsSingleCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsSingleCreateRequestWithDefaults

`func NewSmsSingleCreateRequestWithDefaults() *SmsSingleCreateRequest`

NewSmsSingleCreateRequestWithDefaults instantiates a new SmsSingleCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SmsSingleCreateRequest) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SmsSingleCreateRequest) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SmsSingleCreateRequest) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetMsisdn

`func (o *SmsSingleCreateRequest) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SmsSingleCreateRequest) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SmsSingleCreateRequest) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *SmsSingleCreateRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SmsSingleCreateRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SmsSingleCreateRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SmsSingleCreateRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetOriginator

`func (o *SmsSingleCreateRequest) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SmsSingleCreateRequest) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SmsSingleCreateRequest) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SmsSingleCreateRequest) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SmsSingleCreateRequest) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SmsSingleCreateRequest) SetBody(v string)`

SetBody sets Body field to given value.


### GetCallbackUrl

`func (o *SmsSingleCreateRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *SmsSingleCreateRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *SmsSingleCreateRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *SmsSingleCreateRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetCallbackUrl2way

`func (o *SmsSingleCreateRequest) GetCallbackUrl2way() string`

GetCallbackUrl2way returns the CallbackUrl2way field if non-nil, zero value otherwise.

### GetCallbackUrl2wayOk

`func (o *SmsSingleCreateRequest) GetCallbackUrl2wayOk() (*string, bool)`

GetCallbackUrl2wayOk returns a tuple with the CallbackUrl2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl2way

`func (o *SmsSingleCreateRequest) SetCallbackUrl2way(v string)`

SetCallbackUrl2way sets CallbackUrl2way field to given value.

### HasCallbackUrl2way

`func (o *SmsSingleCreateRequest) HasCallbackUrl2way() bool`

HasCallbackUrl2way returns a boolean if a field has been set.

### GetTransliterate

`func (o *SmsSingleCreateRequest) GetTransliterate() bool`

GetTransliterate returns the Transliterate field if non-nil, zero value otherwise.

### GetTransliterateOk

`func (o *SmsSingleCreateRequest) GetTransliterateOk() (*bool, bool)`

GetTransliterateOk returns a tuple with the Transliterate field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTransliterate

`func (o *SmsSingleCreateRequest) SetTransliterate(v bool)`

SetTransliterate sets Transliterate field to given value.

### HasTransliterate

`func (o *SmsSingleCreateRequest) HasTransliterate() bool`

HasTransliterate returns a boolean if a field has been set.

### GetVar2way

`func (o *SmsSingleCreateRequest) GetVar2way() bool`

GetVar2way returns the Var2way field if non-nil, zero value otherwise.

### GetVar2wayOk

`func (o *SmsSingleCreateRequest) GetVar2wayOk() (*bool, bool)`

GetVar2wayOk returns a tuple with the Var2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVar2way

`func (o *SmsSingleCreateRequest) SetVar2way(v bool)`

SetVar2way sets Var2way field to given value.

### HasVar2way

`func (o *SmsSingleCreateRequest) HasVar2way() bool`

HasVar2way returns a boolean if a field has been set.

### GetTariff

`func (o *SmsSingleCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SmsSingleCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SmsSingleCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SmsSingleCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetScheduledDatetime

`func (o *SmsSingleCreateRequest) GetScheduledDatetime() time.Time`

GetScheduledDatetime returns the ScheduledDatetime field if non-nil, zero value otherwise.

### GetScheduledDatetimeOk

`func (o *SmsSingleCreateRequest) GetScheduledDatetimeOk() (*time.Time, bool)`

GetScheduledDatetimeOk returns a tuple with the ScheduledDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetScheduledDatetime

`func (o *SmsSingleCreateRequest) SetScheduledDatetime(v time.Time)`

SetScheduledDatetime sets ScheduledDatetime field to given value.

### HasScheduledDatetime

`func (o *SmsSingleCreateRequest) HasScheduledDatetime() bool`

HasScheduledDatetime returns a boolean if a field has been set.

### GetDataCodingUcs2

`func (o *SmsSingleCreateRequest) GetDataCodingUcs2() bool`

GetDataCodingUcs2 returns the DataCodingUcs2 field if non-nil, zero value otherwise.

### GetDataCodingUcs2Ok

`func (o *SmsSingleCreateRequest) GetDataCodingUcs2Ok() (*bool, bool)`

GetDataCodingUcs2Ok returns a tuple with the DataCodingUcs2 field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDataCodingUcs2

`func (o *SmsSingleCreateRequest) SetDataCodingUcs2(v bool)`

SetDataCodingUcs2 sets DataCodingUcs2 field to given value.

### HasDataCodingUcs2

`func (o *SmsSingleCreateRequest) HasDataCodingUcs2() bool`

HasDataCodingUcs2 returns a boolean if a field has been set.

### GetValidity

`func (o *SmsSingleCreateRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsSingleCreateRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsSingleCreateRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsSingleCreateRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


