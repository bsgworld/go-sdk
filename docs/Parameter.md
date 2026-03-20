# Parameter

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Text** | Pointer to **NullableString** |  | [optional] 
**Payload** | Pointer to **NullableString** |  | [optional] 

## Methods

### NewParameter

`func NewParameter(type_ string, ) *Parameter`

NewParameter instantiates a new Parameter object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewParameterWithDefaults

`func NewParameterWithDefaults() *Parameter`

NewParameterWithDefaults instantiates a new Parameter object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Parameter) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Parameter) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Parameter) SetType(v string)`

SetType sets Type field to given value.


### GetText

`func (o *Parameter) GetText() string`

GetText returns the Text field if non-nil, zero value otherwise.

### GetTextOk

`func (o *Parameter) GetTextOk() (*string, bool)`

GetTextOk returns a tuple with the Text field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetText

`func (o *Parameter) SetText(v string)`

SetText sets Text field to given value.

### HasText

`func (o *Parameter) HasText() bool`

HasText returns a boolean if a field has been set.

### SetTextNil

`func (o *Parameter) SetTextNil(b bool)`

 SetTextNil sets the value for Text to be an explicit nil

### UnsetText
`func (o *Parameter) UnsetText()`

UnsetText ensures that no value is present for Text, not even an explicit nil
### GetPayload

`func (o *Parameter) GetPayload() string`

GetPayload returns the Payload field if non-nil, zero value otherwise.

### GetPayloadOk

`func (o *Parameter) GetPayloadOk() (*string, bool)`

GetPayloadOk returns a tuple with the Payload field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPayload

`func (o *Parameter) SetPayload(v string)`

SetPayload sets Payload field to given value.

### HasPayload

`func (o *Parameter) HasPayload() bool`

HasPayload returns a boolean if a field has been set.

### SetPayloadNil

`func (o *Parameter) SetPayloadNil(b bool)`

 SetPayloadNil sets the value for Payload to be an explicit nil

### UnsetPayload
`func (o *Parameter) UnsetPayload()`

UnsetPayload ensures that no value is present for Payload, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


