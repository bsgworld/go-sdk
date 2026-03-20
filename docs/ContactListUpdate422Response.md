# ContactListUpdate422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | It may be one of the following errors:  - **Contact group is not found** - There is not contact list with this id, use correct contact list id - **Contact group is already exists** - There are exists another contact list with the same **name**, use different name for new list    | [optional] 
**Errors** | Pointer to **[]interface{}** | errors | [optional] 

## Methods

### NewContactListUpdate422Response

`func NewContactListUpdate422Response() *ContactListUpdate422Response`

NewContactListUpdate422Response instantiates a new ContactListUpdate422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactListUpdate422ResponseWithDefaults

`func NewContactListUpdate422ResponseWithDefaults() *ContactListUpdate422Response`

NewContactListUpdate422ResponseWithDefaults instantiates a new ContactListUpdate422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *ContactListUpdate422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *ContactListUpdate422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *ContactListUpdate422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *ContactListUpdate422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *ContactListUpdate422Response) GetErrors() []interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *ContactListUpdate422Response) GetErrorsOk() (*[]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *ContactListUpdate422Response) SetErrors(v []interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *ContactListUpdate422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


