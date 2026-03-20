# ContactGroupSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | ID of the contact list. generated automatically when creating a [contact list](#operation/contact_list_create) | [optional] 
**Name** | Pointer to **string** | Name of the contact list | [optional] 
**Description** | Pointer to **NullableString** | Description of the contact list | [optional] 
**Default** | Pointer to **NullableBool** | Specifies whether the contact list is a default one | [optional] [default to false]
**CreatedAt** | Pointer to **time.Time** | Date when the item was created in the system ― set by the system automatically. Display format ― Y-m-d H:i:s | [optional] 
**Items** | Pointer to **int32** | Total number of contacts in this list | [optional] 
**StopListCount** | Pointer to **int32** | The number of contacts from the list that are in the stop list of SMS and Viber | [optional] 

## Methods

### NewContactGroupSchema

`func NewContactGroupSchema() *ContactGroupSchema`

NewContactGroupSchema instantiates a new ContactGroupSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactGroupSchemaWithDefaults

`func NewContactGroupSchemaWithDefaults() *ContactGroupSchema`

NewContactGroupSchemaWithDefaults instantiates a new ContactGroupSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactGroupSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactGroupSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactGroupSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ContactGroupSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ContactGroupSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContactGroupSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContactGroupSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ContactGroupSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *ContactGroupSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactGroupSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactGroupSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactGroupSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### SetDescriptionNil

`func (o *ContactGroupSchema) SetDescriptionNil(b bool)`

 SetDescriptionNil sets the value for Description to be an explicit nil

### UnsetDescription
`func (o *ContactGroupSchema) UnsetDescription()`

UnsetDescription ensures that no value is present for Description, not even an explicit nil
### GetDefault

`func (o *ContactGroupSchema) GetDefault() bool`

GetDefault returns the Default field if non-nil, zero value otherwise.

### GetDefaultOk

`func (o *ContactGroupSchema) GetDefaultOk() (*bool, bool)`

GetDefaultOk returns a tuple with the Default field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDefault

`func (o *ContactGroupSchema) SetDefault(v bool)`

SetDefault sets Default field to given value.

### HasDefault

`func (o *ContactGroupSchema) HasDefault() bool`

HasDefault returns a boolean if a field has been set.

### SetDefaultNil

`func (o *ContactGroupSchema) SetDefaultNil(b bool)`

 SetDefaultNil sets the value for Default to be an explicit nil

### UnsetDefault
`func (o *ContactGroupSchema) UnsetDefault()`

UnsetDefault ensures that no value is present for Default, not even an explicit nil
### GetCreatedAt

`func (o *ContactGroupSchema) GetCreatedAt() time.Time`

GetCreatedAt returns the CreatedAt field if non-nil, zero value otherwise.

### GetCreatedAtOk

`func (o *ContactGroupSchema) GetCreatedAtOk() (*time.Time, bool)`

GetCreatedAtOk returns a tuple with the CreatedAt field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedAt

`func (o *ContactGroupSchema) SetCreatedAt(v time.Time)`

SetCreatedAt sets CreatedAt field to given value.

### HasCreatedAt

`func (o *ContactGroupSchema) HasCreatedAt() bool`

HasCreatedAt returns a boolean if a field has been set.

### GetItems

`func (o *ContactGroupSchema) GetItems() int32`

GetItems returns the Items field if non-nil, zero value otherwise.

### GetItemsOk

`func (o *ContactGroupSchema) GetItemsOk() (*int32, bool)`

GetItemsOk returns a tuple with the Items field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetItems

`func (o *ContactGroupSchema) SetItems(v int32)`

SetItems sets Items field to given value.

### HasItems

`func (o *ContactGroupSchema) HasItems() bool`

HasItems returns a boolean if a field has been set.

### GetStopListCount

`func (o *ContactGroupSchema) GetStopListCount() int32`

GetStopListCount returns the StopListCount field if non-nil, zero value otherwise.

### GetStopListCountOk

`func (o *ContactGroupSchema) GetStopListCountOk() (*int32, bool)`

GetStopListCountOk returns a tuple with the StopListCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStopListCount

`func (o *ContactGroupSchema) SetStopListCount(v int32)`

SetStopListCount sets StopListCount field to given value.

### HasStopListCount

`func (o *ContactGroupSchema) HasStopListCount() bool`

HasStopListCount returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


