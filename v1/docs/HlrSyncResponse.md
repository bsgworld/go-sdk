# HlrSyncResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | **string** | Error description | 
**Id** | Pointer to **string** | Internal HLR message ID | [optional] 
**Msisdn** | Pointer to **string** | Phone number in international format | [optional] 
**Reference** | Pointer to **NullableString** | External reference ID (if provided) | [optional] 
**CountryName** | Pointer to **string** | Country name in English | [optional] 
**Brand** | Pointer to **string** | Mobile operator brand | [optional] 
**BrandName** | Pointer to **string** | Full mobile operator name | [optional] 
**Network** | Pointer to **NullableString** | Network name | [optional] 
**Status** | Pointer to **string** | HLR lookup status | [optional] 
**Details** | Pointer to [**NullableHlrSyncResponseDetails**](HlrSyncResponseDetails.md) |  | [optional] 
**CreatedDatetime** | Pointer to **NullableTime** | HLR request creation timestamp | [optional] 
**StatusDatetime** | Pointer to **NullableTime** | HLR status update timestamp | [optional] 

## Methods

### NewHlrSyncResponse

`func NewHlrSyncResponse(error_ int32, errorDescription string, ) *HlrSyncResponse`

NewHlrSyncResponse instantiates a new HlrSyncResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHlrSyncResponseWithDefaults

`func NewHlrSyncResponseWithDefaults() *HlrSyncResponse`

NewHlrSyncResponseWithDefaults instantiates a new HlrSyncResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *HlrSyncResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *HlrSyncResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *HlrSyncResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *HlrSyncResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *HlrSyncResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *HlrSyncResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetId

`func (o *HlrSyncResponse) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *HlrSyncResponse) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *HlrSyncResponse) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *HlrSyncResponse) HasId() bool`

HasId returns a boolean if a field has been set.

### GetMsisdn

`func (o *HlrSyncResponse) GetMsisdn() string`

GetMsisdn returns the Msisdn field if non-nil, zero value otherwise.

### GetMsisdnOk

`func (o *HlrSyncResponse) GetMsisdnOk() (*string, bool)`

GetMsisdnOk returns a tuple with the Msisdn field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdn

`func (o *HlrSyncResponse) SetMsisdn(v string)`

SetMsisdn sets Msisdn field to given value.

### HasMsisdn

`func (o *HlrSyncResponse) HasMsisdn() bool`

HasMsisdn returns a boolean if a field has been set.

### GetReference

`func (o *HlrSyncResponse) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *HlrSyncResponse) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *HlrSyncResponse) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *HlrSyncResponse) HasReference() bool`

HasReference returns a boolean if a field has been set.

### SetReferenceNil

`func (o *HlrSyncResponse) SetReferenceNil(b bool)`

 SetReferenceNil sets the value for Reference to be an explicit nil

### UnsetReference
`func (o *HlrSyncResponse) UnsetReference()`

UnsetReference ensures that no value is present for Reference, not even an explicit nil
### GetCountryName

`func (o *HlrSyncResponse) GetCountryName() string`

GetCountryName returns the CountryName field if non-nil, zero value otherwise.

### GetCountryNameOk

`func (o *HlrSyncResponse) GetCountryNameOk() (*string, bool)`

GetCountryNameOk returns a tuple with the CountryName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCountryName

`func (o *HlrSyncResponse) SetCountryName(v string)`

SetCountryName sets CountryName field to given value.

### HasCountryName

`func (o *HlrSyncResponse) HasCountryName() bool`

HasCountryName returns a boolean if a field has been set.

### GetBrand

`func (o *HlrSyncResponse) GetBrand() string`

GetBrand returns the Brand field if non-nil, zero value otherwise.

### GetBrandOk

`func (o *HlrSyncResponse) GetBrandOk() (*string, bool)`

GetBrandOk returns a tuple with the Brand field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrand

`func (o *HlrSyncResponse) SetBrand(v string)`

SetBrand sets Brand field to given value.

### HasBrand

`func (o *HlrSyncResponse) HasBrand() bool`

HasBrand returns a boolean if a field has been set.

### GetBrandName

`func (o *HlrSyncResponse) GetBrandName() string`

GetBrandName returns the BrandName field if non-nil, zero value otherwise.

### GetBrandNameOk

`func (o *HlrSyncResponse) GetBrandNameOk() (*string, bool)`

GetBrandNameOk returns a tuple with the BrandName field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetBrandName

`func (o *HlrSyncResponse) SetBrandName(v string)`

SetBrandName sets BrandName field to given value.

### HasBrandName

`func (o *HlrSyncResponse) HasBrandName() bool`

HasBrandName returns a boolean if a field has been set.

