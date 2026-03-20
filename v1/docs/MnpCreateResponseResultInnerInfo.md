# MnpCreateResponseResultInnerInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Country** | Pointer to **string** | Full country name in English | [optional] 
**Mcc** | Pointer to **string** | Mobile Country Code according to ITU-T E.212 | [optional] 
**Mnc** | Pointer to **string** | Mobile Network Code identifying operator | [optional] 
**Ported** | Pointer to **int32** | Number portability status: 1 &#x3D; ported, 0 &#x3D; not ported | [optional] 
**Brand** | Pointer to **string** | Commercial brand name of the mobile operator | [optional] 
**Operator** | Pointer to **string** | Full operator name with country | [optional] 

## Methods

### NewMnpCreateResponseResultInnerInfo

`func NewMnpCreateResponseResultInnerInfo() *MnpCreateResponseResultInnerInfo`

NewMnpCreateResponseResultInnerInfo instantiates a new MnpCreateResponseResultInnerInfo object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpCreateResponseResultInnerInfoWithDefaults

`func NewMnpCreateResponseResultInnerInfoWithDefaults() *MnpCreateResponseResultInnerInfo`

NewMnpCreateResponseResultInnerInfoWithDefaults instantiates a new MnpCreateResponseResultInnerInfo object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCountry

`func (o *MnpCreateResponseResultInnerInfo) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *MnpCreateResponseResultInnerInfo) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *MnpCreateResponseResultInnerInfo) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *MnpCreateResponseResultInnerInfo) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetMcc

`func (o *MnpCreateResponseResultInnerInfo) GetMcc() string`

GetMcc returns the Mcc field if non-nil, zero value otherwise.

### GetMccOk

`func (o *MnpCreateResponseResultInnerInfo) GetMccOk() (*string, bool)`

GetMccOk returns a tuple with the Mcc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMcc

`func (o *MnpCreateResponseResultInnerInfo) SetMcc(v string)`

SetMcc sets Mcc field to given value.

### HasMcc

`func (o *MnpCreateResponseResultInnerInfo) HasMcc() bool`

HasMcc returns a boolean if a field has been set.

### GetMnc

`func (o *MnpCreateResponseResultInnerInfo) GetMnc() string`

GetMnc returns the Mnc field if non-nil, zero value otherwise.

### GetMncOk

`func (o *MnpCreateResponseResultInnerInfo) GetMncOk() (*string, bool)`

GetMncOk returns a tuple with the Mnc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMnc

`func (o *MnpCreateResponseResultInnerInfo) SetMnc(v string)`

SetMnc sets Mnc field to given value.

### HasMnc

`func (o *MnpCreateResponseResultInnerInfo) HasMnc() bool`

HasMnc returns a boolean if a field has been set.

### GetPorted

`func (o *MnpCreateResponseResultInnerInfo) GetPorted() int32`

GetPorted returns the Ported field if non-nil, zero value otherwise.

### GetPortedOk

`func (o *MnpCreateResponseResultInnerInfo) GetPortedOk() (*int32, bool)`

GetPortedOk returns a tuple with the Ported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorted

`func (o *MnpCreateResponseResultInnerInfo) SetPorted(v int32)`

SetPorted sets Ported field to given value.

### HasPorted

`func (o *MnpCreateResponseResultInnerInfo) HasPorted() bool`

HasPorted returns a boolean if a field has been set.

### GetBrand

`func (o *MnpCreateResponseResultInnerInfo) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *MnpCreateResponseResultInnerInfo) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *MnpCreateResponseResultInnerInfo) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *MnpCreateResponseResultInnerInfo) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### GetOperator

`func (o *MnpCreateResponseResultInnerInfo) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *MnpCreateResponseResultInnerInfo) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *MnpCreateResponseResultInnerInfo) SetOperator(v string)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *MnpCreateResponseResultInnerInfo) HasOperator() bool`

HasOperator returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


