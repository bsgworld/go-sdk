# SendRcsCampaignGroups

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Groups** | **[]int32** | An array of lists (list id) with contacts from the address book to which RCS campaigns are to be sent. id of the lists can be obtained: using the Get [lists API](#tag/Contact-List) in your account [Contact Book → Lists](https://app.bsg.world/addressbook/lists) | 
**Sender** | **string** | The name of the agent used to send the rcs message | 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**Options** | [**Options**](Options.md) |  | 
**AlternativeChannel** | Pointer to [**NullableSendRcsCampaignGroupsAlternativeChannel**](SendRcsCampaignGroupsAlternativeChannel.md) |  | [optional] 
**AddToContactBook** | Pointer to **bool** | Specifies whether to add the specified phone number of the message recipient to the contact book | [optional] [default to true]
**CheckStopList** | Pointer to **bool** | Check the recipient’s phone number for being in the stop list.  Possible values:    - true – if the number is found in the stop list, do not send the message  - false – ignore the stop list | [optional] [default to true]

## Methods

### NewSendRcsCampaignGroups

`func NewSendRcsCampaignGroups(groups []int32, sender string, options Options, ) *SendRcsCampaignGroups`

NewSendRcsCampaignGroups instantiates a new SendRcsCampaignGroups object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendRcsCampaignGroupsWithDefaults

`func NewSendRcsCampaignGroupsWithDefaults() *SendRcsCampaignGroups`

NewSendRcsCampaignGroupsWithDefaults instantiates a new SendRcsCampaignGroups object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetGroups

`func (o *SendRcsCampaignGroups) GetGroups() []int32`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *SendRcsCampaignGroups) GetGroupsOk() (*[]int32, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *SendRcsCampaignGroups) SetGroups(v []int32)`

SetGroups sets Groups field to given value.


### GetSender

`func (o *SendRcsCampaignGroups) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SendRcsCampaignGroups) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SendRcsCampaignGroups) SetSender(v string)`

SetSender sets Sender field to given value.


### GetTariffCode

`func (o *SendRcsCampaignGroups) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *SendRcsCampaignGroups) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *SendRcsCampaignGroups) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *SendRcsCampaignGroups) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValidity

`func (o *SendRcsCampaignGroups) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SendRcsCampaignGroups) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SendRcsCampaignGroups) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SendRcsCampaignGroups) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetStartAt

`func (o *SendRcsCampaignGroups) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *SendRcsCampaignGroups) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *SendRcsCampaignGroups) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *SendRcsCampaignGroups) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetOptions

`func (o *SendRcsCampaignGroups) GetOptions() Options`

GetOptions returns the Options field if non-nil, zero value otherwise.

### GetOptionsOk

`func (o *SendRcsCampaignGroups) GetOptionsOk() (*Options, bool)`

GetOptionsOk returns a tuple with the Options field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOptions

`func (o *SendRcsCampaignGroups) SetOptions(v Options)`

SetOptions sets Options field to given value.


### GetAlternativeChannel

`func (o *SendRcsCampaignGroups) GetAlternativeChannel() SendRcsCampaignGroupsAlternativeChannel`

GetAlternativeChannel returns the AlternativeChannel field if non-nil, zero value otherwise.

### GetAlternativeChannelOk

`func (o *SendRcsCampaignGroups) GetAlternativeChannelOk() (*SendRcsCampaignGroupsAlternativeChannel, bool)`

GetAlternativeChannelOk returns a tuple with the AlternativeChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannel

`func (o *SendRcsCampaignGroups) SetAlternativeChannel(v SendRcsCampaignGroupsAlternativeChannel)`

SetAlternativeChannel sets AlternativeChannel field to given value.

### HasAlternativeChannel

`func (o *SendRcsCampaignGroups) HasAlternativeChannel() bool`

HasAlternativeChannel returns a boolean if a field has been set.

### SetAlternativeChannelNil

`func (o *SendRcsCampaignGroups) SetAlternativeChannelNil(b bool)`

 SetAlternativeChannelNil sets the value for AlternativeChannel to be an explicit nil

### UnsetAlternativeChannel
`func (o *SendRcsCampaignGroups) UnsetAlternativeChannel()`

UnsetAlternativeChannel ensures that no value is present for AlternativeChannel, not even an explicit nil
### GetAddToContactBook

`func (o *SendRcsCampaignGroups) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *SendRcsCampaignGroups) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *SendRcsCampaignGroups) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *SendRcsCampaignGroups) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *SendRcsCampaignGroups) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *SendRcsCampaignGroups) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *SendRcsCampaignGroups) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *SendRcsCampaignGroups) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


