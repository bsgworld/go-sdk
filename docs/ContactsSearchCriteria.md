# ContactsSearchCriteria

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Field** | Pointer to **string** | Field for search. Possible values: id, phone, group_id, date, {field_id}  {field_id} – custom field ID; can be got from [GET /api/contacts/fields](#operation/contact_fields) | [optional] 
**Operator** | Pointer to [**SearchOperator**](SearchOperator.md) |  | [optional] 
**Value** | Pointer to **string** | Value to to find using search[field] and search[operator] | [optional] 

## Methods

### NewContactsSearchCriteria

`func NewContactsSearchCriteria() *ContactsSearchCriteria`

NewContactsSearchCriteria instantiates a new ContactsSearchCriteria object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactsSearchCriteriaWithDefaults

`func NewContactsSearchCriteriaWithDefaults() *ContactsSearchCriteria`

NewContactsSearchCriteriaWithDefaults instantiates a new ContactsSearchCriteria object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetField

`func (o *ContactsSearchCriteria) GetField() string`

GetField returns the Field field if non-nil, zero value otherwise.

### GetFieldOk

`func (o *ContactsSearchCriteria) GetFieldOk() (*string, bool)`

GetFieldOk returns a tuple with the Field field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetField

`func (o *ContactsSearchCriteria) SetField(v string)`

SetField sets Field field to given value.

### HasField

`func (o *ContactsSearchCriteria) HasField() bool`

HasField returns a boolean if a field has been set.

### GetOperator

`func (o *ContactsSearchCriteria) GetOperator() SearchOperator`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *ContactsSearchCriteria) GetOperatorOk() (*SearchOperator, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *ContactsSearchCriteria) SetOperator(v SearchOperator)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *ContactsSearchCriteria) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetValue

`func (o *ContactsSearchCriteria) GetValue() string`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *ContactsSearchCriteria) GetValueOk() (*string, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *ContactsSearchCriteria) SetValue(v string)`

SetValue sets Value field to given value.

### HasValue

`func (o *ContactsSearchCriteria) HasValue() bool`

HasValue returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


