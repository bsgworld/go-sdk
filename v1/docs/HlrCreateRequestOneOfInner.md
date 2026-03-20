# HlrCreateRequestOneOfInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdn** | **string** | Phone number in international format | 
**Reference** | **string** | External reference ID for tracking | 
**Tariff** | Pointer to **int32** | Tariff code for pricing | [optional] 
**CallbackUrl** | Pointer to **string** | URL for delivery reports (optional) | [optional] 

## Methods

### NewHlrCreateRequestOneOfInner

`func NewHlrCreateRequestOneOfInner(msisdn string, reference string, ) *HlrCreateRequestOneOfInner`

NewHlrCreateRequestOneOfInner instantiates a new HlrCreateRequestOneOfInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHlrCreateRequestOneOfInnerWithDefaults

`func NewHlrCreateRequestOneOfInnerWithDefaults() *HlrCreateRequestOneOfInner`

NewHlrCreateRequestOneOfInnerWithDefaults instantiates a new HlrCreateRequestOneOfInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdn

`func (o *HlrCreateRequestOneOfInner) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *HlrCreateRequestOneOfInner) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *HlrCreateRequestOneOfInner) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.


### GetReference

`func (o *HlrCreateRequestOneOfInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *HlrCreateRequestOneOfInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *HlrCreateRequestOneOfInner) SetReference(v string)`

SetReference sets Reference field to given value.


### GetTariff

`func (o *HlrCreateRequestOneOfInner) GetTariff() int32`

GetTariff returns the Tariff field if non-nil, zero value otherwise.

### GetTariffOk

`func (o *HlrCreateRequestOneOfInner) GetTariffOk() (*int32, bool)`

GetTariffOk returns a tuple with the Tariff field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariff

`func (o *HlrCreateRequestOneOfInner) SetTariff(v int32)`

SetTariff sets Tariff field to given value.

### HasTariff

`func (o *HlrCreateRequestOneOfInner) HasTariff() bool`

HasTariff returns a boolean if a field has been set.

### GetCallbackUrl

`func (o *HlrCreateRequestOneOfInner) GetCallbackUrl() string`

GetCallbackUrl returns the CallbackUrl field if non-nil, zero value otherwise.

### GetCallbackUrlOk

`func (o *HlrCreateRequestOneOfInner) GetCallbackUrlOk() (*string, bool)`

GetCallbackUrlOk returns a tuple with the CallbackUrl field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCallbackUrl

`func (o *HlrCreateRequestOneOfInner) SetCallbackUrl(v string)`

SetCallbackUrl sets CallbackUrl field to given value.

### HasCallbackUrl

`func (o *HlrCreateRequestOneOfInner) HasCallbackUrl() bool`

HasCallbackUrl returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


