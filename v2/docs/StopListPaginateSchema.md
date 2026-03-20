# StopListPaginateSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | ID of the contact added to the stop list | [optional] 
**Phone** | Pointer to **int32** | Phone number without leading plus, just digits | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**SmsStoplist** | Pointer to **bool** | Whether the contact was added to the SMS stop list | [optional] 
**ViberStoplist** | Pointer to **bool** | Whether the contact was added to the Viber stop list | [optional] 
**RcsStoplist** | Pointer to **bool** | Whether the contact was added to the Rcs stop list | [optional] 

## Methods

### NewStopListPaginateSchema

`func NewStopListPaginateSchema() *StopListPaginateSchema`

NewStopListPaginateSchema instantiates a new StopListPaginateSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStopListPaginateSchemaWithDefaults

`func NewStopListPaginateSchemaWithDefaults() *StopListPaginateSchema`

NewStopListPaginateSchemaWithDefaults instantiates a new StopListPaginateSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StopListPaginateSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StopListPaginateSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StopListPaginateSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *StopListPaginateSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPhone

`func (o *StopListPaginateSchema) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *StopListPaginateSchema) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *StopListPaginateSchema) SetPhone(v int32)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *StopListPaginateSchema) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetCreatedAt

`func (o *StopListPaginateSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StopListPaginateSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StopListPaginateSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *StopListPaginateSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSmsStoplist

`func (o *StopListPaginateSchema) GetSmsStoplist() bool`

GetSmsStoplist returns the SmsStoplist field if non-nil, zero value otherwise.

### GetSmsStoplistOk

`func (o *StopListPaginateSchema) GetSmsStoplistOk() (*bool, bool)`

GetSmsStoplistOk returns a tuple with the SmsStoplist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmsStoplist

`func (o *StopListPaginateSchema) SetSmsStoplist(v bool)`

SetSmsStoplist sets SmsStoplist field to given value.

### HasSmsStoplist

`func (o *StopListPaginateSchema) HasSmsStoplist() bool`

HasSmsStoplist returns a boolean if a field has been set.

### GetViberStoplist

`func (o *StopListPaginateSchema) GetViberStoplist() bool`

GetViberStoplist returns the ViberStoplist field if non-nil, zero value otherwise.

### GetViberStoplistOk

`func (o *StopListPaginateSchema) GetViberStoplistOk() (*bool, bool)`

GetViberStoplistOk returns a tuple with the ViberStoplist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViberStoplist

`func (o *StopListPaginateSchema) SetViberStoplist(v bool)`

SetViberStoplist sets ViberStoplist field to given value.

### HasViberStoplist

`func (o *StopListPaginateSchema) HasViberStoplist() bool`

HasViberStoplist returns a boolean if a field has been set.

### GetRcsStoplist

`func (o *StopListPaginateSchema) GetRcsStoplist() bool`

GetRcsStoplist returns the RcsStoplist field if non-nil, zero value otherwise.

### GetRcsStoplistOk

`func (o *StopListPaginateSchema) GetRcsStoplistOk() (*bool, bool)`

GetRcsStoplistOk returns a tuple with the RcsStoplist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRcsStoplist

`func (o *StopListPaginateSchema) SetRcsStoplist(v bool)`

SetRcsStoplist sets RcsStoplist field to given value.

### HasRcsStoplist

`func (o *StopListPaginateSchema) HasRcsStoplist() bool`

HasRcsStoplist returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


