# ExportCreateResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | Pointer to **string** | Human-readable error description | [optional] 
**Key** | Pointer to **string** | Export file key identifier. Use this key to download, check status, or delete the export. | [optional] 

## Methods

### NewExportCreateResponse

`func NewExportCreateResponse(error_ int32, ) *ExportCreateResponse`

NewExportCreateResponse instantiates a new ExportCreateResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExportCreateResponseWithDefaults

`func NewExportCreateResponseWithDefaults() *ExportCreateResponse`

NewExportCreateResponseWithDefaults instantiates a new ExportCreateResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ExportCreateResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ExportCreateResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ExportCreateResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *ExportCreateResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *ExportCreateResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *ExportCreateResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.

### HasErrorDescription

`func (o *ExportCreateResponse) HasErrorDescription() bool`

HasErrorDescription returns a boolean if a field has been set.

### GetKey

`func (o *ExportCreateResponse) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ExportCreateResponse) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ExportCreateResponse) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *ExportCreateResponse) HasKey() bool`

HasKey returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


