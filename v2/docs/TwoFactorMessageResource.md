# TwoFactorMessageResource

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | The unique ID of the message | [optional] 
**Recipient** | Pointer to **string** | Number of the recipient of the message with a one-time code | [optional] 
**Status** | Pointer to [**OtpMessageStatus**](OtpMessageStatus.md) |  | [optional] 
**Channel** | Pointer to [**OtpChannel**](OtpChannel.md) |  | [optional] 
**Sender** | Pointer to **string** | Sender name | [optional] 
**Price** | Pointer to **float32** | Message cost | [optional] 
**Currency** | Pointer to **string** | The three-letter code of the currency in which the value is indicated. Corresponds to the user’s account currency | [optional] 
**SentAt** | Pointer to **NullableString** | The date and time of the message were sent in ISO 8601 format | [optional] 
**CreatedAt** | Pointer to **string** | The date and time the message was created in ISO 8601 format | [optional] 

## Methods

### NewTwoFactorMessageResource

`func NewTwoFactorMessageResource() *TwoFactorMessageResource`

NewTwoFactorMessageResource instantiates a new TwoFactorMessageResource object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTwoFactorMessageResourceWithDefaults

`func NewTwoFactorMessageResourceWithDefaults() *TwoFactorMessageResource`

NewTwoFactorMessageResourceWithDefaults instantiates a new TwoFactorMessageResource object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TwoFactorMessageResource) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TwoFactorMessageResource) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TwoFactorMessageResource) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *TwoFactorMessageResource) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRecipient

`func (o *TwoFactorMessageResource) GetRecipient() string`

GetRecipient returns the Recipient field if non-nil, zero value otherwise.

### GetRecipientOk

`func (o *TwoFactorMessageResource) GetRecipientOk() (*string, bool)`

GetRecipientOk returns a tuple with the Recipient field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipient

`func (o *TwoFactorMessageResource) SetRecipient(v string)`

SetRecipient sets Recipient field to given value.

### HasRecipient

`func (o *TwoFactorMessageResource) HasRecipient() bool`

HasRecipient returns a boolean if a field has been set.

### GetStatus

`func (o *TwoFactorMessageResource) GetStatus() OtpMessageStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *TwoFactorMessageResource) GetStatusOk() (*OtpMessageStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *TwoFactorMessageResource) SetStatus(v OtpMessageStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *TwoFactorMessageResource) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetChannel

`func (o *TwoFactorMessageResource) GetChannel() OtpChannel`

GetChannel returns the Channel field if non-nil, zero value otherwise.

### GetChannelOk

`func (o *TwoFactorMessageResource) GetChannelOk() (*OtpChannel, bool)`

GetChannelOk returns a tuple with the Channel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannel

`func (o *TwoFactorMessageResource) SetChannel(v OtpChannel)`

SetChannel sets Channel field to given value.

### HasChannel

`func (o *TwoFactorMessageResource) HasChannel() bool`

HasChannel returns a boolean if a field has been set.

### GetSender

`func (o *TwoFactorMessageResource) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *TwoFactorMessageResource) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *TwoFactorMessageResource) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *TwoFactorMessageResource) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetPrice

`func (o *TwoFactorMessageResource) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *TwoFactorMessageResource) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *TwoFactorMessageResource) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *TwoFactorMessageResource) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *TwoFactorMessageResource) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *TwoFactorMessageResource) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *TwoFactorMessageResource) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *TwoFactorMessageResource) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetSentAt

`func (o *TwoFactorMessageResource) GetSentAt() string`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *TwoFactorMessageResource) GetSentAtOk() (*string, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *TwoFactorMessageResource) SetSentAt(v string)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *TwoFactorMessageResource) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *TwoFactorMessageResource) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *TwoFactorMessageResource) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetCreatedAt

`func (o *TwoFactorMessageResource) GetCreatedAt() string`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *TwoFactorMessageResource) GetCreatedAtOk() (*string, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *TwoFactorMessageResource) SetCreatedAt(v string)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *TwoFactorMessageResource) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


