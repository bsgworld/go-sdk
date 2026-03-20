# Components

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**SubType** | Pointer to **NullableString** |  | [optional] 
**Index** | Pointer to **NullableString** |  | [optional] 
**Parameters** | Pointer to [**[]Parameter**](Parameter.md) |  | [optional] 

## Methods

### NewComponents

`func NewComponents(type_ string, ) *Components`

NewComponents instantiates a new Components object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewComponentsWithDefaults

`func NewComponentsWithDefaults() *Components`

NewComponentsWithDefaults instantiates a new Components object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *Components) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *Components) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *Components) SetType(v string)`

SetType sets Type field to given value.


### GetSubType

`func (o *Components) GetSubType() string`

GetSubType returns the SubType field if non-nil, zero value otherwise.

### GetSubTypeOk

`func (o *Components) GetSubTypeOk() (*string, bool)`

GetSubTypeOk returns a tuple with the SubType field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSubType

`func (o *Components) SetSubType(v string)`

SetSubType sets SubType field to given value.

### HasSubType

`func (o *Components) HasSubType() bool`

HasSubType returns a boolean if a field has been set.

### SetSubTypeNil

`func (o *Components) SetSubTypeNil(b bool)`

 SetSubTypeNil sets the value for SubType to be an explicit nil

### UnsetSubType
`func (o *Components) UnsetSubType()`

UnsetSubType ensures that no value is present for SubType, not even an explicit nil
### GetIndex

`func (o *Components) GetIndex() string`

GetIndex returns the Index field if non-nil, zero value otherwise.

### GetIndexOk

`func (o *Components) GetIndexOk() (*string, bool)`

GetIndexOk returns a tuple with the Index field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIndex

`func (o *Components) SetIndex(v string)`

SetIndex sets Index field to given value.

### HasIndex

`func (o *Components) HasIndex() bool`

HasIndex returns a boolean if a field has been set.

### SetIndexNil

`func (o *Components) SetIndexNil(b bool)`

 SetIndexNil sets the value for Index to be an explicit nil

### UnsetIndex
`func (o *Components) UnsetIndex()`

UnsetIndex ensures that no value is present for Index, not even an explicit nil
### GetParameters

`func (o *Components) GetParameters() []Parameter`

GetParameters returns the Parameters field if non-nil, zero value otherwise.

### GetParametersOk

`func (o *Components) GetParametersOk() (*[]Parameter, bool)`

GetParametersOk returns a tuple with the Parameters field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetParameters

`func (o *Components) SetParameters(v []Parameter)`

SetParameters sets Parameters field to given value.

### HasParameters

`func (o *Components) HasParameters() bool`

HasParameters returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


