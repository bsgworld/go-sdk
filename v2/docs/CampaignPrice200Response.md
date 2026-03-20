# CampaignPrice200Response

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Price** | Pointer to **NullableFloat32** | estimate campaign cost  **Please note:** price defined only as the response to create campaign or calculate price requests | [optional] 
**Currency** | Pointer to **string** | The currency code of the account. Specified according to the ISO-4217 standard | [optional] 

## Methods

### NewCampaignPrice200Response

`func NewCampaignPrice200Response() *CampaignPrice200Response`

NewCampaignPrice200Response instantiates a new CampaignPrice200Response object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewCampaignPrice200ResponseWithDefaults

`func NewCampaignPrice200ResponseWithDefaults() *CampaignPrice200Response`

NewCampaignPrice200ResponseWithDefaults instantiates a new CampaignPrice200Response object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPrice

`func (o *CampaignPrice200Response) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *CampaignPrice200Response) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *CampaignPrice200Response) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *CampaignPrice200Response) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### SetPriceNil

`func (o *CampaignPrice200Response) SetPriceNil(b bool)`

 SetPriceNil sets the value for Price to be an explicit nil

### UnsetPrice
`func (o *CampaignPrice200Response) UnsetPrice()`

UnsetPrice ensures that no value is present for Price, not even an explicit nil
### GetCurrency

`func (o *CampaignPrice200Response) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *CampaignPrice200Response) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *CampaignPrice200Response) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *CampaignPrice200Response) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


