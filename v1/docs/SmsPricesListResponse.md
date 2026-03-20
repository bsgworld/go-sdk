# SmsPricesListResponse

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code: 0 for success, non-zero for various error conditions | 
**ErrorDescription** | **string** | Human-readable error description | 
**Prices** | [**[]PriceInfo**](PriceInfo.md) | Array of SMS pricing information | 

## Methods

### NewSmsPricesListResponse

`func NewSmsPricesListResponse(error_ int32, errorDescription string, prices []PriceInfo, ) *SmsPricesListResponse`

NewSmsPricesListResponse instantiates a new SmsPricesListResponse object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewSmsPricesListResponseWithDefaults

`func NewSmsPricesListResponseWithDefaults() *SmsPricesListResponse`

NewSmsPricesListResponseWithDefaults instantiates a new SmsPricesListResponse object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *SmsPricesListResponse) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *SmsPricesListResponse) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *SmsPricesListResponse) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *SmsPricesListResponse) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *SmsPricesListResponse) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *SmsPricesListResponse) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetPrices

`func (o *SmsPricesListResponse) GetPrices() []PriceInfo`

GetPrices returns the Prices field if non-nil, zero value otherwise.

### GetPricesOk

`func (o *SmsPricesListResponse) GetPricesOk() (*[]PriceInfo, bool)`

GetPricesOk returns a tuple with the Prices field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrices

`func (o *SmsPricesListResponse) SetPrices(v []PriceInfo)`

SetPrices sets Prices field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


