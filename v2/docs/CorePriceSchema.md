# CorePriceSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Tariff** | Pointer to **int32** |  | [optional] 
**LimitationInfo** | Pointer to **NullableString** |  | [optional] 
**CountryId** | Pointer to **string** |  | [optional] 
**Operators** | Pointer to [**[]OperatorSchema**](OperatorSchema.md) |  | [optional] 

## Methods

### NewCorePriceSchema

`func NewCorePriceSchema() *CorePriceSchema`

NewCorePriceSchema instantiates a new CorePriceSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCorePriceSchemaWithDefaults

`func NewCorePriceSchemaWithDefaults() *CorePriceSchema`

NewCorePriceSchemaWithDefaults instantiates a new CorePriceSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetTariff

`func (o *CorePriceSchema) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *CorePriceSchema) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *CorePriceSchema) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *CorePriceSchema) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetLimitationInfo

`func (o *CorePriceSchema) GetLimitationInfo() string`

GetLimitationInfo returns the LimitationInfo field if non-nil, zero value otherwise.

### GetLimitationInfoOk

`func (o *CorePriceSchema) GetLimitationInfoOk() (*string, bool)`

GetLimitationInfoOk returns a tuple with the LimitationInfo field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetLimitationInfo

`func (o *CorePriceSchema) SetLimitationInfo(v string)`

SetLimitationInfo sets LimitationInfo field to given value.

### HasLimitationInfo

`func (o *CorePriceSchema) HasLimitationInfo() bool`

HasLimitationInfo returns a boolean if a field has been set.

### SetLimitationInfoNil

`func (o *CorePriceSchema) SetLimitationInfoNil(b bool)`

 SetLimitationInfoNil sets the value for LimitationInfo to be an explicit nil

### UnsetLimitationInfo
`func (o *CorePriceSchema) UnsetLimitationInfo()`

UnsetLimitationInfo ensures that no value is present for LimitationInfo, not even an explicit nil
### GetCountryId

`func (o *CorePriceSchema) GetCountryId() string`

GetCountryId returns the CountryId field if non-nil, zero value otherwise.

### GetCountryIdOk

`func (o *CorePriceSchema) GetCountryIdOk() (*string, bool)`

GetCountryIdOk returns a tuple with the CountryId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryId

`func (o *CorePriceSchema) SetCountryId(v string)`

SetCountryId sets CountryId field to given value.

### HasCountryId

`func (o *CorePriceSchema) HasCountryId() bool`

HasCountryId returns a boolean if a field has been set.

### GetOperators

`func (o *CorePriceSchema) GetOperators() []OperatorSchema`

GetOperators returns the Operators field if non-nil, zero value otherwise.

### GetOperatorsOk

`func (o *CorePriceSchema) GetOperatorsOk() (*[]OperatorSchema, bool)`

GetOperatorsOk returns a tuple with the Operators field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperators

`func (o *CorePriceSchema) SetOperators(v []OperatorSchema)`

SetOperators sets Operators field to given value.

### HasOperators

`func (o *CorePriceSchema) HasOperators() bool`

HasOperators returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


