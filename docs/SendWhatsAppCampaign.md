# SendWhatsAppCampaign

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phones** | [**[]Phone**](Phone.md) | $phones | 
**Sender** | **string** | The name of the agent used to send the whatsapp message | 
**Type** | **string** | Type of Whatsapp message, only \&quot;template\&quot; now is supported | 
**Template** | Pointer to [**NullableTemplate**](Template.md) | Required for type \&quot;template\&quot; | [optional] 
**AlternativeChannel** | Pointer to [**NullableSendWhatsAppCampaignAlternativeChannel**](SendWhatsAppCampaignAlternativeChannel.md) |  | [optional] 
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**AddToContactBook** | Pointer to **bool** | Specifies whether to add the specified phone number of the message recipient to the contact book | [optional] [default to true]
**CheckStopList** | Pointer to **bool** | Check the recipient’s phone number for being in the stop list.  Possible values:    - true – if the number is found in the stop list, do not send the message  - false – ignore the stop list | [optional] [default to true]

## Methods

### NewSendWhatsAppCampaign

`func NewSendWhatsAppCampaign(phones []Phone, sender string, type_ string, ) *SendWhatsAppCampaign`

NewSendWhatsAppCampaign instantiates a new SendWhatsAppCampaign object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendWhatsAppCampaignWithDefaults

`func NewSendWhatsAppCampaignWithDefaults() *SendWhatsAppCampaign`

NewSendWhatsAppCampaignWithDefaults instantiates a new SendWhatsAppCampaign object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhones

`func (o *SendWhatsAppCampaign) GetPhones() []Phone`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *SendWhatsAppCampaign) GetPhonesOk() (*[]Phone, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *SendWhatsAppCampaign) SetPhones(v []Phone)`

SetPhones sets Phones field to given value.


### GetSender

`func (o *SendWhatsAppCampaign) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SendWhatsAppCampaign) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SendWhatsAppCampaign) SetSender(v string)`

SetSender sets Sender field to given value.


### GetType

`func (o *SendWhatsAppCampaign) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *SendWhatsAppCampaign) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *SendWhatsAppCampaign) SetType(v string)`

SetType sets Type field to given value.


### GetTemplate

`func (o *SendWhatsAppCampaign) GetTemplate() Template`

GetTemplate returns the Template field if non-nil, zero value otherwise.

### GetTemplateOk

`func (o *SendWhatsAppCampaign) GetTemplateOk() (*Template, bool)`

GetTemplateOk returns a tuple with the Template field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTemplate

`func (o *SendWhatsAppCampaign) SetTemplate(v Template)`

SetTemplate sets Template field to given value.

### HasTemplate

`func (o *SendWhatsAppCampaign) HasTemplate() bool`

HasTemplate returns a boolean if a field has been set.

### SetTemplateNil

`func (o *SendWhatsAppCampaign) SetTemplateNil(b bool)`

 SetTemplateNil sets the value for Template to be an explicit nil

### UnsetTemplate
`func (o *SendWhatsAppCampaign) UnsetTemplate()`

UnsetTemplate ensures that no value is present for Template, not even an explicit nil
### GetAlternativeChannel

`func (o *SendWhatsAppCampaign) GetAlternativeChannel() SendWhatsAppCampaignAlternativeChannel`

GetAlternativeChannel returns the AlternativeChannel field if non-nil, zero value otherwise.

### GetAlternativeChannelOk

`func (o *SendWhatsAppCampaign) GetAlternativeChannelOk() (*SendWhatsAppCampaignAlternativeChannel, bool)`

GetAlternativeChannelOk returns a tuple with the AlternativeChannel field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannel

`func (o *SendWhatsAppCampaign) SetAlternativeChannel(v SendWhatsAppCampaignAlternativeChannel)`

SetAlternativeChannel sets AlternativeChannel field to given value.

### HasAlternativeChannel

`func (o *SendWhatsAppCampaign) HasAlternativeChannel() bool`

HasAlternativeChannel returns a boolean if a field has been set.

### SetAlternativeChannelNil

`func (o *SendWhatsAppCampaign) SetAlternativeChannelNil(b bool)`

 SetAlternativeChannelNil sets the value for AlternativeChannel to be an explicit nil

### UnsetAlternativeChannel
`func (o *SendWhatsAppCampaign) UnsetAlternativeChannel()`

UnsetAlternativeChannel ensures that no value is present for AlternativeChannel, not even an explicit nil
### GetStartAt

`func (o *SendWhatsAppCampaign) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *SendWhatsAppCampaign) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *SendWhatsAppCampaign) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *SendWhatsAppCampaign) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetAddToContactBook

`func (o *SendWhatsAppCampaign) GetAddToContactBook() bool`

GetAddToContactBook returns the AddToContactBook field if non-nil, zero value otherwise.

### GetAddToContactBookOk

`func (o *SendWhatsAppCampaign) GetAddToContactBookOk() (*bool, bool)`

GetAddToContactBookOk returns a tuple with the AddToContactBook field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAddToContactBook

`func (o *SendWhatsAppCampaign) SetAddToContactBook(v bool)`

SetAddToContactBook sets AddToContactBook field to given value.

### HasAddToContactBook

`func (o *SendWhatsAppCampaign) HasAddToContactBook() bool`

HasAddToContactBook returns a boolean if a field has been set.

### GetCheckStopList

`func (o *SendWhatsAppCampaign) GetCheckStopList() bool`

GetCheckStopList returns the CheckStopList field if non-nil, zero value otherwise.

### GetCheckStopListOk

`func (o *SendWhatsAppCampaign) GetCheckStopListOk() (*bool, bool)`

GetCheckStopListOk returns a tuple with the CheckStopList field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCheckStopList

`func (o *SendWhatsAppCampaign) SetCheckStopList(v bool)`

SetCheckStopList sets CheckStopList field to given value.

### HasCheckStopList

`func (o *SendWhatsAppCampaign) HasCheckStopList() bool`

HasCheckStopList returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


