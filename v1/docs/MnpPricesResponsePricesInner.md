# MnpPricesResponsePricesInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Type** | **string** | Service type (always \&quot;mnp\&quot; for this API) | 
**Country** | **string** | ISO 3166-1 alpha-2 country code | 
**CountryName** | **string** | Full country name in English | 
**Mcc** | **string** | Mobile Country Code (ITU-T E.212) | 
**Mnc** | **string** | Mobile Network Code (0 &#x3D; all operators) | 
**Price** | **string** | Price per MNP lookup with 7 decimal precision | 
**Currency** | **string** | Currency code (ISO 4217) | 

## Methods

### NewMnpPricesResponsePricesInner

`func NewMnpPricesResponsePricesInner(type_ string, country string, countryName string, mcc string, mnc string, price string, currency string, ) *MnpPricesResponsePricesInner`

NewMnpPricesResponsePricesInner instantiates a new MnpPricesResponsePricesInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpPricesResponsePricesInnerWithDefaults

`func NewMnpPricesResponsePricesInnerWithDefaults() *MnpPricesResponsePricesInner`

NewMnpPricesResponsePricesInnerWithDefaults instantiates a new MnpPricesResponsePricesInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetType

`func (o *MnpPricesResponsePricesInner) GetType() string`

GetType returns the Type field if non-nil, zero value otherwise.

### GetTypeOk

`func (o *MnpPricesResponsePricesInner) GetTypeOk() (*string, bool)`

GetTypeOk returns a tuple with the Type field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetType

`func (o *MnpPricesResponsePricesInner) SetType(v string)`

SetType sets Type field to given value.


### GetCountry

`func (o *MnpPricesResponsePricesInner) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *MnpPricesResponsePricesInner) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *MnpPricesResponsePricesInner) SetCountry(v string)`

SetCountry sets Country field to given value.


### GetCountryName

`func (o *MnpPricesResponsePricesInner) GetCountryName() string`

GetCountryName returns the CountryName field if non-nil, zero value otherwise.

### GetCountryNameOk

`func (o *MnpPricesResponsePricesInner) GetCountryNameOk() (*string, bool)`

GetCountryNameOk returns a tuple with the CountryName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryName

`func (o *MnpPricesResponsePricesInner) SetCountryName(v string)`

SetCountryName sets CountryName field to given value.


### GetMcc

`func (o *MnpPricesResponsePricesInner) GetMcc() string`

GetMcc returns the Mcc field if non-nil, zero value otherwise.

### GetMccOk

`func (o *MnpPricesResponsePricesInner) GetMccOk() (*string, bool)`

GetMccOk returns a tuple with the Mcc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMcc

`func (o *MnpPricesResponsePricesInner) SetMcc(v string)`

SetMcc sets Mcc field to given value.


### GetMnc

`func (o *MnpPricesResponsePricesInner) GetMnc() string`

GetMnc returns the Mnc field if non-nil, zero value otherwise.

### GetMncOk

`func (o *MnpPricesResponsePricesInner) GetMncOk() (*string, bool)`

GetMncOk returns a tuple with the Mnc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMnc

`func (o *MnpPricesResponsePricesInner) SetMnc(v string)`

SetMnc sets Mnc field to given value.


### GetPrice

`func (o *MnpPricesResponsePricesInner) GetPrice() string`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *MnpPricesResponsePricesInner) GetPriceOk() (*string, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *MnpPricesResponsePricesInner) SetPrice(v string)`

SetPrice sets Price field to given value.


### GetCurrency

`func (o *MnpPricesResponsePricesInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *MnpPricesResponsePricesInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *MnpPricesResponsePricesInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


