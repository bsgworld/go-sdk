# CurrencyItem

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | Pointer to **string** |  | [optional] 
**Ratio** | Pointer to **float32** | EUR exchange rate | [optional] 
**Nominal** | Pointer to **int32** |  | [optional] 
**Date** | Pointer to **interface{}** |  | [optional] 

## Methods

### NewCurrencyItem

`func NewCurrencyItem() *CurrencyItem`

NewCurrencyItem instantiates a new CurrencyItem object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCurrencyItemWithDefaults

`func NewCurrencyItemWithDefaults() *CurrencyItem`

NewCurrencyItemWithDefaults instantiates a new CurrencyItem object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetId

`func (o *CurrencyItem) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *CurrencyItem) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *CurrencyItem) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *CurrencyItem) HasId() bool`

HasId returns a boolean if a field has been set.

### GetRatio

`func (o *CurrencyItem) GetRatio() float32`

GetRatio returns the Ratio field if non-nil, zero value otherwise.

### GetRatioOk

`func (o *CurrencyItem) GetRatioOk() (*float32, bool)`

GetRatioOk returns a tuple with the Ratio field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRatio

`func (o *CurrencyItem) SetRatio(v float32)`

SetRatio sets Ratio field to given value.

### HasRatio

`func (o *CurrencyItem) HasRatio() bool`

HasRatio returns a boolean if a field has been set.

### GetNominal

`func (o *CurrencyItem) GetNominal() int32`

GetNominal returns the Nominal field if non-nil, zero value otherwise.

### GetNominalOk

`func (o *CurrencyItem) GetNominalOk() (*int32, bool)`

GetNominalOk returns a tuple with the Nominal field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNominal

`func (o *CurrencyItem) SetNominal(v int32)`

SetNominal sets Nominal field to given value.

### HasNominal

`func (o *CurrencyItem) HasNominal() bool`

HasNominal returns a boolean if a field has been set.

### GetDate

`func (o *CurrencyItem) GetDate() interface{}`

GetDate returns the Date field if non-nil, zero value otherwise.

### GetDateOk

`func (o *CurrencyItem) GetDateOk() (*interface{}, bool)`

GetDateOk returns a tuple with the Date field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDate

`func (o *CurrencyItem) SetDate(v interface{})`

SetDate sets Date field to given value.

### HasDate

`func (o *CurrencyItem) HasDate() bool`

HasDate returns a boolean if a field has been set.

### SetDateNil

`func (o *CurrencyItem) SetDateNil(b bool)`

 SetDateNil sets the value for Date to be an explicit nil

### UnsetDate
`func (o *CurrencyItem) UnsetDate()`

UnsetDate ensures that no value is present for Date, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


