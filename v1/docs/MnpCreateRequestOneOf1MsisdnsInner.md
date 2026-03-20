# MnpCreateRequestOneOf1MsisdnsInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdn** | **string** | Phone number in international format for MNP lookup | 
**Tariff** | Pointer to **int32** | Tariff code for pricing (optional, uses user default if not provided) | [optional] 
**Reference** | Pointer to **string** | External reference ID for tracking (optional) | [optional] 

## Methods

### NewMnpCreateRequestOneOf1MsisdnsInner

`func NewMnpCreateRequestOneOf1MsisdnsInner(msisdn string, ) *MnpCreateRequestOneOf1MsisdnsInner`

NewMnpCreateRequestOneOf1MsisdnsInner instantiates a new MnpCreateRequestOneOf1MsisdnsInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpCreateRequestOneOf1MsisdnsInnerWithDefaults

`func NewMnpCreateRequestOneOf1MsisdnsInnerWithDefaults() *MnpCreateRequestOneOf1MsisdnsInner`

NewMnpCreateRequestOneOf1MsisdnsInnerWithDefaults instantiates a new MnpCreateRequestOneOf1MsisdnsInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdn

`func (o *MnpCreateRequestOneOf1MsisdnsInner) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *MnpCreateRequestOneOf1MsisdnsInner) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *MnpCreateRequestOneOf1MsisdnsInner) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetTariff

`func (o *MnpCreateRequestOneOf1MsisdnsInner) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *MnpCreateRequestOneOf1MsisdnsInner) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *MnpCreateRequestOneOf1MsisdnsInner) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *MnpCreateRequestOneOf1MsisdnsInner) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetReference

`func (o *MnpCreateRequestOneOf1MsisdnsInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *MnpCreateRequestOneOf1MsisdnsInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *MnpCreateRequestOneOf1MsisdnsInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *MnpCreateRequestOneOf1MsisdnsInner) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


