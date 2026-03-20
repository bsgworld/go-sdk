# StoplistRemoveRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ids** | **[]int32** | An array of contact IDs to remove from stop list | 
**Types** | **[]string** | Specify the stop list type from which you want to remove contacts | 

## Methods

### NewStoplistRemoveRequest

`func NewStoplistRemoveRequest(ids []int32, types []string, ) *StoplistRemoveRequest`

NewStoplistRemoveRequest instantiates a new StoplistRemoveRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoplistRemoveRequestWithDefaults

`func NewStoplistRemoveRequestWithDefaults() *StoplistRemoveRequest`

NewStoplistRemoveRequestWithDefaults instantiates a new StoplistRemoveRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetIds

`func (o *StoplistRemoveRequest) GetIds() []int32`

GetIds returns the Ids field if non-nil, zero value otherwise.

### GetIdsOk

`func (o *StoplistRemoveRequest) GetIdsOk() (*[]int32, bool)`

GetIdsOk returns a tuple with the Ids field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIds

`func (o *StoplistRemoveRequest) SetIds(v []int32)`

SetIds sets Ids field to given value.


### GetTypes

`func (o *StoplistRemoveRequest) GetTypes() []string`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *StoplistRemoveRequest) GetTypesOk() (*[]string, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *StoplistRemoveRequest) SetTypes(v []string)`

SetTypes sets Types field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


