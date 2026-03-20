# ContactListSearchCriteria

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | Pointer to [**ContactGroupSearchField**](ContactGroupSearchField.md) |  | [optional] 
**Operator** | Pointer to [**SearchOperator**](SearchOperator.md) |  | [optional] 
**Value** | Pointer to **string** | Value to to find using search[field] and search[operator] | [optional] 

## Methods

### NewContactListSearchCriteria

`func NewContactListSearchCriteria() *ContactListSearchCriteria`

NewContactListSearchCriteria instantiates a new ContactListSearchCriteria object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactListSearchCriteriaWithDefaults

`func NewContactListSearchCriteriaWithDefaults() *ContactListSearchCriteria`

NewContactListSearchCriteriaWithDefaults instantiates a new ContactListSearchCriteria object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *ContactListSearchCriteria) GetField() ContactGroupSearchField`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *ContactListSearchCriteria) GetFieldOk() (*ContactGroupSearchField, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *ContactListSearchCriteria) SetField(v ContactGroupSearchField)`

SetField sets Field field to given value.

### HasField

`func (o *ContactListSearchCriteria) HasField() bool`

HasField returns a boolean if a field has been set.

### GetOperator

`func (o *ContactListSearchCriteria) GetOperator() SearchOperator`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *ContactListSearchCriteria) GetOperatorOk() (*SearchOperator, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *ContactListSearchCriteria) SetOperator(v SearchOperator)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *ContactListSearchCriteria) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetValue

`func (o *ContactListSearchCriteria) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ContactListSearchCriteria) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ContactListSearchCriteria) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *ContactListSearchCriteria) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


