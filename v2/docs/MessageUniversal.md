# MessageUniversal

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Channels** | **[]string** |  | 
**Phone** | [**Phone**](Phone.md) |  | 
**Rcs** | Pointer to [**Rcs**](Rcs.md) |  | [optional] 
**Viber** | Pointer to [**Viber**](Viber.md) |  | [optional] 
**Sms** | Pointer to [**Sms**](Sms.md) |  | [optional] 
**Voice** | Pointer to [**Voice**](Voice.md) |  | [optional] 
**Telegram** | Pointer to [**Telegram**](Telegram.md) |  | [optional] 
**CallbackUrl** | Pointer to **interface{}** | Link to get the delivery status of messages. If this parameter is specified in the method, it will take precedence over the value specified in the “Callback URL” field in the Personal Area. | [optional] 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**ValiditySeconds** | Pointer to **int32** | Message validity period in seconds. After this period expires, the message will be in **EXPIRED** status or will be redirected to the SMS channel if it was specified in the request. Incompatible with **validity** | [optional] 
**RespectCurfew** | Pointer to **bool** | Check the curfew if it&#39;s set up in user settings. | [optional] [default to false]
**AddToContactBook** | Pointer to **bool** | Specifies whether to add the specified phone number of the message recipient to the contact book | [optional] [default to true]
**CheckStopList** | Pointer to **bool** | Check the recipient’s phone number for being in the stop list.  Possible values:    - true – if the number is found in the stop list, do not send the message  - false – ignore the stop list | [optional] [default to true]
**DryRun** | Pointer to **NullableBool** | Allows you to check the validity of the request without actual message sending | [optional] [default to false]

## Methods

### NewMessageUniversal

`func NewMessageUniversal(channels []string, phone Phone, ) *MessageUniversal`

NewMessageUniversal instantiates a new MessageUniversal object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageUniversalWithDefaults

`func NewMessageUniversalWithDefaults() *MessageUniversal`

NewMessageUniversalWithDefaults instantiates a new MessageUniversal object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetChannels

`func (o *MessageUniversal) GetChannels() []string`

GetChannels returns the Channels field if non-nil, zero value otherwise.

### GetChannelsOk

`func (o *MessageUniversal) GetChannelsOk() (*[]string, bool)`

GetChannelsOk returns a tuple with the Channels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannels

`func (o *MessageUniversal) SetChannels(v []string)`

SetChannels sets Channels field to given value.


### GetPhone

`func (o *MessageUniversal) GetPhone() Phone`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *MessageUniversal) GetPhoneOk() (*Phone, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *MessageUniversal) SetPhone(v Phone)`

SetPhone sets Phone field to given value.


### GetRcs

`func (o *MessageUniversal) GetRcs() Rcs`

GetRcs returns the Rcs field if non-nil, zero value otherwise.

### GetRcsOk

`func (o *MessageUniversal) GetRcsOk() (*Rcs, bool)`

GetRcsOk returns a tuple with the Rcs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRcs

`func (o *MessageUniversal) SetRcs(v Rcs)`

SetRcs sets Rcs field to given value.

### HasRcs

`func (o *MessageUniversal) HasRcs() bool`

HasRcs returns a boolean if a field has been set.

### GetViber

`func (o *MessageUniversal) GetViber() Viber`

GetViber returns the Viber field if non-nil, zero value otherwise.

### GetViberOk

`func (o *MessageUniversal) GetViberOk() (*Viber, bool)`

GetViberOk returns a tuple with the Viber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViber

`func (o *MessageUniversal) SetViber(v Viber)`

SetViber sets Viber field to given value.

### HasViber

`func (o *MessageUniversal) HasViber() bool`

HasViber returns a boolean if a field has been set.

### GetSms

`func (o *MessageUniversal) GetSms() Sms`

GetSms returns the Sms field if non-nil, zero value otherwise.

### GetSmsOk

`func (o *MessageUniversal) GetSmsOk() (*Sms, bool)`

GetSmsOk returns a tuple with the Sms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSms

`func (o *MessageUniversal) SetSms(v Sms)`

SetSms sets Sms field to given value.

### HasSms

`func (o *MessageUniversal) HasSms() bool`

HasSms returns a boolean if a field has been set.

### GetVoice

`func (o *MessageUniversal) GetVoice() Voice`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *MessageUniversal) GetVoiceOk() (*Voice, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *MessageUniversal) SetVoice(v Voice)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *MessageUniversal) HasVoice() bool`

