# StoplistAddRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Phones** | **[]int32** | Array of the phone numbers | 
**Types** | **[]string** | Specify the stop list type | 

## Methods

### NewStoplistAddRequest

`func NewStoplistAddRequest(phones []int32, types []string, ) *StoplistAddRequest`

NewStoplistAddRequest instantiates a new StoplistAddRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoplistAddRequestWithDefaults

`func NewStoplistAddRequestWithDefaults() *StoplistAddRequest`

NewStoplistAddRequestWithDefaults instantiates a new StoplistAddRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPhones

`func (o *StoplistAddRequest) GetPhones() []int32`

GetPhones returns the Phones field if non-nil, zero value otherwise.

### GetPhonesOk

`func (o *StoplistAddRequest) GetPhonesOk() (*[]int32, bool)`

GetPhonesOk returns a tuple with the Phones field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPhones

`func (o *StoplistAddRequest) SetPhones(v []int32)`

SetPhones sets Phones field to given value.


### GetTypes

`func (o *StoplistAddRequest) GetTypes() []string`

GetTypes returns the Types field if non-nil, zero value otherwise.

### GetTypesOk

`func (o *StoplistAddRequest) GetTypesOk() (*[]string, bool)`

GetTypesOk returns a tuple with the Types field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTypes

`func (o *StoplistAddRequest) SetTypes(v []string)`

SetTypes sets Types field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


