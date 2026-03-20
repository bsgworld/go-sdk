# ContactUpdate422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | It may be one of the following errors:  - **Phone number is already exist in contact book** - There are exists another contact with the same phone number, use that instead of change phone of this   - **Invalid contact id** - Pass correct contact id  - **Invalid phone number format** - Pass correct phone number  | [optional] 
**Errors** | Pointer to **[]interface{}** | errors | [optional] 

## Methods

### NewContactUpdate422Response

`func NewContactUpdate422Response() *ContactUpdate422Response`

NewContactUpdate422Response instantiates a new ContactUpdate422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactUpdate422ResponseWithDefaults

`func NewContactUpdate422ResponseWithDefaults() *ContactUpdate422Response`

NewContactUpdate422ResponseWithDefaults instantiates a new ContactUpdate422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ContactUpdate422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ContactUpdate422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ContactUpdate422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ContactUpdate422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *ContactUpdate422Response) GetErrors() []interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ContactUpdate422Response) GetErrorsOk() (*[]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ContactUpdate422Response) SetErrors(v []interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ContactUpdate422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


