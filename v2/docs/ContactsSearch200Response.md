# ContactsSearch200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ContactSchema**](ContactSchema.md) | List of searched contacts | [optional] 
**Meta** | Pointer to [**ContactsSearchMeta**](ContactsSearchMeta.md) |  | [optional] 

## Methods

### NewContactsSearch200Response

`func NewContactsSearch200Response() *ContactsSearch200Response`

NewContactsSearch200Response instantiates a new ContactsSearch200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsSearch200ResponseWithDefaults

`func NewContactsSearch200ResponseWithDefaults() *ContactsSearch200Response`

NewContactsSearch200ResponseWithDefaults instantiates a new ContactsSearch200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ContactsSearch200Response) GetData() []ContactSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ContactsSearch200Response) GetDataOk() (*[]ContactSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ContactsSearch200Response) SetData(v []ContactSchema)`

SetData sets Data field to given value.

### HasData

`func (o *ContactsSearch200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMeta

`func (o *ContactsSearch200Response) GetMeta() ContactsSearchMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *ContactsSearch200Response) GetMetaOk() (*ContactsSearchMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *ContactsSearch200Response) SetMeta(v ContactsSearchMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *ContactsSearch200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


