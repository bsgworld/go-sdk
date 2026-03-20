# Contact422Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Message** | Pointer to **string** | Invalid contact id | [optional] 
**Errors** | Pointer to **[]interface{}** | errors | [optional] 

## Methods

### NewContact422Response

`func NewContact422Response() *Contact422Response`

NewContact422Response instantiates a new Contact422Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContact422ResponseWithDefaults

`func NewContact422ResponseWithDefaults() *Contact422Response`

NewContact422ResponseWithDefaults instantiates a new Contact422Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessage

`func (o *Contact422Response) GetMessage() string`

GetMessage returns the Message field if non-nil, zero value otherwise.

### GetMessageOk

`func (o *Contact422Response) GetMessageOk() (*string, bool)`

GetMessageOk returns a tuple with the Message field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessage

`func (o *Contact422Response) SetMessage(v string)`

SetMessage sets Message field to given value.

### HasMessage

`func (o *Contact422Response) HasMessage() bool`

HasMessage returns a boolean if a field has been set.

### GetErrors

`func (o *Contact422Response) GetErrors() []interface{}`

GetErrors returns the Errors field if non-nil, zero value otherwise.

### GetErrorsOk

`func (o *Contact422Response) GetErrorsOk() (*[]interface{}, bool)`

GetErrorsOk returns a tuple with the Errors field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrors

`func (o *Contact422Response) SetErrors(v []interface{})`

SetErrors sets Errors field to given value.

### HasErrors

`func (o *Contact422Response) HasErrors() bool`

HasErrors returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


