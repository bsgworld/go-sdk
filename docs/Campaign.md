# Campaign

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**AddToContactBook** | Pointer to **bool** | Specifies whether to add the specified phone number of the message recipient to the contact book | [optional] [default to true]
**CheckStopList** | Pointer to **bool** | Check the recipient’s phone number for being in the stop list.  Possible values:    - true – if the number is found in the stop list, do not send the message  - false – ignore the stop list | [optional] [default to true]
**Recipients** | [**Recipients**](Recipients.md) |  | 
**Channels** | **[]string** |  | 
**Rcs** | Pointer to [**Rcs**](Rcs.md) |  | [optional] 
**Viber** | Pointer to [**Viber**](Viber.md) |  | [optional] 
**Sms** | Pointer to [**Sms**](Sms.md) |  | [optional] 
**Voice** | Pointer to [**Voice**](Voice.md) |  | [optional] 
**Telegram** | Pointer to [**Telegram**](Telegram.md) |  | [optional] 
**DryRun** | Pointer to **NullableBool** | Allows you to check the validity of the request without actual campaign sending | [optional] [default to false]

## Methods

### NewCampaign

`func NewCampaign(recipients Recipients, channels []string, ) *Campaign`

NewCampaign instantiates a new Campaign object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCampaignWithDefaults

`func NewCampaignWithDefaults() *Campaign`

NewCampaignWithDefaults instantiates a new Campaign object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTariffCode

`func (o *Campaign) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *Campaign) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *Campaign) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *Campaign) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValidity

`func (o *Campaign) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *Campaign) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *Campaign) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *Campaign) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetStartAt

`func (o *Campaign) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *Campaign) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *Campaign) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *Campaign) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetAddToContactBook

`func (o *Campaign) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *Campaign) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *Campaign) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *Campaign) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *Campaign) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *Campaign) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *Campaign) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *Campaign) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.

### GetRecipients

`func (o *Campaign) GetRecipients() Recipients`

GetRecipients returns the Recipients field if non-nil, zero value otherwise.

### GetRecipientsOk

`func (o *Campaign) GetRecipientsOk() (*Recipients, bool)`

GetRecipientsOk returns a tuple with the Recipients field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRecipients

`func (o *Campaign) SetRecipients(v Recipients)`

SetRecipients sets Recipients field to given value.


### GetChannels

`func (o *Campaign) GetChannels() []string`

GetChannels returns the Channels field if non-nil, zero value otherwise.

### GetChannelsOk

`func (o *Campaign) GetChannelsOk() (*[]string, bool)`

GetChannelsOk returns a tuple with the Channels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetChannels

`func (o *Campaign) SetChannels(v []string)`

SetChannels sets Channels field to given value.


### GetRcs

`func (o *Campaign) GetRcs() Rcs`

GetRcs returns the Rcs field if non-nil, zero value otherwise.

### GetRcsOk

`func (o *Campaign) GetRcsOk() (*Rcs, bool)`

GetRcsOk returns a tuple with the Rcs field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRcs

`func (o *Campaign) SetRcs(v Rcs)`

SetRcs sets Rcs field to given value.

### HasRcs

`func (o *Campaign) HasRcs() bool`

HasRcs returns a boolean if a field has been set.

### GetViber

`func (o *Campaign) GetViber() Viber`

GetViber returns the Viber field if non-nil, zero value otherwise.

### GetViberOk

`func (o *Campaign) GetViberOk() (*Viber, bool)`

GetViberOk returns a tuple with the Viber field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViber

`func (o *Campaign) SetViber(v Viber)`

SetViber sets Viber field to given value.

### HasViber

`func (o *Campaign) HasViber() bool`

HasViber returns a boolean if a field has been set.

### GetSms

`func (o *Campaign) GetSms() Sms`

GetSms returns the Sms field if non-nil, zero value otherwise.

### GetSmsOk

`func (o *Campaign) GetSmsOk() (*Sms, bool)`

GetSmsOk returns a tuple with the Sms field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSms

`func (o *Campaign) SetSms(v Sms)`

SetSms sets Sms field to given value.

### HasSms

`func (o *Campaign) HasSms() bool`

HasSms returns a boolean if a field has been set.

### GetVoice

`func (o *Campaign) GetVoice() Voice`

GetVoice returns the Voice field if non-nil, zero value otherwise.

### GetVoiceOk

`func (o *Campaign) GetVoiceOk() (*Voice, bool)`

GetVoiceOk returns a tuple with the Voice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetVoice

`func (o *Campaign) SetVoice(v Voice)`

SetVoice sets Voice field to given value.

### HasVoice

`func (o *Campaign) HasVoice() bool`

HasVoice returns a boolean if a field has been set.

### GetTelegram

`func (o *Campaign) GetTelegram() Telegram`

GetTelegram returns the Telegram field if non-nil, zero value otherwise.

### GetTelegramOk

`func (o *Campaign) GetTelegramOk() (*Telegram, bool)`

GetTelegramOk returns a tuple with the Telegram field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTelegram

`func (o *Campaign) SetTelegram(v Telegram)`

SetTelegram sets Telegram field to given value.

### HasTelegram

`func (o *Campaign) HasTelegram() bool`

HasTelegram returns a boolean if a field has been set.

### GetDryRun

`func (o *Campaign) GetDryRun() bool`

GetDryRun returns the DryRun field if non-nil, zero value otherwise.

### GetDryRunOk

`func (o *Campaign) GetDryRunOk() (*bool, bool)`

GetDryRunOk returns a tuple with the DryRun field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDryRun

`func (o *Campaign) SetDryRun(v bool)`

SetDryRun sets DryRun field to given value.

### HasDryRun

`func (o *Campaign) HasDryRun() bool`

HasDryRun returns a boolean if a field has been set.

### SetDryRunNil

`func (o *Campaign) SetDryRunNil(b bool)`

 SetDryRunNil sets the value for DryRun to be an explicit nil

### UnsetDryRun
`func (o *Campaign) UnsetDryRun()`

UnsetDryRun ensures that no value is present for DryRun, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


