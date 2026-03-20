# StoplistItems200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]StopListPaginateSchema**](StopListPaginateSchema.md) |  | [optional] 
**Total** | Pointer to **int32** | Total items count at all of the pages | [optional] 

## Methods

### NewStoplistItems200Response

`func NewStoplistItems200Response() *StoplistItems200Response`

NewStoplistItems200Response instantiates a new StoplistItems200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoplistItems200ResponseWithDefaults

`func NewStoplistItems200ResponseWithDefaults() *StoplistItems200Response`

NewStoplistItems200ResponseWithDefaults instantiates a new StoplistItems200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *StoplistItems200Response) GetData() []StopListPaginateSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StoplistItems200Response) GetDataOk() (*[]StopListPaginateSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StoplistItems200Response) SetData(v []StopListPaginateSchema)`

SetData sets Data field to given value.

### HasData

`func (o *StoplistItems200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *StoplistItems200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *StoplistItems200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *StoplistItems200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *StoplistItems200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


