# MnpServiceStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | **string** | Human-readable error description | 
**Status** | Pointer to **string** | Service status | [optional] 
**TotalRequests** | Pointer to **int32** | Total number of MNP lookup requests | [optional] 
**TodayRequests** | Pointer to **int32** | Number of MNP lookup requests today | [optional] 

## Methods

### NewMnpServiceStatusResponse

`func NewMnpServiceStatusResponse(error_ int32, errorDescription string, ) *MnpServiceStatusResponse`

NewMnpServiceStatusResponse instantiates a new MnpServiceStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpServiceStatusResponseWithDefaults

`func NewMnpServiceStatusResponseWithDefaults() *MnpServiceStatusResponse`

NewMnpServiceStatusResponseWithDefaults instantiates a new MnpServiceStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *MnpServiceStatusResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MnpServiceStatusResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MnpServiceStatusResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *MnpServiceStatusResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *MnpServiceStatusResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *MnpServiceStatusResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetStatus

`func (o *MnpServiceStatusResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *MnpServiceStatusResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *MnpServiceStatusResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *MnpServiceStatusResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetTotalRequests

`func (o *MnpServiceStatusResponse) GetTotalRequests() int32`

GetTotalRequests returns the TotalRequests field if non-nil, zero value otherwise.

### GetTotalRequestsOk

`func (o *MnpServiceStatusResponse) GetTotalRequestsOk() (*int32, bool)`

GetTotalRequestsOk returns a tuple with the TotalRequests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotalRequests

`func (o *MnpServiceStatusResponse) SetTotalRequests(v int32)`

SetTotalRequests sets TotalRequests field to given value.

### HasTotalRequests

`func (o *MnpServiceStatusResponse) HasTotalRequests() bool`

HasTotalRequests returns a boolean if a field has been set.

### GetTodayRequests

`func (o *MnpServiceStatusResponse) GetTodayRequests() int32`

GetTodayRequests returns the TodayRequests field if non-nil, zero value otherwise.

### GetTodayRequestsOk

`func (o *MnpServiceStatusResponse) GetTodayRequestsOk() (*int32, bool)`

GetTodayRequestsOk returns a tuple with the TodayRequests field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTodayRequests

`func (o *MnpServiceStatusResponse) SetTodayRequests(v int32)`

SetTodayRequests sets TodayRequests field to given value.

### HasTodayRequests

`func (o *MnpServiceStatusResponse) HasTodayRequests() bool`

HasTodayRequests returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


