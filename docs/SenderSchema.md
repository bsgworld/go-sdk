# SenderSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **NullableInt32** |  | [optional] 
**Status** | Pointer to **string** |  | [optional] 
**Country** | Pointer to **NullableString** | Country code according to ISO 3166-1 alpha-2 standard | [optional] 
**Sender** | Pointer to **string** | Sender name.   Up to 11 Latin letters or digits, up to 15 – only digits. To setup senders visit the [account](https://app.bsg.world/sms/senders) or use [sender api](#tag/Senders) | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**IsDefault** | Pointer to **bool** |  | [optional] 

## Methods

### NewSenderSchema

`func NewSenderSchema() *SenderSchema`

NewSenderSchema instantiates a new SenderSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSenderSchemaWithDefaults

`func NewSenderSchemaWithDefaults() *SenderSchema`

NewSenderSchemaWithDefaults instantiates a new SenderSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *SenderSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *SenderSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *SenderSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *SenderSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### SetIdNil

`func (o *SenderSchema) SetIdNil(b bool)`

 SetIdNil sets the value for Id to be an explicit nil

### UnsetId
`func (o *SenderSchema) UnsetId()`

UnsetId ensures that no value is present for Id, not even an explicit nil
### GetStatus

`func (o *SenderSchema) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *SenderSchema) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *SenderSchema) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *SenderSchema) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetCountry

`func (o *SenderSchema) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *SenderSchema) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *SenderSchema) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *SenderSchema) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### SetCountryNil

`func (o *SenderSchema) SetCountryNil(b bool)`

 SetCountryNil sets the value for Country to be an explicit nil

### UnsetCountry
`func (o *SenderSchema) UnsetCountry()`

UnsetCountry ensures that no value is present for Country, not even an explicit nil
### GetSender

`func (o *SenderSchema) GetSender() string`

GetSender returns the Sender field if non-nil, zero value otherwise.

### GetSenderOk

`func (o *SenderSchema) GetSenderOk() (*string, bool)`

GetSenderOk returns a tuple with the Sender field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSender

`func (o *SenderSchema) SetSender(v string)`

SetSender sets Sender field to given value.

### HasSender

`func (o *SenderSchema) HasSender() bool`

HasSender returns a boolean if a field has been set.

### GetCreatedAt

`func (o *SenderSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *SenderSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *SenderSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *SenderSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetIsDefault

`func (o *SenderSchema) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *SenderSchema) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *SenderSchema) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *SenderSchema) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


