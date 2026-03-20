# MessageInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Message ID – a unique identifier automatically generated on the Platform when the message is created | [optional] 
**ReferenceId** | Pointer to **string** | external unique ID. String up to 32 characters containing only alpha numeric characters.  **Please note:** messages with duplicate reference_id will be rejected | [optional] 
**Source** | Pointer to [**MessageSource**](MessageSource.md) |  | [optional] 
**Type** | Pointer to [**MessageType**](MessageType.md) |  | [optional] 
**Phone** | Pointer to **int32** | Phone number without leading plus, just digits | [optional] 
**Status** | Pointer to [**MessageStatus**](MessageStatus.md) |  | [optional] 
**Validity** | Pointer to **int32** | validity time in hours. The default is 72 hours. Integer from 1 to 72 | [optional] [default to 72]
**Amount** | Pointer to [**MessagePriceObject**](MessagePriceObject.md) |  | [optional] 
**Sender** | Pointer to **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**SentAt** | Pointer to **NullableTime** | Date and time of sending the message | [optional] 
**DeliveredAt** | Pointer to **NullableTime** | Date and time of receipt of the delivery report response | [optional] 

## Methods

### NewMessageInfo

`func NewMessageInfo() *MessageInfo`

NewMessageInfo instantiates a new MessageInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessageInfoWithDefaults

`func NewMessageInfoWithDefaults() *MessageInfo`

NewMessageInfoWithDefaults instantiates a new MessageInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *MessageInfo) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *MessageInfo) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *MessageInfo) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *MessageInfo) HasId() bool`

HasId returns a boolean if a field has been set.

### GetReferenceId

`func (o *MessageInfo) GetReferenceId() string`

GetReferenceId returns the ReferenceId field if non-nil, zero value otherwise.

### GetReferenceIdOk

`func (o *MessageInfo) GetReferenceIdOk() (*string, bool)`

GetReferenceIdOk returns a tuple with the ReferenceId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReferenceId

`func (o *MessageInfo) SetReferenceId(v string)`

SetReferenceId sets ReferenceId field to given value.

### HasReferenceId

`func (o *MessageInfo) HasReferenceId() bool`

HasReferenceId returns a boolean if a field has been set.

### GetSource

`func (o *MessageInfo) GetSource() MessageSource`

GetSource returns the Source field if non-nil, zero value otherwise.

### GetSourceOk

`func (o *MessageInfo) GetSourceOk() (*MessageSource, bool)`

GetSourceOk returns a tuple with the Source field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSource

`func (o *MessageInfo) SetSource(v MessageSource)`

SetSource sets Source field to given value.

### HasSource

`func (o *MessageInfo) HasSource() bool`

HasSource returns a boolean if a field has been set.

### GetType

`func (o *MessageInfo) GetType() MessageType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MessageInfo) GetTypeOk() (*MessageType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MessageInfo) SetType(v MessageType)`

SetType sets Type field to given value.

### HasType

`func (o *MessageInfo) HasType() bool`

HasType returns a boolean if a field has been set.

### GetPhone

`func (o *MessageInfo) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *MessageInfo) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *MessageInfo) SetPhone(v int32)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *MessageInfo) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetStatus

`func (o *MessageInfo) GetStatus() MessageStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MessageInfo) GetStatusOk() (*MessageStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MessageInfo) SetStatus(v MessageStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *MessageInfo) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetValidity

`func (o *MessageInfo) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *MessageInfo) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *MessageInfo) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *MessageInfo) HasValidity() bool`

HasValidity returns a boolean if a field has been set.

### GetAmount

`func (o *MessageInfo) GetAmount() MessagePriceObject`

GetAmount returns the Amount field if non-nil, zero value otherwise.

### GetAmountOk

`func (o *MessageInfo) GetAmountOk() (*MessagePriceObject, bool)`

GetAmountOk returns a tuple with the Amount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAmount

`func (o *MessageInfo) SetAmount(v MessagePriceObject)`

SetAmount sets Amount field to given value.

### HasAmount

`func (o *MessageInfo) HasAmount() bool`

HasAmount returns a boolean if a field has been set.

### GetSender

`func (o *MessageInfo) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *MessageInfo) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *MessageInfo) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *MessageInfo) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetCreatedAt

`func (o *MessageInfo) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *MessageInfo) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *MessageInfo) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *MessageInfo) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSentAt

`func (o *MessageInfo) GetSentAt() time.Time`

GetSentAt returns the SentAt field if non-nil, zero value otherwise.

### GetSentAtOk

`func (o *MessageInfo) GetSentAtOk() (*time.Time, bool)`

GetSentAtOk returns a tuple with the SentAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSentAt

`func (o *MessageInfo) SetSentAt(v time.Time)`

SetSentAt sets SentAt field to given value.

### HasSentAt

`func (o *MessageInfo) HasSentAt() bool`

HasSentAt returns a boolean if a field has been set.

### SetSentAtNil

`func (o *MessageInfo) SetSentAtNil(b bool)`

 SetSentAtNil sets the value for SentAt to be an explicit nil

### UnsetSentAt
`func (o *MessageInfo) UnsetSentAt()`

UnsetSentAt ensures that no value is present for SentAt, not even an explicit nil
### GetDeliveredAt

`func (o *MessageInfo) GetDeliveredAt() time.Time`

GetDeliveredAt returns the DeliveredAt field if non-nil, zero value otherwise.

### GetDeliveredAtOk

`func (o *MessageInfo) GetDeliveredAtOk() (*time.Time, bool)`

GetDeliveredAtOk returns a tuple with the DeliveredAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDeliveredAt

`func (o *MessageInfo) SetDeliveredAt(v time.Time)`

SetDeliveredAt sets DeliveredAt field to given value.

### HasDeliveredAt

`func (o *MessageInfo) HasDeliveredAt() bool`

HasDeliveredAt returns a boolean if a field has been set.

### SetDeliveredAtNil

`func (o *MessageInfo) SetDeliveredAtNil(b bool)`

 SetDeliveredAtNil sets the value for DeliveredAt to be an explicit nil

### UnsetDeliveredAt
`func (o *MessageInfo) UnsetDeliveredAt()`

UnsetDeliveredAt ensures that no value is present for DeliveredAt, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


