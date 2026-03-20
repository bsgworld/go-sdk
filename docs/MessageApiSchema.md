# MessageApiSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Message ID – a unique identifier automatically generated on the Platform when the message is created | [optional] 
**CampaignId** | Pointer to **int32** | campaign unique identifier | [optional] 
**ReferenceId** | Pointer to **string** | external unique ID. String up to 32 characters containing only alpha numeric characters.  **Please note:** messages with duplicate reference_id will be rejected | [optional] 
**Type** | Pointer to [**MessageType**](MessageType.md) |  | [optional] 
**Source** | Pointer to [**MessageSource**](MessageSource.md) |  | [optional] 
**Text** | Pointer to **string** | Message text to send | [optional] 
**Phone** | Pointer to **int32** | Phone number without leading plus, just digits | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**Status** | Pointer to [**MessageStatus**](MessageStatus.md) |  | [optional] 
**Amount** | Pointer to [**MessagePriceObject**](MessagePriceObject.md) |  | [optional] 
**Sender** | Pointer to **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**SentAt** | Pointer to **NullableTime** | Date and time of sending the message | [optional] 
**DeliveredAt** | Pointer to **NullableTime** | Date and time of receipt of the delivery report response | [optional] 
**Country** | Pointer to **string** | Country code according to ISO 3166-1 alpha-2 standard | [optional] 
**Parts** | Pointer to **int32** |  | [optional] 
**RcsOptions** | Pointer to [**Options**](Options.md) |  | [optional] 
**AlternativeChannels** | Pointer to [**NullableMessageApiSchemaAlternativeChannels**](MessageApiSchemaAlternativeChannels.md) |  | [optional] 

## Methods

### NewMessageApiSchema

`func NewMessageApiSchema() *MessageApiSchema`

NewMessageApiSchema instantiates a new MessageApiSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageApiSchemaWithDefaults

`func NewMessageApiSchemaWithDefaults() *MessageApiSchema`

NewMessageApiSchemaWithDefaults instantiates a new MessageApiSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MessageApiSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessageApiSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessageApiSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *MessageApiSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetCampaignId

`func (o *MessageApiSchema) GetCampaignId() int32`

GetCampaignId returns the CampaignId field if non-nil, zero value otherwise.

### GetCampaignIdOk

`func (o *MessageApiSchema) GetCampaignIdOk() (*int32, bool)`

GetCampaignIdOk returns a tuple with the CampaignId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCampaignId

`func (o *MessageApiSchema) SetCampaignId(v int32)`

SetCampaignId sets CampaignId field to given value.

### HasCampaignId

`func (o *MessageApiSchema) HasCampaignId() bool`

HasCampaignId returns a boolean if a field has been set.

### GetReferenceId

`func (o *MessageApiSchema) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *MessageApiSchema) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *MessageApiSchema) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *MessageApiSchema) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.

### GetType

`func (o *MessageApiSchema) GetType() MessageType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MessageApiSchema) GetTypeOk() (*MessageType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MessageApiSchema) SetType(v MessageType)`

SetType sets Type field to given value.

### HasType

`func (o *MessageApiSchema) HasType() bool`

HasType returns a boolean if a field has been set.

### GetSource

`func (o *MessageApiSchema) GetSource() MessageSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *MessageApiSchema) GetSourceOk() (*MessageSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *MessageApiSchema) SetSource(v MessageSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *MessageApiSchema) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetText

`func (o *MessageApiSchema) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *MessageApiSchema) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *MessageApiSchema) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *MessageApiSchema) HasText() bool`

HasText returns a boolean if a field has been set.

### GetPhone

`func (o *MessageApiSchema) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *MessageApiSchema) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *MessageApiSchema) SetPhone(v int32)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *MessageApiSchema) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetValidity

`func (o *MessageApiSchema) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *MessageApiSchema) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *MessageApiSchema) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *MessageApiSchema) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetStatus

