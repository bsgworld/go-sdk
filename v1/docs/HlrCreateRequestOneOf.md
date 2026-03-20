# HlrCreateRequestOneOf

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdn** | **string** | Phone number in international format | 
**Reference** | Pointer to **string** | External reference ID for tracking (optional for sync) | [optional] 
**Tariff** | Pointer to **int32** | Tariff code for pricing (optional, uses default if not provided) | [optional] 
**CallbackUrl** | Pointer to **string** | URL for delivery reports (optional) | [optional] 

## Methods

### NewHlrCreateRequestOneOf

`func NewHlrCreateRequestOneOf(msisdn string, ) *HlrCreateRequestOneOf`

NewHlrCreateRequestOneOf instantiates a new HlrCreateRequestOneOf object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHlrCreateRequestOneOfWithDefaults

`func NewHlrCreateRequestOneOfWithDefaults() *HlrCreateRequestOneOf`

NewHlrCreateRequestOneOfWithDefaults instantiates a new HlrCreateRequestOneOf object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdn

`func (o *HlrCreateRequestOneOf) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *HlrCreateRequestOneOf) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *HlrCreateRequestOneOf) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *HlrCreateRequestOneOf) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *HlrCreateRequestOneOf) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *HlrCreateRequestOneOf) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *HlrCreateRequestOneOf) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTariff

`func (o *HlrCreateRequestOneOf) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *HlrCreateRequestOneOf) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *HlrCreateRequestOneOf) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *HlrCreateRequestOneOf) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *HlrCreateRequestOneOf) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *HlrCreateRequestOneOf) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *HlrCreateRequestOneOf) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *HlrCreateRequestOneOf) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


