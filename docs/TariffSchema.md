# TariffSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **float32** | Tariff id | [optional] 
**Name** | Pointer to **string** | Tariff name | [optional] 
**Code** | Pointer to **int32** | Tariff code null by default. Your can pass specified one if you have several. For more information please visit the [account prices](https://app.bsg.world/prices/sms) | [optional] 
**IsActive** | Pointer to **bool** | Indicates whether the tariff is active | [optional] 
**IsDefault** | Pointer to **bool** | Indicates whether the rate is the default | [optional] 

## Methods

### NewTariffSchema

`func NewTariffSchema() *TariffSchema`

NewTariffSchema instantiates a new TariffSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewTariffSchemaWithDefaults

`func NewTariffSchemaWithDefaults() *TariffSchema`

NewTariffSchemaWithDefaults instantiates a new TariffSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *TariffSchema) GetId() float32`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *TariffSchema) GetIdOk() (*float32, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *TariffSchema) SetId(v float32)`

SetId sets Id field to given value.

### HasId

`func (o *TariffSchema) HasId() bool`

HasId returns a boolean if a field has been set.

### GetName

`func (o *TariffSchema) GetName() string`

GetName returns the Name field if non-nil, zero value otherwise.

### GetNameOk

`func (o *TariffSchema) GetNameOk() (*string, bool)`

GetNameOk returns a tuple with the Name field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetName

`func (o *TariffSchema) SetName(v string)`

SetName sets Name field to given value.

### HasName

`func (o *TariffSchema) HasName() bool`

HasName returns a boolean if a field has been set.

### GetCode

`func (o *TariffSchema) GetCode() int32`

GetCode returns the Code field if non-nil, zero value otherwise.

### GetCodeOk

`func (o *TariffSchema) GetCodeOk() (*int32, bool)`

GetCodeOk returns a tuple with the Code field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCode

`func (o *TariffSchema) SetCode(v int32)`

SetCode sets Code field to given value.

### HasCode

`func (o *TariffSchema) HasCode() bool`

HasCode returns a boolean if a field has been set.

### GetIsActive

`func (o *TariffSchema) GetIsActive() bool`

GetIsActive returns the IsActive field if non-nil, zero value otherwise.

### GetIsActiveOk

`func (o *TariffSchema) GetIsActiveOk() (*bool, bool)`

GetIsActiveOk returns a tuple with the IsActive field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsActive

`func (o *TariffSchema) SetIsActive(v bool)`

SetIsActive sets IsActive field to given value.

### HasIsActive

`func (o *TariffSchema) HasIsActive() bool`

HasIsActive returns a boolean if a field has been set.

### GetIsDefault

`func (o *TariffSchema) GetIsDefault() bool`

GetIsDefault returns the IsDefault field if non-nil, zero value otherwise.

### GetIsDefaultOk

`func (o *TariffSchema) GetIsDefaultOk() (*bool, bool)`

GetIsDefaultOk returns a tuple with the IsDefault field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetIsDefault

`func (o *TariffSchema) SetIsDefault(v bool)`

SetIsDefault sets IsDefault field to given value.

### HasIsDefault

`func (o *TariffSchema) HasIsDefault() bool`

HasIsDefault returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