`func (o *MessageApiSchema) GetStatus() MessageStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MessageApiSchema) GetStatusOk() (*MessageStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MessageApiSchema) SetStatus(v MessageStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *MessageApiSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetAmount

`func (o *MessageApiSchema) GetAmount() MessagePriceObject`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *MessageApiSchema) GetAmountOk() (*MessagePriceObject, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *MessageApiSchema) SetAmount(v MessagePriceObject)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *MessageApiSchema) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetSender

`func (o *MessageApiSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *MessageApiSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *MessageApiSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *MessageApiSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetCreatedAt

`func (o *MessageApiSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MessageApiSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MessageApiSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *MessageApiSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSentAt

`func (o *MessageApiSchema) GetSentAt() time.Time`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *MessageApiSchema) GetSentAtOk() (*time.Time, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *MessageApiSchema) SetSentAt(v time.Time)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *MessageApiSchema) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *MessageApiSchema) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *MessageApiSchema) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetDeliveredAt

`func (o *MessageApiSchema) GetDeliveredAt() time.Time`

GetDeliveredAt returns the DeliveredAt field if non-nil, zero value otherwise.

### GetDeliveredAtOk

`func (o *MessageApiSchema) GetDeliveredAtOk() (*time.Time, bool)`

GetDeliveredAtOk returns a tuple with the DeliveredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredAt

`func (o *MessageApiSchema) SetDeliveredAt(v time.Time)`

SetDeliveredAt sets DeliveredAt field to given value.

### HasDeliveredAt

`func (o *MessageApiSchema) HasDeliveredAt() bool`

HasDeliveredAt returns a boolean if a field has been set.

### SetDeliveredAtNil

`func (o *MessageApiSchema) SetDeliveredAtNil(b bool)`

 SetDeliveredAtNil sets the value for DeliveredAt to be an explicit nil

### UnsetDeliveredAt
`func (o *MessageApiSchema) UnsetDeliveredAt()`

UnsetDeliveredAt ensures that no value is present for DeliveredAt, not even an explicit nil
### GetCountry

`func (o *MessageApiSchema) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *MessageApiSchema) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *MessageApiSchema) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *MessageApiSchema) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetParts

`func (o *MessageApiSchema) GetParts() int32`

GetParts returns the Parts field if non-nil, zero value otherwise.

### GetPartsOk

`func (o *MessageApiSchema) GetPartsOk() (*int32, bool)`

GetPartsOk returns a tuple with the Parts field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParts

`func (o *MessageApiSchema) SetParts(v int32)`

SetParts sets Parts field to given value.

### HasParts

`func (o *MessageApiSchema) HasParts() bool`

HasParts returns a boolean if a field has been set.

### GetRcsOptions

`func (o *MessageApiSchema) GetRcsOptions() Options`

GetRcsOptions returns the RcsOptions field if non-nil, zero value otherwise.

### GetRcsOptionsOk

`func (o *MessageApiSchema) GetRcsOptionsOk() (*Options, bool)`

GetRcsOptionsOk returns a tuple with the RcsOptions field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRcsOptions

`func (o *MessageApiSchema) SetRcsOptions(v Options)`

SetRcsOptions sets RcsOptions field to given value.

### HasRcsOptions

`func (o *MessageApiSchema) HasRcsOptions() bool`

HasRcsOptions returns a boolean if a field has been set.

### GetAlternativeChannels

`func (o *MessageApiSchema) GetAlternativeChannels() MessageApiSchemaAlternativeChannels`

GetAlternativeChannels returns the AlternativeChannels field if non-nil, zero value otherwise.

### GetAlternativeChannelsOk

`func (o *MessageApiSchema) GetAlternativeChannelsOk() (*MessageApiSchemaAlternativeChannels, bool)`

GetAlternativeChannelsOk returns a tuple with the AlternativeChannels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannels

`func (o *MessageApiSchema) SetAlternativeChannels(v MessageApiSchemaAlternativeChannels)`

SetAlternativeChannels sets AlternativeChannels field to given value.

### HasAlternativeChannels

`func (o *MessageApiSchema) HasAlternativeChannels() bool`

HasAlternativeChannels returns a boolean if a field has been set.

### SetAlternativeChannelsNil

`func (o *MessageApiSchema) SetAlternativeChannelsNil(b bool)`

 SetAlternativeChannelsNil sets the value for AlternativeChannels to be an explicit nil

### UnsetAlternativeChannels
`func (o *MessageApiSchema) UnsetAlternativeChannels()`

UnsetAlternativeChannels ensures that no value is present for AlternativeChannels, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


