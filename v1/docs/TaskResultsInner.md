# TaskResultsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **int32** | Error code: 0 for success, non-zero for various error conditions | [optional] 
**ErrorDescription** | Pointer to **string** | Human-readable error description. \&quot;No errors\&quot; when operation succeeds | [optional] 
**Reference** | Pointer to **string** | External reference ID provided in request or auto-generated | [optional] 
**Id** | Pointer to **string** | Internal message ID assigned by SMS Gateway | [optional] 
**Price** | Pointer to **float32** | Actual cost of sending this SMS message | [optional] 
**Currency** | Pointer to **string** | Currency code according to ISO-4217 standard | [optional] 

## Methods

### NewTaskResultsInner

`func NewTaskResultsInner() *TaskResultsInner`

NewTaskResultsInner instantiates a new TaskResultsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTaskResultsInnerWithDefaults

`func NewTaskResultsInnerWithDefaults() *TaskResultsInner`

NewTaskResultsInnerWithDefaults instantiates a new TaskResultsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *TaskResultsInner) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *TaskResultsInner) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *TaskResultsInner) SetError(v int32)`

SetError sets Error field to given value.

### HasError

`func (o *TaskResultsInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorDescription

`func (o *TaskResultsInner) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *TaskResultsInner) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *TaskResultsInner) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.

### HasErrorDescription

`func (o *TaskResultsInner) HasErrorDescription() bool`

HasErrorDescription returns a boolean if a field has been set.

### GetReference

`func (o *TaskResultsInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *TaskResultsInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *TaskResultsInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *TaskResultsInner) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetId

`func (o *TaskResultsInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TaskResultsInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TaskResultsInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *TaskResultsInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPrice

`func (o *TaskResultsInner) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *TaskResultsInner) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *TaskResultsInner) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *TaskResultsInner) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *TaskResultsInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *TaskResultsInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *TaskResultsInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *TaskResultsInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


