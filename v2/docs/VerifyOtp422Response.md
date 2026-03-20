# VerifyOtp422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | TwoFA Service error. | [optional] 
**Errors** | Pointer to **[]string** | It may be one of the following:  - **Authentication expired** - Your OTP password has expired. OTP password is no longer valid.  - **Authentication failed status** - This error can occur when attempts limit is exceeded for authentication session.   | [optional] 

## Methods

### NewVerifyOtp422Response

`func NewVerifyOtp422Response() *VerifyOtp422Response`

NewVerifyOtp422Response instantiates a new VerifyOtp422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyOtp422ResponseWithDefaults

`func NewVerifyOtp422ResponseWithDefaults() *VerifyOtp422Response`

NewVerifyOtp422ResponseWithDefaults instantiates a new VerifyOtp422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *VerifyOtp422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *VerifyOtp422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *VerifyOtp422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *VerifyOtp422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *VerifyOtp422Response) GetErrors() []string`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *VerifyOtp422Response) GetErrorsOk() (*[]string, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *VerifyOtp422Response) SetErrors(v []string)`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *VerifyOtp422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


