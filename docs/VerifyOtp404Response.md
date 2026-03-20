# VerifyOtp404Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | TwoFA Service error. | [optional] 
**Errors** | Pointer to **[]string** | It may be one of the following: - **Authentication not found** - This error can occur when the authentication identifier is specified incorrectly or the specified authentication is not present in the system. Please ensure that you are using the correct authentication identifier and try again. - **The code does not match the expected value** - The error occurs when the provided code does not match the value that was sent to the recipient’s number.  | [optional] 

## Methods

### NewVerifyOtp404Response

`func NewVerifyOtp404Response() *VerifyOtp404Response`

NewVerifyOtp404Response instantiates a new VerifyOtp404Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyOtp404ResponseWithDefaults

`func NewVerifyOtp404ResponseWithDefaults() *VerifyOtp404Response`

NewVerifyOtp404ResponseWithDefaults instantiates a new VerifyOtp404Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *VerifyOtp404Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *VerifyOtp404Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *VerifyOtp404Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *VerifyOtp404Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *VerifyOtp404Response) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *VerifyOtp404Response) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *VerifyOtp404Response) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *VerifyOtp404Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


