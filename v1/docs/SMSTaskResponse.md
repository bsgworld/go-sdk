# SMSTaskResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**TaskId** | **string** | Task ID for bulk SMS operations | 
**Result** | [**[]TaskResultsInner**](TaskResultsInner.md) | Array of results for task-based SMS sending | 
**TotalPrice** | **float32** | Total price for all messages in task | 
**Currency** | **string** | Currency code for total price | 

## Methods

### NewSMSTaskResponse

`func NewSMSTaskResponse(taskId string, result []TaskResultsInner, totalPrice float32, currency string, ) *SMSTaskResponse`

NewSMSTaskResponse instantiates a new SMSTaskResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSMSTaskResponseWithDefaults

`func NewSMSTaskResponseWithDefaults() *SMSTaskResponse`

NewSMSTaskResponseWithDefaults instantiates a new SMSTaskResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTaskId

`func (o *SMSTaskResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *SMSTaskResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *SMSTaskResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetResult

`func (o *SMSTaskResponse) GetResult() []TaskResultsInner`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *SMSTaskResponse) GetResultOk() (*[]TaskResultsInner, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *SMSTaskResponse) SetResult(v []TaskResultsInner)`

SetResult sets Result field to given value.


### GetTotalPrice

`func (o *SMSTaskResponse) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *SMSTaskResponse) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *SMSTaskResponse) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.


### GetCurrency

`func (o *SMSTaskResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SMSTaskResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SMSTaskResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


