# HlrCreateResponseResultInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | Pointer to **int32** | Error code (0 &#x3D; success) | [optional] 
**ErrorDescription** | Pointer to **string** | Error description | [optional] 
**Msisdn** | Pointer to **string** | Phone number in international format | [optional] 
**Reference** | Pointer to **string** | External reference ID for tracking | [optional] 
**TariffCode** | Pointer to **int32** | Applied tariff code | [optional] 

## Methods

### NewHlrCreateResponseResultInner

`func NewHlrCreateResponseResultInner() *HlrCreateResponseResultInner`

NewHlrCreateResponseResultInner instantiates a new HlrCreateResponseResultInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHlrCreateResponseResultInnerWithDefaults

`func NewHlrCreateResponseResultInnerWithDefaults() *HlrCreateResponseResultInner`

NewHlrCreateResponseResultInnerWithDefaults instantiates a new HlrCreateResponseResultInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *HlrCreateResponseResultInner) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *HlrCreateResponseResultInner) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *HlrCreateResponseResultInner) SetError(v int32)`

SetError sets Error field to given value.

### HasError

`func (o *HlrCreateResponseResultInner) HasError() bool`

HasError returns a boolean if a field has been set.

### GetErrorDescription

`func (o *HlrCreateResponseResultInner) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *HlrCreateResponseResultInner) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *HlrCreateResponseResultInner) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.

### HasErrorDescription

`func (o *HlrCreateResponseResultInner) HasErrorDescription() bool`

HasErrorDescription returns a boolean if a field has been set.

### GetMsisdn

`func (o *HlrCreateResponseResultInner) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *HlrCreateResponseResultInner) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *HlrCreateResponseResultInner) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *HlrCreateResponseResultInner) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetReference

`func (o *HlrCreateResponseResultInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *HlrCreateResponseResultInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *HlrCreateResponseResultInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *HlrCreateResponseResultInner) HasReference() bool`

HasReference returns a boolean if a field has been set.

### GetTariffCode

`func (o *HlrCreateResponseResultInner) GetTariffCode() int32`

GetTariffCode returns the TariffCode field if non-nil, zero value otherwise.

### GetTariffCodeOk

`func (o *HlrCreateResponseResultInner) GetTariffCodeOk() (*int32, bool)`

GetTariffCodeOk returns a tuple with the TariffCode field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTariffCode

`func (o *HlrCreateResponseResultInner) SetTariffCode(v int32)`

SetTariffCode sets TariffCode field to given value.

### HasTariffCode

`func (o *HlrCreateResponseResultInner) HasTariffCode() bool`

HasTariffCode returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


