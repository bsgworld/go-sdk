# DetailCampaignSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | campaign unique identifier | [optional] 
**Name** | Pointer to **string** | campaign auto generated name | [optional] 
**Sender** | Pointer to **string** | Sender’s name: from 3 to 11 characters for the sender’s alphanumeric name (Latin letters, symbols, numbers, spaces); 3 to 15 characters for the sender’s numeric name. To setup senders visit the [account](https://app.bsg.world/sms/senders) | [optional] 
**Status** | Pointer to [**CampaignStatus**](CampaignStatus.md) |  | [optional] 
**Type** | Pointer to [**MessageType**](MessageType.md) |  | [optional] 
**StartedAt** | Pointer to **time.Time** | Start sending the messages at | [optional] 
**ActualStartAt** | Pointer to **NullableTime** | Real time when sending the messages starts | [optional] 
**FinishedAt** | Pointer to **NullableTime** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**Statistics** | Pointer to [**StatisticsData**](StatisticsData.md) |  | [optional] 
**AlternativeChannels** | Pointer to [**NullableDetailCampaignSchemaAlternativeChannels**](DetailCampaignSchemaAlternativeChannels.md) |  | [optional] 
**TotalMessages** | Pointer to **int32** | Total count of messages sent in campaign | [optional] 
**TotalPhones** | Pointer to **int32** | Total count if phone numbers in campaign | [optional] 
**TotalPrice** | Pointer to **float32** | Total price of all the messages sent in campaign | [optional] 
**Currency** | Pointer to **string** | The currency code of the account. Specified according to the ISO-4217 standard | [optional] 

## Methods

### NewDetailCampaignSchema

`func NewDetailCampaignSchema() *DetailCampaignSchema`

NewDetailCampaignSchema instantiates a new DetailCampaignSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewDetailCampaignSchemaWithDefaults

`func NewDetailCampaignSchemaWithDefaults() *DetailCampaignSchema`

NewDetailCampaignSchemaWithDefaults instantiates a new DetailCampaignSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *DetailCampaignSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *DetailCampaignSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *DetailCampaignSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *DetailCampaignSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *DetailCampaignSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *DetailCampaignSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *DetailCampaignSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *DetailCampaignSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetSender

`func (o *DetailCampaignSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *DetailCampaignSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *DetailCampaignSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *DetailCampaignSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetStatus

`func (o *DetailCampaignSchema) GetStatus() CampaignStatus`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *DetailCampaignSchema) GetStatusOk() (*CampaignStatus, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *DetailCampaignSchema) SetStatus(v CampaignStatus)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *DetailCampaignSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetType

`func (o *DetailCampaignSchema) GetType() MessageType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *DetailCampaignSchema) GetTypeOk() (*MessageType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *DetailCampaignSchema) SetType(v MessageType)`

SetType sets Type field to given value.

### HasType

`func (o *DetailCampaignSchema) HasType() bool`

HasType returns a boolean if a field has been set.

### GetStartedAt

`func (o *DetailCampaignSchema) GetStartedAt() time.Time`

GetStartedAt returns the StartedAt field if non-nil, zero value otherwise.

### GetStartedAtOk

`func (o *DetailCampaignSchema) GetStartedAtOk() (*time.Time, bool)`

GetStartedAtOk returns a tuple with the StartedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStartedAt

`func (o *DetailCampaignSchema) SetStartedAt(v time.Time)`

SetStartedAt sets StartedAt field to given value.

### HasStartedAt

`func (o *DetailCampaignSchema) HasStartedAt() bool`

HasStartedAt returns a boolean if a field has been set.

### GetActualStartAt

`func (o *DetailCampaignSchema) GetActualStartAt() time.Time`

GetActualStartAt returns the ActualStartAt field if non-nil, zero value otherwise.

### GetActualStartAtOk

`func (o *DetailCampaignSchema) GetActualStartAtOk() (*time.Time, bool)`

GetActualStartAtOk returns a tuple with the ActualStartAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetActualStartAt

`func (o *DetailCampaignSchema) SetActualStartAt(v time.Time)`

SetActualStartAt sets ActualStartAt field to given value.

### HasActualStartAt

`func (o *DetailCampaignSchema) HasActualStartAt() bool`

HasActualStartAt returns a boolean if a field has been set.

### SetActualStartAtNil

`func (o *DetailCampaignSchema) SetActualStartAtNil(b bool)`

 SetActualStartAtNil sets the value for ActualStartAt to be an explicit nil

### UnsetActualStartAt
`func (o *DetailCampaignSchema) UnsetActualStartAt()`

UnsetActualStartAt ensures that no value is present for ActualStartAt, not even an explicit nil
### GetFinishedAt

`func (o *DetailCampaignSchema) GetFinishedAt() time.Time`

GetFinishedAt returns the FinishedAt field if non-nil, zero value otherwise.

### GetFinishedAtOk

`func (o *DetailCampaignSchema) GetFinishedAtOk() (*time.Time, bool)`

GetFinishedAtOk returns a tuple with the FinishedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFinishedAt

`func (o *DetailCampaignSchema) SetFinishedAt(v time.Time)`

SetFinishedAt sets FinishedAt field to given value.

### HasFinishedAt

`func (o *DetailCampaignSchema) HasFinishedAt() bool`

HasFinishedAt returns a boolean if a field has been set.

### SetFinishedAtNil

`func (o *DetailCampaignSchema) SetFinishedAtNil(b bool)`

 SetFinishedAtNil sets the value for FinishedAt to be an explicit nil

### UnsetFinishedAt
`func (o *DetailCampaignSchema) UnsetFinishedAt()`

UnsetFinishedAt ensures that no value is present for FinishedAt, not even an explicit nil
### GetCreatedAt

`func (o *DetailCampaignSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *DetailCampaignSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *DetailCampaignSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *DetailCampaignSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetStatistics

`func (o *DetailCampaignSchema) GetStatistics() StatisticsData`

GetStatistics returns the Statistics field if non-nil, zero value otherwise.

### GetStatisticsOk

`func (o *DetailCampaignSchema) GetStatisticsOk() (*StatisticsData, bool)`

GetStatisticsOk returns a tuple with the Statistics field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatistics

`func (o *DetailCampaignSchema) SetStatistics(v StatisticsData)`

SetStatistics sets Statistics field to given value.

### HasStatistics

`func (o *DetailCampaignSchema) HasStatistics() bool`

HasStatistics returns a boolean if a field has been set.

### GetAlternativeChannels

`func (o *DetailCampaignSchema) GetAlternativeChannels() DetailCampaignSchemaAlternativeChannels`

GetAlternativeChannels returns the AlternativeChannels field if non-nil, zero value otherwise.

### GetAlternativeChannelsOk

`func (o *DetailCampaignSchema) GetAlternativeChannelsOk() (*DetailCampaignSchemaAlternativeChannels, bool)`

GetAlternativeChannelsOk returns a tuple with the AlternativeChannels field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAlternativeChannels

`func (o *DetailCampaignSchema) SetAlternativeChannels(v DetailCampaignSchemaAlternativeChannels)`

SetAlternativeChannels sets AlternativeChannels field to given value.

### HasAlternativeChannels

`func (o *DetailCampaignSchema) HasAlternativeChannels() bool`

HasAlternativeChannels returns a boolean if a field has been set.

### SetAlternativeChannelsNil

`func (o *DetailCampaignSchema) SetAlternativeChannelsNil(b bool)`

 SetAlternativeChannelsNil sets the value for AlternativeChannels to be an explicit nil

### UnsetAlternativeChannels
`func (o *DetailCampaignSchema) UnsetAlternativeChannels()`

UnsetAlternativeChannels ensures that no value is present for AlternativeChannels, not even an explicit nil
### GetTotalMessages

`func (o *DetailCampaignSchema) GetTotalMessages() int32`

GetTotalMessages returns the TotalMessages field if non-nil, zero value otherwise.

### GetTotalMessagesOk

`func (o *DetailCampaignSchema) GetTotalMessagesOk() (*int32, bool)`

GetTotalMessagesOk returns a tuple with the TotalMessages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalMessages

`func (o *DetailCampaignSchema) SetTotalMessages(v int32)`

SetTotalMessages sets TotalMessages field to given value.

### HasTotalMessages

`func (o *DetailCampaignSchema) HasTotalMessages() bool`

HasTotalMessages returns a boolean if a field has been set.

### GetTotalPhones

`func (o *DetailCampaignSchema) GetTotalPhones() int32`

GetTotalPhones returns the TotalPhones field if non-nil, zero value otherwise.

### GetTotalPhonesOk

`func (o *DetailCampaignSchema) GetTotalPhonesOk() (*int32, bool)`

GetTotalPhonesOk returns a tuple with the TotalPhones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPhones

`func (o *DetailCampaignSchema) SetTotalPhones(v int32)`

SetTotalPhones sets TotalPhones field to given value.

### HasTotalPhones

`func (o *DetailCampaignSchema) HasTotalPhones() bool`

HasTotalPhones returns a boolean if a field has been set.

### GetTotalPrice

`func (o *DetailCampaignSchema) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *DetailCampaignSchema) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *DetailCampaignSchema) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.

### HasTotalPrice

`func (o *DetailCampaignSchema) HasTotalPrice() bool`

HasTotalPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *DetailCampaignSchema) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *DetailCampaignSchema) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *DetailCampaignSchema) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *DetailCampaignSchema) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


