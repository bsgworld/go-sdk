# AccountTariffs200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Data** | Pointer to [**[]TariffSchema**](TariffSchema.md) |  | [optional] 
**Total** | Pointer to **int32** | Total items count at all of the pages | [optional] 

## Methods

### NewAccountTariffs200Response

`func NewAccountTariffs200Response() *AccountTariffs200Response`

NewAccountTariffs200Response instantiates a new AccountTariffs200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAccountTariffs200ResponseWithDefaults

`func NewAccountTariffs200ResponseWithDefaults() *AccountTariffs200Response`

NewAccountTariffs200ResponseWithDefaults instantiates a new AccountTariffs200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetData

`func (o *AccountTariffs200Response) GetData() []TariffSchema`

GetData returns the Data field if non-nil, zero value otherwise.

### GetDataOk

`func (o *AccountTariffs200Response) GetDataOk() (*[]TariffSchema, bool)`

GetDataOk returns a tuple with the Data field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetData

`func (o *AccountTariffs200Response) SetData(v []TariffSchema)`

SetData sets Data field to given value.

### HasData

`func (o *AccountTariffs200Response) HasData() bool`

HasData returns a boolean if a field has been set.

### GetTotal

`func (o *AccountTariffs200Response) GetTotal() int32`

GetTotal returns the Total field if non-nil, zero value otherwise.

### GetTotalOk

`func (o *AccountTariffs200Response) GetTotalOk() (*int32, bool)`

GetTotalOk returns a tuple with the Total field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTotal

`func (o *AccountTariffs200Response) SetTotal(v int32)`

SetTotal sets Total field to given value.

### HasTotal

`func (o *AccountTariffs200Response) HasTotal() bool`

HasTotal returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


