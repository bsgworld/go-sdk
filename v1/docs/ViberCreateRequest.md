# ViberCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | [**[]ViberCreateRequestMessagesInner**](ViberCreateRequestMessagesInner.md) | Array of Viber messages | 
**Tariff** | Pointer to **int32** | Tariff code for pricing (optional) | [optional] 
**Validity** | Pointer to **int32** | Message validity period in seconds (max 24 hours &#x3D; 86400 sec, default &#x3D; 24 hours) | [optional] 

## Methods

### NewViberCreateRequest

`func NewViberCreateRequest(messages []ViberCreateRequestMessagesInner, ) *ViberCreateRequest`

NewViberCreateRequest instantiates a new ViberCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberCreateRequestWithDefaults

`func NewViberCreateRequestWithDefaults() *ViberCreateRequest`

NewViberCreateRequestWithDefaults instantiates a new ViberCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessages

`func (o *ViberCreateRequest) GetMessages() []ViberCreateRequestMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ViberCreateRequest) GetMessagesOk() (*[]ViberCreateRequestMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ViberCreateRequest) SetMessages(v []ViberCreateRequestMessagesInner)`

SetMessages sets Messages field to given value.


### GetTariff

`func (o *ViberCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *ViberCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *ViberCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *ViberCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetValidity

`func (o *ViberCreateRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *ViberCreateRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *ViberCreateRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *ViberCreateRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


