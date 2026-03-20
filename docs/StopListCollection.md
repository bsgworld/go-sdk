# StopListCollection

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** |  | [optional] 
**Phone** | Pointer to **int32** |  | [optional] 
**CreatedAt** | Pointer to **time.Time** |  | [optional] 
**SmsStoplist** | Pointer to **bool** |  | [optional] [default to true]
**ViberStoplist** | Pointer to **bool** |  | [optional] [default to true]
**RcsStoplist** | Pointer to **bool** |  | [optional] [default to true]

## Methods

### NewStopListCollection

`func NewStopListCollection() *StopListCollection`

NewStopListCollection instantiates a new StopListCollection object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStopListCollectionWithDefaults

`func NewStopListCollectionWithDefaults() *StopListCollection`

NewStopListCollectionWithDefaults instantiates a new StopListCollection object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *StopListCollection) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *StopListCollection) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *StopListCollection) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *StopListCollection) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPhone

`func (o *StopListCollection) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *StopListCollection) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *StopListCollection) SetPhone(v int32)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *StopListCollection) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetCreatedAt

`func (o *StopListCollection) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *StopListCollection) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *StopListCollection) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *StopListCollection) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetSmsStoplist

`func (o *StopListCollection) GetSmsStoplist() bool`

GetSmsStoplist returns the SmsStoplist field if non-nil, zero value otherwise.

### GetSmsStoplistOk

`func (o *StopListCollection) GetSmsStoplistOk() (*bool, bool)`

GetSmsStoplistOk returns a tuple with the SmsStoplist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSmsStoplist

`func (o *StopListCollection) SetSmsStoplist(v bool)`

SetSmsStoplist sets SmsStoplist field to given value.

### HasSmsStoplist

`func (o *StopListCollection) HasSmsStoplist() bool`

HasSmsStoplist returns a boolean if a field has been set.

### GetViberStoplist

`func (o *StopListCollection) GetViberStoplist() bool`

GetViberStoplist returns the ViberStoplist field if non-nil, zero value otherwise.

### GetViberStoplistOk

`func (o *StopListCollection) GetViberStoplistOk() (*bool, bool)`

GetViberStoplistOk returns a tuple with the ViberStoplist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetViberStoplist

`func (o *StopListCollection) SetViberStoplist(v bool)`

SetViberStoplist sets ViberStoplist field to given value.

### HasViberStoplist

`func (o *StopListCollection) HasViberStoplist() bool`

HasViberStoplist returns a boolean if a field has been set.

### GetRcsStoplist

`func (o *StopListCollection) GetRcsStoplist() bool`

GetRcsStoplist returns the RcsStoplist field if non-nil, zero value otherwise.

### GetRcsStoplistOk

`func (o *StopListCollection) GetRcsStoplistOk() (*bool, bool)`

GetRcsStoplistOk returns a tuple with the RcsStoplist field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRcsStoplist

`func (o *StopListCollection) SetRcsStoplist(v bool)`

SetRcsStoplist sets RcsStoplist field to given value.

### HasRcsStoplist

`func (o *StopListCollection) HasRcsStoplist() bool`

HasRcsStoplist returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


