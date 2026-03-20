# ResendOtp422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | TwoFA Service error. | [optional] 
**Errors** | Pointer to **[]string** | It may be one of the following:  - **Authentication failed status**  This error can occur when attempting to resend the OTP code for an authentication session that has already been completed with a ‘failed’ status. Resending the OTP code is only possible when the authentication session is in the ‘pending’ status.  - **Authentication canceled status** This error can occur when attempting to resend the OTP code for an authentication session that has already been completed with a ‘canceled’ status. Resending the OTP code is only possible when the authentication session is in the ‘pending’ status.  - **Authentication expired**   This error can occur when attempting to resend the OTP code for an authentication session that has already been completed with an ‘expired’ status. Resending the OTP code is only possible when the authentication session is in the ‘pending’ status   | [optional] 

## Methods

### NewResendOtp422Response

`func NewResendOtp422Response() *ResendOtp422Response`

NewResendOtp422Response instantiates a new ResendOtp422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewResendOtp422ResponseWithDefaults

`func NewResendOtp422ResponseWithDefaults() *ResendOtp422Response`

NewResendOtp422ResponseWithDefaults instantiates a new ResendOtp422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ResendOtp422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ResendOtp422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ResendOtp422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ResendOtp422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *ResendOtp422Response) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ResendOtp422Response) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ResendOtp422Response) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ResendOtp422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


