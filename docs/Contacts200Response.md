# Contacts200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ContactSchema**](ContactSchema.md) | list of contacts | [optional] 
**Total** | Pointer to **int32** | Total items count at all of the pages | [optional] 

## Methods

### NewContacts200Response

`func NewContacts200Response() *Contacts200Response`

NewContacts200Response instantiates a new Contacts200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContacts200ResponseWithDefaults

`func NewContacts200ResponseWithDefaults() *Contacts200Response`

NewContacts200ResponseWithDefaults instantiates a new Contacts200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *Contacts200Response) GetData() []ContactSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *Contacts200Response) GetDataOk() (*[]ContactSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *Contacts200Response) SetData(v []ContactSchema)`

SetData sets Data field to given value.

### HasData

`func (o *Contacts200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *Contacts200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *Contacts200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *Contacts200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *Contacts200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


