# ContactFieldSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **int32** | Custom field ID | [optional] 
**Name** | Pointer to **string** | The name of the custom field for the contacts | [optional] 
**Type** | Pointer to [**ContactFieldType**](ContactFieldType.md) |  | [optional] 
**Description** | Pointer to **string** | Description of the custom contact field | [optional] 
**IsVisible** | Pointer to **bool** | Whether the field is displayed: true or false value | [optional] [default to true]

## Methods

### NewContactFieldSchema

`func NewContactFieldSchema() *ContactFieldSchema`

NewContactFieldSchema instantiates a new ContactFieldSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactFieldSchemaWithDefaults

`func NewContactFieldSchemaWithDefaults() *ContactFieldSchema`

NewContactFieldSchemaWithDefaults instantiates a new ContactFieldSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *ContactFieldSchema) GetId() int32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ContactFieldSchema) GetIdOk() (*int32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ContactFieldSchema) SetId(v int32)`

SetId sets Id field to given value.

### HasId

`func (o *ContactFieldSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *ContactFieldSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContactFieldSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContactFieldSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ContactFieldSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetType

`func (o *ContactFieldSchema) GetType() ContactFieldType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactFieldSchema) GetTypeOk() (*ContactFieldType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactFieldSchema) SetType(v ContactFieldType)`

SetType sets Type field to given value.

### HasType

`func (o *ContactFieldSchema) HasType() bool`

HasType returns a boolean if a field has been set.

### GetDescription

`func (o *ContactFieldSchema) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactFieldSchema) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactFieldSchema) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactFieldSchema) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsVisible

`func (o *ContactFieldSchema) GetIsVisible() bool`

GetIsVisible returns the IsVisible field if non-nil, zero value otherwise.

### GetIsVisibleOk

`func (o *ContactFieldSchema) GetIsVisibleOk() (*bool, bool)`

GetIsVisibleOk returns a tuple with the IsVisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVisible

`func (o *ContactFieldSchema) SetIsVisible(v bool)`

SetIsVisible sets IsVisible field to given value.

### HasIsVisible

`func (o *ContactFieldSchema) HasIsVisible() bool`

HasIsVisible returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


