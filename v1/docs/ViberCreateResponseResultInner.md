# ViberCreateResponseResultInner

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Error** | **int32** | Error code. Possible values: 0 &#x3D; No errors, 41 &#x3D; Invalid phone number, 43 &#x3D; External reference ID already exists, 44 &#x3D; Invalid request payload, 45 &#x3D; Invalid or unregistered sender, 46 &#x3D; Invalid message text (empty or &gt;1000 chars), 47 &#x3D; Invalid external reference ID format, 48 &#x3D; Invalid validity period, 49 &#x3D; Invalid Viber options, 51 &#x3D; Duplicate phone number in same request | 
**ErrorDescription** | **string** | Human-readable error description | 
**Reference** | Pointer to **NullableString** | Message reference ID (echoed from request if provided) | [optional] 
**Id** | Pointer to **string** | Internal message ID (only present when error &#x3D; 0) | [optional] 
**Price** | Pointer to **float32** | Message price (only present when error &#x3D; 0) | [optional] 
**Currency** | Pointer to **string** | Price currency (only present when error &#x3D; 0) | [optional] 

## Methods

### NewViberCreateResponseResultInner

`func NewViberCreateResponseResultInner(error_ int32, errorDescription string, ) *ViberCreateResponseResultInner`

NewViberCreateResponseResultInner instantiates a new ViberCreateResponseResultInner object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewViberCreateResponseResultInnerWithDefaults

`func NewViberCreateResponseResultInnerWithDefaults() *ViberCreateResponseResultInner`

NewViberCreateResponseResultInnerWithDefaults instantiates a new ViberCreateResponseResultInner object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetError

`func (o *ViberCreateResponseResultInner) GetError() int32`

GetError returns the Error field if non-nil, zero value otherwise.

### GetErrorOk

`func (o *ViberCreateResponseResultInner) GetErrorOk() (*int32, bool)`

GetErrorOk returns a tuple with the Error field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetError

`func (o *ViberCreateResponseResultInner) SetError(v int32)`

SetError sets Error field to given value.


### GetErrorDescription

`func (o *ViberCreateResponseResultInner) GetErrorDescription() string`

GetErrorDescription returns the ErrorDescription field if non-nil, zero value otherwise.

### GetErrorDescriptionOk

`func (o *ViberCreateResponseResultInner) GetErrorDescriptionOk() (*string, bool)`

GetErrorDescriptionOk returns a tuple with the ErrorDescription field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetErrorDescription

`func (o *ViberCreateResponseResultInner) SetErrorDescription(v string)`

SetErrorDescription sets ErrorDescription field to given value.


### GetReference

`func (o *ViberCreateResponseResultInner) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *ViberCreateResponseResultInner) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *ViberCreateResponseResultInner) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *ViberCreateResponseResultInner) HasReference() bool`

HasReference returns a boolean if a field has been set.

### SetReferenceNil

`func (o *ViberCreateResponseResultInner) SetReferenceNil(b bool)`

 SetReferenceNil sets the value for Reference to be an explicit nil

### UnsetReference
`func (o *ViberCreateResponseResultInner) UnsetReference()`

UnsetReference ensures that no value is present for Reference, not even an explicit nil
### GetId

`func (o *ViberCreateResponseResultInner) GetId() string`

GetId returns the Id field if non-nil, zero value otherwise.

### GetIdOk

`func (o *ViberCreateResponseResultInner) GetIdOk() (*string, bool)`

GetIdOk returns a tuple with the Id field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetId

`func (o *ViberCreateResponseResultInner) SetId(v string)`

SetId sets Id field to given value.

### HasId

`func (o *ViberCreateResponseResultInner) HasId() bool`

HasId returns a boolean if a field has been set.

### GetPrice

`func (o *ViberCreateResponseResultInner) GetPrice() float32`

GetPrice returns the Price field if non-nil, zero value otherwise.

### GetPriceOk

`func (o *ViberCreateResponseResultInner) GetPriceOk() (*float32, bool)`

GetPriceOk returns a tuple with the Price field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetPrice

`func (o *ViberCreateResponseResultInner) SetPrice(v float32)`

SetPrice sets Price field to given value.

### HasPrice

`func (o *ViberCreateResponseResultInner) HasPrice() bool`

HasPrice returns a boolean if a field has been set.

### GetCurrency

`func (o *ViberCreateResponseResultInner) GetCurrency() string`

GetCurrency returns the Currency field if non-nil, zero value otherwise.

### GetCurrencyOk

`func (o *ViberCreateResponseResultInner) GetCurrencyOk() (*string, bool)`

GetCurrencyOk returns a tuple with the Currency field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCurrency

`func (o *ViberCreateResponseResultInner) SetCurrency(v string)`

SetCurrency sets Currency field to given value.

### HasCurrency

`func (o *ViberCreateResponseResultInner) HasCurrency() bool`

HasCurrency returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


