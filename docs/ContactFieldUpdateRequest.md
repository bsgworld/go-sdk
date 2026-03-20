# ContactFieldUpdateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | Pointer to **string** | The name of the custom field for the contacts | [optional] 
**Description** | Pointer to **string** | Description of the custom contact field | [optional] 
**IsVisible** | Pointer to **bool** | Whether the field is displayed: true or false value | [optional] [default to true]

## Methods

### NewContactFieldUpdateRequest

`func NewContactFieldUpdateRequest() *ContactFieldUpdateRequest`

NewContactFieldUpdateRequest instantiates a new ContactFieldUpdateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactFieldUpdateRequestWithDefaults

`func NewContactFieldUpdateRequestWithDefaults() *ContactFieldUpdateRequest`

NewContactFieldUpdateRequestWithDefaults instantiates a new ContactFieldUpdateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ContactFieldUpdateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContactFieldUpdateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContactFieldUpdateRequest) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *ContactFieldUpdateRequest) HasName() bool`

HasName returns a boolean if a field has been set.

### GetDescription

`func (o *ContactFieldUpdateRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactFieldUpdateRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactFieldUpdateRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactFieldUpdateRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsVisible

`func (o *ContactFieldUpdateRequest) GetIsVisible() bool`

GetIsVisible returns the IsVisible field if non-nil, zero value otherwise.

### GetIsVisibleOk

`func (o *ContactFieldUpdateRequest) GetIsVisibleOk() (*bool, bool)`

GetIsVisibleOk returns a tuple with the IsVisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVisible

`func (o *ContactFieldUpdateRequest) SetIsVisible(v bool)`

SetIsVisible sets IsVisible field to given value.

### HasIsVisible

`func (o *ContactFieldUpdateRequest) HasIsVisible() bool`

HasIsVisible returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


