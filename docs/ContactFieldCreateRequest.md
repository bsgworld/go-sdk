# ContactFieldCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Name** | **string** | The name of the custom field for the contacts | 
**Description** | Pointer to **string** | Description of the custom contact field | [optional] 
**IsVisible** | Pointer to **bool** | Whether the field is displayed: true or false value | [optional] [default to true]
**Type** | [**ContactFieldType**](ContactFieldType.md) |  | 

## Methods

### NewContactFieldCreateRequest

`func NewContactFieldCreateRequest(name string, type_ ContactFieldType, ) *ContactFieldCreateRequest`

NewContactFieldCreateRequest instantiates a new ContactFieldCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewContactFieldCreateRequestWithDefaults

`func NewContactFieldCreateRequestWithDefaults() *ContactFieldCreateRequest`

NewContactFieldCreateRequestWithDefaults instantiates a new ContactFieldCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetName

`func (o *ContactFieldCreateRequest) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *ContactFieldCreateRequest) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *ContactFieldCreateRequest) SetName(v string)`

SetName sets Name field to given value.


### GetDescription

`func (o *ContactFieldCreateRequest) GetDescription() string`

GetDescription returns the Description field if non-nil, zero value otherwise.

### GetDescriptionOk

`func (o *ContactFieldCreateRequest) GetDescriptionOk() (*string, bool)`

GetDescriptionOk returns a tuple with the Description field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDescription

`func (o *ContactFieldCreateRequest) SetDescription(v string)`

SetDescription sets Description field to given value.

### HasDescription

`func (o *ContactFieldCreateRequest) HasDescription() bool`

HasDescription returns a boolean if a field has been set.

### GetIsVisible

`func (o *ContactFieldCreateRequest) GetIsVisible() bool`

GetIsVisible returns the IsVisible field if non-nil, zero value otherwise.

### GetIsVisibleOk

`func (o *ContactFieldCreateRequest) GetIsVisibleOk() (*bool, bool)`

GetIsVisibleOk returns a tuple with the IsVisible field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsVisible

`func (o *ContactFieldCreateRequest) SetIsVisible(v bool)`

SetIsVisible sets IsVisible field to given value.

### HasIsVisible

`func (o *ContactFieldCreateRequest) HasIsVisible() bool`

HasIsVisible returns a boolean if a field has been set.

### GetType

`func (o *ContactFieldCreateRequest) GetType() ContactFieldType`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *ContactFieldCreateRequest) GetTypeOk() (*ContactFieldType, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *ContactFieldCreateRequest) SetType(v ContactFieldType)`

SetType sets Type field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


