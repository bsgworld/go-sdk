# OtpTemplateCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | Name of the template.  A string of 3 to 50 characters. | 
**Text** | **string** | The text of the template message. | 
**Countries** | Pointer to **[]string** | Two-letter country code(s) for which the template must apply. Sending messages with the OTP code will only be possible if the recipient’s number belongs to the country you specify for the template. | [optional] 

## Methods

### NewOtpTemplateCreateRequest

`func NewOtpTemplateCreateRequest(name string, text string, ) *OtpTemplateCreateRequest`

NewOtpTemplateCreateRequest instantiates a new OtpTemplateCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewOtpTemplateCreateRequestWithDefaults

`func NewOtpTemplateCreateRequestWithDefaults() *OtpTemplateCreateRequest`

NewOtpTemplateCreateRequestWithDefaults instantiates a new OtpTemplateCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *OtpTemplateCreateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *OtpTemplateCreateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *OtpTemplateCreateRequest) SetName(v string)`

SetName sets Name field to given value.


### GetText

`func (o *OtpTemplateCreateRequest) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *OtpTemplateCreateRequest) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *OtpTemplateCreateRequest) SetText(v string)`

SetText sets Text field to given value.


### GetCountries

`func (o *OtpTemplateCreateRequest) GetCountries() []string`

GetCountries returns the Countries field if non-nil, zero value otherwise.

### GetCountriesOk

`func (o *OtpTemplateCreateRequest) GetCountriesOk() (*[]string, bool)`

GetCountriesOk returns a tuple with the Countries field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountries

`func (o *OtpTemplateCreateRequest) SetCountries(v []string)`

SetCountries sets Countries field to given value.

### HasCountries

`func (o *OtpTemplateCreateRequest) HasCountries() bool`

HasCountries returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


