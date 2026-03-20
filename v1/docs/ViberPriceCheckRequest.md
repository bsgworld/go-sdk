# ViberPriceCheckRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Messages** | [**[]ViberPriceCheckRequestMessagesInner**](ViberPriceCheckRequestMessagesInner.md) | Array of Viber messages for price calculation | 
**Tariff** | Pointer to **int32** | Optional. Tariff code for pricing (0 &#x3D; account default). Affects which price list is used for calculation. | [optional] 
**Validity** | Pointer to **int32** | Optional. Message validity period in seconds (max 24 hours &#x3D; 86400 sec, default &#x3D; 24 hours) | [optional] 

## Methods

### NewViberPriceCheckRequest

`func NewViberPriceCheckRequest(messages []ViberPriceCheckRequestMessagesInner, ) *ViberPriceCheckRequest`

NewViberPriceCheckRequest instantiates a new ViberPriceCheckRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberPriceCheckRequestWithDefaults

`func NewViberPriceCheckRequestWithDefaults() *ViberPriceCheckRequest`

NewViberPriceCheckRequestWithDefaults instantiates a new ViberPriceCheckRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMessages

`func (o *ViberPriceCheckRequest) GetMessages() []ViberPriceCheckRequestMessagesInner`

GetMessages returns the Messages field if non-nil, zero value otherwise.

### GetMessagesOk

`func (o *ViberPriceCheckRequest) GetMessagesOk() (*[]ViberPriceCheckRequestMessagesInner, bool)`

GetMessagesOk returns a tuple with the Messages field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMessages

`func (o *ViberPriceCheckRequest) SetMessages(v []ViberPriceCheckRequestMessagesInner)`

SetMessages sets Messages field to given value.


### GetTariff

`func (o *ViberPriceCheckRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *ViberPriceCheckRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *ViberPriceCheckRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *ViberPriceCheckRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetValidity

`func (o *ViberPriceCheckRequest) GetValidity() int32`

GetValidity returns the Validity field if non-nil, zero value otherwise.

### GetValidityOk

`func (o *ViberPriceCheckRequest) GetValidityOk() (*int32, bool)`

GetValidityOk returns a tuple with the Validity field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValidity

`func (o *ViberPriceCheckRequest) SetValidity(v int32)`

SetValidity sets Validity field to given value.

### HasValidity

`func (o *ViberPriceCheckRequest) HasValidity() bool`

HasValidity returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


