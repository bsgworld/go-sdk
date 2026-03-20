# MnpStatusResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success, 80 &#x3D; not found) | 
**ErrorDescription** | **string** | Human-readable error description | 
**Country** | Pointer to **string** | Full country name in English | [optional] 
**Brand** | Pointer to **string** | Mobile operator brand name | [optional] 
**Operator** | Pointer to **string** | Full operator name with country | [optional] 
**Mcc** | Pointer to **string** | Mobile Country Code (ITU-T E.212) | [optional] 
**Mnc** | Pointer to **string** | Mobile Network Code identifying operator | [optional] 
**Ported** | Pointer to **int32** | Number portability status (0 &#x3D; not ported, 1 &#x3D; ported) | [optional] 
**Reference** | Pointer to **string** | External reference ID for tracking | [optional] 

## Methods

### NewMnpStatusResponse

`func NewMnpStatusResponse(error_ int32, errorDescription string, ) *MnpStatusResponse`

NewMnpStatusResponse instantiates a new MnpStatusResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpStatusResponseWithDefaults

`func NewMnpStatusResponseWithDefaults() *MnpStatusResponse`

NewMnpStatusResponseWithDefaults instantiates a new MnpStatusResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *MnpStatusResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MnpStatusResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MnpStatusResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *MnpStatusResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *MnpStatusResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *MnpStatusResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetCountry

`func (o *MnpStatusResponse) GetCountry() string`

GetCountry returns the Country field if non-nil, zero value otherwise.

### GetCountryOk

`func (o *MnpStatusResponse) GetCountryOk() (*string, bool)`

GetCountryOk returns a tuple with the Country field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountry

`func (o *MnpStatusResponse) SetCountry(v string)`

SetCountry sets Country field to given value.

### HasCountry

`func (o *MnpStatusResponse) HasCountry() bool`

HasCountry returns a boolean if a field has been set.

### GetBrand

`func (o *MnpStatusResponse) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *MnpStatusResponse) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *MnpStatusResponse) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *MnpStatusResponse) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### GetOperator

`func (o *MnpStatusResponse) GetOperator() string`

GetOperator returns the Operator field if non-nil, zero value otherwise.

### GetOperatorOk

`func (o *MnpStatusResponse) GetOperatorOk() (*string, bool)`

GetOperatorOk returns a tuple with the Operator field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetOperator

`func (o *MnpStatusResponse) SetOperator(v string)`

SetOperator sets Operator field to given value.

### HasOperator

`func (o *MnpStatusResponse) HasOperator() bool`

HasOperator returns a boolean if a field has been set.

### GetMcc

`func (o *MnpStatusResponse) GetMcc() string`

GetMcc returns the Mcc field if non-nil, zero value otherwise.

### GetMccOk

`func (o *MnpStatusResponse) GetMccOk() (*string, bool)`

GetMccOk returns a tuple with the Mcc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMcc

`func (o *MnpStatusResponse) SetMcc(v string)`

SetMcc sets Mcc field to given value.

### HasMcc

`func (o *MnpStatusResponse) HasMcc() bool`

HasMcc returns a boolean if a field has been set.

### GetMnc

`func (o *MnpStatusResponse) GetMnc() string`

GetMnc returns the Mnc field if non-nil, zero value otherwise.

### GetMncOk

`func (o *MnpStatusResponse) GetMncOk() (*string, bool)`

GetMncOk returns a tuple with the Mnc field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMnc

`func (o *MnpStatusResponse) SetMnc(v string)`

SetMnc sets Mnc field to given value.

### HasMnc

`func (o *MnpStatusResponse) HasMnc() bool`

HasMnc returns a boolean if a field has been set.

### GetPorted

`func (o *MnpStatusResponse) GetPorted() int32`

GetPorted returns the Ported field if non-nil, zero value otherwise.

### GetPortedOk

`func (o *MnpStatusResponse) GetPortedOk() (*int32, bool)`

GetPortedOk returns a tuple with the Ported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorted

`func (o *MnpStatusResponse) SetPorted(v int32)`

SetPorted sets Ported field to given value.

### HasPorted

`func (o *MnpStatusResponse) HasPorted() bool`

HasPorted returns a boolean if a field has been set.

### GetReference

`func (o *MnpStatusResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *MnpStatusResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *MnpStatusResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *MnpStatusResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