HasVoice returns a boolean if a field has been set.

### GetTelegram

`func (o *MessageUniversal) GetTelegram() Telegram`

GetTelegram returns the Telegram field if non-nil, zero value otherwise.

### GetTelegramOk

`func (o *MessageUniversal) GetTelegramOk() (*Telegram, bool)`

GetTelegramOk returns a tuple with the Telegram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelegram

`func (o *MessageUniversal) SetTelegram(v Telegram)`

SetTelegram sets Telegram field to given value.

### HasTelegram

`func (o *MessageUniversal) HasTelegram() bool`

HasTelegram returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *MessageUniversal) GetCallbackUrl() interface{}`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *MessageUniversal) GetCallbackUrlOk() (*interface{}, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *MessageUniversal) SetCallbackUrl(v interface{})`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *MessageUniversal) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### SetCallbackUrlNil

`func (o *MessageUniversal) SetCallbackUrlNil(b bool)`

 SetCallbackUrlNil sets the value for CallbackUrl to be an explicit nil

### UnsetCallbackUrl
`func (o *MessageUniversal) UnsetCallbackUrl()`

UnsetCallbackUrl ensures that no value is present for CallbackUrl, not even an explicit nil
### GetTariffCode

`func (o *MessageUniversal) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *MessageUniversal) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *MessageUniversal) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *MessageUniversal) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValidity

`func (o *MessageUniversal) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *MessageUniversal) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *MessageUniversal) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *MessageUniversal) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetValiditySeconds

`func (o *MessageUniversal) GetValiditySeconds() int32`

GetValiditySeconds returns the ValiditySeconds field if non-nil, zero value otherwise.

### GetValiditySecondsOk

`func (o *MessageUniversal) GetValiditySecondsOk() (*int32, bool)`

GetValiditySecondsOk returns a tuple with the ValiditySeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValiditySeconds

`func (o *MessageUniversal) SetValiditySeconds(v int32)`

SetValiditySeconds sets ValiditySeconds field to given value.

### HasValiditySeconds

`func (o *MessageUniversal) HasValiditySeconds() bool`

HasValiditySeconds returns a boolean if a field has been set.

### GetRespectCurfew

`func (o *MessageUniversal) GetRespectCurfew() bool`

GetRespectCurfew returns the RespectCurfew field if non-nil, zero value otherwise.

### GetRespectCurfewOk

`func (o *MessageUniversal) GetRespectCurfewOk() (*bool, bool)`

GetRespectCurfewOk returns a tuple with the RespectCurfew field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRespectCurfew

`func (o *MessageUniversal) SetRespectCurfew(v bool)`

SetRespectCurfew sets RespectCurfew field to given value.

### HasRespectCurfew

`func (o *MessageUniversal) HasRespectCurfew() bool`

HasRespectCurfew returns a boolean if a field has been set.

### GetAddToContactBook

`func (o *MessageUniversal) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *MessageUniversal) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *MessageUniversal) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *MessageUniversal) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *MessageUniversal) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *MessageUniversal) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *MessageUniversal) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *MessageUniversal) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.

### GetDryRun

`func (o *MessageUniversal) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *MessageUniversal) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *MessageUniversal) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.

### HasDryRun

`func (o *MessageUniversal) HasDryRun() bool`

HasDryRun returns a boolean if a field has been set.

### SetDryRunNil

`func (o *MessageUniversal) SetDryRunNil(b bool)`

 SetDryRunNil sets the value for DryRun to be an explicit nil

### UnsetDryRun
`func (o *MessageUniversal) UnsetDryRun()`

UnsetDryRun ensures that no value is present for DryRun, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


