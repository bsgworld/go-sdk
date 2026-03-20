# SendOtpRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Recipient** | **string** | The phone number of the recipient of the one-time password. 9 to 15 digits without the + sign. 3 to 15 characters for the sender’s numeric name. | 
**Channel** | **string** | A channel for sending a one-time password. Possible values: sms, viber. | 
**Sender** | **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | 
**SenderAlt** | Pointer to **NullableString** | Used only for the Viber channel to alternatively send a one-time code in SMS (if it was not possible to send the code in a Viber message, for example, if the recipient is not a Viber user).The name or number of the SMS sender. String up to 15 characters: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. | [optional] 
**TemplateId** | **int32** | Unique identifier of the [template](https://app.bsg.world/2fa/templates) with the Approved status. It’s not allowed to specify the template ID in other statuses. The template ID must be from 1 to 9 digits | 
**CodeLifetime** | **int32** | The password expiration time after which the password becomes invalid. An integer from 30 seconds to 300 seconds. | 
**CodeMaxTries** | **int32** | The number of password verification attempts. An integer from 1 to 5. | 
**CodeDigits** | **int32** | The length of the numeric code, from 3 to 9 digits. | 

## Methods

### NewSendOtpRequest

`func NewSendOtpRequest(recipient string, channel string, sender string, templateId int32, codeLifetime int32, codeMaxTries int32, codeDigits int32, ) *SendOtpRequest`

NewSendOtpRequest instantiates a new SendOtpRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendOtpRequestWithDefaults

`func NewSendOtpRequestWithDefaults() *SendOtpRequest`

NewSendOtpRequestWithDefaults instantiates a new SendOtpRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetRecipient

`func (o *SendOtpRequest) GetRecipient() string`

GetRecipient returns the Recipient field if non-nil, zero value otherwise.

### GetRecipientOk

`func (o *SendOtpRequest) GetRecipientOk() (*string, bool)`

GetRecipientOk returns a tuple with the Recipient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipient

`func (o *SendOtpRequest) SetRecipient(v string)`

SetRecipient sets Recipient field to given value.


### GetChannel

`func (o *SendOtpRequest) GetChannel() string`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *SendOtpRequest) GetChannelOk() (*string, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *SendOtpRequest) SetChannel(v string)`

SetChannel sets Channel field to given value.


### GetSender

`func (o *SendOtpRequest) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SendOtpRequest) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SendOtpRequest) SetSender(v string)`

SetSender sets Sender field to given value.


### GetSenderAlt

`func (o *SendOtpRequest) GetSenderAlt() string`

GetSenderAlt returns the SenderAlt field if non-nil, zero value otherwise.

### GetSenderAltOk

`func (o *SendOtpRequest) GetSenderAltOk() (*string, bool)`

GetSenderAltOk returns a tuple with the SenderAlt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSenderAlt

`func (o *SendOtpRequest) SetSenderAlt(v string)`

SetSenderAlt sets SenderAlt field to given value.

### HasSenderAlt

`func (o *SendOtpRequest) HasSenderAlt() bool`

HasSenderAlt returns a boolean if a field has been set.

### SetSenderAltNil

`func (o *SendOtpRequest) SetSenderAltNil(b bool)`

 SetSenderAltNil sets the value for SenderAlt to be an explicit nil

### UnsetSenderAlt
`func (o *SendOtpRequest) UnsetSenderAlt()`

UnsetSenderAlt ensures that no value is present for SenderAlt, not even an explicit nil
### GetTemplateId

`func (o *SendOtpRequest) GetTemplateId() int32`

GetTemplateId returns the TemplateId field if non-nil, zero value otherwise.

### GetTemplateIdOk

`func (o *SendOtpRequest) GetTemplateIdOk() (*int32, bool)`

GetTemplateIdOk returns a tuple with the TemplateId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplateId

`func (o *SendOtpRequest) SetTemplateId(v int32)`

SetTemplateId sets TemplateId field to given value.


### GetCodeLifetime

`func (o *SendOtpRequest) GetCodeLifetime() int32`

GetCodeLifetime returns the CodeLifetime field if non-nil, zero value otherwise.

### GetCodeLifetimeOk

`func (o *SendOtpRequest) GetCodeLifetimeOk() (*int32, bool)`

GetCodeLifetimeOk returns a tuple with the CodeLifetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeLifetime

`func (o *SendOtpRequest) SetCodeLifetime(v int32)`

SetCodeLifetime sets CodeLifetime field to given value.


### GetCodeMaxTries

`func (o *SendOtpRequest) GetCodeMaxTries() int32`

GetCodeMaxTries returns the CodeMaxTries field if non-nil, zero value otherwise.

### GetCodeMaxTriesOk

`func (o *SendOtpRequest) GetCodeMaxTriesOk() (*int32, bool)`

GetCodeMaxTriesOk returns a tuple with the CodeMaxTries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeMaxTries

`func (o *SendOtpRequest) SetCodeMaxTries(v int32)`

SetCodeMaxTries sets CodeMaxTries field to given value.


### GetCodeDigits

`func (o *SendOtpRequest) GetCodeDigits() int32`

GetCodeDigits returns the CodeDigits field if non-nil, zero value otherwise.

### GetCodeDigitsOk

`func (o *SendOtpRequest) GetCodeDigitsOk() (*int32, bool)`

GetCodeDigitsOk returns a tuple with the CodeDigits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCodeDigits

`func (o *SendOtpRequest) SetCodeDigits(v int32)`

SetCodeDigits sets CodeDigits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


