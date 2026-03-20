# ContactGroupSearchSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | ID of the contact list. generated automatically when creating a [contact list](#operation/contact_list_create) | [optional] 
**Name** | Pointer to **string** | Name of the contact list | [optional] 
**Description** | Pointer to **NullableString** | Description of the contact list | [optional] 
**IsDefault** | Pointer to **NullableBool** | Specifies whether the contact list is a default one | [optional] [default to false]
**Items** | Pointer to **int32** | Total number of contacts in this list | [optional] 
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 

## Methods

### NewContactGroupSearchSchema

`func NewContactGroupSearchSchema() *ContactGroupSearchSchema`

NewContactGroupSearchSchema instantiates a new ContactGroupSearchSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactGroupSearchSchemaWithDefaults

`func NewContactGroupSearchSchemaWithDefaults() *ContactGroupSearchSchema`

NewContactGroupSearchSchemaWithDefaults instantiates a new ContactGroupSearchSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactGroupSearchSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactGroupSearchSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactGroupSearchSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ContactGroupSearchSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ContactGroupSearchSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContactGroupSearchSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContactGroupSearchSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ContactGroupSearchSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *ContactGroupSearchSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactGroupSearchSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactGroupSearchSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactGroupSearchSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ContactGroupSearchSchema) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ContactGroupSearchSchema) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetIsDefault

`func (o *ContactGroupSearchSchema) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *ContactGroupSearchSchema) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *ContactGroupSearchSchema) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *ContactGroupSearchSchema) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.

### SetIsDefaultNil

`func (o *ContactGroupSearchSchema) SetIsDefaultNil(b bool)`

 SetIsDefaultNil sets the value for IsDefault to be an explicit nil

### UnsetIsDefault
`func (o *ContactGroupSearchSchema) UnsetIsDefault()`

UnsetIsDefault ensures that no value is present for IsDefault, not even an explicit nil
### GetItems

`func (o *ContactGroupSearchSchema) GetItems() int32`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ContactGroupSearchSchema) GetItemsOk() (*int32, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ContactGroupSearchSchema) SetItems(v int32)`

SetItems sets Items field to given value.

### HasItems

`func (o *ContactGroupSearchSchema) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetCreatedAt

`func (o *ContactGroupSearchSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ContactGroupSearchSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ContactGroupSearchSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ContactGroupSearchSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


