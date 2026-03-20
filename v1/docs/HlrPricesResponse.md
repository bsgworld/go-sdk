# HlrPricesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | **string** | Human-readable error description | 
**Prices** | [**[]HlrPricesResponsePricesInner**](HlrPricesResponsePricesInner.md) | List of available HLR destinations with pricing | 

## Methods

### NewHlrPricesResponse

`func NewHlrPricesResponse(error_ int32, errorDescription string, prices []HlrPricesResponsePricesInner, ) *HlrPricesResponse`

NewHlrPricesResponse instantiates a new HlrPricesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewHlrPricesResponseWithDefaults

`func NewHlrPricesResponseWithDefaults() *HlrPricesResponse`

NewHlrPricesResponseWithDefaults instantiates a new HlrPricesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *HlrPricesResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *HlrPricesResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *HlrPricesResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *HlrPricesResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *HlrPricesResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *HlrPricesResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetPrices

`func (o *HlrPricesResponse) GetPrices() []HlrPricesResponsePricesInner`

GetPrices returns the Prices field if non-nil, zero value otherwise.

### GetPricesOk

`func (o *HlrPricesResponse) GetPricesOk() (*[]HlrPricesResponsePricesInner, bool)`

GetPricesOk returns a tuple with the Prices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrices

`func (o *HlrPricesResponse) SetPrices(v []HlrPricesResponsePricesInner)`

SetPrices sets Prices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


