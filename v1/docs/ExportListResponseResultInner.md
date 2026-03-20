# ExportListResponseResultInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Key** | Pointer to **string** | Export file key identifier | [optional] 
**Request** | Pointer to **map[string]interface{}** | Original export request parameters that were used to create this export | [optional] 
**Status** | Pointer to **string** | Current export job status | [optional] 

## Methods

### NewExportListResponseResultInner

`func NewExportListResponseResultInner() *ExportListResponseResultInner`

NewExportListResponseResultInner instantiates a new ExportListResponseResultInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewExportListResponseResultInnerWithDefaults

`func NewExportListResponseResultInnerWithDefaults() *ExportListResponseResultInner`

NewExportListResponseResultInnerWithDefaults instantiates a new ExportListResponseResultInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetKey

`func (o *ExportListResponseResultInner) GetKey() string`

GetKey returns the Key field if non-nil, zero value otherwise.

### GetKeyOk

`func (o *ExportListResponseResultInner) GetKeyOk() (*string, bool)`

GetKeyOk returns a tuple with the Key field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetKey

`func (o *ExportListResponseResultInner) SetKey(v string)`

SetKey sets Key field to given value.

### HasKey

`func (o *ExportListResponseResultInner) HasKey() bool`

HasKey returns a boolean if a field has been set.

### GetRequest

`func (o *ExportListResponseResultInner) GetRequest() map[string]interface{}`

GetRequest returns the Request field if non-nil, zero value otherwise.

### GetRequestOk

`func (o *ExportListResponseResultInner) GetRequestOk() (*map[string]interface{}, bool)`

GetRequestOk returns a tuple with the Request field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRequest

`func (o *ExportListResponseResultInner) SetRequest(v map[string]interface{})`

SetRequest sets Request field to given value.

### HasRequest

`func (o *ExportListResponseResultInner) HasRequest() bool`

HasRequest returns a boolean if a field has been set.

### GetStatus

`func (o *ExportListResponseResultInner) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *ExportListResponseResultInner) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *ExportListResponseResultInner) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *ExportListResponseResultInner) HasStatus() bool`

HasStatus returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