### GetNetwork

`func (o *HlrSyncResponse) GetNetwork() string`

GetNetwork returns the Network field if non-nil, zero value otherwise.

### GetNetworkOk

`func (o *HlrSyncResponse) GetNetworkOk() (*string, bool)`

GetNetworkOk returns a tuple with the Network field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetNetwork

`func (o *HlrSyncResponse) SetNetwork(v string)`

SetNetwork sets Network field to given value.

### HasNetwork

`func (o *HlrSyncResponse) HasNetwork() bool`

HasNetwork returns a boolean if a field has been set.

### SetNetworkNil

`func (o *HlrSyncResponse) SetNetworkNil(b bool)`

 SetNetworkNil sets the value for Network to be an explicit nil

### UnsetNetwork
`func (o *HlrSyncResponse) UnsetNetwork()`

UnsetNetwork ensures that no value is present for Network, not even an explicit nil
### GetStatus

`func (o *HlrSyncResponse) GetStatus() string`

GetStatus returns the Status field if non-nil, zero value otherwise.

### GetStatusOk

`func (o *HlrSyncResponse) GetStatusOk() (*string, bool)`

GetStatusOk returns a tuple with the Status field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatus

`func (o *HlrSyncResponse) SetStatus(v string)`

SetStatus sets Status field to given value.

### HasStatus

`func (o *HlrSyncResponse) HasStatus() bool`

HasStatus returns a boolean if a field has been set.

### GetDetails

`func (o *HlrSyncResponse) GetDetails() HlrSyncResponseDetails`

GetDetails returns the Details field if non-nil, zero value otherwise.

### GetDetailsOk

`func (o *HlrSyncResponse) GetDetailsOk() (*HlrSyncResponseDetails, bool)`

GetDetailsOk returns a tuple with the Details field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetDetails

`func (o *HlrSyncResponse) SetDetails(v HlrSyncResponseDetails)`

SetDetails sets Details field to given value.

### HasDetails

`func (o *HlrSyncResponse) HasDetails() bool`

HasDetails returns a boolean if a field has been set.

### SetDetailsNil

`func (o *HlrSyncResponse) SetDetailsNil(b bool)`

 SetDetailsNil sets the value for Details to be an explicit nil

### UnsetDetails
`func (o *HlrSyncResponse) UnsetDetails()`

UnsetDetails ensures that no value is present for Details, not even an explicit nil
### GetCreatedDatetime

`func (o *HlrSyncResponse) GetCreatedDatetime() time.Time`

GetCreatedDatetime returns the CreatedDatetime field if non-nil, zero value otherwise.

### GetCreatedDatetimeOk

`func (o *HlrSyncResponse) GetCreatedDatetimeOk() (*time.Time, bool)`

GetCreatedDatetimeOk returns a tuple with the CreatedDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCreatedDatetime

`func (o *HlrSyncResponse) SetCreatedDatetime(v time.Time)`

SetCreatedDatetime sets CreatedDatetime field to given value.

### HasCreatedDatetime

`func (o *HlrSyncResponse) HasCreatedDatetime() bool`

HasCreatedDatetime returns a boolean if a field has been set.

### SetCreatedDatetimeNil

`func (o *HlrSyncResponse) SetCreatedDatetimeNil(b bool)`

 SetCreatedDatetimeNil sets the value for CreatedDatetime to be an explicit nil

### UnsetCreatedDatetime
`func (o *HlrSyncResponse) UnsetCreatedDatetime()`

UnsetCreatedDatetime ensures that no value is present for CreatedDatetime, not even an explicit nil
### GetStatusDatetime

`func (o *HlrSyncResponse) GetStatusDatetime() time.Time`

GetStatusDatetime returns the StatusDatetime field if non-nil, zero value otherwise.

### GetStatusDatetimeOk

`func (o *HlrSyncResponse) GetStatusDatetimeOk() (*time.Time, bool)`

GetStatusDatetimeOk returns a tuple with the StatusDatetime field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetStatusDatetime

`func (o *HlrSyncResponse) SetStatusDatetime(v time.Time)`

SetStatusDatetime sets StatusDatetime field to given value.

### HasStatusDatetime

`func (o *HlrSyncResponse) HasStatusDatetime() bool`

HasStatusDatetime returns a boolean if a field has been set.

### SetStatusDatetimeNil

`func (o *HlrSyncResponse) SetStatusDatetimeNil(b bool)`

 SetStatusDatetimeNil sets the value for StatusDatetime to be an explicit nil

### UnsetStatusDatetime
`func (o *HlrSyncResponse) UnsetStatusDatetime()`

UnsetStatusDatetime ensures that no value is present for StatusDatetime, not even an explicit nil

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


