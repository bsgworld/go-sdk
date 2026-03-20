# Sms2WayIncomingResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success, 35 for inactive 2way SMS service | 
**ErrorDescription** | **string** | Human-readable error description | 
**Result** | [**[]Sms2WayIncomingResponseResultInner**](Sms2WayIncomingResponseResultInner.md) | Array of incoming messages | 
**TotalCount** | **int32** | Total number of messages found | 

## Methods

### NewSms2WayIncomingResponse

`func NewSms2WayIncomingResponse(error_ int32, errorDescription string, result []Sms2WayIncomingResponseResultInner, totalCount int32, ) *Sms2WayIncomingResponse`

NewSms2WayIncomingResponse instantiates a new Sms2WayIncomingResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSms2WayIncomingResponseWithDefaults

`func NewSms2WayIncomingResponseWithDefaults() *Sms2WayIncomingResponse`

NewSms2WayIncomingResponseWithDefaults instantiates a new Sms2WayIncomingResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *Sms2WayIncomingResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *Sms2WayIncomingResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *Sms2WayIncomingResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *Sms2WayIncomingResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *Sms2WayIncomingResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *Sms2WayIncomingResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetResult

`func (o *Sms2WayIncomingResponse) GetResult() []Sms2WayIncomingResponseResultInner`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *Sms2WayIncomingResponse) GetResultOk() (*[]Sms2WayIncomingResponseResultInner, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *Sms2WayIncomingResponse) SetResult(v []Sms2WayIncomingResponseResultInner)`

SetResult sets Result field to given value.


### GetTotalCount

`func (o *Sms2WayIncomingResponse) GetTotalCount() int32`

GetTotalCount returns the TotalCount field if non-nil, zero value otherwise.

### GetTotalCountOk

`func (o *Sms2WayIncomingResponse) GetTotalCountOk() (*int32, bool)`

GetTotalCountOk returns a tuple with the TotalCount field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalCount

`func (o *Sms2WayIncomingResponse) SetTotalCount(v int32)`

SetTotalCount sets TotalCount field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


