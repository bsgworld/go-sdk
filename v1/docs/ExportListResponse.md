# ExportListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**Result** | Pointer to [**[]ExportListResponseResultInner**](ExportListResponseResultInner.md) | Array of export jobs | [optional] 

## Methods

### NewExportListResponse

`func NewExportListResponse(error_ int32, ) *ExportListResponse`

NewExportListResponse instantiates a new ExportListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExportListResponseWithDefaults

`func NewExportListResponseWithDefaults() *ExportListResponse`

NewExportListResponseWithDefaults instantiates a new ExportListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ExportListResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ExportListResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ExportListResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetResult

`func (o *ExportListResponse) GetResult() []ExportListResponseResultInner`

GetResult returns the Result field if non-nil, zero value otherwise.

### GetResultOk

`func (o *ExportListResponse) GetResultOk() (*[]ExportListResponseResultInner, bool)`

GetResultOk returns a tuple with the Result field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetResult

`func (o *ExportListResponse) SetResult(v []ExportListResponseResultInner)`

SetResult sets Result field to given value.

### HasResult

`func (o *ExportListResponse) HasResult() bool`

HasResult returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


