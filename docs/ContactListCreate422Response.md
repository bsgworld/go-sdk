# ContactListCreate422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | It may be one of the following errors:  - **Contact group is already exists** - There are exists another contact list with the same **name**, use different name for new list    | [optional] 
**Errors** | Pointer to **[]interface{}** | errors | [optional] 

## Methods

### NewContactListCreate422Response

`func NewContactListCreate422Response() *ContactListCreate422Response`

NewContactListCreate422Response instantiates a new ContactListCreate422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactListCreate422ResponseWithDefaults

`func NewContactListCreate422ResponseWithDefaults() *ContactListCreate422Response`

NewContactListCreate422ResponseWithDefaults instantiates a new ContactListCreate422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ContactListCreate422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ContactListCreate422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ContactListCreate422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ContactListCreate422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *ContactListCreate422Response) GetErrors() []interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ContactListCreate422Response) GetErrorsOk() (*[]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ContactListCreate422Response) SetErrors(v []interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ContactListCreate422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


