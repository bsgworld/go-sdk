# MessagePriceObject

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Value** | Pointer to **float32** | Message price | [optional] 
**Currency** | Pointer to **string** | The currency code of the account. Specified according to the ISO-4217 standard | [optional] 

## Methods

### NewMessagePriceObject

`func NewMessagePriceObject() *MessagePriceObject`

NewMessagePriceObject instantiates a new MessagePriceObject object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMessagePriceObjectWithDefaults

`func NewMessagePriceObjectWithDefaults() *MessagePriceObject`

NewMessagePriceObjectWithDefaults instantiates a new MessagePriceObject object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetValue

`func (o *MessagePriceObject) GetValue() float32`

GetValue returns the Value field if non-nil, zero value otherwise.

### GetValueOk

`func (o *MessagePriceObject) GetValueOk() (*float32, bool)`

GetValueOk returns a tuple with the Value field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetValue

`func (o *MessagePriceObject) SetValue(v float32)`

SetValue sets Value field to given value.

### HasValue

`func (o *MessagePriceObject) HasValue() bool`

HasValue returns a boolean if a field has been set.

### GetCurrency

`func (o *MessagePriceObject) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *MessagePriceObject) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *MessagePriceObject) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *MessagePriceObject) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


