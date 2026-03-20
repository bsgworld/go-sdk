# ContactLists200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]ContactGroupSchema**](ContactGroupSchema.md) |  | [optional] 
**Total** | Pointer to **int32** | Total items count at all of the pages | [optional] 

## Methods

### NewContactLists200Response

`func NewContactLists200Response() *ContactLists200Response`

NewContactLists200Response instantiates a new ContactLists200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactLists200ResponseWithDefaults

`func NewContactLists200ResponseWithDefaults() *ContactLists200Response`

NewContactLists200ResponseWithDefaults instantiates a new ContactLists200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *ContactLists200Response) GetData() []ContactGroupSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *ContactLists200Response) GetDataOk() (*[]ContactGroupSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *ContactLists200Response) SetData(v []ContactGroupSchema)`

SetData sets Data field to given value.

### HasData

`func (o *ContactLists200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *ContactLists200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *ContactLists200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *ContactLists200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *ContactLists200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


