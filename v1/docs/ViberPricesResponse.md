# ViberPricesResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code (0 &#x3D; success) | 
**ErrorDescription** | **string** | Human-readable error description | 
**Prices** | [**[]ViberPricesResponsePricesInner**](ViberPricesResponsePricesInner.md) | List of available Viber destinations with pricing | 

## Methods

### NewViberPricesResponse

`func NewViberPricesResponse(error_ int32, errorDescription string, prices []ViberPricesResponsePricesInner, ) *ViberPricesResponse`

NewViberPricesResponse instantiates a new ViberPricesResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberPricesResponseWithDefaults

`func NewViberPricesResponseWithDefaults() *ViberPricesResponse`

NewViberPricesResponseWithDefaults instantiates a new ViberPricesResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ViberPricesResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ViberPricesResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ViberPricesResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *ViberPricesResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *ViberPricesResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *ViberPricesResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetPrices

`func (o *ViberPricesResponse) GetPrices() []ViberPricesResponsePricesInner`

GetPrices returns the Prices field if non-nil, zero value otherwise.

### GetPricesOk

`func (o *ViberPricesResponse) GetPricesOk() (*[]ViberPricesResponsePricesInner, bool)`

GetPricesOk returns a tuple with the Prices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrices

`func (o *ViberPricesResponse) SetPrices(v []ViberPricesResponsePricesInner)`

SetPrices sets Prices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


