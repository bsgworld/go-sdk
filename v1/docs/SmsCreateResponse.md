# SmsCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Result** | [**[]TaskResultsInner**](TaskResultsInner.md) | Array of results for task-based SMS sending | 
**TaskId** | **string** | Task ID for bulk SMS operations | 
**TotalPrice** | **float32** | Total price for all messages in task | 
**Currency** | **string** | Currency code for total price | 

## Methods

### NewSmsCreateResponse

`func NewSmsCreateResponse(result []TaskResultsInner, taskId string, totalPrice float32, currency string, ) *SmsCreateResponse`

NewSmsCreateResponse instantiates a new SmsCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsCreateResponseWithDefaults

`func NewSmsCreateResponseWithDefaults() *SmsCreateResponse`

NewSmsCreateResponseWithDefaults instantiates a new SmsCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetResult

`func (o *SmsCreateResponse) GetResult() []TaskResultsInner`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *SmsCreateResponse) GetResultOk() (*[]TaskResultsInner, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *SmsCreateResponse) SetResult(v []TaskResultsInner)`

SetResult sets Result field to given value.


### GetTaskId

`func (o *SmsCreateResponse) GetTaskId() string`

GetTaskId returns the TaskId field if non-nil, zero value otherwise.

### GetTaskIdOk

`func (o *SmsCreateResponse) GetTaskIdOk() (*string, bool)`

GetTaskIdOk returns a tuple with the TaskId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTaskId

`func (o *SmsCreateResponse) SetTaskId(v string)`

SetTaskId sets TaskId field to given value.


### GetTotalPrice

`func (o *SmsCreateResponse) GetTotalPrice() float32`

GetTotalPrice returns the TotalPrice field if non-nil, zero value otherwise.

### GetTotalPriceOk

`func (o *SmsCreateResponse) GetTotalPriceOk() (*float32, bool)`

GetTotalPriceOk returns a tuple with the TotalPrice field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalPrice

`func (o *SmsCreateResponse) SetTotalPrice(v float32)`

SetTotalPrice sets TotalPrice field to given value.


### GetCurrency

`func (o *SmsCreateResponse) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *SmsCreateResponse) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *SmsCreateResponse) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


