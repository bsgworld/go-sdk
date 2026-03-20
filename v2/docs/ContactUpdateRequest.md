# ContactUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phone** | **int32** | Contact’s phone number | 
**Groups** | Pointer to [**[]ContactGroupSchema**](ContactGroupSchema.md) | contains embedded data of the list where the contact is added | [optional] 
**Fields** | Pointer to [**[]ContactFieldValuePair**](ContactFieldValuePair.md) | Array of custom fields values | [optional] 

## Methods

### NewContactUpdateRequest

`func NewContactUpdateRequest(phone int32, ) *ContactUpdateRequest`

NewContactUpdateRequest instantiates a new ContactUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactUpdateRequestWithDefaults

`func NewContactUpdateRequestWithDefaults() *ContactUpdateRequest`

NewContactUpdateRequestWithDefaults instantiates a new ContactUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhone

`func (o *ContactUpdateRequest) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactUpdateRequest) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactUpdateRequest) SetPhone(v int32)`

SetPhone sets Phone field to given value.


### GetGroups

`func (o *ContactUpdateRequest) GetGroups() []ContactGroupSchema`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *ContactUpdateRequest) GetGroupsOk() (*[]ContactGroupSchema, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *ContactUpdateRequest) SetGroups(v []ContactGroupSchema)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *ContactUpdateRequest) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetFields

`func (o *ContactUpdateRequest) GetFields() []ContactFieldValuePair`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *ContactUpdateRequest) GetFieldsOk() (*[]ContactFieldValuePair, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *ContactUpdateRequest) SetFields(v []ContactFieldValuePair)`

SetFields sets Fields field to given value.

### HasFields

`func (o *ContactUpdateRequest) HasFields() bool`

HasFields returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


