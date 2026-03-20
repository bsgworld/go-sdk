# StoplistSearch200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]StopListCollection**](StopListCollection.md) |  | [optional] 
**Meta** | Pointer to [**StoplistSearchMeta**](StoplistSearchMeta.md) |  | [optional] 

## Methods

### NewStoplistSearch200Response

`func NewStoplistSearch200Response() *StoplistSearch200Response`

NewStoplistSearch200Response instantiates a new StoplistSearch200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoplistSearch200ResponseWithDefaults

`func NewStoplistSearch200ResponseWithDefaults() *StoplistSearch200Response`

NewStoplistSearch200ResponseWithDefaults instantiates a new StoplistSearch200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *StoplistSearch200Response) GetData() []StopListCollection`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *StoplistSearch200Response) GetDataOk() (*[]StopListCollection, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *StoplistSearch200Response) SetData(v []StopListCollection)`

SetData sets Data field to given value.

### HasData

`func (o *StoplistSearch200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetMeta

`func (o *StoplistSearch200Response) GetMeta() StoplistSearchMeta`

GetMeta returns the Meta field if non-nil, zero value otherwise.

### GetMetaOk

`func (o *StoplistSearch200Response) GetMetaOk() (*StoplistSearchMeta, bool)`

GetMetaOk returns a tuple with the Meta field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMeta

`func (o *StoplistSearch200Response) SetMeta(v StoplistSearchMeta)`

SetMeta sets Meta field to given value.

### HasMeta

`func (o *StoplistSearch200Response) HasMeta() bool`

HasMeta returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


