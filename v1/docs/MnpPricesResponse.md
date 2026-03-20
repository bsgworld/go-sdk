# MnpPricesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | **string** | Human-readable error description | 
**Prices** | [**[]MnpPricesResponsePricesInner**](MnpPricesResponsePricesInner.md) | List of available MNP destinations with pricing | 

## Methods

### NewMnpPricesResponse

`func NewMnpPricesResponse(error_ int32, errorDescription string, prices []MnpPricesResponsePricesInner, ) *MnpPricesResponse`

NewMnpPricesResponse instantiates a new MnpPricesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpPricesResponseWithDefaults

`func NewMnpPricesResponseWithDefaults() *MnpPricesResponse`

NewMnpPricesResponseWithDefaults instantiates a new MnpPricesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *MnpPricesResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *MnpPricesResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *MnpPricesResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *MnpPricesResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *MnpPricesResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *MnpPricesResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetPrices

`func (o *MnpPricesResponse) GetPrices() []MnpPricesResponsePricesInner`

GetPrices returns the Prices field if non-nil, zero value otherwise.

### GetPricesOk

`func (o *MnpPricesResponse) GetPricesOk() (*[]MnpPricesResponsePricesInner, bool)`

GetPricesOk returns a tuple with the Prices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrices

`func (o *MnpPricesResponse) SetPrices(v []MnpPricesResponsePricesInner)`

SetPrices sets Prices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


