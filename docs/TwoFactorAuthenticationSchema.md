# TwoFactorAuthenticationSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** | The ID of the generated authentication | [optional] 
**Recipient** | Pointer to **string** | Number of the recipient of the message with a one-time code | [optional] 
**Status** | Pointer to [**OtpStatus**](OtpStatus.md) |  | [optional] 
**Channel** | Pointer to [**OtpChannel**](OtpChannel.md) |  | [optional] 
**Sender** | Pointer to **string** | Sender name | [optional] 
**SenderAlt** | Pointer to **NullableString** | SMS sender name | [optional] 
**MessageText** | Pointer to **string** | Message text. | [optional] 
**CodeLifetime** | Pointer to **int32** | OTP expiration date | [optional] 
**CodeMaxTries** | Pointer to **int32** | The number of OTP check attempts | [optional] 
**CodeDigits** | Pointer to **int32** | The number of digits in the OTP | [optional] 
**Price** | Pointer to **float32** | Authentication cost. At the time of creating the authentication, 0 is indicated | [optional] 
**Currency** | Pointer to **string** | The three-letter code of the currency in which the value is indicated. Corresponds to the user’s account currency | [optional] 
**CountryCode** | Pointer to **string** | The country code of the recipient of the one-time password according to the ISO 3166-1 alpha-2 standard | [optional] 
**ExpiredAt** | Pointer to **time.Time** | Date and time when the authentication expires in ISO 8601 format | [optional] 
**CreatedAt** | Pointer to **time.Time** | The date and time of the authentication session were created in ISO 8601 format | [optional] 
**FinishedAt** | Pointer to **time.Time** | Date and time when the authentication session was closed. At the time of creating the authentication, the value “null” is indicated | [optional] 

## Methods

### NewTwoFactorAuthenticationSchema

`func NewTwoFactorAuthenticationSchema() *TwoFactorAuthenticationSchema`

NewTwoFactorAuthenticationSchema instantiates a new TwoFactorAuthenticationSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTwoFactorAuthenticationSchemaWithDefaults

`func NewTwoFactorAuthenticationSchemaWithDefaults() *TwoFactorAuthenticationSchema`

NewTwoFactorAuthenticationSchemaWithDefaults instantiates a new TwoFactorAuthenticationSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TwoFactorAuthenticationSchema) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TwoFactorAuthenticationSchema) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TwoFactorAuthenticationSchema) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *TwoFactorAuthenticationSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRecipient

`func (o *TwoFactorAuthenticationSchema) GetRecipient() string`

GetRecipient returns the Recipient field if non-nil, zero value otherwise.

### GetRecipientOk

`func (o *TwoFactorAuthenticationSchema) GetRecipientOk() (*string, bool)`

GetRecipientOk returns a tuple with the Recipient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipient

`func (o *TwoFactorAuthenticationSchema) SetRecipient(v string)`

SetRecipient sets Recipient field to given value.

### HasRecipient

`func (o *TwoFactorAuthenticationSchema) HasRecipient() bool`

HasRecipient returns a boolean if a field has been set.

### GetStatus

`func (o *TwoFactorAuthenticationSchema) GetStatus() OtpStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TwoFactorAuthenticationSchema) GetStatusOk() (*OtpStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TwoFactorAuthenticationSchema) SetStatus(v OtpStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TwoFactorAuthenticationSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetChannel

`func (o *TwoFactorAuthenticationSchema) GetChannel() OtpChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *TwoFactorAuthenticationSchema) GetChannelOk() (*OtpChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *TwoFactorAuthenticationSchema) SetChannel(v OtpChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *TwoFactorAuthenticationSchema) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetSender

`func (o *TwoFactorAuthenticationSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *TwoFactorAuthenticationSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *TwoFactorAuthenticationSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *TwoFactorAuthenticationSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetSenderAlt

`func (o *TwoFactorAuthenticationSchema) GetSenderAlt() string`

GetSenderAlt returns the SenderAlt field if non-nil, zero value otherwise.

### GetSenderAltOk

`func (o *TwoFactorAuthenticationSchema) GetSenderAltOk() (*string, bool)`

GetSenderAltOk returns a tuple with the SenderAlt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderAlt

`func (o *TwoFactorAuthenticationSchema) SetSenderAlt(v string)`

SetSenderAlt sets SenderAlt field to given value.

### HasSenderAlt

`func (o *TwoFactorAuthenticationSchema) HasSenderAlt() bool`

HasSenderAlt returns a boolean if a field has been set.

### SetSenderAltNil

`func (o *TwoFactorAuthenticationSchema) SetSenderAltNil(b bool)`

 SetSenderAltNil sets the value for SenderAlt to be an explicit nil

### UnsetSenderAlt
`func (o *TwoFactorAuthenticationSchema) UnsetSenderAlt()`

UnsetSenderAlt ensures that no value is present for SenderAlt, not even an explicit nil
### GetMessageText

`func (o *TwoFactorAuthenticationSchema) GetMessageText() string`

GetMessageText returns the MessageText field if non-nil, zero value otherwise.

### GetMessageTextOk

`func (o *TwoFactorAuthenticationSchema) GetMessageTextOk() (*string, bool)`

GetMessageTextOk returns a tuple with the MessageText field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageText

`func (o *TwoFactorAuthenticationSchema) SetMessageText(v string)`

SetMessageText sets MessageText field to given value.

### HasMessageText

`func (o *TwoFactorAuthenticationSchema) HasMessageText() bool`

HasMessageText returns a boolean if a field has been set.

### GetCodeLifetime

`func (o *TwoFactorAuthenticationSchema) GetCodeLifetime() int32`

GetCodeLifetime returns the CodeLifetime field if non-nil, zero value otherwise.

### GetCodeLifetimeOk

`func (o *TwoFactorAuthenticationSchema) GetCodeLifetimeOk() (*int32, bool)`

GetCodeLifetimeOk returns a tuple with the CodeLifetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeLifetime

`func (o *TwoFactorAuthenticationSchema) SetCodeLifetime(v int32)`

SetCodeLifetime sets CodeLifetime field to given value.

### HasCodeLifetime

`func (o *TwoFactorAuthenticationSchema) HasCodeLifetime() bool`

HasCodeLifetime returns a boolean if a field has been set.

### GetCodeMaxTries

`func (o *TwoFactorAuthenticationSchema) GetCodeMaxTries() int32`

GetCodeMaxTries returns the CodeMaxTries field if non-nil, zero value otherwise.

### GetCodeMaxTriesOk

`func (o *TwoFactorAuthenticationSchema) GetCodeMaxTriesOk() (*int32, bool)`

GetCodeMaxTriesOk returns a tuple with the CodeMaxTries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeMaxTries

`func (o *TwoFactorAuthenticationSchema) SetCodeMaxTries(v int32)`

SetCodeMaxTries sets CodeMaxTries field to given value.

### HasCodeMaxTries

`func (o *TwoFactorAuthenticationSchema) HasCodeMaxTries() bool`

HasCodeMaxTries returns a boolean if a field has been set.

### GetCodeDigits

`func (o *TwoFactorAuthenticationSchema) GetCodeDigits() int32`

GetCodeDigits returns the CodeDigits field if non-nil, zero value otherwise.

### GetCodeDigitsOk

`func (o *TwoFactorAuthenticationSchema) GetCodeDigitsOk() (*int32, bool)`

GetCodeDigitsOk returns a tuple with the CodeDigits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeDigits

`func (o *TwoFactorAuthenticationSchema) SetCodeDigits(v int32)`

SetCodeDigits sets CodeDigits field to given value.

### HasCodeDigits

`func (o *TwoFactorAuthenticationSchema) HasCodeDigits() bool`

HasCodeDigits returns a boolean if a field has been set.

### GetPrice

`func (o *TwoFactorAuthenticationSchema) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *TwoFactorAuthenticationSchema) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *TwoFactorAuthenticationSchema) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *TwoFactorAuthenticationSchema) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *TwoFactorAuthenticationSchema) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *TwoFactorAuthenticationSchema) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *TwoFactorAuthenticationSchema) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *TwoFactorAuthenticationSchema) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetCountryCode

`func (o *TwoFactorAuthenticationSchema) GetCountryCode() string`

GetCountryCode returns the CountryCode field if non-nil, zero value otherwise.

### GetCountryCodeOk

`func (o *TwoFactorAuthenticationSchema) GetCountryCodeOk() (*string, bool)`

GetCountryCodeOk returns a tuple with the CountryCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryCode

`func (o *TwoFactorAuthenticationSchema) SetCountryCode(v string)`

SetCountryCode sets CountryCode field to given value.

### HasCountryCode

`func (o *TwoFactorAuthenticationSchema) HasCountryCode() bool`

HasCountryCode returns a boolean if a field has been set.

### GetExpiredAt

`func (o *TwoFactorAuthenticationSchema) GetExpiredAt() time.Time`

GetExpiredAt returns the ExpiredAt field if non-nil, zero value otherwise.

### GetExpiredAtOk

`func (o *TwoFactorAuthenticationSchema) GetExpiredAtOk() (*time.Time, bool)`

GetExpiredAtOk returns a tuple with the ExpiredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetExpiredAt

`func (o *TwoFactorAuthenticationSchema) SetExpiredAt(v time.Time)`

SetExpiredAt sets ExpiredAt field to given value.

### HasExpiredAt

`func (o *TwoFactorAuthenticationSchema) HasExpiredAt() bool`

HasExpiredAt returns a boolean if a field has been set.

### GetCreatedAt

`func (o *TwoFactorAuthenticationSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TwoFactorAuthenticationSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TwoFactorAuthenticationSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TwoFactorAuthenticationSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetFinishedAt

`func (o *TwoFactorAuthenticationSchema) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *TwoFactorAuthenticationSchema) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *TwoFactorAuthenticationSchema) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *TwoFactorAuthenticationSchema) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


