# StoplistSearchCriteria

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | Pointer to [**StoplistSearchField**](StoplistSearchField.md) |  | [optional] 
**Operator** | Pointer to [**SearchOperator**](SearchOperator.md) |  | [optional] 
**Value** | Pointer to **string** | Value to to find using search[field] and search[operator] | [optional] 

## Methods

### NewStoplistSearchCriteria

`func NewStoplistSearchCriteria() *StoplistSearchCriteria`

NewStoplistSearchCriteria instantiates a new StoplistSearchCriteria object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewStoplistSearchCriteriaWithDefaults

`func NewStoplistSearchCriteriaWithDefaults() *StoplistSearchCriteria`

NewStoplistSearchCriteriaWithDefaults instantiates a new StoplistSearchCriteria object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *StoplistSearchCriteria) GetField() StoplistSearchField`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *StoplistSearchCriteria) GetFieldOk() (*StoplistSearchField, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *StoplistSearchCriteria) SetField(v StoplistSearchField)`

SetField sets Field field to given value.

### HasField

`func (o *StoplistSearchCriteria) HasField() bool`

HasField returns a boolean if a field has been set.

### GetOperator

`func (o *StoplistSearchCriteria) GetOperator() SearchOperator`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *StoplistSearchCriteria) GetOperatorOk() (*SearchOperator, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *StoplistSearchCriteria) SetOperator(v SearchOperator)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *StoplistSearchCriteria) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetValue

`func (o *StoplistSearchCriteria) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *StoplistSearchCriteria) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *StoplistSearchCriteria) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *StoplistSearchCriteria) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


