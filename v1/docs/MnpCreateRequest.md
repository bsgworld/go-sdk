# MnpCreateRequest

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdn** | **string** | Phone number in international format for MNP lookup | 
**Reference** | Pointer to **string** | Global reference ID for the entire batch | [optional] 
**Tariff** | Pointer to **int32** | Tariff code for pricing (optional, uses user default if not provided) | [optional] 
**CallbackUrl** | Pointer to **string** | URL for delivery reports (optional) | [optional] 
**Msisdns** | [**[]MnpCreateRequestOneOf1MsisdnsInner**](MnpCreateRequestOneOf1MsisdnsInner.md) | Array of phone numbers for MNP lookup | 

## Methods

### NewMnpCreateRequest

`func NewMnpCreateRequest(msisdn string, msisdns []MnpCreateRequestOneOf1MsisdnsInner, ) *MnpCreateRequest`

NewMnpCreateRequest instantiates a new MnpCreateRequest object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpCreateRequestWithDefaults

`func NewMnpCreateRequestWithDefaults() *MnpCreateRequest`

NewMnpCreateRequestWithDefaults instantiates a new MnpCreateRequest object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdn

`func (o *MnpCreateRequest) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *MnpCreateRequest) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *MnpCreateRequest) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *MnpCreateRequest) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *MnpCreateRequest) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *MnpCreateRequest) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *MnpCreateRequest) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTariff

`func (o *MnpCreateRequest) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *MnpCreateRequest) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *MnpCreateRequest) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *MnpCreateRequest) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *MnpCreateRequest) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *MnpCreateRequest) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *MnpCreateRequest) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *MnpCreateRequest) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.

### GetMsisdns

`func (o *MnpCreateRequest) GetMsisdns() []MnpCreateRequestOneOf1MsisdnsInner`

GetMsisdns returns the Msisdns field if non-nil, zero value otherwise.

### GetMsisdnsOk

`func (o *MnpCreateRequest) GetMsisdnsOk() (*[]MnpCreateRequestOneOf1MsisdnsInner, bool)`

GetMsisdnsOk returns a tuple with the Msisdns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdns

`func (o *MnpCreateRequest) SetMsisdns(v []MnpCreateRequestOneOf1MsisdnsInner)`

SetMsisdns sets Msisdns field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


