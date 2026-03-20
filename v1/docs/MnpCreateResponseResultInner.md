# MnpCreateResponseResultInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **int32** | Error code: 0 for success, 80-86 for MNP-specific errors | [optional] 
**ErrorDescription** | Pointer to **string** | Human-readable error description | [optional] 
**Msisdn** | Pointer to **string** | Phone number for MNP lookup in international format | [optional] 
**TariffCode** | Pointer to **string** | Service tariff code used for pricing | [optional] 
**Price** | Pointer to **float32** | Price for MNP lookup request | [optional] 
**Currency** | Pointer to **string** | Currency code according to ISO-4217 standard | [optional] 
**Info** | Pointer to [**MnpCreateResponseResultInnerInfo**](MnpCreateResponseResultInnerInfo.md) |  | [optional] 

## Methods

### NewMnpCreateResponseResultInner

`func NewMnpCreateResponseResultInner() *MnpCreateResponseResultInner`

NewMnpCreateResponseResultInner instantiates a new MnpCreateResponseResultInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpCreateResponseResultInnerWithDefaults

`func NewMnpCreateResponseResultInnerWithDefaults() *MnpCreateResponseResultInner`

NewMnpCreateResponseResultInnerWithDefaults instantiates a new MnpCreateResponseResultInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *MnpCreateResponseResultInner) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MnpCreateResponseResultInner) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MnpCreateResponseResultInner) SetError(v int32)`

SetError sets Error field to given value.

### HasError

`func (o *MnpCreateResponseResultInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorDescription

`func (o *MnpCreateResponseResultInner) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *MnpCreateResponseResultInner) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *MnpCreateResponseResultInner) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.

### HasErrorDescription

`func (o *MnpCreateResponseResultInner) HasErrorDescription() bool`

HasErrorDescription returns a boolean if a field has been set.

### GetMsisdn

`func (o *MnpCreateResponseResultInner) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *MnpCreateResponseResultInner) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *MnpCreateResponseResultInner) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *MnpCreateResponseResultInner) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetTariffCode

`func (o *MnpCreateResponseResultInner) GetTariffCode() string`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *MnpCreateResponseResultInner) GetTariffCodeOk() (*string, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *MnpCreateResponseResultInner) SetTariffCode(v string)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *MnpCreateResponseResultInner) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.

### GetPrice

`func (o *MnpCreateResponseResultInner) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *MnpCreateResponseResultInner) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *MnpCreateResponseResultInner) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *MnpCreateResponseResultInner) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *MnpCreateResponseResultInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *MnpCreateResponseResultInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *MnpCreateResponseResultInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *MnpCreateResponseResultInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.

### GetInfo

`func (o *MnpCreateResponseResultInner) GetInfo() MnpCreateResponseResultInnerInfo`

GetInfo returns the Info field if non-nil, zero value otherwise.

### GetInfoOk

`func (o *MnpCreateResponseResultInner) GetInfoOk() (*MnpCreateResponseResultInnerInfo, bool)`

GetInfoOk returns a tuple with the Info field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetInfo

`func (o *MnpCreateResponseResultInner) SetInfo(v MnpCreateResponseResultInnerInfo)`

SetInfo sets Info field to given value.

### HasInfo

`func (o *MnpCreateResponseResultInner) HasInfo() bool`

HasInfo returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


