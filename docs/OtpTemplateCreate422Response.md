# OtpTemplateCreate422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | The given data was invalid. | [optional] 
**Errors** | Pointer to **[]string** | It may be one of the following:  - **The number of requests to create a template is limited to 10. Please wait for the manager approve before making a new request.** You can have no more than 10 templates with the current status “Requested”. If you already have 10 templates with this status, you need to delete one of them to create a new template. Additionally, if any of the existing templates transitions to the “Approved” or “Rejected” status, it also frees up space for creating a new template. - **The variable {code2fa} is required in the text** This error occurs when the message template text does not contain the required variable {code2fa} or the variable syntax is incorrect. This variable is intended for inserting the actual OTP code into the message text. - **The {code2fa} variable must occur only once in the text** This error occurs when multiple occurrences of the {code2fa} variable are found in the message template text. Please check the entire template text and remove any additional occurrences of the variable. - **This action is not available for the account of your type** Creating a message template for sending OTP codes is not allowed in Demo and Test account mode. - **User has a template with the identical name!** The template with the specified name in the parameter ‘name’ already exists. Please use names that are distinct from your existing templates.  | [optional] 

## Methods

### NewOtpTemplateCreate422Response

`func NewOtpTemplateCreate422Response() *OtpTemplateCreate422Response`

NewOtpTemplateCreate422Response instantiates a new OtpTemplateCreate422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOtpTemplateCreate422ResponseWithDefaults

`func NewOtpTemplateCreate422ResponseWithDefaults() *OtpTemplateCreate422Response`

NewOtpTemplateCreate422ResponseWithDefaults instantiates a new OtpTemplateCreate422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *OtpTemplateCreate422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *OtpTemplateCreate422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *OtpTemplateCreate422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *OtpTemplateCreate422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *OtpTemplateCreate422Response) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *OtpTemplateCreate422Response) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *OtpTemplateCreate422Response) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *OtpTemplateCreate422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


