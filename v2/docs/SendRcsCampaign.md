# SendRcsCampaign

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phones** | [**[]Phone**](Phone.md) | The list of objects containing information about the mobile phone number (number) and (reference_id) to send a message to | 
**Sender** | **string** | The name of the agent used to send the rcs message | 
**Options** | [**Options**](Options.md) |  | 
**AlternativeChannel** | Pointer to [**AlternativeChannel**](AlternativeChannel.md) |  | [optional] 
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**ValiditySeconds** | Pointer to **int32** | Message validity period in seconds. After this period expires, the message will be in **EXPIRED** status or will be redirected to the SMS channel if it was specified in the request. Incompatible with **validity** | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**AddToContactBook** | Pointer to **bool** | Specifies whether to add the specified phone number of the message recipient to the contact book | [optional] [default to true]
**CheckStopList** | Pointer to **bool** | Check the recipient’s phone number for being in the stop list.  Possible values:    - true – if the number is found in the stop list, do not send the message  - false – ignore the stop list | [optional] [default to true]

## Methods

### NewSendRcsCampaign

`func NewSendRcsCampaign(phones []Phone, sender string, options Options, ) *SendRcsCampaign`

NewSendRcsCampaign instantiates a new SendRcsCampaign object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendRcsCampaignWithDefaults

`func NewSendRcsCampaignWithDefaults() *SendRcsCampaign`

NewSendRcsCampaignWithDefaults instantiates a new SendRcsCampaign object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhones

`func (o *SendRcsCampaign) GetPhones() []Phone`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SendRcsCampaign) GetPhonesOk() (*[]Phone, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SendRcsCampaign) SetPhones(v []Phone)`

SetPhones sets Phones field to given value.


### GetSender

`func (o *SendRcsCampaign) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SendRcsCampaign) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SendRcsCampaign) SetSender(v string)`

SetSender sets Sender field to given value.


### GetOptions

`func (o *SendRcsCampaign) GetOptions() Options`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *SendRcsCampaign) GetOptionsOk() (*Options, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *SendRcsCampaign) SetOptions(v Options)`

SetOptions sets Options field to given value.


### GetAlternativeChannel

`func (o *SendRcsCampaign) GetAlternativeChannel() AlternativeChannel`

GetAlternativeChannel returns the AlternativeChannel field if non-nil, zero value otherwise.

### GetAlternativeChannelOk

`func (o *SendRcsCampaign) GetAlternativeChannelOk() (*AlternativeChannel, bool)`

GetAlternativeChannelOk returns a tuple with the AlternativeChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannel

`func (o *SendRcsCampaign) SetAlternativeChannel(v AlternativeChannel)`

SetAlternativeChannel sets AlternativeChannel field to given value.

### HasAlternativeChannel

`func (o *SendRcsCampaign) HasAlternativeChannel() bool`

HasAlternativeChannel returns a boolean if a field has been set.

### GetStartAt

`func (o *SendRcsCampaign) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *SendRcsCampaign) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *SendRcsCampaign) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *SendRcsCampaign) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetTariffCode

`func (o *SendRcsCampaign) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *SendRcsCampaign) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *SendRcsCampaign) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *SendRcsCampaign) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValiditySeconds

`func (o *SendRcsCampaign) GetValiditySeconds() int32`

GetValiditySeconds returns the ValiditySeconds field if non-nil, zero value otherwise.

### GetValiditySecondsOk

`func (o *SendRcsCampaign) GetValiditySecondsOk() (*int32, bool)`

GetValiditySecondsOk returns a tuple with the ValiditySeconds field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValiditySeconds

`func (o *SendRcsCampaign) SetValiditySeconds(v int32)`

SetValiditySeconds sets ValiditySeconds field to given value.

### HasValiditySeconds

`func (o *SendRcsCampaign) HasValiditySeconds() bool`

HasValiditySeconds returns a boolean if a field has been set.

### GetValidity

`func (o *SendRcsCampaign) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SendRcsCampaign) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SendRcsCampaign) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SendRcsCampaign) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetAddToContactBook

`func (o *SendRcsCampaign) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *SendRcsCampaign) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *SendRcsCampaign) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *SendRcsCampaign) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *SendRcsCampaign) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *SendRcsCampaign) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *SendRcsCampaign) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *SendRcsCampaign) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


