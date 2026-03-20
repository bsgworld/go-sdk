# ContactFieldCollectionSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ContactFieldSchema**](ContactFieldSchema.md) | List of contact fields | [optional] 

## Methods

### NewContactFieldCollectionSchema

`func NewContactFieldCollectionSchema() *ContactFieldCollectionSchema`

NewContactFieldCollectionSchema instantiates a new ContactFieldCollectionSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactFieldCollectionSchemaWithDefaults

`func NewContactFieldCollectionSchemaWithDefaults() *ContactFieldCollectionSchema`

NewContactFieldCollectionSchemaWithDefaults instantiates a new ContactFieldCollectionSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ContactFieldCollectionSchema) GetData() []ContactFieldSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ContactFieldCollectionSchema) GetDataOk() (*[]ContactFieldSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ContactFieldCollectionSchema) SetData(v []ContactFieldSchema)`

SetData sets Data field to given value.

### HasData

`func (o *ContactFieldCollectionSchema) HasData() bool`

HasData returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


