# MnpCreateRequestOneOf1

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Msisdns** | [**[]MnpCreateRequestOneOf1MsisdnsInner**](MnpCreateRequestOneOf1MsisdnsInner.md) | Array of phone numbers for MNP lookup | 
**Reference** | Pointer to **string** | Global reference ID for the entire batch | [optional] 

## Methods

### NewMnpCreateRequestOneOf1

`func NewMnpCreateRequestOneOf1(msisdns []MnpCreateRequestOneOf1MsisdnsInner, ) *MnpCreateRequestOneOf1`

NewMnpCreateRequestOneOf1 instantiates a new MnpCreateRequestOneOf1 object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewMnpCreateRequestOneOf1WithDefaults

`func NewMnpCreateRequestOneOf1WithDefaults() *MnpCreateRequestOneOf1`

NewMnpCreateRequestOneOf1WithDefaults instantiates a new MnpCreateRequestOneOf1 object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMsisdns

`func (o *MnpCreateRequestOneOf1) GetMsisdns() []MnpCreateRequestOneOf1MsisdnsInner`

GetMsisdns returns the Msisdns field if non-nil, zero value otherwise.

### GetMsisdnsOk

`func (o *MnpCreateRequestOneOf1) GetMsisdnsOk() (*[]MnpCreateRequestOneOf1MsisdnsInner, bool)`

GetMsisdnsOk returns a tuple with the Msisdns field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMsisdns

`func (o *MnpCreateRequestOneOf1) SetMsisdns(v []MnpCreateRequestOneOf1MsisdnsInner)`

SetMsisdns sets Msisdns field to given value.


### GetReference

`func (o *MnpCreateRequestOneOf1) GetReference() string`

GetReference returns the Reference field if non-nil, zero value otherwise.

### GetReferenceOk

`func (o *MnpCreateRequestOneOf1) GetReferenceOk() (*string, bool)`

GetReferenceOk returns a tuple with the Reference field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetReference

`func (o *MnpCreateRequestOneOf1) SetReference(v string)`

SetReference sets Reference field to given value.

### HasReference

`func (o *MnpCreateRequestOneOf1) HasReference() bool`

HasReference returns a boolean if a field has been set.


[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


