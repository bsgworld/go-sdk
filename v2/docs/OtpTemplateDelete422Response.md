# OtpTemplateDelete422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | The given data was invalid. | [optional] 
**Errors** | Pointer to **[]string** | It may be one of the following:  - **Default template is not available for deletion** This error occurs when attempting to delete a template that is set as the default template. The default template cannot be deleted.   | [optional] 

## Methods

### NewOtpTemplateDelete422Response

`func NewOtpTemplateDelete422Response() *OtpTemplateDelete422Response`

NewOtpTemplateDelete422Response instantiates a new OtpTemplateDelete422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOtpTemplateDelete422ResponseWithDefaults

`func NewOtpTemplateDelete422ResponseWithDefaults() *OtpTemplateDelete422Response`

NewOtpTemplateDelete422ResponseWithDefaults instantiates a new OtpTemplateDelete422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *OtpTemplateDelete422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *OtpTemplateDelete422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *OtpTemplateDelete422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *OtpTemplateDelete422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *OtpTemplateDelete422Response) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *OtpTemplateDelete422Response) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *OtpTemplateDelete422Response) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *OtpTemplateDelete422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


