# VerifyOtpRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**AccessCode** | **string** | The one-time password received by the user through the specified channel or alternative channel (optional) in the generation request that needs to be validated. An integer from 3 to 9 digits. | 

## Methods

### NewVerifyOtpRequest

`func NewVerifyOtpRequest(accessCode string, ) *VerifyOtpRequest`

NewVerifyOtpRequest instantiates a new VerifyOtpRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewVerifyOtpRequestWithDefaults

`func NewVerifyOtpRequestWithDefaults() *VerifyOtpRequest`

NewVerifyOtpRequestWithDefaults instantiates a new VerifyOtpRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetAccessCode

`func (o *VerifyOtpRequest) GetAccessCode() string`

GetAccessCode returns the AccessCode field if non-nil, zero value otherwise.

### GetAccessCodeOk

`func (o *VerifyOtpRequest) GetAccessCodeOk() (*string, bool)`

GetAccessCodeOk returns a tuple with the AccessCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetAccessCode

`func (o *VerifyOtpRequest) SetAccessCode(v string)`

SetAccessCode sets AccessCode field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


