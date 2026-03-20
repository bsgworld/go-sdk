# SendViberCampaign

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phones** | [**[]Phone**](Phone.md) | The list of objects containing information about the mobile phone number (number) and (reference_id) to send a message to | 
**Sender** | **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | 
**Text** | **string** |  | 
**ImageUrl** | Pointer to **string** |  | [optional] 
**ButtonCaption** | Pointer to **string** |  | [optional] 
**LinkUrl** | Pointer to **string** | Required if button_caption is set | [optional] 
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**TariffCode** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**AlternativeChannel** | Pointer to [**AlternativeChannel**](AlternativeChannel.md) |  | [optional] 
**AddToContactBook** | Pointer to **bool** | Specifies whether to add the specified phone number of the message recipient to the contact book | [optional] [default to true]
**CheckStopList** | Pointer to **bool** | Check the recipient’s phone number for being in the stop list.  Possible values:    - true – if the number is found in the stop list, do not send the message  - false – ignore the stop list | [optional] [default to true]

## Methods

### NewSendViberCampaign

`func NewSendViberCampaign(phones []Phone, sender string, text string, ) *SendViberCampaign`

NewSendViberCampaign instantiates a new SendViberCampaign object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendViberCampaignWithDefaults

`func NewSendViberCampaignWithDefaults() *SendViberCampaign`

NewSendViberCampaignWithDefaults instantiates a new SendViberCampaign object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhones

`func (o *SendViberCampaign) GetPhones() []Phone`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SendViberCampaign) GetPhonesOk() (*[]Phone, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SendViberCampaign) SetPhones(v []Phone)`

SetPhones sets Phones field to given value.


### GetSender

`func (o *SendViberCampaign) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SendViberCampaign) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SendViberCampaign) SetSender(v string)`

SetSender sets Sender field to given value.


### GetText

`func (o *SendViberCampaign) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *SendViberCampaign) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *SendViberCampaign) SetText(v string)`

SetText sets Text field to given value.


### GetImageUrl

`func (o *SendViberCampaign) GetImageUrl() string`

GetImageUrl returns the ImageUrl field if non-nil, zero value otherwise.

### GetImageUrlOk

`func (o *SendViberCampaign) GetImageUrlOk() (*string, bool)`

GetImageUrlOk returns a tuple with the ImageUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImageUrl

`func (o *SendViberCampaign) SetImageUrl(v string)`

SetImageUrl sets ImageUrl field to given value.

### HasImageUrl

`func (o *SendViberCampaign) HasImageUrl() bool`

HasImageUrl returns a boolean if a field has been set.

### GetButtonCaption

`func (o *SendViberCampaign) GetButtonCaption() string`

GetButtonCaption returns the ButtonCaption field if non-nil, zero value otherwise.

### GetButtonCaptionOk

`func (o *SendViberCampaign) GetButtonCaptionOk() (*string, bool)`

GetButtonCaptionOk returns a tuple with the ButtonCaption field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetButtonCaption

`func (o *SendViberCampaign) SetButtonCaption(v string)`

SetButtonCaption sets ButtonCaption field to given value.

### HasButtonCaption

`func (o *SendViberCampaign) HasButtonCaption() bool`

HasButtonCaption returns a boolean if a field has been set.

### GetLinkUrl

`func (o *SendViberCampaign) GetLinkUrl() string`

GetLinkUrl returns the LinkUrl field if non-nil, zero value otherwise.

### GetLinkUrlOk

`func (o *SendViberCampaign) GetLinkUrlOk() (*string, bool)`

GetLinkUrlOk returns a tuple with the LinkUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLinkUrl

`func (o *SendViberCampaign) SetLinkUrl(v string)`

SetLinkUrl sets LinkUrl field to given value.

### HasLinkUrl

`func (o *SendViberCampaign) HasLinkUrl() bool`

HasLinkUrl returns a boolean if a field has been set.

### GetStartAt

`func (o *SendViberCampaign) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *SendViberCampaign) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *SendViberCampaign) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *SendViberCampaign) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetTariffCode

`func (o *SendViberCampaign) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *SendViberCampaign) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *SendViberCampaign) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *SendViberCampaign) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetValidity

`func (o *SendViberCampaign) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *SendViberCampaign) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *SendViberCampaign) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *SendViberCampaign) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetAlternativeChannel

`func (o *SendViberCampaign) GetAlternativeChannel() AlternativeChannel`

GetAlternativeChannel returns the AlternativeChannel field if non-nil, zero value otherwise.

### GetAlternativeChannelOk

`func (o *SendViberCampaign) GetAlternativeChannelOk() (*AlternativeChannel, bool)`

GetAlternativeChannelOk returns a tuple with the AlternativeChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannel

`func (o *SendViberCampaign) SetAlternativeChannel(v AlternativeChannel)`

SetAlternativeChannel sets AlternativeChannel field to given value.

### HasAlternativeChannel

`func (o *SendViberCampaign) HasAlternativeChannel() bool`

HasAlternativeChannel returns a boolean if a field has been set.

### GetAddToContactBook

`func (o *SendViberCampaign) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *SendViberCampaign) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *SendViberCampaign) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *SendViberCampaign) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *SendViberCampaign) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *SendViberCampaign) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *SendViberCampaign) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *SendViberCampaign) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


