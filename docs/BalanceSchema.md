# BalanceSchema

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Balance** | Pointer to **float32** | Current amount of funds on the account balance | [optional] 
**Currency** | Pointer to **string** | The currency code of the account. Specified according to the ISO-4217 standard | [optional] 
**Credit** | Pointer to **float32** | Available credit limit of the account by the postpay type | [optional] 

## Methods

### NewBalanceSchema

`func NewBalanceSchema() *BalanceSchema`

NewBalanceSchema instantiates a new BalanceSchema object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewBalanceSchemaWithDefaults

`func NewBalanceSchemaWithDefaults() *BalanceSchema`

NewBalanceSchemaWithDefaults instantiates a new BalanceSchema object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetBalance

`func (o *BalanceSchema) GetBalance() float32`

GetBalance returns the Balance field if non-nil, zero value otherwise.

### GetBalanceOk

`func (o *BalanceSchema) GetBalanceOk() (*float32, bool)`

GetBalanceOk returns a tuple with the Balance field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBalance

`func (o *BalanceSchema) SetBalance(v float32)`

SetBalance sets Balance field to given value.

### HasBalance

`func (o *BalanceSchema) HasBalance() bool`

HasBalance returns a boolean if a field has been set.

### GetCurrency

`func (o *BalanceSchema) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *BalanceSchema) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *BalanceSchema) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *BalanceSchema) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetCredit

`func (o *BalanceSchema) GetCredit() float32`

GetCredit returns the Credit field if non-nil, zero value otherwise.

### GetCreditOk

`func (o *BalanceSchema) GetCreditOk() (*float32, bool)`

GetCreditOk returns a tuple with the Credit field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCredit

`func (o *BalanceSchema) SetCredit(v float32)`

SetCredit sets Credit field to given value.

### HasCredit

`func (o *BalanceSchema) HasCredit() bool`

HasCredit returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


