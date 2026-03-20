# SmsOtpCreateRequest

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
**Tariff** | Pointer to **int32** | Specific tariff code to use for pricing this message. Optional - uses user&#39;s default tariff if not specified | [optional] 
**Validity** | Pointer to **int32** | Message validity period in hours. Default is 72 hours (3 days). Maximum is 87840 hours (10 years). After this time, undelivered message will expire | [optional] 

## Methods

### NewSmsOtpCreateRequest

`func NewSmsOtpCreateRequest(destination string, msisdn string, originator string, body string, ) *SmsOtpCreateRequest`

NewSmsOtpCreateRequest instantiates a new SmsOtpCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsOtpCreateRequestWithDefaults

`func NewSmsOtpCreateRequestWithDefaults() *SmsOtpCreateRequest`

NewSmsOtpCreateRequestWithDefaults instantiates a new SmsOtpCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetDestination

`func (o *SmsOtpCreateRequest) GetDestination() string`

GetDestination returns the Destination field if non-nil, zero value otherwise.

### GetDestinationOk

`func (o *SmsOtpCreateRequest) GetDestinationOk() (*string, bool)`

GetDestinationOk returns a tuple with the Destination field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDestination

`func (o *SmsOtpCreateRequest) SetDestination(v string)`

SetDestination sets Destination field to given value.


### GetMsisdn

`func (o *SmsOtpCreateRequest) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *SmsOtpCreateRequest) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *SmsOtpCreateRequest) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *SmsOtpCreateRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *SmsOtpCreateRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *SmsOtpCreateRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *SmsOtpCreateRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetOriginator

`func (o *SmsOtpCreateRequest) GetOriginator() string`

GetOriginator returns the Originator field if non-nil, zero value otherwise.

### GetOriginatorOk

`func (o *SmsOtpCreateRequest) GetOriginatorOk() (*string, bool)`

GetOriginatorOk returns a tuple with the Originator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOriginator

`func (o *SmsOtpCreateRequest) SetOriginator(v string)`

SetOriginator sets Originator field to given value.


### GetBody

`func (o *SmsOtpCreateRequest) GetBody() string`

GetBody returns the Body field if non-nil, zero value otherwise.

### GetBodyOk

`func (o *SmsOtpCreateRequest) GetBodyOk() (*string, bool)`

GetBodyOk returns a tuple with the Body field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBody

`func (o *SmsOtpCreateRequest) SetBody(v string)`

SetBody sets Body field to given value.


### GetCallbackUrl

`func (o *SmsOtpCreateRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *SmsOtpCreateRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *SmsOtpCreateRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *SmsOtpCreateRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetCallbackUrl2way

`func (o *SmsOtpCreateRequest) GetCallbackUrl2way() string`

GetCallbackUrl2way returns the CallbackUrl2way field if non-nil, zero value otherwise.

### GetCallbackUrl2wayOk

`func (o *SmsOtpCreateRequest) GetCallbackUrl2wayOk() (*string, bool)`

GetCallbackUrl2wayOk returns a tuple with the CallbackUrl2way field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl2way

`func (o *SmsOtpCreateRequest) SetCallbackUrl2way(v string)`

SetCallbackUrl2way sets CallbackUrl2way field to given value.

### HasCallbackUrl2way

`func (o *SmsOtpCreateRequest) HasCallbackUrl2way() bool`

HasCallbackUrl2way returns a boolean if a field has been set.

### GetTariff

`func (o *SmsOtpCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *SmsOtpCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *SmsOtpCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *SmsOtpCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetValidity

`func (o *SmsOtpCreateRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SmsOtpCreateRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SmsOtpCreateRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SmsOtpCreateRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


