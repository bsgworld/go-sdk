# StoreContact

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phone** | **int32** | Contact’s phone number | 
**Groups** | Pointer to [**[]ContactGroupSchema**](ContactGroupSchema.md) | contains embedded data of the list where the contact is added | [optional] 
**Fields** | Pointer to [**[]ContactFieldValuePair**](ContactFieldValuePair.md) | Array of custom fields values | [optional] 

## Methods

### NewStoreContact

`func NewStoreContact(phone int32, ) *StoreContact`

NewStoreContact instantiates a new StoreContact object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoreContactWithDefaults

`func NewStoreContactWithDefaults() *StoreContact`

NewStoreContactWithDefaults instantiates a new StoreContact object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhone

`func (o *StoreContact) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *StoreContact) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *StoreContact) SetPhone(v int32)`

SetPhone sets Phone field to given value.


### GetGroups

`func (o *StoreContact) GetGroups() []ContactGroupSchema`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *StoreContact) GetGroupsOk() (*[]ContactGroupSchema, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *StoreContact) SetGroups(v []ContactGroupSchema)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *StoreContact) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetFields

`func (o *StoreContact) GetFields() []ContactFieldValuePair`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *StoreContact) GetFieldsOk() (*[]ContactFieldValuePair, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *StoreContact) SetFields(v []ContactFieldValuePair)`

SetFields sets Fields field to given value.

### HasFields

`func (o *StoreContact) HasFields() bool`

HasFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


