# ContactSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Contact ID in the platform personal account, which is generated automatically when a contact is added to the Contact Book | [optional] 
**Phone** | Pointer to **int32** | Contact’s phone number | [optional] 
**Fields** | Pointer to **[]map[string]string** | List of contact custom field values | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**Groups** | Pointer to [**[]ContactGroupSchema**](ContactGroupSchema.md) | contains embedded data of the list where the contact is added | [optional] 
**HlrStatus** | Pointer to **string** | Last hlr check status of contact phone number | [optional] 
**HlrLastCheck** | Pointer to **NullableTime** | Last hlr check time of contact phone number | [optional] 

## Methods

### NewContactSchema

`func NewContactSchema() *ContactSchema`

NewContactSchema instantiates a new ContactSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactSchemaWithDefaults

`func NewContactSchemaWithDefaults() *ContactSchema`

NewContactSchemaWithDefaults instantiates a new ContactSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ContactSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPhone

`func (o *ContactSchema) GetPhone() int32`

GetPhone returns the Phone field if non-nil, zero value otherwise.

### GetPhoneOk

`func (o *ContactSchema) GetPhoneOk() (*int32, bool)`

GetPhoneOk returns a tuple with the Phone field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhone

`func (o *ContactSchema) SetPhone(v int32)`

SetPhone sets Phone field to given value.

### HasPhone

`func (o *ContactSchema) HasPhone() bool`

HasPhone returns a boolean if a field has been set.

### GetFields

`func (o *ContactSchema) GetFields() []map[string]string`

GetFields returns the Fields field if non-nil, zero value otherwise.

### GetFieldsOk

`func (o *ContactSchema) GetFieldsOk() (*[]map[string]string, bool)`

GetFieldsOk returns a tuple with the Fields field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetFields

`func (o *ContactSchema) SetFields(v []map[string]string)`

SetFields sets Fields field to given value.

### HasFields

`func (o *ContactSchema) HasFields() bool`

HasFields returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ContactSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ContactSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ContactSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ContactSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetGroups

`func (o *ContactSchema) GetGroups() []ContactGroupSchema`

GetGroups returns the Groups field if non-nil, zero value otherwise.

### GetGroupsOk

`func (o *ContactSchema) GetGroupsOk() (*[]ContactGroupSchema, bool)`

GetGroupsOk returns a tuple with the Groups field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetGroups

`func (o *ContactSchema) SetGroups(v []ContactGroupSchema)`

SetGroups sets Groups field to given value.

### HasGroups

`func (o *ContactSchema) HasGroups() bool`

HasGroups returns a boolean if a field has been set.

### GetHlrStatus

`func (o *ContactSchema) GetHlrStatus() string`

GetHlrStatus returns the HlrStatus field if non-nil, zero value otherwise.

### GetHlrStatusOk

`func (o *ContactSchema) GetHlrStatusOk() (*string, bool)`

GetHlrStatusOk returns a tuple with the HlrStatus field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHlrStatus

`func (o *ContactSchema) SetHlrStatus(v string)`

SetHlrStatus sets HlrStatus field to given value.

### HasHlrStatus

`func (o *ContactSchema) HasHlrStatus() bool`

HasHlrStatus returns a boolean if a field has been set.

### GetHlrLastCheck

`func (o *ContactSchema) GetHlrLastCheck() time.Time`

GetHlrLastCheck returns the HlrLastCheck field if non-nil, zero value otherwise.

### GetHlrLastCheckOk

`func (o *ContactSchema) GetHlrLastCheckOk() (*time.Time, bool)`

GetHlrLastCheckOk returns a tuple with the HlrLastCheck field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetHlrLastCheck

`func (o *ContactSchema) SetHlrLastCheck(v time.Time)`

SetHlrLastCheck sets HlrLastCheck field to given value.

### HasHlrLastCheck

`func (o *ContactSchema) HasHlrLastCheck() bool`

HasHlrLastCheck returns a boolean if a field has been set.

### SetHlrLastCheckNil

`func (o *ContactSchema) SetHlrLastCheckNil(b bool)`

 SetHlrLastCheckNil sets the value for HlrLastCheck to be an explicit nil

### UnsetHlrLastCheck
`func (o *ContactSchema) UnsetHlrLastCheck()`

UnsetHlrLastCheck ensures that no value is present for HlrLastCheck, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


