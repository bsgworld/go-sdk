# CampaignSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | campaign unique identifier | [optional] 
**Name** | Pointer to **string** | campaign auto generated name | [optional] 
**Sender** | Pointer to **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | [optional] 
**Status** | Pointer to [**CampaignStatus**](CampaignStatus.md) |  | [optional] 
**MessageType** | Pointer to [**MessageType**](MessageType.md) |  | [optional] 
**StartAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**RealStartAt** | Pointer to **NullableTime** | Real time when sending the messages starts | [optional] 
**FinishedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**Statistics** | Pointer to [**StatisticsShort**](StatisticsShort.md) |  | [optional] 
**CalculatedPrice** | Pointer to **NullableFloat32** | estimate campaign cost  **Please note:** price defined only as the response to create campaign or calculate price requests | [optional] 
**Currency** | Pointer to **string** | The currency code of the account. Specified according to the ISO-4217 standard | [optional] 

## Methods

### NewCampaignSchema

`func NewCampaignSchema() *CampaignSchema`

NewCampaignSchema instantiates a new CampaignSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCampaignSchemaWithDefaults

`func NewCampaignSchemaWithDefaults() *CampaignSchema`

NewCampaignSchemaWithDefaults instantiates a new CampaignSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CampaignSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CampaignSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CampaignSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *CampaignSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *CampaignSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *CampaignSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *CampaignSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *CampaignSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSender

`func (o *CampaignSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *CampaignSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *CampaignSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *CampaignSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetStatus

`func (o *CampaignSchema) GetStatus() CampaignStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *CampaignSchema) GetStatusOk() (*CampaignStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *CampaignSchema) SetStatus(v CampaignStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *CampaignSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetMessageType

`func (o *CampaignSchema) GetMessageType() MessageType`

GetMessageType returns the MessageType field if non-nil, zero value otherwise.

### GetMessageTypeOk

`func (o *CampaignSchema) GetMessageTypeOk() (*MessageType, bool)`

GetMessageTypeOk returns a tuple with the MessageType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessageType

`func (o *CampaignSchema) SetMessageType(v MessageType)`

SetMessageType sets MessageType field to given value.

### HasMessageType

`func (o *CampaignSchema) HasMessageType() bool`

HasMessageType returns a boolean if a field has been set.

### GetStartAt

`func (o *CampaignSchema) GetStartAt() time.Time`

GetStartAt returns the StartAt field if non-nil, zero value otherwise.

### GetStartAtOk

`func (o *CampaignSchema) GetStartAtOk() (*time.Time, bool)`

GetStartAtOk returns a tuple with the StartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartAt

`func (o *CampaignSchema) SetStartAt(v time.Time)`

SetStartAt sets StartAt field to given value.

### HasStartAt

`func (o *CampaignSchema) HasStartAt() bool`

HasStartAt returns a boolean if a field has been set.

### GetRealStartAt

`func (o *CampaignSchema) GetRealStartAt() time.Time`

GetRealStartAt returns the RealStartAt field if non-nil, zero value otherwise.

### GetRealStartAtOk

`func (o *CampaignSchema) GetRealStartAtOk() (*time.Time, bool)`

GetRealStartAtOk returns a tuple with the RealStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRealStartAt

`func (o *CampaignSchema) SetRealStartAt(v time.Time)`

SetRealStartAt sets RealStartAt field to given value.

### HasRealStartAt

`func (o *CampaignSchema) HasRealStartAt() bool`

HasRealStartAt returns a boolean if a field has been set.

### SetRealStartAtNil

`func (o *CampaignSchema) SetRealStartAtNil(b bool)`

 SetRealStartAtNil sets the value for RealStartAt to be an explicit nil

### UnsetRealStartAt
`func (o *CampaignSchema) UnsetRealStartAt()`

UnsetRealStartAt ensures that no value is present for RealStartAt, not even an explicit nil
### GetFinishedAt

`func (o *CampaignSchema) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *CampaignSchema) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *CampaignSchema) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *CampaignSchema) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *CampaignSchema) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *CampaignSchema) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetCreatedAt

`func (o *CampaignSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *CampaignSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *CampaignSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *CampaignSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetStatistics

`func (o *CampaignSchema) GetStatistics() StatisticsShort`

GetStatistics returns the Statistics field if non-nil, zero value otherwise.

### GetStatisticsOk

`func (o *CampaignSchema) GetStatisticsOk() (*StatisticsShort, bool)`

GetStatisticsOk returns a tuple with the Statistics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatistics

`func (o *CampaignSchema) SetStatistics(v StatisticsShort)`

SetStatistics sets Statistics field to given value.

### HasStatistics

`func (o *CampaignSchema) HasStatistics() bool`

HasStatistics returns a boolean if a field has been set.

### GetCalculatedPrice

`func (o *CampaignSchema) GetCalculatedPrice() float32`

GetCalculatedPrice returns the CalculatedPrice field if non-nil, zero value otherwise.

### GetCalculatedPriceOk

`func (o *CampaignSchema) GetCalculatedPriceOk() (*float32, bool)`

GetCalculatedPriceOk returns a tuple with the CalculatedPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCalculatedPrice

`func (o *CampaignSchema) SetCalculatedPrice(v float32)`

SetCalculatedPrice sets CalculatedPrice field to given value.

### HasCalculatedPrice

`func (o *CampaignSchema) HasCalculatedPrice() bool`

HasCalculatedPrice returns a boolean if a field has been set.

### SetCalculatedPriceNil

`func (o *CampaignSchema) SetCalculatedPriceNil(b bool)`

 SetCalculatedPriceNil sets the value for CalculatedPrice to be an explicit nil

### UnsetCalculatedPrice
`func (o *CampaignSchema) UnsetCalculatedPrice()`

UnsetCalculatedPrice ensures that no value is present for CalculatedPrice, not even an explicit nil
### GetCurrency

`func (o *CampaignSchema) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CampaignSchema) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CampaignSchema) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CampaignSchema) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


