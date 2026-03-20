# HlrSyncResponseDetails

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Ported** | Pointer to **int32** | Porting status (0 &#x3D; not ported, 1 &#x3D; ported) | [optional] 
**Roaming** | Pointer to **int32** | Roaming status (0 &#x3D; not roaming, 1 &#x3D; roaming) | [optional] 
**Imsi** | Pointer to **NullableString** | IMSI prefix (MCC+MNC+partial MSIN, masked) | [optional] 

## Methods

### NewHlrSyncResponseDetails

`func NewHlrSyncResponseDetails() *HlrSyncResponseDetails`

NewHlrSyncResponseDetails instantiates a new HlrSyncResponseDetails object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHlrSyncResponseDetailsWithDefaults

`func NewHlrSyncResponseDetailsWithDefaults() *HlrSyncResponseDetails`

NewHlrSyncResponseDetailsWithDefaults instantiates a new HlrSyncResponseDetails object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetPorted

`func (o *HlrSyncResponseDetails) GetPorted() int32`

GetPorted returns the Ported field if non-nil, zero value otherwise.

### GetPortedOk

`func (o *HlrSyncResponseDetails) GetPortedOk() (*int32, bool)`

GetPortedOk returns a tuple with the Ported field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPorted

`func (o *HlrSyncResponseDetails) SetPorted(v int32)`

SetPorted sets Ported field to given value.

### HasPorted

`func (o *HlrSyncResponseDetails) HasPorted() bool`

HasPorted returns a boolean if a field has been set.

### GetRoaming

`func (o *HlrSyncResponseDetails) GetRoaming() int32`

GetRoaming returns the Roaming field if non-nil, zero value otherwise.

### GetRoamingOk

`func (o *HlrSyncResponseDetails) GetRoamingOk() (*int32, bool)`

GetRoamingOk returns a tuple with the Roaming field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetRoaming

`func (o *HlrSyncResponseDetails) SetRoaming(v int32)`

SetRoaming sets Roaming field to given value.

### HasRoaming

`func (o *HlrSyncResponseDetails) HasRoaming() bool`

HasRoaming returns a boolean if a field has been set.

### GetImsi

`func (o *HlrSyncResponseDetails) GetImsi() string`

GetImsi returns the Imsi field if non-nil, zero value otherwise.

### GetImsiOk

`func (o *HlrSyncResponseDetails) GetImsiOk() (*string, bool)`

GetImsiOk returns a tuple with the Imsi field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetImsi

`func (o *HlrSyncResponseDetails) SetImsi(v string)`

SetImsi sets Imsi field to given value.

### HasImsi

`func (o *HlrSyncResponseDetails) HasImsi() bool`

HasImsi returns a boolean if a field has been set.

### SetImsiNil

`func (o *HlrSyncResponseDetails) SetImsiNil(b bool)`

 SetImsiNil sets the value for Imsi to be an explicit nil

### UnsetImsi
`func (o *HlrSyncResponseDetails) UnsetImsi()`

UnsetImsi ensures that no value is present for Imsi, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


