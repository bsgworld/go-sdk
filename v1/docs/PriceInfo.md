# PriceInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** |  | 
**Country** | **string** | ISO 3166-1 alpha-2 country code | 
**CountryName** | **string** | Full country name in English | 
**Mcc** | **string** | Mobile Country Code according to ITU-T E.212 | 
**Mnc** | **string** | Mobile Network Code. \&quot;0\&quot; represents all networks | 
**Price** | **string** | SMS price per message with high precision decimal | 
**Currency** | **string** | Currency code according to ISO-4217 | 

## Methods

### NewPriceInfo

`func NewPriceInfo(type_ string, country string, countryName string, mcc string, mnc string, price string, currency string, ) *PriceInfo`

NewPriceInfo instantiates a new PriceInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewPriceInfoWithDefaults

`func NewPriceInfoWithDefaults() *PriceInfo`

NewPriceInfoWithDefaults instantiates a new PriceInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *PriceInfo) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *PriceInfo) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *PriceInfo) SetType(v string)`

SetType sets Type field to given value.


### GetCountry

`func (o *PriceInfo) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *PriceInfo) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *PriceInfo) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetCountryName

`func (o *PriceInfo) GetCountryName() string`

GetCountryName returns the CountryName field if non-nil, zero value otherwise.

### GetCountryNameOk

`func (o *PriceInfo) GetCountryNameOk() (*string, bool)`

GetCountryNameOk returns a tuple with the CountryName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryName

`func (o *PriceInfo) SetCountryName(v string)`

SetCountryName sets CountryName field to given value.


### GetMcc

`func (o *PriceInfo) GetMcc() string`

GetMcc returns the Mcc field if non-nil, zero value otherwise.

### GetMccOk

`func (o *PriceInfo) GetMccOk() (*string, bool)`

GetMccOk returns a tuple with the Mcc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMcc

`func (o *PriceInfo) SetMcc(v string)`

SetMcc sets Mcc field to given value.


### GetMnc

`func (o *PriceInfo) GetMnc() string`

GetMnc returns the Mnc field if non-nil, zero value otherwise.

### GetMncOk

`func (o *PriceInfo) GetMncOk() (*string, bool)`

GetMncOk returns a tuple with the Mnc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMnc

`func (o *PriceInfo) SetMnc(v string)`

SetMnc sets Mnc field to given value.


### GetPrice

`func (o *PriceInfo) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *PriceInfo) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *PriceInfo) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *PriceInfo) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *PriceInfo) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *PriceInfo) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


