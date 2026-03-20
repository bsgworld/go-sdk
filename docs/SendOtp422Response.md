# SendOtp422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | The given data was invalid. | [optional] 
**Errors** | Pointer to **[]string** | It may be one of the following:  - **User channel not found**  This error can occur when the channel is specified incorrectly. Please ensure that you are using the correct channel and try again.  - **Template not found**  This error can occur when the template identifier is specified incorrectly or the specified template is not present in the system. Please ensure that you are using the correct template identifier and try again.  - **Invalid template status**  This error occurs when the provided template identifier in the request does not match the “Approved” status.  - **Insufficient funds**  Insufficient funds to send OTP. Please top up your account.  - **Exists on the stop list**  We’re unable to send message as the phone number of recipient is currently in stop list.  - **User channel inactive**  The message sending method is disabled. Please enable method in your personal account and try again.  - **This action is available for the account of your type only for your manager phone number.**  To send OTP code is not allowed in Demo account mode.   - **Authentication limit with status pending**  This error can occur when total authentication limit with status “pending” is exceeded for your account.  - **Total authentication limit**  This error can occur when total authentication limit is exceeded for your account.  - **Template is not available** This error occurs when you try to create authentication using a template that is only available in the test mode of your account. Please choose a different template.  | [optional] 

## Methods

### NewSendOtp422Response

`func NewSendOtp422Response() *SendOtp422Response`

NewSendOtp422Response instantiates a new SendOtp422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSendOtp422ResponseWithDefaults

`func NewSendOtp422ResponseWithDefaults() *SendOtp422Response`

NewSendOtp422ResponseWithDefaults instantiates a new SendOtp422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *SendOtp422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *SendOtp422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *SendOtp422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *SendOtp422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *SendOtp422Response) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *SendOtp422Response) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *SendOtp422Response) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *SendOtp422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


